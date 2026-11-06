# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-03

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-pixel-5`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 1 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 43.
- Requests observed by the sensor: 37014. Third-party registrable domains per site, counted by this script from the page's own requests: median 55; 8 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 203 (203 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 205 detections, 2 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 735 | 56 | — |
| 2 | www.dagbladet.no | yes | — | yes | 516 | 66 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 3 | www.nettavisen.no | yes | — | yes | 821 | 83 | page.hidden_iframe_after_load [suspicious] |
| 4 | www.tv2.no | yes | — | yes | 619 | 69 | page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 421 | 24 | — |
| 6 | www.seher.no | yes | — | yes | 762 | 67 | page.hidden_iframe_after_load [suspicious] |
| 7 | www.kk.no | yes | — | yes | 764 | 67 | page.hidden_iframe_after_load [suspicious] |
| 8 | www.dinside.no | yes | — | no | 372 | 41 | page.hidden_iframe_after_load [suspicious] |
| 9 | www.klikk.no | yes | — | yes | 597 | 69 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 10 | www.dailymail.co.uk | yes | — | no | 466 | 84 | — |
| 11 | www.thesun.co.uk | yes | — | yes | 1490 | 150 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 12 | www.mirror.co.uk | yes | — | yes | 1721 | 172 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 1083 | 122 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | text "OK" | yes | 801 | 70 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 940 | 90 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 16 | www.express.co.uk | yes | — | yes | 3010 | 185 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1350 | 60 | — |
| 18 | www.sofascore.com | yes | — | no | 10 | 1 | — |
| 19 | www.livescore.com | yes | — | yes | 847 | 105 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 20 | www.goal.com | yes | — | yes | 1335 | 71 | page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 535 | 34 | — |
| 22 | www.azlyrics.com | yes | — | yes | 4459 | 138 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | yes | 937 | 99 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 555 | 82 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 50 | 4 | — |
| 26 | convertio.co | yes | — | no | 19 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 158 | 7 | — |
| 28 | www.timeanddate.com | yes | — | yes | 95 | 9 | — |
| 29 | poki.com | yes | — | yes | 444 | 11 | — |
| 30 | www.crazygames.com | yes | — | yes | 632 | 47 | page.hidden_iframe_after_load [suspicious] |
| 31 | www.boredpanda.com | yes | — | yes | 1913 | 158 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 32 | 9gag.com | yes | — | no | 90 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 1040 | 32 | — |
| 34 | ria.ru | yes | — | yes | 505 | 17 | — |
| 35 | www.gazeta.ru | yes | — | yes | 443 | 19 | — |
| 36 | www.kp.ru | yes | — | yes | 283 | 56 | — |
| 37 | www.sports.ru | yes | — | yes | 416 | 15 | — |
| 38 | www.blic.rs | yes | — | yes | 367 | 43 | page.hidden_iframe_after_load [suspicious] |
| 39 | www.kurir.rs | yes | — | yes | 1210 | 98 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 877 | 85 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 478 | 43 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 42 | www.masrawy.com | yes | — | yes | 427 | 36 | page.hidden_iframe_after_load [suspicious] |
| 43 | www.aljazeera.net | yes | — | yes | 334 | 20 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 333 | 31 | page.hidden_iframe_after_load [suspicious] |
| 46 | www.sozcu.com.tr | yes | — | yes | 433 | 29 | page.hidden_iframe_after_load [suspicious] |
| 47 | punchng.com | yes | — | yes | 278 | 21 | — |
| 48 | www.vanguardngr.com | yes | — | no | 12 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 549 | 55 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 475 | 42 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames (documented infrastructure, elevated and above) |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
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
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
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
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.crazygames.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.blic.rs | — |
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
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.hurriyet.com.tr | — |
| `page.hidden_iframe_after_load` | suspicious | www.sozcu.com.tr | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.indiatimes.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.indiatimes.com | — |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
