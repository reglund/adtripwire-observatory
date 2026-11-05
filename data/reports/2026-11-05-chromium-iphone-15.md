# Interactive exposure run, chromium (iPhone 15 emulation) — 2026-11-05

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-iphone-15`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 2 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 43.
- Requests observed by the sensor: 28521. Third-party registrable domains per site, counted by this script from the page's own requests: median 32; 8 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 108 (108 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 309 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 595 | 54 | page.hidden_iframe_after_load [suspicious] |
| 2 | www.dagbladet.no | yes | — | yes | 468 | 32 | — |
| 3 | www.nettavisen.no | yes | — | yes | 533 | 28 | — |
| 4 | www.tv2.no | yes | — | yes | 536 | 28 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 418 | 25 | — |
| 6 | www.seher.no | yes | — | yes | 618 | 36 | — |
| 7 | www.kk.no | yes | — | yes | 554 | 26 | — |
| 8 | www.dinside.no | yes | — | no | 273 | 23 | — |
| 9 | www.klikk.no | yes | — | yes | 532 | 42 | — |
| 10 | www.dailymail.co.uk | yes | — | no | 451 | 59 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 11 | www.thesun.co.uk | yes | text "OK" | yes | 1281 | 104 | — |
| 12 | www.mirror.co.uk | yes | — | yes | 1819 | 157 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 770 | 82 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | text "OK" | yes | 723 | 71 | page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 679 | 61 | — |
| 16 | www.express.co.uk | yes | — | yes | 2214 | 125 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1213 | 40 | — |
| 18 | www.sofascore.com | yes | — | no | 10 | 1 | — |
| 19 | www.livescore.com | yes | — | yes | 608 | 48 | page.hidden_iframe_after_load [suspicious] |
| 20 | www.goal.com | yes | — | yes | 1204 | 60 | — |
| 21 | www.espn.com | yes | — | yes | 492 | 31 | — |
| 22 | www.azlyrics.com | yes | — | yes | 1148 | 95 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | yes | 1608 | 117 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 305 | 52 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 50 | 5 | — |
| 26 | convertio.co | yes | — | no | 22 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 161 | 8 | — |
| 28 | www.timeanddate.com | yes | — | yes | 87 | 8 | — |
| 29 | poki.com | yes | — | yes | 426 | 11 | — |
| 30 | www.crazygames.com | yes | — | yes | 597 | 33 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 31 | www.boredpanda.com | yes | — | yes | 242 | 26 | — |
| 32 | 9gag.com | yes | — | no | 99 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 948 | 48 | — |
| 34 | ria.ru | yes | — | yes | 482 | 18 | — |
| 35 | www.gazeta.ru | yes | — | yes | 518 | 30 | — |
| 36 | www.kp.ru | yes | — | yes | 248 | 43 | — |
| 37 | www.sports.ru | yes | — | yes | 450 | 18 | — |
| 38 | www.blic.rs | yes | — | yes | 316 | 40 | — |
| 39 | www.kurir.rs | yes | — | yes | 1223 | 76 | page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 894 | 65 | page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 407 | 32 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 42 | www.masrawy.com | yes | — | yes | 349 | 37 | — |
| 43 | www.aljazeera.net | yes | — | yes | 324 | 19 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 316 | 29 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 402 | 30 | — |
| 47 | punchng.com | yes | — | yes | 288 | 21 | — |
| 48 | www.vanguardngr.com | yes | — | no | 11 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 426 | 43 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 176 | 23 | — |

## Detections

| Rule | Severity | Site | Subject hostnames (documented infrastructure, elevated and above) |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.vg.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
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
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
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
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.crazygames.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.crazygames.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
