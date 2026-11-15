# Interactive exposure run, chromium (iPhone 15 emulation) — 2026-11-15

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-iphone-15`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 43.
- Requests observed by the sensor: 27529. Third-party registrable domains per site, counted by this script from the page's own requests: median 32; 9 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 81 (81 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 846 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 525 | 30 | — |
| 2 | www.dagbladet.no | yes | — | yes | 774 | 39 | — |
| 3 | www.nettavisen.no | yes | — | yes | 553 | 28 | — |
| 4 | www.tv2.no | yes | — | yes | 551 | 29 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 413 | 24 | — |
| 6 | www.seher.no | yes | — | yes | 578 | 34 | — |
| 7 | www.kk.no | yes | — | yes | 531 | 29 | — |
| 8 | www.dinside.no | yes | — | no | 310 | 30 | — |
| 9 | www.klikk.no | yes | — | yes | 324 | 32 | — |
| 10 | www.dailymail.co.uk | yes | — | no | 344 | 48 | — |
| 11 | www.thesun.co.uk | yes | — | yes | 682 | 77 | — |
| 12 | www.mirror.co.uk | yes | — | yes | 1347 | 109 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 973 | 73 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | — | yes | 632 | 66 | — |
| 15 | www.independent.co.uk | yes | — | yes | 816 | 69 | page.hidden_iframe_after_load [suspicious] |
| 16 | www.express.co.uk | yes | — | yes | 2145 | 99 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1314 | 45 | — |
| 18 | www.sofascore.com | yes | — | no | 10 | 1 | — |
| 19 | www.livescore.com | yes | — | yes | 624 | 47 | — |
| 20 | www.goal.com | yes | — | yes | 1056 | 85 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 416 | 20 | — |
| 22 | www.azlyrics.com | yes | — | yes | 914 | 85 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | yes | 899 | 101 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 176 | 31 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 50 | 5 | — |
| 26 | convertio.co | yes | — | no | 17 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 161 | 8 | — |
| 28 | www.timeanddate.com | yes | — | yes | 91 | 8 | — |
| 29 | poki.com | yes | — | yes | 440 | 11 | — |
| 30 | www.crazygames.com | yes | — | yes | 567 | 6 | — |
| 31 | www.boredpanda.com | yes | — | yes | 769 | 82 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 32 | 9gag.com | yes | — | no | 85 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 1498 | 49 | — |
| 34 | ria.ru | yes | — | yes | 435 | 16 | — |
| 35 | www.gazeta.ru | yes | — | yes | 543 | 30 | — |
| 36 | www.kp.ru | yes | — | yes | 235 | 35 | — |
| 37 | www.sports.ru | yes | — | yes | 401 | 17 | — |
| 38 | www.blic.rs | yes | — | yes | 359 | 39 | page.hidden_iframe_after_load [suspicious] |
| 39 | www.kurir.rs | yes | — | yes | 1074 | 67 | page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 543 | 41 | page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 367 | 32 | — |
| 42 | www.masrawy.com | yes | — | yes | 350 | 27 | — |
| 43 | www.aljazeera.net | yes | — | yes | 326 | 19 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 315 | 29 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 417 | 32 | — |
| 47 | punchng.com | yes | — | yes | 460 | 32 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 48 | www.vanguardngr.com | yes | — | no | 11 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 416 | 47 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 685 | 45 | page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 435f1578aad5f8c6f3e8f807f0aac56f.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 435f1578aad5f8c6f3e8f807f0aac56f.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ams.creativecdn.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | web-cf-event-cell8011.ads.aps.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | 645be2d17792d5c702c951992597cf33.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | 645be2d17792d5c702c951992597cf33.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | www.youtube.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | ams.creativecdn.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | am-match.taboola.com, us-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | am-match.taboola.com, ssum.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.vrtcal.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.vrtcal.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.vrtcal.com, ad-cdn.technoratimedia.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.vrtcal.com, cs.startappnetwork.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.vrtcal.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, us-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, u-ams.4dex.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, sync.rbstsystems.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.lunamedia.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync-us-east.escalax.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | 1b4fb6687fd748cb5ed3f195017f785c.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | 1b4fb6687fd748cb5ed3f195017f785c.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.blic.rs | pulsembed.eu, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | ads.eu.criteo.com, dis.fr3.eu.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | b92adrs.hit.gemius.pl, ls.hit.gemius.pl |
| `page.hidden_iframe_after_load` | suspicious | punchng.com | 8ad839b4980e5659dedf18a5d0daad1b.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | punchng.com | 8ad839b4980e5659dedf18a5d0daad1b.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, imasdk.googleapis.com |
| `page.hidden_iframe_after_load` | suspicious | www.indiatimes.com | js-sec.indexww.com, ssum-sec.casalemedia.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
