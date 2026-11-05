# Interactive exposure run, chromium — 2026-11-05

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 37.
- Requests observed by the sensor: 22145. Third-party registrable domains per site, counted by this script from the page's own requests: median 30; 13 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 66 (66 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 264 detections, 2 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 526 | 30 | — |
| 2 | www.dagbladet.no | yes | — | yes | 537 | 31 | page.hidden_iframe_after_load [suspicious] |
| 3 | www.nettavisen.no | yes | — | yes | 618 | 44 | page.hidden_iframe_after_load [suspicious] |
| 4 | www.tv2.no | yes | — | yes | 515 | 47 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 525 | 33 | page.hidden_iframe_after_load [suspicious] |
| 6 | www.seher.no | yes | — | yes | 758 | 58 | page.hidden_iframe_after_load [suspicious] |
| 7 | www.kk.no | yes | — | yes | 720 | 59 | page.hidden_iframe_after_load [suspicious] |
| 8 | www.dinside.no | yes | — | no | 290 | 23 | page.hidden_iframe_after_load [suspicious] |
| 9 | www.klikk.no | yes | — | yes | 302 | 47 | page.hidden_iframe_after_load [suspicious] |
| 10 | www.dailymail.co.uk | yes | — | no | 0 | 0 | — |
| 11 | www.thesun.co.uk | yes | — | no | 25 | 3 | — |
| 12 | www.mirror.co.uk | yes | — | yes | 1319 | 132 | page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 781 | 101 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | — | yes | 526 | 37 | page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 777 | 65 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 16 | www.express.co.uk | yes | — | no | 1651 | 169 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1185 | 33 | — |
| 18 | www.sofascore.com | yes | — | yes | 567 | 26 | — |
| 19 | www.livescore.com | yes | — | yes | 368 | 7 | — |
| 20 | www.goal.com | yes | — | yes | 642 | 51 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 493 | 61 | — |
| 22 | www.azlyrics.com | yes | — | no | 21 | 4 | — |
| 23 | genius.com | yes | — | no | 15 | 3 | — |
| 24 | www.speedtest.net | yes | — | yes | 268 | 55 | — |
| 25 | www.ilovepdf.com | yes | — | yes | 58 | 5 | — |
| 26 | convertio.co | yes | — | no | 24 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 161 | 7 | — |
| 28 | www.timeanddate.com | yes | — | no | 11 | 1 | — |
| 29 | poki.com | yes | — | yes | 523 | 11 | — |
| 30 | www.crazygames.com | yes | — | no | 239 | 5 | — |
| 31 | www.boredpanda.com | yes | — | yes | 166 | 11 | — |
| 32 | 9gag.com | yes | — | no | 99 | 23 | — |
| 33 | lenta.ru | yes | — | yes | 701 | 39 | — |
| 34 | ria.ru | yes | — | yes | 446 | 19 | — |
| 35 | www.gazeta.ru | yes | — | yes | 651 | 39 | — |
| 36 | www.kp.ru | yes | — | yes | 235 | 39 | — |
| 37 | www.sports.ru | yes | — | yes | 405 | 12 | — |
| 38 | www.blic.rs | yes | — | yes | 365 | 36 | — |
| 39 | www.kurir.rs | yes | — | yes | 1153 | 87 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 410 | 22 | page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 818 | 52 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 42 | www.masrawy.com | yes | — | yes | 298 | 19 | — |
| 43 | www.aljazeera.net | yes | — | yes | 278 | 17 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 413 | 34 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 792 | 49 | page.hidden_iframe_after_load [suspicious] |
| 47 | punchng.com | yes | — | yes | 258 | 19 | — |
| 48 | www.vanguardngr.com | yes | — | no | 11 | 1 | — |
| 49 | www.ndtv.com | yes | — | no | 0 | 0 | — |
| 50 | www.indiatimes.com | yes | — | yes | 194 | 20 | — |

## Detections

| Rule | Severity | Site | Subject hostnames (documented infrastructure, elevated and above) |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
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
| `page.hidden_iframe_after_load` | suspicious | www.sozcu.com.tr | — |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
