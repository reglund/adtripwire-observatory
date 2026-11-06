# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-06

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-pixel-5`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 1 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 42.
- Requests observed by the sensor: 32050. Third-party registrable domains per site, counted by this script from the page's own requests: median 40; 8 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 241 (241 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 785 detections, 2 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 633 | 66 | — |
| 2 | www.dagbladet.no | yes | — | yes | 554 | 42 | page.hidden_iframe_after_load [suspicious] |
| 3 | www.nettavisen.no | yes | — | yes | 550 | 46 | page.hidden_iframe_after_load [suspicious] |
| 4 | www.tv2.no | yes | — | yes | 540 | 25 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 417 | 25 | — |
| 6 | www.seher.no | yes | — | yes | 683 | 40 | page.hidden_iframe_after_load [suspicious] |
| 7 | www.kk.no | yes | — | yes | 712 | 37 | page.hidden_iframe_after_load [suspicious] |
| 8 | www.dinside.no | yes | — | no | 371 | 26 | page.hidden_iframe_after_load [suspicious] |
| 9 | www.klikk.no | yes | — | yes | 637 | 62 | page.hidden_iframe_after_load [suspicious] |
| 10 | www.dailymail.co.uk | yes | — | no | 497 | 87 | — |
| 11 | www.thesun.co.uk | yes | — | yes | 1410 | 105 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 12 | www.mirror.co.uk | yes | — | yes | 1869 | 145 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 976 | 88 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | text "OK" | yes | 761 | 68 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 611 | 58 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 16 | www.express.co.uk | yes | — | no | 1641 | 151 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1231 | 73 | — |
| 18 | www.sofascore.com | yes | — | no | 10 | 1 | — |
| 19 | www.livescore.com | yes | — | yes | 981 | 88 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 20 | www.goal.com | yes | — | yes | 1195 | 68 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 426 | 37 | — |
| 22 | www.azlyrics.com | yes | — | yes | 3239 | 107 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | yes | 1061 | 95 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 369 | 75 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 51 | 4 | — |
| 26 | convertio.co | yes | — | no | 22 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 158 | 7 | — |
| 28 | www.timeanddate.com | yes | — | yes | 88 | 8 | — |
| 29 | poki.com | yes | — | yes | 450 | 11 | — |
| 30 | www.crazygames.com | yes | — | yes | 629 | 45 | — |
| 31 | www.boredpanda.com | yes | — | yes | 1190 | 148 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 32 | 9gag.com | yes | — | no | 94 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 841 | 33 | — |
| 34 | ria.ru | yes | — | yes | 408 | 18 | — |
| 35 | www.gazeta.ru | yes | — | yes | 425 | 18 | — |
| 36 | www.kp.ru | yes | — | yes | 243 | 44 | — |
| 37 | www.sports.ru | yes | — | yes | 417 | 17 | — |
| 38 | www.blic.rs | yes | — | yes | 282 | 33 | page.hidden_iframe_after_load [suspicious] |
| 39 | www.kurir.rs | yes | — | yes | 1368 | 102 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 1084 | 91 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 493 | 43 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 42 | www.masrawy.com | yes | — | yes | 419 | 36 | — |
| 43 | www.aljazeera.net | yes | — | yes | 311 | 18 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 329 | 31 | page.hidden_iframe_after_load [suspicious] |
| 46 | www.sozcu.com.tr | yes | — | yes | 375 | 29 | page.hidden_iframe_after_load [suspicious] |
| 47 | punchng.com | yes | — | yes | 264 | 21 | — |
| 48 | www.vanguardngr.com | yes | — | no | 11 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 483 | 60 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 234 | 30 | — |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | cabd25b6bf441dbd03c3ddae4dc1722a.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | cabd25b6bf441dbd03c3ddae4dc1722a.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | cabd25b6bf441dbd03c3ddae4dc1722a.safeframe.googlesyndication.com, inviso.rampanel.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | hbx.media.net, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | hbx.media.net, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | web-cf-event-cell8013.ads.aps.amazon-adsystem.com, lyr.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ams.creativecdn.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cdn.taboola.com, tsdtocl.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | sync.richaudience.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | tags.crwdcntrl.net, bcp.crwdcntrl.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | hbx.media.net, bh.contextweb.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | www.foxnews.com, static.foxnews.com |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | cdn.taboola.com, tsdtocl.com |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cookies.nextmillmedia.com, rtb.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cookies.nextmillmedia.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cookies.nextmillmedia.com, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cookies.nextmillmedia.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, u-ams.4dex.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, pbs-cs.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.admatic.de, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.pixad.com.tr, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.pixad.com.tr, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.pixad.com.tr, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.pixad.com.tr, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.pixad.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.pixad.com.tr, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.pixad.com.tr, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | dsp-service.pixad.com.tr, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | s.console.adtarget.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | s.console.adtarget.com.tr, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cdn.taboola.com, tsdtocl.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | usync.ingage.tech, prebid-server.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | sync.adkernel.com, cookies.nextmillmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | sync.adkernel.com, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | sync.adkernel.com, dsp-service.admatic.de |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | sync.richaudience.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | sync.richaudience.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | public.servenobid.com, prebidsrvr.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | public.servenobid.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | public.servenobid.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | public.servenobid.com, sync.programmaticx.ai |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | public.servenobid.com, pixel.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | ads.pubmatic.com, s.seedtag.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, sync.ipredictive.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, beachfront-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, visitor.omnitagjs.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ads.pubmatic.com, sync.inmobi.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.inmobi.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | sync.inmobi.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | ads.pubmatic.com, ce.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | ce.lijit.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, lyr.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | hbx.media.net, bh.contextweb.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | hbx.media.net, bh.contextweb.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | s.console.adtarget.com.tr, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | s.console.adtarget.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ads.pubmatic.com, ssp.api.tappx.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync-us-east.escalax.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.lunamedia.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | hbx.media.net, bh.contextweb.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | hbx.media.net, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | sync.kueezrtb.com, s.ad.smaato.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | sync.kueezrtb.com, csync.copper6.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | sync.kueezrtb.com, sync.copper6.live |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | sync.kueezrtb.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | sync.kueezrtb.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | sync.kueezrtb.com, sync.cootlogix.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | sync.kueezrtb.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | sync.kueezrtb.com, sync.rbstsystems.live |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | ads.pubmatic.com, sync.missena.io |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, visitor-missena.omnitagjs.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, secure.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, csync.smilewanted.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, sync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | sync.missena.io, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | gosrv.pixfuture.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | gosrv.pixfuture.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | gosrv.pixfuture.com, hbx.media.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | gosrv.pixfuture.com, sync.go.sonobi.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | gosrv.pixfuture.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | gosrv.pixfuture.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | usync.ingage.tech, pbs2.cpmstar.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.blic.rs | pks.blic.rs, ls.hit.gemius.pl |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | googleads.g.doubleclick.net, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.connectad.io, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.connectad.io, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | sync.connectad.io, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.pixad.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.pixad.com.tr, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.pixad.com.tr, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.pixad.com.tr, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.pixad.com.tr, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.pixad.com.tr, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.pixad.com.tr, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.pixad.com.tr, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | s.console.adtarget.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | s.console.adtarget.com.tr, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, u-ams.4dex.io |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, pbs-cs.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.admatic.de, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | pbam.orangeclickmedia.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | rt.marphezis.com, dsp-service.admatic.de |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | rt.marphezis.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | b92adrs.hit.gemius.pl, ls.hit.gemius.pl |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.adtarget.biz, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | rt.marphezis.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | ads.pubmatic.com, u.4dex.io |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | sync.sparteo.com, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, gum.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.hurriyet.com.tr | cdn.taboola.com, tsdtocl.com |
| `page.hidden_iframe_after_load` | suspicious | www.sozcu.com.tr | www.youtube.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, ice.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, secure.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, id5-sync.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, sync.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | csync.smilewanted.com, sync.smartadserver.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
