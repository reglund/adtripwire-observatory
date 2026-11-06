# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-04

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-pixel-5`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 1 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 42.
- Requests observed by the sensor: 34066. Third-party registrable domains per site, counted by this script from the page's own requests: median 50; 8 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 168 (168 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 373 detections, 2 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 655 | 55 | — |
| 2 | www.dagbladet.no | yes | — | yes | 797 | 66 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 3 | www.nettavisen.no | yes | — | yes | 879 | 86 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.tv2.no | yes | — | yes | 691 | 69 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 421 | 25 | — |
| 6 | www.seher.no | yes | — | yes | 669 | 65 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 7 | www.kk.no | yes | — | yes | 757 | 74 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 8 | www.dinside.no | yes | — | no | 442 | 34 | page.hidden_iframe_after_load [suspicious] |
| 9 | www.klikk.no | yes | — | yes | 674 | 58 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 10 | www.dailymail.co.uk | yes | — | no | 569 | 100 | — |
| 11 | www.thesun.co.uk | yes | — | yes | 1664 | 134 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 12 | www.mirror.co.uk | yes | — | yes | 1742 | 160 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 1127 | 115 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | text "OK" | yes | 845 | 75 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 330 | 55 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 16 | www.express.co.uk | yes | — | no | 1874 | 197 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1393 | 67 | page.hidden_iframe_after_load [suspicious] |
| 18 | www.sofascore.com | yes | — | no | 11 | 1 | — |
| 19 | www.livescore.com | yes | — | yes | 909 | 108 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 20 | www.goal.com | yes | — | yes | 1370 | 72 | page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 479 | 46 | — |
| 22 | www.azlyrics.com | yes | — | yes | 2890 | 142 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | yes | 1903 | 136 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 295 | 75 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 50 | 4 | — |
| 26 | convertio.co | yes | — | no | 17 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 158 | 7 | — |
| 28 | www.timeanddate.com | yes | — | yes | 89 | 8 | — |
| 29 | poki.com | yes | — | yes | 447 | 11 | — |
| 30 | www.crazygames.com | yes | — | yes | 631 | 46 | — |
| 31 | www.boredpanda.com | yes | — | yes | 965 | 129 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 32 | 9gag.com | yes | — | no | 90 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 866 | 33 | — |
| 34 | ria.ru | yes | — | yes | 483 | 17 | — |
| 35 | www.gazeta.ru | yes | — | yes | 444 | 19 | — |
| 36 | www.kp.ru | yes | — | yes | 270 | 50 | — |
| 37 | www.sports.ru | yes | — | yes | 405 | 15 | — |
| 38 | www.blic.rs | yes | — | yes | 297 | 34 | — |
| 39 | www.kurir.rs | yes | — | yes | 1321 | 95 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 989 | 89 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 484 | 40 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 42 | www.masrawy.com | yes | — | yes | 374 | 40 | page.hidden_iframe_after_load [suspicious] |
| 43 | www.aljazeera.net | yes | — | yes | 322 | 20 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 336 | 30 | page.hidden_iframe_after_load [suspicious] |
| 46 | www.sozcu.com.tr | yes | — | yes | 408 | 28 | — |
| 47 | punchng.com | yes | — | yes | 294 | 21 | — |
| 48 | www.vanguardngr.com | yes | — | no | 11 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 482 | 56 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 440 | 44 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames (documented infrastructure, elevated and above) |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | — |
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
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.flashscore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
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
