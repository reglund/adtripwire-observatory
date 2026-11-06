# Interactive exposure run, chromium (iPhone 15 emulation) — 2026-11-04

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-iphone-15`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 1 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 42.
- Requests observed by the sensor: 30893. Third-party registrable domains per site, counted by this script from the page's own requests: median 33; 8 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 113 (113 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 201 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 584 | 51 | — |
| 2 | www.dagbladet.no | yes | — | yes | 598 | 32 | — |
| 3 | www.nettavisen.no | yes | — | yes | 625 | 33 | — |
| 4 | www.tv2.no | yes | — | yes | 504 | 37 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 404 | 25 | — |
| 6 | www.seher.no | yes | — | yes | 613 | 35 | — |
| 7 | www.kk.no | yes | — | yes | 598 | 30 | — |
| 8 | www.dinside.no | yes | — | no | 321 | 29 | — |
| 9 | www.klikk.no | yes | — | yes | 542 | 42 | — |
| 10 | www.dailymail.co.uk | yes | — | no | 594 | 69 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 11 | www.thesun.co.uk | yes | — | yes | 1320 | 94 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 12 | www.mirror.co.uk | yes | — | yes | 1740 | 130 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 1289 | 207 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | text "OK" | yes | 679 | 71 | page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 936 | 79 | — |
| 16 | www.express.co.uk | yes | — | yes | 2365 | 118 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1212 | 37 | — |
| 18 | www.sofascore.com | yes | — | no | 11 | 1 | — |
| 19 | www.livescore.com | yes | — | yes | 620 | 49 | page.hidden_iframe_after_load [suspicious] |
| 20 | www.goal.com | yes | — | yes | 1222 | 72 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 489 | 23 | — |
| 22 | www.azlyrics.com | yes | — | yes | 1191 | 101 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | yes | 2956 | 144 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 286 | 42 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 50 | 5 | — |
| 26 | convertio.co | yes | — | no | 21 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 161 | 8 | — |
| 28 | www.timeanddate.com | yes | — | yes | 87 | 8 | — |
| 29 | poki.com | yes | — | yes | 425 | 11 | — |
| 30 | www.crazygames.com | yes | — | yes | 598 | 33 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 31 | www.boredpanda.com | yes | — | yes | 271 | 26 | — |
| 32 | 9gag.com | yes | — | no | 93 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 903 | 37 | — |
| 34 | ria.ru | yes | — | yes | 504 | 16 | — |
| 35 | www.gazeta.ru | yes | — | yes | 521 | 30 | — |
| 36 | www.kp.ru | yes | — | yes | 255 | 38 | — |
| 37 | www.sports.ru | yes | — | yes | 490 | 18 | — |
| 38 | www.blic.rs | yes | — | yes | 273 | 32 | page.hidden_iframe_after_load [suspicious] |
| 39 | www.kurir.rs | yes | — | yes | 1046 | 72 | — |
| 40 | www.b92.net | yes | — | no | 564 | 68 | page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 381 | 30 | — |
| 42 | www.masrawy.com | yes | — | yes | 354 | 38 | — |
| 43 | www.aljazeera.net | yes | — | yes | 334 | 23 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 318 | 29 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 403 | 30 | — |
| 47 | punchng.com | yes | — | yes | 291 | 21 | — |
| 48 | www.vanguardngr.com | yes | — | no | 11 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 430 | 45 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 403 | 41 | — |

## Detections

| Rule | Severity | Site | Subject hostnames (documented infrastructure, elevated and above) |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | genius.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.crazygames.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.crazygames.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.blic.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
