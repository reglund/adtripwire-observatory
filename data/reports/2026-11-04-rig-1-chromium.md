# Interactive exposure run, chromium — 2026-11-04

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 37.
- Requests observed by the sensor: 23791. Third-party registrable domains per site, counted by this script from the page's own requests: median 30; 13 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 94 (94 suspicious). Contact with documented infrastructure (rules known_infra.*): 1.
- Cumulative in this profile: 198 detections, 2 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 466 | 29 | — |
| 2 | www.dagbladet.no | yes | — | yes | 296 | 30 | page.hidden_iframe_after_load [suspicious] |
| 3 | www.nettavisen.no | yes | — | yes | 619 | 51 | page.hidden_iframe_after_load [suspicious] |
| 4 | www.tv2.no | yes | — | yes | 513 | 56 | page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 499 | 31 | page.hidden_iframe_after_load [suspicious] |
| 6 | www.seher.no | yes | — | yes | 795 | 64 | page.hidden_iframe_after_load [suspicious] |
| 7 | www.kk.no | yes | — | yes | 647 | 57 | page.hidden_iframe_after_load [suspicious] |
| 8 | www.dinside.no | yes | — | no | 190 | 25 | page.hidden_iframe_after_load [suspicious] |
| 9 | www.klikk.no | yes | — | yes | 287 | 49 | page.hidden_iframe_after_load [suspicious] |
| 10 | www.dailymail.co.uk | yes | — | no | 0 | 0 | — |
| 11 | www.thesun.co.uk | yes | — | no | 25 | 3 | — |
| 12 | www.mirror.co.uk | yes | — | yes | 1771 | 191 | page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 1101 | 121 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | — | yes | 540 | 37 | page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 829 | 99 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>known_infra.surveillance_contact [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 16 | www.express.co.uk | yes | — | no | 2430 | 179 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1200 | 35 | — |
| 18 | www.sofascore.com | yes | — | yes | 667 | 39 | — |
| 19 | www.livescore.com | yes | — | yes | 334 | 7 | — |
| 20 | www.goal.com | yes | — | yes | 631 | 52 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 420 | 50 | — |
| 22 | www.azlyrics.com | yes | — | no | 21 | 4 | — |
| 23 | genius.com | yes | — | no | 15 | 3 | — |
| 24 | www.speedtest.net | yes | — | yes | 319 | 72 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 59 | 5 | — |
| 26 | convertio.co | yes | — | no | 24 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 165 | 8 | — |
| 28 | www.timeanddate.com | yes | — | no | 10 | 1 | — |
| 29 | poki.com | yes | — | yes | 520 | 11 | — |
| 30 | www.crazygames.com | yes | — | no | 238 | 5 | — |
| 31 | www.boredpanda.com | yes | — | yes | 194 | 11 | — |
| 32 | 9gag.com | yes | — | no | 97 | 21 | — |
| 33 | lenta.ru | yes | — | yes | 808 | 46 | — |
| 34 | ria.ru | yes | — | yes | 434 | 18 | — |
| 35 | www.gazeta.ru | yes | — | yes | 681 | 38 | — |
| 36 | www.kp.ru | yes | — | yes | 209 | 28 | — |
| 37 | www.sports.ru | yes | — | yes | 422 | 11 | — |
| 38 | www.blic.rs | yes | — | yes | 376 | 36 | — |
| 39 | www.kurir.rs | yes | — | yes | 1043 | 96 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 418 | 24 | page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 860 | 55 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 42 | www.masrawy.com | yes | — | yes | 240 | 18 | — |
| 43 | www.aljazeera.net | yes | — | yes | 333 | 24 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 388 | 33 | page.hidden_iframe_after_load [suspicious] |
| 46 | www.sozcu.com.tr | yes | — | yes | 916 | 53 | page.hidden_iframe_after_load [suspicious] |
| 47 | punchng.com | yes | — | yes | 243 | 19 | — |
| 48 | www.vanguardngr.com | yes | — | no | 12 | 1 | — |
| 49 | www.ndtv.com | yes | — | no | 0 | 0 | — |
| 50 | www.indiatimes.com | yes | — | yes | 479 | 39 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames (documented infrastructure, elevated and above) |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `known_infra.surveillance_contact` | suspicious | www.independent.co.uk | tracookiepixel.xyz |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.hurriyet.com.tr | — |
| `page.hidden_iframe_after_load` | suspicious | www.sozcu.com.tr | — |
| `page.hidden_iframe_after_load` | suspicious | www.indiatimes.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.indiatimes.com | — |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
