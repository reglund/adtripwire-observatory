# Interactive exposure run, firefox — 2026-11-02

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless firefox, persistent profile `~/snap/firefox/common/adtripwire-yandex-etpoff-profile`, 75 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, response_body_inspection, frame_ancestry, third_party_flag, url_classification, page_signals.

## Summary

- Sites: 12; loaded 12; consent clicked on 2 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 12.
- Requests observed by the sensor: 6398. Third-party registrable domains per site, counted by this script from the page's own requests: median 22; 1 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 7 (7 informational). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 7 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | ria.ru | yes | — | yes | 474 | 22 | — |
| 2 | lenta.ru | yes | — | yes | 1012 | 48 | ad_delivery.redirect_chain [informational] |
| 3 | www.gazeta.ru | yes | — | yes | 805 | 22 | — |
| 4 | www.rbc.ru | yes | — | yes | 351 | 20 | — |
| 5 | www.kp.ru | yes | — | yes | 253 | 32 | ad_delivery.redirect_chain [informational] |
| 6 | www.mk.ru | yes | text "OK" | yes | 546 | 80 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [informational]<br>profiling.identifier_rich_request [informational] |
| 7 | iz.ru | yes | — | yes | 498 | 28 | — |
| 8 | www.sports.ru | yes | — | yes | 471 | 12 | — |
| 9 | www.championat.com | yes | — | yes | 488 | 22 | — |
| 10 | www.kinopoisk.ru | yes | text "Allow all" | yes | 766 | 12 | — |
| 11 | habr.com | yes | — | yes | 416 | 16 | — |
| 12 | www.drom.ru | yes | — | yes | 318 | 4 | profiling.identifier_rich_request [informational]<br>profiling.identifier_rich_request [informational] |

## Detections

| Rule | Severity | Site | Subject hostnames (documented infrastructure, elevated and above) |
|---|---|---|---|
| `ad_delivery.redirect_chain` | informational | lenta.ru | — |
| `ad_delivery.redirect_chain` | informational | www.kp.ru | — |
| `ad_delivery.redirect_chain` | informational | www.mk.ru | — |
| `profiling.identifier_rich_request` | informational | www.mk.ru | — |
| `profiling.identifier_rich_request` | informational | www.mk.ru | — |
| `profiling.identifier_rich_request` | informational | www.drom.ru | — |
| `profiling.identifier_rich_request` | informational | www.drom.ru | — |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
