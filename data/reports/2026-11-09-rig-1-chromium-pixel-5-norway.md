# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-09

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-chromium-pixel-5-norway`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 24; loaded 24; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 22.
- Requests observed by the sensor: 12922. Third-party registrable domains per site, counted by this script from the page's own requests: median 32; 0 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 142 (142 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 431 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.aftenposten.no | yes | — | yes | 321 | 26 | — |
| 2 | www.dagsavisen.no | yes | — | yes | 405 | 46 | page.hidden_iframe_after_load [suspicious] |
| 3 | www.abcnyheter.no | yes | — | yes | 690 | 71 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.vl.no | yes | — | yes | 328 | 34 | — |
| 5 | www.nationen.no | yes | — | yes | 420 | 32 | page.hidden_iframe_after_load [suspicious] |
| 6 | www.klassekampen.no | yes | — | yes | 312 | 11 | — |
| 7 | e24.no | yes | — | yes | 474 | 23 | — |
| 8 | www.dn.no | yes | — | yes | 1554 | 63 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 9 | www.finansavisen.no | yes | — | yes | 1051 | 80 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 10 | www.bt.no | yes | — | yes | 365 | 30 | — |
| 11 | www.adressa.no | yes | — | yes | 256 | 19 | — |
| 12 | www.fvn.no | yes | — | yes | 355 | 19 | — |
| 13 | www.aftenbladet.no | yes | — | yes | 289 | 27 | — |
| 14 | www.nordlys.no | yes | — | yes | 592 | 34 | page.hidden_iframe_after_load [suspicious] |
| 15 | www.itromso.no | yes | — | yes | 221 | 16 | — |
| 16 | www.sa.no | yes | — | yes | 683 | 31 | page.hidden_iframe_after_load [suspicious] |
| 17 | www.oa.no | yes | — | yes | 755 | 32 | page.hidden_iframe_after_load [suspicious] |
| 18 | www.rb.no | yes | — | yes | 781 | 31 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 19 | www.tek.no | yes | — | yes | 259 | 24 | — |
| 20 | www.side3.no | yes | — | no | 277 | 33 | — |
| 21 | www.hegnar.no | yes | — | no | 672 | 75 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 22 | www.kk.no | yes | — | yes | 737 | 40 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | www.seher.no | yes | — | yes | 883 | 46 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.godt.no | yes | — | yes | 242 | 21 | — |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.dagsavisen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | 71f651942c35dd9d38be844a8d8b7700.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | 71f651942c35dd9d38be844a8d8b7700.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, ssp.disqus.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, t.adx.opera.com |
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
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | euw2-sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.nationen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ssp.disqus.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ads.betweendigital.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, secure.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | euw2-sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | cdn.connectad.io, sync-eu.connectad.io |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, lwadm.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | www.dn.no, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, btloader.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, js-sec.indexww.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, cdn.btloader.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, ssp.disqus.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, ads.betweendigital.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, secure.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | euw2-sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | ms-cookie-sync.presage.io, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | ms-cookie-sync.presage.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.nordlys.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.sa.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.oa.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.rb.no | 2c2117d1e3a4cf97742cbe2746aee0c9.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.rb.no | 2c2117d1e3a4cf97742cbe2746aee0c9.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.rb.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | tv.finansavisen.no, js-sec.indexww.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | tv.finansavisen.no, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | tv.finansavisen.no, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | tv.finansavisen.no, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | tv.finansavisen.no, btloader.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, ssp.disqus.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, ads.betweendigital.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, secure.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | csync.smilewanted.com, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | ms-cookie-sync.presage.io, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | ms-cookie-sync.presage.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | euw2-sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | euw2-sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | euw2-sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | js-sec.indexww.com, ssum-sec.casalemedia.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
