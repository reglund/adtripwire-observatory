# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-06

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-chromium-pixel-5-mena-africa`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 25; loaded 25; consent clicked on 10 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 22.
- Requests observed by the sensor: 11387. Third-party registrable domains per site, counted by this script from the page's own requests: median 35; 2 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 138 (138 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 138 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.youm7.com | yes | — | yes | 658 | 71 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 2 | www.masrawy.com | yes | — | yes | 803 | 102 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 3 | www.almasryalyoum.com | yes | text "Consent" | yes | 1249 | 90 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.elwatannews.com | yes | — | yes | 361 | 37 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.alarabiya.net | yes | — | yes | 174 | 15 | — |
| 6 | www.albayan.ae | yes | — | yes | 206 | 11 | — |
| 7 | www.alittihad.ae | yes | — | no | 168 | 13 | — |
| 8 | www.okaz.com.sa | yes | — | yes | 145 | 13 | — |
| 9 | sabq.org | yes | text "Consent" | yes | 674 | 35 | — |
| 10 | www.alghad.com | yes | — | no | 13 | 1 | — |
| 11 | www.annahar.com | yes | text "Consent" | yes | 439 | 47 | — |
| 12 | www.hespress.com | yes | — | yes | 133 | 15 | — |
| 13 | www.elkhabar.com | yes | — | yes | 363 | 13 | — |
| 14 | punchng.com | yes | — | yes | 292 | 21 | — |
| 15 | www.vanguardngr.com | yes | — | yes | 374 | 24 | — |
| 16 | www.legit.ng | yes | selector .qc-cmp2-summary-buttons button[mode=primary] | yes | 259 | 48 | — |
| 17 | www.pulse.ng | yes | — | yes | 385 | 21 | — |
| 18 | www.nairaland.com | yes | — | yes | 49 | 9 | — |
| 19 | www.tuko.co.ke | yes | selector .qc-cmp2-summary-buttons button[mode=primary] | yes | 199 | 35 | — |
| 20 | nation.africa | yes | text "Consent" | yes | 282 | 36 | page.hidden_iframe_after_load [suspicious] |
| 21 | www.the-star.co.ke | yes | text "Consent" | yes | 1612 | 164 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 22 | www.news24.com | yes | selector #onetrust-accept-btn-handler | yes | 881 | 38 | — |
| 23 | www.iol.co.za | yes | — | yes | 909 | 95 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.timeslive.co.za | yes | text "OK" | yes | 419 | 61 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.sowetanlive.co.za | yes | text "OK" | no | 340 | 41 | — |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | ce.lijit.com, us-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | user-sync.fwmrm.net, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, gum.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | dsp-service.pixad.com.tr, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | s.console.adtarget.com.tr, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | s.console.adtarget.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | s.console.adtarget.com.tr, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, sync.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | ittpx.eskimi.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.programmaticx.ai |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, us-east-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, prebidsrvr.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.kueezrtb.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, pixel.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, beachfront-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, pixel-sync.sitescout.com |
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
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | imasdk.googleapis.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | ce4c511e162ef1f3e6ccb9c2a5aca6c4.safeframe.googlesyndication.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | ce4c511e162ef1f3e6ccb9c2a5aca6c4.safeframe.googlesyndication.com, static.admaster.cc |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | ce4c511e162ef1f3e6ccb9c2a5aca6c4.safeframe.googlesyndication.com, cdn.mediago.io |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | 7a409694c717794de86601bf9e3cbe6a.safeframe.googlesyndication.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | 7a409694c717794de86601bf9e3cbe6a.safeframe.googlesyndication.com, static.admaster.cc |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.elwatannews.com | sync.sparteo.com, pbs-cs.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | nation.africa | 60563e277a1bcf2922b1519a02e3930e.safeframe.googlesyndication.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | cs-tam.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, eu-sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, crb.kargo.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, cs-tam.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, amazon-tam-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, sync-amz.ads.yieldmo.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, bh.contextweb.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, rtb.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | aax-eu.amazon-adsystem.com, cs-tam.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, ups.analytics.yahoo.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, cms.quantserve.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, pbsj.bricks-co.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, um.simpli.fi |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | ads.pubmatic.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | pbs-cs.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | pbs-cs.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.iol.co.za | imasdk.googleapis.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.iol.co.za | csync.smartadserver.com, image6.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.iol.co.za | csync.smartadserver.com, eu-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.iol.co.za | csync.smartadserver.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.iol.co.za | csync.smartadserver.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.timeslive.co.za | csync.smartadserver.com, image6.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.timeslive.co.za | csync.smartadserver.com, eu-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.timeslive.co.za | csync.smartadserver.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.timeslive.co.za | csync.smartadserver.com, ssum-sec.casalemedia.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
