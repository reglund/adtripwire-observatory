# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-09

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-chromium-pixel-5-mena-africa`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 25; loaded 25; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 18.
- Requests observed by the sensor: 9352. Third-party registrable domains per site, counted by this script from the page's own requests: median 27; 5 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 101 (101 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 311 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.youm7.com | yes | — | yes | 442 | 37 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 2 | www.masrawy.com | yes | — | yes | 551 | 94 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 3 | www.almasryalyoum.com | yes | — | yes | 874 | 71 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.elwatannews.com | yes | — | yes | 257 | 28 | — |
| 5 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 6 | www.albayan.ae | yes | — | yes | 197 | 11 | — |
| 7 | www.alittihad.ae | yes | — | no | 163 | 13 | — |
| 8 | www.okaz.com.sa | yes | — | yes | 87 | 12 | — |
| 9 | sabq.org | yes | — | yes | 544 | 27 | — |
| 10 | www.alghad.com | yes | — | no | 13 | 1 | — |
| 11 | www.annahar.com | yes | — | yes | 485 | 46 | — |
| 12 | www.hespress.com | yes | — | yes | 108 | 14 | — |
| 13 | www.elkhabar.com | yes | — | yes | 357 | 13 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | punchng.com | yes | — | yes | 273 | 20 | — |
| 15 | www.vanguardngr.com | yes | — | no | 11 | 1 | — |
| 16 | www.legit.ng | yes | — | yes | 276 | 35 | — |
| 17 | www.pulse.ng | yes | — | yes | 257 | 21 | — |
| 18 | www.nairaland.com | yes | — | no | 11 | 1 | — |
| 19 | www.tuko.co.ke | yes | — | yes | 262 | 33 | — |
| 20 | nation.africa | yes | — | no | 11 | 1 | — |
| 21 | www.the-star.co.ke | yes | — | yes | 1815 | 116 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 22 | www.news24.com | yes | — | yes | 907 | 37 | — |
| 23 | www.iol.co.za | yes | — | yes | 591 | 50 | page.hidden_iframe_after_load [suspicious] |
| 24 | www.timeslive.co.za | yes | — | yes | 411 | 47 | — |
| 25 | www.sowetanlive.co.za | yes | — | no | 442 | 75 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, gum.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.programmaticx.ai |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, us-east-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, prebidsrvr.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.kueezrtb.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, pixel.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, sync.ipredictive.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, beachfront-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, visitor.omnitagjs.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | imasdk.googleapis.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, image6.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, eu-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, visitor.omnitagjs.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, sync.ipredictive.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, beachfront-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.elkhabar.com | d177ca529fa1fcff2379d127b1635513.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.elkhabar.com | d177ca529fa1fcff2379d127b1635513.safeframe.googlesyndication.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | am-match.taboola.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | am-match.taboola.com, ssum.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | user-sync.fwmrm.net, pbsj.bricks-co.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | prebid.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.iol.co.za | imasdk.googleapis.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | user-sync.fwmrm.net, pbsj.bricks-co.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
