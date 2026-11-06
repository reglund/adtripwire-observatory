# Interactive exposure run, firefox — 2026-11-06

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless firefox, persistent profile `~/snap/firefox/common/adtripwire-exposure-profile`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, response_body_inspection, frame_ancestry, third_party_flag, url_classification, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 41.
- Requests observed by the sensor: 45013. Third-party registrable domains per site, counted by this script from the page's own requests: median 47; 7 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 661 (628 suspicious, 33 informational). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 2240 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 596 | 34 | — |
| 2 | www.dagbladet.no | yes | — | yes | 479 | 64 | profiling.identifier_rich_request [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 3 | www.nettavisen.no | yes | — | yes | 1157 | 34 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.tv2.no | yes | — | yes | 536 | 52 | page.hidden_iframe_after_load [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 1043 | 56 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 6 | www.seher.no | yes | — | no | 666 | 75 | profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 7 | www.kk.no | yes | — | yes | 376 | 17 | — |
| 8 | www.dinside.no | yes | — | no | 447 | 70 | page.hidden_iframe_after_load [suspicious]<br>profiling.identifier_rich_request [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 9 | www.klikk.no | yes | — | yes | 199 | 21 | — |
| 10 | www.dailymail.co.uk | yes | — | no | 1011 | 117 | profiling.identifier_rich_request [suspicious]<br>ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 11 | www.thesun.co.uk | yes | — | yes | 1692 | 156 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 12 | www.mirror.co.uk | yes | — | yes | 2926 | 215 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 1499 | 146 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | — | yes | 813 | 69 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 628 | 55 | — |
| 16 | www.express.co.uk | yes | — | yes | 3616 | 222 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>profiling.identifier_rich_request [informational]<br>profiling.identifier_rich_request [informational]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1867 | 41 | profiling.identifier_rich_request [suspicious]<br>ad_delivery.redirect_chain [informational] |
| 18 | www.sofascore.com | yes | — | yes | 693 | 47 | — |
| 19 | www.livescore.com | yes | — | yes | 2110 | 139 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 20 | www.goal.com | yes | — | yes | 1082 | 100 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 574 | 49 | ad_delivery.redirect_chain [informational] |
| 22 | www.azlyrics.com | yes | — | yes | 1854 | 158 | profiling.identifier_rich_request [informational]<br>profiling.identifier_rich_request [suspicious]<br>ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | no | 2767 | 197 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 1361 | 149 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 85 | 8 | — |
| 26 | convertio.co | yes | — | no | 25 | 6 | — |
| 27 | www.online-convert.com | yes | — | yes | 243 | 8 | — |
| 28 | www.timeanddate.com | yes | — | yes | 255 | 16 | — |
| 29 | poki.com | yes | — | yes | 510 | 12 | — |
| 30 | www.crazygames.com | yes | — | no | 457 | 4 | — |
| 31 | www.boredpanda.com | yes | — | yes | 2367 | 195 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>profiling.identifier_rich_request [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 32 | 9gag.com | yes | — | no | 52 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 797 | 34 | ad_delivery.redirect_chain [informational] |
| 34 | ria.ru | yes | — | yes | 455 | 17 | — |
| 35 | www.gazeta.ru | yes | — | yes | 663 | 30 | ad_delivery.redirect_chain [informational] |
| 36 | www.kp.ru | yes | — | yes | 262 | 35 | ad_delivery.redirect_chain [informational] |
| 37 | www.sports.ru | yes | — | yes | 458 | 12 | — |
| 38 | www.blic.rs | yes | — | yes | 412 | 38 | — |
| 39 | www.kurir.rs | yes | — | yes | 1465 | 139 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>profiling.identifier_rich_request [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 1001 | 65 | page.hidden_iframe_after_load [suspicious]<br>ad_delivery.redirect_chain [informational] |
| 41 | www.youm7.com | yes | — | yes | 889 | 47 | — |
| 42 | www.masrawy.com | yes | — | yes | 837 | 110 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 43 | www.aljazeera.net | yes | — | yes | 364 | 23 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 1061 | 41 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 700 | 42 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 47 | punchng.com | yes | — | yes | 309 | 20 | — |
| 48 | www.vanguardngr.com | yes | — | no | 15 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 1034 | 123 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 298 | 33 | — |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `profiling.identifier_rich_request` | suspicious | www.dagbladet.no | securepubads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | cfb668c29bdf35d3a6eae4e841f8a59d.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | cfb668c29bdf35d3a6eae4e841f8a59d.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `ad_delivery.redirect_chain` | informational | www.nettavisen.no | dsum-sec.casalemedia.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | 037de2191480b5e11a972c3e8c302718.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | 037de2191480b5e11a972c3e8c302718.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 6145c8efd6feeabdc4bd1435b2d6f54d.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `ad_delivery.redirect_chain` | informational | www.tv2.no | d5p.de17a.com, euw-ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | acd3a7c02bec7e94e9e551ed0bdbc9ff.safeframe.googlesyndication.com, inviso.rampanel.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.finn.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `profiling.identifier_rich_request` | informational | www.seher.no | track.madington.io |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, cm.adgrx.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, s.company-target.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, a.tribalfusion.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, prebid-server.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, x.bidswitch.net |
| `ad_delivery.redirect_chain` | informational | www.seher.no | d5p.de17a.com, euw-ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, prebid-server.rubiconproject.com |
| `profiling.identifier_rich_request` | suspicious | www.dinside.no | securepubads.g.doubleclick.net |
| `ad_delivery.redirect_chain` | informational | www.dinside.no | cm.g.doubleclick.net, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, cm-supply-web.gammaplatform.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, cm.mgid.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, cs.loudecho.ai |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, cm-mx.advolve.io |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, a.tribalfusion.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, cm.adgrx.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, s.company-target.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `profiling.identifier_rich_request` | suspicious | www.dailymail.co.uk | pubads.g.doubleclick.net |
| `ad_delivery.redirect_chain` | informational | www.dailymail.co.uk | x.bidswitch.net, ads.creative-serving.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, rtb.gumgum.com |
| `ad_delivery.redirect_chain` | informational | www.thesun.co.uk | id5-sync.com, ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `profiling.identifier_rich_request` | informational | www.thesun.co.uk | region1.google-analytics.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, a.tribalfusion.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, elb.the-ozone-project.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, ipac.ctnsnet.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, usersync.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | elb.the-ozone-project.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | elb.the-ozone-project.com, rtb.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | hbx.media.net, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | hbx.media.net, p.rfihub.com |
| `ad_delivery.redirect_chain` | informational | www.mirror.co.uk | sync.1rx.io, sync.targeting.unrulymedia.com, live.primis.tech |
| `profiling.identifier_rich_request` | suspicious | www.mirror.co.uk | securepubads.g.doubleclick.net |
| `profiling.identifier_rich_request` | informational | www.mirror.co.uk | wt.rqtrk.eu |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, ipac.ctnsnet.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `ad_delivery.redirect_chain` | informational | nypost.com | match.adsrvr.org, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aax-eu.amazon-adsystem.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aax-eu.amazon-adsystem.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aax-eu.amazon-adsystem.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aax-eu.amazon-adsystem.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aax-eu.amazon-adsystem.com, rtb.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, elb.the-ozone-project.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | elb.the-ozone-project.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | hbx.media.net, cs.media.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | hbx.media.net, bh.contextweb.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | www.foxnews.com, static.foxnews.com |
| `ad_delivery.redirect_chain` | informational | www.express.co.uk | sync.1rx.io, sync.targeting.unrulymedia.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cdn.taboola.com, tsdtocl.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | am-match.taboola.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | b8fc9b0a6274f8833986d6d9be4377bd.safeframe.googlesyndication.com, pagead2.googlesyndication.com |
| `profiling.identifier_rich_request` | informational | www.express.co.uk | ie1-bid.adsrvr.org |
| `profiling.identifier_rich_request` | informational | www.express.co.uk | ssl.connextra.com |
| `profiling.identifier_rich_request` | informational | www.express.co.uk | choices.truste.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs-tam.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs-tam.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, cs-tam.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, s.seedtag.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, sync.inmobi.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, amazon-tam-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, cs-tam.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, rtb.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | tags.crwdcntrl.net, bcp.crwdcntrl.net |
| `profiling.identifier_rich_request` | suspicious | www.flashscore.com | securepubads.g.doubleclick.net |
| `ad_delivery.redirect_chain` | informational | www.flashscore.com | id5-sync.com, d.turn.com, csync.smilewanted.com |
| `ad_delivery.redirect_chain` | informational | www.livescore.com | id5-sync.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ap.lijit.com, us-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, d5p.de17a.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, a.tribalfusion.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, cm.adgrx.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, dsp.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, s.company-target.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, sync.inmobi.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, ipac.ctnsnet.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.inmobi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.inmobi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, um.simpli.fi |
| `ad_delivery.redirect_chain` | informational | www.goal.com | id5-sync.com, d.turn.com, dis.eu.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | csync-eu.smartadserver.com, eu-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | csync-eu.smartadserver.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | csync-eu.smartadserver.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | csync-eu.smartadserver.com, image6.pubmatic.com |
| `ad_delivery.redirect_chain` | informational | www.espn.com | token.rubiconproject.com, cm.g.doubleclick.net, pixel.rubiconproject.com |
| `profiling.identifier_rich_request` | informational | www.azlyrics.com | g2.gumgum.com |
| `profiling.identifier_rich_request` | suspicious | www.azlyrics.com | securepubads.g.doubleclick.net |
| `ad_delivery.redirect_chain` | informational | www.azlyrics.com | sync.1rx.io, sync.targeting.unrulymedia.com, live.primis.tech |
| `profiling.identifier_rich_request` | informational | www.azlyrics.com | wt.rqtrk.eu |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, d5p.de17a.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, live.primis.tech |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, ipac.ctnsnet.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, cs-tam.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, s.seedtag.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, sync-amz.ads.yieldmo.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, bh.contextweb.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, sync.inmobi.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, cs-tam.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, rtb.gumgum.com |
| `ad_delivery.redirect_chain` | informational | genius.com | sync.1rx.io, sync.targeting.unrulymedia.com, ads.assemblyexchange.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.lunamedia.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync-us-east.escalax.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, ads.assemblyexchange.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rt.marphezis.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, i.liadm.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, id5-sync.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, ads.assemblyexchange.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, ads.assemblyexchange.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, dsp.360yield.com |
| `ad_delivery.redirect_chain` | informational | www.speedtest.net | sync.1rx.io, sync.targeting.unrulymedia.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, sync-us-east.escalax.io |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, sync.lunamedia.live |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | cs-tam.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | cs-tam.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, cs-tam.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, ssp.api.tappx.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `ad_delivery.redirect_chain` | informational | www.boredpanda.com | cm.g.doubleclick.net, ssum-sec.casalemedia.com |
| `profiling.identifier_rich_request` | suspicious | www.boredpanda.com | securepubads.g.doubleclick.net |
| `profiling.identifier_rich_request` | informational | www.boredpanda.com | wt.rqtrk.eu |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, ipac.ctnsnet.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, d5p.de17a.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, beachfront-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, visitor.omnitagjs.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, sync.ipredictive.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | hbx.media.net, cs.media.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.richaudience.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.richaudience.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.richaudience.com, us-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `ad_delivery.redirect_chain` | informational | lenta.ru | sync.rambler.ru, dmg.digitaltarget.ru |
| `ad_delivery.redirect_chain` | informational | www.gazeta.ru | sync.rambler.ru, dmg.digitaltarget.ru |
| `ad_delivery.redirect_chain` | informational | www.kp.ru | www.acint.net, ssp-rtb.sape.ru, acint.net, statmedia.ru |
| `ad_delivery.redirect_chain` | informational | www.kurir.rs | x.bidswitch.net, cm.g.doubleclick.net |
| `profiling.identifier_rich_request` | suspicious | www.kurir.rs | googleads.g.doubleclick.net |
| `profiling.identifier_rich_request` | suspicious | www.kurir.rs | securepubads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, ads.betweendigital.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | s.console.adtarget.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | s.console.adtarget.com.tr, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | dsp-service.pixad.com.tr, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, secure.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, sync.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, pbs-cs.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.sparteo.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | cdn.snigelweb.com, visitor.omnitagjs.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | b92adrs.hit.gemius.pl, ls.hit.gemius.pl |
| `ad_delivery.redirect_chain` | informational | www.b92.net | b92rs.adocean.pl, b92adrs.hit.gemius.pl |
| `ad_delivery.redirect_chain` | informational | www.masrawy.com | sync.1rx.io, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, sync.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, us-east-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, prebidsrvr.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.kueezrtb.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.programmaticx.ai |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, pixel.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.ipredictive.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, beachfront-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, visitor.omnitagjs.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.sozcu.com.tr | www.youtube.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.sozcu.com.tr | ads.eu.criteo.com, dis.fr3.eu.criteo.com |
| `ad_delivery.redirect_chain` | informational | www.ndtv.com | sync.1rx.io, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | cs.pgammedia.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | cs.pgammedia.com, ssbsync-global.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | cs.pgammedia.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | cs.pgammedia.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | cs.pgammedia.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, secure.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, aax-eu.amazon-adsystem.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
