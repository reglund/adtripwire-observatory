# Interactive exposure run, firefox — 2026-11-09

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless firefox, persistent profile `~/snap/firefox/common/adtripwire-exposure-profile`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, response_body_inspection, frame_ancestry, third_party_flag, url_classification, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 1 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 41.
- Requests observed by the sensor: 39742. Third-party registrable domains per site, counted by this script from the page's own requests: median 41; 8 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 623 (592 suspicious, 31 informational). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 2423 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 417 | 28 | profiling.identifier_rich_request [informational] |
| 2 | www.dagbladet.no | yes | — | yes | 583 | 92 | profiling.identifier_rich_request [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 3 | www.nettavisen.no | yes | — | yes | 1090 | 33 | page.hidden_iframe_after_load [suspicious] |
| 4 | www.tv2.no | yes | — | yes | 565 | 51 | ad_delivery.redirect_chain [informational] |
| 5 | www.finn.no | yes | — | yes | 1001 | 55 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 6 | www.seher.no | yes | — | yes | 968 | 93 | page.hidden_iframe_after_load [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 7 | www.kk.no | yes | — | yes | 853 | 88 | page.hidden_iframe_after_load [suspicious]<br>profiling.identifier_rich_request [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 8 | www.dinside.no | yes | — | no | 304 | 41 | page.hidden_iframe_after_load [suspicious] |
| 9 | www.klikk.no | yes | — | yes | 196 | 21 | — |
| 10 | www.dailymail.co.uk | yes | — | no | 860 | 101 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 11 | www.thesun.co.uk | yes | text "OK" | yes | 1379 | 148 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 12 | www.mirror.co.uk | yes | — | yes | 2467 | 190 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 1596 | 141 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | — | yes | 677 | 69 | page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 873 | 53 | — |
| 16 | www.express.co.uk | yes | — | yes | 2914 | 198 | profiling.identifier_rich_request [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1827 | 45 | ad_delivery.redirect_chain [informational]<br>ad_delivery.redirect_chain [informational] |
| 18 | www.sofascore.com | yes | — | no | 11 | 1 | — |
| 19 | www.livescore.com | yes | — | yes | 2411 | 156 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 20 | www.goal.com | yes | — | yes | 713 | 54 | ad_delivery.redirect_chain [informational] |
| 21 | www.espn.com | yes | — | yes | 552 | 51 | ad_delivery.redirect_chain [informational] |
| 22 | www.azlyrics.com | yes | — | yes | 1944 | 161 | profiling.identifier_rich_request [suspicious]<br>profiling.identifier_rich_request [informational]<br>ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | no | 1017 | 134 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 1025 | 136 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 85 | 8 | — |
| 26 | convertio.co | yes | — | no | 25 | 6 | — |
| 27 | www.online-convert.com | yes | — | yes | 224 | 7 | — |
| 28 | www.timeanddate.com | yes | — | yes | 159 | 11 | — |
| 29 | poki.com | yes | — | yes | 491 | 11 | — |
| 30 | www.crazygames.com | yes | — | no | 456 | 4 | — |
| 31 | www.boredpanda.com | yes | — | yes | 2104 | 186 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 32 | 9gag.com | yes | — | no | 69 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 880 | 36 | ad_delivery.redirect_chain [informational] |
| 34 | ria.ru | yes | — | yes | 472 | 18 | — |
| 35 | www.gazeta.ru | yes | — | yes | 602 | 27 | ad_delivery.redirect_chain [informational] |
| 36 | www.kp.ru | yes | — | yes | 219 | 25 | — |
| 37 | www.sports.ru | yes | — | yes | 455 | 12 | — |
| 38 | www.blic.rs | yes | — | yes | 318 | 30 | — |
| 39 | www.kurir.rs | yes | — | yes | 1327 | 136 | profiling.identifier_rich_request [suspicious]<br>profiling.identifier_rich_request [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 735 | 37 | page.hidden_iframe_after_load [suspicious]<br>ad_delivery.redirect_chain [informational] |
| 41 | www.youm7.com | yes | — | yes | 919 | 49 | page.hidden_iframe_after_load [suspicious] |
| 42 | www.masrawy.com | yes | — | yes | 767 | 108 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 43 | www.aljazeera.net | yes | — | yes | 384 | 19 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 739 | 32 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 443 | 31 | — |
| 47 | punchng.com | yes | — | yes | 330 | 20 | — |
| 48 | www.vanguardngr.com | yes | — | no | 15 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 942 | 125 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 332 | 32 | — |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `profiling.identifier_rich_request` | informational | www.vg.no | t.nodals.io |
| `profiling.identifier_rich_request` | suspicious | www.dagbladet.no | securepubads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `ad_delivery.redirect_chain` | informational | www.dagbladet.no | cm.g.doubleclick.net, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, cm.mgid.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, cs.loudecho.ai |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, cm.adgrx.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, cm-supply-web.gammaplatform.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, prebid-server.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, a.tribalfusion.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, cm-mx.advolve.io |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, s.company-target.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | smartembedtwitterxtweet.getbagera.no, platform.twitter.com |
| `ad_delivery.redirect_chain` | informational | www.tv2.no | d5p.de17a.com, euw-ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `ad_delivery.redirect_chain` | informational | www.seher.no | d5p.de17a.com, euw-ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, cm-supply-web.gammaplatform.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, cm.mgid.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, cs.loudecho.ai |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, cm.adgrx.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, prebid-server.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, a.tribalfusion.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, cm-mx.advolve.io |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, s.company-target.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `profiling.identifier_rich_request` | suspicious | www.kk.no | securepubads.g.doubleclick.net |
| `ad_delivery.redirect_chain` | informational | www.kk.no | dsum-sec.casalemedia.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, cs.loudecho.ai |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, cm.adgrx.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, cm-supply-web.gammaplatform.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, cm.mgid.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, a.tribalfusion.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, cm-mx.advolve.io |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, s.company-target.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, prebid-server.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `ad_delivery.redirect_chain` | informational | www.dailymail.co.uk | dsum-sec.casalemedia.com, cm.g.doubleclick.net |
| `profiling.identifier_rich_request` | suspicious | www.dailymail.co.uk | pubads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, rtb.gumgum.com |
| `ad_delivery.redirect_chain` | informational | www.thesun.co.uk | id5-sync.com, uipglob.semasio.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `profiling.identifier_rich_request` | informational | www.thesun.co.uk | region1.google-analytics.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, usersync.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, ipac.ctnsnet.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | elb.the-ozone-project.com, rtb.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, elb.the-ozone-project.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | hbx.media.net, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | hbx.media.net, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | elb.the-ozone-project.com, ads.pubmatic.com |
| `ad_delivery.redirect_chain` | informational | www.mirror.co.uk | sync.1rx.io, sync.targeting.unrulymedia.com, live.primis.tech |
| `profiling.identifier_rich_request` | suspicious | www.mirror.co.uk | securepubads.g.doubleclick.net |
| `profiling.identifier_rich_request` | informational | www.mirror.co.uk | wt.rqtrk.eu |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, ipac.ctnsnet.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, d5p.de17a.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, live.primis.tech |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `ad_delivery.redirect_chain` | informational | nypost.com | dsum-sec.casalemedia.com, cm.g.doubleclick.net |
| `profiling.identifier_rich_request` | informational | nypost.com | widgets.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aax-eu.amazon-adsystem.com, rtb.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, elb.the-ozone-project.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | elb.the-ozone-project.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | hbx.media.net, cs.media.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | hbx.media.net, bh.contextweb.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | 5ae977f6362ae8b1d7dfb3f06e402fdd.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | 5ae977f6362ae8b1d7dfb3f06e402fdd.safeframe.googlesyndication.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | 5ae977f6362ae8b1d7dfb3f06e402fdd.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `profiling.identifier_rich_request` | suspicious | www.express.co.uk | securepubads.g.doubleclick.net |
| `ad_delivery.redirect_chain` | informational | www.express.co.uk | x.bidswitch.net, dsp.nrich.ai |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs-tam.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs-tam.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, s.seedtag.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, cs-tam.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, amazon-tam-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, sync.inmobi.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, cs-tam.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, rtb.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | tags.crwdcntrl.net, bcp.crwdcntrl.net |
| `ad_delivery.redirect_chain` | informational | www.flashscore.com | dsum-sec.casalemedia.com, cm.g.doubleclick.net |
| `ad_delivery.redirect_chain` | informational | www.flashscore.com | id5-sync.com, s.seedtag.com, csync.smilewanted.com |
| `ad_delivery.redirect_chain` | informational | www.livescore.com | id5-sync.com, uipglob.semasio.net |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.inmobi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.inmobi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.omni-dex.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.omni-dex.io, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.omni-dex.io, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.omni-dex.io, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.omni-dex.io, us-east-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.omni-dex.io, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, creativecdn.com |
| `ad_delivery.redirect_chain` | informational | www.goal.com | id5-sync.com, ice.360yield.com |
| `ad_delivery.redirect_chain` | informational | www.espn.com | token.rubiconproject.com, cm.g.doubleclick.net, pixel.rubiconproject.com |
| `profiling.identifier_rich_request` | suspicious | www.azlyrics.com | securepubads.g.doubleclick.net |
| `profiling.identifier_rich_request` | informational | www.azlyrics.com | g2.gumgum.com |
| `ad_delivery.redirect_chain` | informational | www.azlyrics.com | id5-sync.com, s.seedtag.com, dis.eu.criteo.com |
| `profiling.identifier_rich_request` | informational | www.azlyrics.com | wt.rqtrk.eu |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, bh.contextweb.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, cs-tam.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, sync.inmobi.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, s.seedtag.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, sync-amz.ads.yieldmo.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, cs-tam.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, rtb.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, ipac.ctnsnet.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, d5p.de17a.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, live.primis.tech |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, cms.quantserve.com |
| `ad_delivery.redirect_chain` | informational | genius.com | creativecdn.com, simage2.pubmatic.com, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, sync.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, us-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, ssp.api.tappx.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync-us-east.escalax.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.lunamedia.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cs-rtb.minutemedia-prebid.com |
| `ad_delivery.redirect_chain` | informational | www.speedtest.net | id5-sync.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ittpx.eskimi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ittpx.eskimi.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ittpx.eskimi.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ittpx.eskimi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ittpx.eskimi.com, sync.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ittpx.eskimi.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, sync.lunamedia.live |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, sync-us-east.escalax.io |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | cs-tam.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | cs-tam.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, ssp.api.tappx.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, cs-tam.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `ad_delivery.redirect_chain` | informational | www.boredpanda.com | dsum-sec.casalemedia.com, cm.g.doubleclick.net |
| `profiling.identifier_rich_request` | suspicious | www.boredpanda.com | securepubads.g.doubleclick.net |
| `profiling.identifier_rich_request` | informational | www.boredpanda.com | wt.rqtrk.eu |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, sync.ipredictive.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, beachfront-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, visitor.omnitagjs.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.richaudience.com, us-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.richaudience.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | hbx.media.net, cs.media.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `ad_delivery.redirect_chain` | informational | lenta.ru | sync.upravel.com, dmg.digitaltarget.ru |
| `ad_delivery.redirect_chain` | informational | www.gazeta.ru | sync.upravel.com, ad.mail.ru |
| `profiling.identifier_rich_request` | suspicious | www.kurir.rs | securepubads.g.doubleclick.net |
| `profiling.identifier_rich_request` | suspicious | www.kurir.rs | googleads.g.doubleclick.net |
| `ad_delivery.redirect_chain` | informational | www.kurir.rs | sync.1rx.io, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | cdn.snigelweb.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | cdn.snigelweb.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, secure.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | cdn.snigelweb.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | s.console.adtarget.com.tr, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | s.console.adtarget.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | cdn.snigelweb.com, hbx.media.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, pbs-cs.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, sync.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | b92adrs.hit.gemius.pl, ls.hit.gemius.pl |
| `ad_delivery.redirect_chain` | informational | www.b92.net | b92rs.adocean.pl, b92adrs.hit.gemius.pl |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | ads.eu.criteo.com, dis.fr3.eu.criteo.com |
| `ad_delivery.redirect_chain` | informational | www.masrawy.com | sync.1rx.io, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, sync.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.programmaticx.ai |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, us-east-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, prebidsrvr.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.kueezrtb.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, pixel.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, visitor.omnitagjs.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.ipredictive.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, beachfront-match.dotomi.com |
| `ad_delivery.redirect_chain` | informational | www.ndtv.com | sync.1rx.io, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | cs.pgammedia.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | cs.pgammedia.com, ssbsync-global.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | cs.pgammedia.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | cs.pgammedia.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | cs.pgammedia.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, sync.programmaticx.ai |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, us-east-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, prebidsrvr.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, sync.kueezrtb.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | public.servenobid.com, pixel.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, aax-eu.amazon-adsystem.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
