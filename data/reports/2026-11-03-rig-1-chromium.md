# Interactive exposure run, chromium — 2026-11-03

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 38.
- Requests observed by the sensor: 23549. Third-party registrable domains per site, counted by this script from the page's own requests: median 33; 13 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 103 (103 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 104 detections, 1 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 456 | 29 | — |
| 2 | www.dagbladet.no | yes | — | yes | 420 | 49 | page.hidden_iframe_after_load [suspicious] |
| 3 | www.nettavisen.no | yes | — | yes | 665 | 62 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.tv2.no | yes | — | yes | 530 | 56 | page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 549 | 33 | page.hidden_iframe_after_load [suspicious] |
| 6 | www.seher.no | yes | — | yes | 884 | 66 | page.hidden_iframe_after_load [suspicious] |
| 7 | www.kk.no | yes | — | yes | 768 | 69 | page.hidden_iframe_after_load [suspicious] |
| 8 | www.dinside.no | yes | — | no | 308 | 30 | page.hidden_iframe_after_load [suspicious] |
| 9 | www.klikk.no | yes | — | yes | 388 | 49 | page.hidden_iframe_after_load [suspicious] |
| 10 | www.dailymail.co.uk | yes | — | no | 0 | 0 | — |
| 11 | www.thesun.co.uk | yes | — | no | 25 | 3 | — |
| 12 | www.mirror.co.uk | yes | — | yes | 1111 | 136 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 791 | 108 | page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | — | yes | 604 | 41 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 736 | 99 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 16 | www.express.co.uk | yes | — | yes | 1864 | 153 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1191 | 36 | — |
| 18 | www.sofascore.com | yes | — | yes | 722 | 76 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 19 | www.livescore.com | yes | — | yes | 365 | 7 | — |
| 20 | www.goal.com | yes | — | yes | 637 | 50 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 462 | 57 | — |
| 22 | www.azlyrics.com | yes | — | no | 21 | 4 | — |
| 23 | genius.com | yes | — | no | 14 | 3 | — |
| 24 | www.speedtest.net | yes | — | yes | 1008 | 95 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 58 | 5 | — |
| 26 | convertio.co | yes | — | no | 21 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 160 | 7 | — |
| 28 | www.timeanddate.com | yes | — | no | 10 | 1 | — |
| 29 | poki.com | yes | — | yes | 523 | 11 | — |
| 30 | www.crazygames.com | yes | — | no | 238 | 5 | — |
| 31 | www.boredpanda.com | yes | — | yes | 199 | 11 | — |
| 32 | 9gag.com | yes | — | no | 96 | 20 | — |
| 33 | lenta.ru | yes | — | yes | 732 | 41 | — |
| 34 | ria.ru | yes | — | yes | 403 | 17 | — |
| 35 | www.gazeta.ru | yes | — | yes | 689 | 37 | — |
| 36 | www.kp.ru | yes | — | yes | 186 | 26 | — |
| 37 | www.sports.ru | yes | — | yes | 385 | 11 | — |
| 38 | www.blic.rs | yes | — | yes | 411 | 40 | — |
| 39 | www.kurir.rs | yes | — | yes | 1403 | 111 | — |
| 40 | www.b92.net | yes | — | yes | 338 | 23 | page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 847 | 55 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 42 | www.masrawy.com | yes | — | yes | 254 | 19 | — |
| 43 | www.aljazeera.net | yes | — | yes | 235 | 17 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 460 | 44 | page.hidden_iframe_after_load [suspicious] |
| 46 | www.sozcu.com.tr | yes | — | yes | 766 | 59 | page.hidden_iframe_after_load [suspicious] |
| 47 | punchng.com | yes | — | yes | 252 | 19 | — |
| 48 | www.vanguardngr.com | yes | — | no | 12 | 1 | — |
| 49 | www.ndtv.com | yes | — | no | 0 | 0 | — |
| 50 | www.indiatimes.com | yes | — | yes | 345 | 42 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames (documented infrastructure, elevated and above) |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sofascore.com | — |
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
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
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
