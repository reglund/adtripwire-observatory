# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-06

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-chromium-pixel-5-norway`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 24; loaded 24; consent clicked on 23 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 22.
- Requests observed by the sensor: 13979. Third-party registrable domains per site, counted by this script from the page's own requests: median 40; 0 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 120 (120 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 120 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.aftenposten.no | yes | selector button.sp_choice_type_11 | yes | 390 | 27 | — |
| 2 | www.dagsavisen.no | yes | selector button.sp_choice_type_11 | yes | 381 | 40 | — |
| 3 | www.abcnyheter.no | yes | selector button.sp_choice_type_11 | yes | 735 | 102 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.vl.no | yes | selector button.sp_choice_type_11 | yes | 402 | 38 | — |
| 5 | www.nationen.no | yes | selector button.sp_choice_type_11 | yes | 496 | 45 | page.hidden_iframe_after_load [suspicious] |
| 6 | www.klassekampen.no | yes | selector #CybotCookiebotDialogBodyLevelButtonLevelOptinAllowAll | yes | 318 | 12 | — |
| 7 | e24.no | yes | selector button.sp_choice_type_11 | yes | 525 | 31 | — |
| 8 | www.dn.no | yes | selector #onetrust-accept-btn-handler | yes | 1301 | 86 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 9 | www.finansavisen.no | yes | selector button.sp_choice_type_11 | yes | 1049 | 97 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 10 | www.bt.no | yes | selector button.sp_choice_type_11 | yes | 414 | 34 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 11 | www.adressa.no | yes | selector button.sp_choice_type_11 | yes | 430 | 28 | — |
| 12 | www.fvn.no | yes | selector button.sp_choice_type_11 | yes | 470 | 33 | page.hidden_iframe_after_load [suspicious] |
| 13 | www.aftenbladet.no | yes | selector button.sp_choice_type_11 | yes | 524 | 40 | — |
| 14 | www.nordlys.no | yes | selector button.sp_choice_type_11 | yes | 633 | 44 | page.hidden_iframe_after_load [suspicious] |
| 15 | www.itromso.no | yes | selector button.sp_choice_type_11 | yes | 377 | 27 | — |
| 16 | www.sa.no | yes | selector button.sp_choice_type_11 | yes | 694 | 44 | page.hidden_iframe_after_load [suspicious] |
| 17 | www.oa.no | yes | selector button.sp_choice_type_11 | yes | 720 | 45 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 18 | www.rb.no | yes | selector button.sp_choice_type_11 | yes | 821 | 43 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 19 | www.tek.no | yes | selector button.sp_choice_type_11 | yes | 320 | 30 | page.hidden_iframe_after_load [suspicious] |
| 20 | www.side3.no | yes | selector button.sp_choice_type_11 | no | 295 | 35 | — |
| 21 | www.hegnar.no | yes | — | no | 519 | 81 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 22 | www.kk.no | yes | selector button.sp_choice_type_11 | yes | 704 | 65 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | www.seher.no | yes | selector button.sp_choice_type_11 | yes | 952 | 72 | page.hidden_iframe_after_load [suspicious] |
| 24 | www.godt.no | yes | selector button.sp_choice_type_11 | yes | 509 | 29 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, ads.betweendigital.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, secure.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | euw2-sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | sync.richaudience.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | 114460942b556a8e1c0932d863a29b14.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | 114460942b556a8e1c0932d863a29b14.safeframe.googlesyndication.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | 114460942b556a8e1c0932d863a29b14.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.nationen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ssp.disqus.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, id5-sync.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | ads.pubmatic.com, lwadm.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | cdn.connectad.io, sync-eu.connectad.io |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | e502195aeb441fc5b5598b511b629818.safeframe.googlesyndication.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | ads.pubmatic.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | ms-cookie-sync.presage.io, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, secure.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | ms-cookie-sync.presage.io, lwadm.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | ms-cookie-sync.presage.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | ads.pubmatic.com, u.4dex.io |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | www.dn.no, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, js-sec.indexww.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | imasdk.googleapis.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, btloader.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, cdn.btloader.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, ssp.disqus.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, id5-sync.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | ms-cookie-sync.presage.io, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.bt.no | adsdk.microsoft.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.bt.no | adsdk.microsoft.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.fvn.no | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.nordlys.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.sa.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.oa.no | 5c72309fe0d12008b4317dfc12374f96.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.oa.no | 5c72309fe0d12008b4317dfc12374f96.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.oa.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.rb.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.rb.no | bc1df4f96497607aabf92f5aa9447b45.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.rb.no | bc1df4f96497607aabf92f5aa9447b45.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.tek.no | adsdk.microsoft.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, ssp.disqus.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, id5-sync.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | ads.pubmatic.com, prebid-server.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.godt.no | adsdk.microsoft.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.godt.no | adsdk.microsoft.com, googleads.g.doubleclick.net |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
