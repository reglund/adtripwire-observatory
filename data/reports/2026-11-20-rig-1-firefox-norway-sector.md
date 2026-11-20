# Interactive exposure run, firefox — 2026-11-20

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless firefox, persistent profile `~/snap/firefox/common/adtripwire-exposure-profile-norway-sector`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, response_body_inspection, frame_ancestry, third_party_flag, url_classification, page_signals.

## Summary

- Sites: 15; loaded 15; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 15.
- Requests observed by the sensor: 5278. Third-party registrable domains per site, counted by this script from the page's own requests: median 18; 3 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 76 (73 suspicious, 3 informational). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 1488 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.tu.no | yes | — | yes | 966 | 96 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 2 | www.forskning.no | yes | — | yes | 1098 | 130 | ad_delivery.redirect_chain [informational]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 3 | www.morgenbladet.no | yes | — | yes | 292 | 19 | — |
| 4 | www.khrono.no | yes | — | yes | 161 | 10 | — |
| 5 | www.kommunal-rapport.no | yes | — | yes | 188 | 12 | — |
| 6 | www.digi.no | yes | — | yes | 971 | 97 | ad_delivery.redirect_chain [informational]<br>profiling.identifier_rich_request [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 7 | www.dagensperspektiv.no | yes | — | yes | 203 | 21 | — |
| 8 | www.dagensmedisin.no | yes | — | yes | 261 | 20 | — |
| 9 | www.utdanningsnytt.no | yes | — | yes | 175 | 18 | profiling.identifier_rich_request [suspicious] |
| 10 | www.altinget.no | yes | — | yes | 409 | 23 | — |
| 11 | www.universitetsavisa.no | yes | — | yes | 159 | 11 | — |
| 12 | www.kode24.no | yes | — | yes | 137 | 11 | — |
| 13 | www.samordnaopptak.no | yes | — | yes | 100 | 5 | — |
| 14 | www.regjeringen.no | yes | — | yes | 69 | 2 | — |
| 15 | www.uio.no | yes | — | yes | 89 | 2 | — |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `ad_delivery.redirect_chain` | informational | www.tu.no | d5p.de17a.com, euw-ice.360yield.com |
| `profiling.identifier_rich_request` | suspicious | www.tu.no | securepubads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | sync.connectad.io, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | 72fc5224f63029204b9ba930b13861a2.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | sync.connectad.io, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | 72fc5224f63029204b9ba930b13861a2.safeframe.googlesyndication.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | 72fc5224f63029204b9ba930b13861a2.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | sync.connectad.io, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | sync.connectad.io, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | sync.connectad.io, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | ads.pubmatic.com, otc-pbs.relevant-digital.com |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.tu.no | ads.pubmatic.com, um.simpli.fi |
| `ad_delivery.redirect_chain` | informational | www.forskning.no | cm.g.doubleclick.net, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | sync.connectad.io, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | sync.connectad.io, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | sync.connectad.io, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | sync.connectad.io, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, otc-pbs.relevant-digital.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | 4a085d9ce2e0891739e2b388ee9fe8bd.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | 4a085d9ce2e0891739e2b388ee9fe8bd.safeframe.googlesyndication.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | 4a085d9ce2e0891739e2b388ee9fe8bd.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | dsp-service.adtarget.biz, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.forskning.no | dsp-service.adtarget.biz, image8.pubmatic.com |
| `ad_delivery.redirect_chain` | informational | www.digi.no | d5p.de17a.com, euw-ice.360yield.com |
| `profiling.identifier_rich_request` | suspicious | www.digi.no | securepubads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, otc-pbs.relevant-digital.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | sync.connectad.io, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | sync.connectad.io, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | sync.connectad.io, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | sync.connectad.io, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | sync.connectad.io, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | sync.connectad.io, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | sync.connectad.io, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | sync.connectad.io, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | dsp-service.adtarget.biz, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.digi.no | dsp-service.adtarget.biz, image8.pubmatic.com |
| `profiling.identifier_rich_request` | suspicious | www.utdanningsnytt.no | utdanningsforbundet.matomo.cloud |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
