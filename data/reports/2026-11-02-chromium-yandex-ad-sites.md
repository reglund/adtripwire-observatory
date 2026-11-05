# Interactive exposure run, chromium — 2026-11-02

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-yandex-profile`, 75 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 12; loaded 12; consent clicked on 2 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 12.
- Requests observed by the sensor: 6466. Third-party registrable domains per site, counted by this script from the page's own requests: median 38; 1 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 1 (1 suspicious). Contact with documented infrastructure (rules known_infra.*): 1.
- Cumulative in this profile: 1 detections, 1 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | ria.ru | yes | — | yes | 451 | 21 | — |
| 2 | lenta.ru | yes | — | yes | 1086 | 66 | — |
| 3 | www.gazeta.ru | yes | — | yes | 1029 | 79 | known_infra.surveillance_contact [suspicious] |
| 4 | www.rbc.ru | yes | — | yes | 348 | 21 | — |
| 5 | www.kp.ru | yes | — | yes | 234 | 39 | — |
| 6 | www.mk.ru | yes | text "OK" | yes | 422 | 78 | — |
| 7 | iz.ru | yes | — | yes | 442 | 38 | — |
| 8 | www.sports.ru | yes | — | yes | 415 | 12 | — |
| 9 | www.championat.com | yes | — | yes | 688 | 42 | — |
| 10 | www.kinopoisk.ru | yes | text "Allow all" | yes | 659 | 12 | — |
| 11 | habr.com | yes | — | yes | 396 | 15 | — |
| 12 | www.drom.ru | yes | — | yes | 296 | 4 | — |

## Detections

| Rule | Severity | Site | Subject hostnames (documented infrastructure, elevated and above) |
|---|---|---|---|
| `known_infra.surveillance_contact` | suspicious | www.gazeta.ru | events.myweb3id.io |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
