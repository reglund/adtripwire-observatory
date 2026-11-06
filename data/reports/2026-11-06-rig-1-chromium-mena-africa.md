# Interactive exposure run, chromium — 2026-11-06

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-chromium-mena-africa`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 25; loaded 25; consent clicked on 4 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 10.
- Requests observed by the sensor: 6198. Third-party registrable domains per site, counted by this script from the page's own requests: median 1; 13 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 150 (150 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 150 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.youm7.com | yes | — | yes | 838 | 70 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 2 | www.masrawy.com | yes | — | yes | 653 | 96 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 3 | www.almasryalyoum.com | yes | — | no | 13 | 1 | — |
| 4 | www.elwatannews.com | yes | — | yes | 372 | 36 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 6 | www.albayan.ae | yes | — | yes | 217 | 11 | — |
| 7 | www.alittihad.ae | yes | — | no | 165 | 12 | — |
| 8 | www.okaz.com.sa | yes | — | no | 3 | 0 | — |
| 9 | sabq.org | yes | — | no | 15 | 1 | — |
| 10 | www.alghad.com | yes | — | no | 15 | 1 | — |
| 11 | www.annahar.com | yes | text "Consent" | yes | 418 | 46 | — |
| 12 | www.hespress.com | yes | — | no | 7 | 1 | — |
| 13 | www.elkhabar.com | yes | — | yes | 574 | 14 | page.hidden_iframe_after_load [suspicious] |
| 14 | punchng.com | yes | — | yes | 263 | 19 | — |
| 15 | www.vanguardngr.com | yes | — | no | 13 | 1 | — |
| 16 | www.legit.ng | yes | — | no | 2 | 0 | — |
| 17 | www.pulse.ng | yes | — | yes | 503 | 37 | — |
| 18 | www.nairaland.com | yes | — | no | 13 | 1 | — |
| 19 | www.tuko.co.ke | yes | — | no | 12 | 1 | — |
| 20 | nation.africa | yes | — | no | 12 | 1 | — |
| 21 | www.the-star.co.ke | yes | text "Consent" | yes | 1493 | 158 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 22 | www.news24.com | yes | — | no | 15 | 1 | — |
| 23 | www.iol.co.za | yes | — | no | 10 | 1 | — |
| 24 | www.timeslive.co.za | yes | text "OK" | yes | 373 | 67 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.sowetanlive.co.za | yes | text "OK" | no | 192 | 32 | — |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, pbs-cs.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | ce.lijit.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | user-sync.fwmrm.net, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | s.console.adtarget.com.tr, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | s.console.adtarget.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | s.console.adtarget.com.tr, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, sync.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.programmaticx.ai |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, us-east-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, prebidsrvr.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.kueezrtb.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, pixel.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.ipredictive.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, beachfront-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, visitor.omnitagjs.com |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, pbs-cs.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.elkhabar.com | 55fb729862f1eb0d1356515052576bc5.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, cm.adgrx.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, s.company-target.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, cm-mx.advolve.io |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, green.erne.co |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, cm-supply-web.gammaplatform.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, cm.mgid.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, cs.loudecho.ai |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, u-ams03.e-planning.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, ipac.ctnsnet.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, tr.blismedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, d5p.de17a.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, a.tribalfusion.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, usersync.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, match.adsby.bidtheatre.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, pubmatic-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, dsp-cookie.adfarm1.adition.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, cookiesync.api.bliink.io |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | cdn.connectad.io, sync-eu.connectad.io |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tag.bliink.io, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tag.bliink.io, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tag.bliink.io, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tag.bliink.io, cdn.connectad.io |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tag.bliink.io, cookiesync.api.bliink.io |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tag.bliink.io, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tag.bliink.io, acdn.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tag.bliink.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, pbsj.bricks-co.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | pbs-cs.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | pbs-cs.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.timeslive.co.za | csync.smartadserver.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.timeslive.co.za | csync.smartadserver.com, image6.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.timeslive.co.za | csync.smartadserver.com, eu-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.timeslive.co.za | csync.smartadserver.com, ad.turn.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
