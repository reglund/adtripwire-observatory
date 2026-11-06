# Interactive exposure run, firefox — 2026-11-03

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless firefox, persistent profile `~/snap/firefox/common/adtripwire-exposure-profile`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, response_body_inspection, frame_ancestry, third_party_flag, url_classification, page_signals.

## Summary

- Sites: 50; loaded 48; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 41.
- Requests observed by the sensor: 42960. Third-party registrable domains per site, counted by this script from the page's own requests: median 48; 7 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 532 (499 suspicious, 33 informational). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 888 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 489 | 31 | profiling.identifier_rich_request [informational] |
| 2 | www.dagbladet.no | yes | — | yes | 442 | 71 | page.hidden_iframe_after_load [suspicious]<br>profiling.identifier_rich_request [suspicious]<br>profiling.identifier_rich_request [suspicious] |
| 3 | www.nettavisen.no | yes | — | yes | 1018 | 32 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.tv2.no | yes | — | yes | 548 | 57 | profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 1005 | 65 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 6 | www.seher.no | yes | — | no | 626 | 54 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious] |
| 7 | www.kk.no | no | — | no | 61 | 8 | —<br>error: Navigation timeout of 45000 ms exceeded |
| 8 | www.dinside.no | no | — | no | 36 | 7 | —<br>error: Navigation timeout of 45000 ms exceeded |
| 9 | www.klikk.no | yes | — | yes | 384 | 54 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 10 | www.dailymail.co.uk | yes | — | no | 1176 | 125 | profiling.identifier_rich_request [suspicious]<br>ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 11 | www.thesun.co.uk | yes | — | yes | 1836 | 164 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 12 | www.mirror.co.uk | yes | — | yes | 2380 | 211 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 1135 | 143 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | — | yes | 857 | 72 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 1410 | 109 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 16 | www.express.co.uk | yes | — | yes | 3059 | 206 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1808 | 34 | ad_delivery.redirect_chain [informational] |
| 18 | www.sofascore.com | yes | — | yes | 648 | 42 | — |
| 19 | www.livescore.com | yes | — | yes | 2043 | 135 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 20 | www.goal.com | yes | — | yes | 1255 | 106 | page.hidden_iframe_after_load [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 553 | 54 | profiling.identifier_rich_request [suspicious]<br>ad_delivery.redirect_chain [informational] |
| 22 | www.azlyrics.com | yes | — | yes | 1758 | 155 | profiling.identifier_rich_request [informational]<br>ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | yes | 2128 | 193 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 1189 | 143 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 85 | 8 | — |
| 26 | convertio.co | yes | — | no | 27 | 6 | — |
| 27 | www.online-convert.com | yes | — | yes | 256 | 9 | — |
| 28 | www.timeanddate.com | yes | — | yes | 161 | 11 | — |
| 29 | poki.com | yes | — | yes | 595 | 11 | — |
| 30 | www.crazygames.com | yes | — | no | 449 | 4 | — |
| 31 | www.boredpanda.com | yes | — | yes | 2332 | 217 | profiling.identifier_rich_request [suspicious]<br>ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 32 | 9gag.com | yes | — | no | 59 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 831 | 32 | ad_delivery.redirect_chain [informational] |
| 34 | ria.ru | yes | — | yes | 440 | 15 | — |
| 35 | www.gazeta.ru | yes | — | yes | 593 | 25 | ad_delivery.redirect_chain [informational] |
| 36 | www.kp.ru | yes | — | yes | 238 | 32 | ad_delivery.redirect_chain [informational] |
| 37 | www.sports.ru | yes | — | yes | 455 | 12 | — |
| 38 | www.blic.rs | yes | — | yes | 357 | 35 | — |
| 39 | www.kurir.rs | yes | — | yes | 1607 | 139 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>profiling.identifier_rich_request [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 892 | 71 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 983 | 48 | page.hidden_iframe_after_load [suspicious] |
| 42 | www.masrawy.com | yes | — | yes | 792 | 104 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 43 | www.aljazeera.net | yes | — | yes | 333 | 20 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 1064 | 41 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 669 | 42 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 47 | punchng.com | yes | — | yes | 301 | 20 | — |
| 48 | www.vanguardngr.com | yes | — | no | 15 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 1057 | 121 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 518 | 48 | profiling.identifier_rich_request [informational]<br>profiling.identifier_rich_request [informational]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames (documented infrastructure, elevated and above) |
|---|---|---|---|
| `profiling.identifier_rich_request` | informational | www.vg.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | — |
| `profiling.identifier_rich_request` | suspicious | www.dagbladet.no | — |
| `profiling.identifier_rich_request` | suspicious | www.dagbladet.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | — |
| `profiling.identifier_rich_request` | informational | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | — |
| `ad_delivery.redirect_chain` | informational | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | — |
| `ad_delivery.redirect_chain` | informational | www.seher.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | — |
| `ad_delivery.redirect_chain` | informational | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | — |
| `profiling.identifier_rich_request` | suspicious | www.dailymail.co.uk | — |
| `ad_delivery.redirect_chain` | informational | www.dailymail.co.uk | — |
| `profiling.identifier_rich_request` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | — |
| `ad_delivery.redirect_chain` | informational | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `profiling.identifier_rich_request` | informational | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | — |
| `ad_delivery.redirect_chain` | informational | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | — |
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
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `ad_delivery.redirect_chain` | informational | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | — |
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
| `ad_delivery.redirect_chain` | informational | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | — |
| `ad_delivery.redirect_chain` | informational | www.express.co.uk | — |
| `profiling.identifier_rich_request` | suspicious | www.express.co.uk | — |
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
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | — |
| `ad_delivery.redirect_chain` | informational | www.flashscore.com | — |
| `ad_delivery.redirect_chain` | informational | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `ad_delivery.redirect_chain` | informational | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | — |
| `profiling.identifier_rich_request` | suspicious | www.espn.com | — |
| `ad_delivery.redirect_chain` | informational | www.espn.com | — |
| `profiling.identifier_rich_request` | informational | www.azlyrics.com | — |
| `ad_delivery.redirect_chain` | informational | www.azlyrics.com | — |
| `profiling.identifier_rich_request` | informational | www.azlyrics.com | — |
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
| `ad_delivery.redirect_chain` | informational | genius.com | — |
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
| `ad_delivery.redirect_chain` | informational | www.speedtest.net | — |
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
| `profiling.identifier_rich_request` | suspicious | www.boredpanda.com | — |
| `ad_delivery.redirect_chain` | informational | www.boredpanda.com | — |
| `profiling.identifier_rich_request` | informational | www.boredpanda.com | — |
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
| `ad_delivery.redirect_chain` | informational | lenta.ru | — |
| `ad_delivery.redirect_chain` | informational | www.gazeta.ru | — |
| `ad_delivery.redirect_chain` | informational | www.kp.ru | — |
| `ad_delivery.redirect_chain` | informational | www.kurir.rs | — |
| `profiling.identifier_rich_request` | suspicious | www.kurir.rs | — |
| `profiling.identifier_rich_request` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | — |
| `ad_delivery.redirect_chain` | informational | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | — |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | — |
| `ad_delivery.redirect_chain` | informational | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.sozcu.com.tr | — |
| `page.hidden_iframe_after_load` | suspicious | www.sozcu.com.tr | — |
| `ad_delivery.redirect_chain` | informational | www.ndtv.com | — |
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
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | — |
| `profiling.identifier_rich_request` | informational | www.indiatimes.com | — |
| `profiling.identifier_rich_request` | informational | www.indiatimes.com | — |
| `profiling.identifier_rich_request` | informational | www.indiatimes.com | — |
| `page.hidden_iframe_after_load` | suspicious | www.indiatimes.com | — |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
