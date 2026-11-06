# Observatory data

Everything here is produced by the exposure harness (`scripts/exposure-run.mjs`) on a
measurement rig with synthetic profiles. The only thing removed is what identifies the rig
itself: its home directory, and `/home/<login name>`, replaced by `~` wherever they appear in a
string. Contact with documented infrastructure is exposure to an ad-delivery
path described in public reporting; it is not evidence of targeting or of anything reaching a
device.

## Files

| Path | Content |
|---|---|
| `index.json` | Summary used by the site (fields below). |
| `trend.md` | Markdown trend report over all runs. |
| `runs/<date>-<rig>-<variant>.json` | One run, as written by the run script (fields below). |
| `runs/<date>-<rig>-<variant>.evidence.json` | Optional. The extension's evidence export (default redaction profile) for that run. |
| `reports/<date>-<rig>-<variant>.md` | Optional. The Markdown report of that run. |

`<rig>` is the name of the measurement machine that made the run (lower case letters, digits and
hyphens, for example `rig-1`); several rigs may contribute. `<variant>` is the slug of browser,
device, ETP setting and site list, for example `chromium`, `chromium-pixel-5` or
`firefox-etp-off-yandex-ad-sites`.

## Run file

| Field | Meaning |
|---|---|
| `date` | Day of the run, `YYYY-MM-DD`. |
| `rig` | Name of the rig that made the run. Absent in runs from before rigs existed; those are attributed to `rig-1`. |
| `rigCountry` | Optional. ISO 3166-1 alpha-2 country declared by the rig owner. Not verified. |
| `rigNetwork` | Optional. Network class declared by the rig owner: `home`, `mobile`, `office` or `datacentre`. Not verified. |
| `browser` | `firefox` or `chromium`. |
| `device` | Emulated device name, or `null` for a desktop profile. |
| `sites` | Path of the site list used (relative to the repository). |
| `etpOff` | `true` when Firefox Enhanced Tracking Protection was off. |
| `seconds` | Observation time per site. |
| `totals.sites` | Sites visited. |
| `totals.loaded` | Sites that loaded. |
| `totals.consent` | Sites where a consent control was clicked. |
| `totals.article` | Sites where an article was opened. |
| `totals.events` | Requests observed by the sensor. |
| `totals.thirdPartyMedian` | Median third-party registrable domains per loaded site. |
| `totals.lowAuction` | Loaded sites that contacted fewer than 10 third-party domains. |
| `totals.detections[]` | Every detection of the run: `ruleId`, `severity`. |
| `results[].site` | Site host. |
| `results[].loaded` | Whether the page loaded. |
| `results[].consent` | `null`, or a string of the form `selector <css>` or `text "<label>"` naming how the consent control was found. |
| `results[].article` | Whether an article was opened. |
| `results[].events` | Requests observed while this site was open. |
| `results[].thirdPartyDomains` | Third-party registrable domains seen on this site. |
| `results[].error` | Optional. Why a step failed. |
| `results[].detections[]` | Detections raised on this site (below). |

A detection always has `ruleId` and `severity` (`informational`, `suspicious`, `elevated`,
`high_priority`). Optional fields, present only in runs made by newer versions of the run script:

| Field | Meaning |
|---|---|
| `hostnames` | Subject hostnames. Older runs record them only for `known_infra.*` rules and elevated or above. |
| `detectionId` | Id of the detection inside the extension. |
| `timestamp` | When it was raised. |
| `confidence` | The rule's confidence. |
| `matchedIndicatorIds` | Indicator ids that matched. |
| `occurrenceCount` | How many times the pattern was seen. |
| `summary` | The extension's one-line summary. |
| `evidence[]` | Observed strings (hostnames, path patterns, query names) behind the detection. |

## index.json

| Field | Meaning |
|---|---|
| `schemaVersion` | `1`. |
| `generatedAt` | ISO time the site was built. |
| `period` | `from`, `to`, `days` (days with runs), `calendarDays` (days from first to last). |
| `rigs[]` | One entry per rig, sorted by name: `rig`, `country` and `network` (declared by the rig owner, or `null`), `days` (days with runs), `runs`, `variants`, `contacts`, `hosts` (distinct documented hosts). |
| `runs[]` | One entry per run: `file`, optional `evidence` and `report`, `date`, `rig`, `variant`, `slug`, `browser`, `device`, `etpOff`, `siteList`, `seconds`, `sites`, `loaded`, `consent`, `requests`, `thirdPartyMedian`, `bySev`, `noisy` (hidden-iframe detections, counted apart), `contacts`, `strong`. |
| `hosts[]` | Documented hosts: `host`, `first`, `last`, `days[]`, `variants[]`, `sites[]`, `rigs[]`. |
| `contacts[]` | Contacts: `date`, `rig`, `variant`, `slug`, `site`, `ruleId`, `severity`, optional `hostnames[]`. |

A contact is a detection from a `known_infra.*` or `correlation.*` rule, or at elevated or above.
`strong` counts contacts from `correlation.*` rules or at elevated or above.
