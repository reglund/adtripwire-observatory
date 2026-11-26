# Interactive exposure run, chromium (iPhone 15 emulation) — 2026-11-26

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-iphone-15`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 1 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 43.
- Requests observed by the sensor: 29632. Third-party registrable domains per site, counted by this script from the page's own requests: median 34; 9 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 106 (106 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 1905 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 451 | 29 | — |
| 2 | www.dagbladet.no | yes | — | yes | 511 | 27 | — |
| 3 | www.nettavisen.no | yes | — | yes | 691 | 33 | — |
| 4 | www.tv2.no | yes | — | yes | 545 | 27 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 404 | 24 | — |
| 6 | www.seher.no | yes | — | yes | 595 | 34 | — |
| 7 | www.kk.no | yes | — | yes | 473 | 29 | — |
| 8 | www.dinside.no | yes | — | no | 245 | 25 | — |
| 9 | www.klikk.no | yes | — | yes | 345 | 32 | — |
| 10 | www.dailymail.co.uk | yes | — | no | 340 | 48 | — |
| 11 | www.thesun.co.uk | yes | text "OK" | yes | 988 | 92 | page.hidden_iframe_after_load [suspicious] |
| 12 | www.mirror.co.uk | yes | — | yes | 1359 | 106 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 1418 | 103 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | — | yes | 581 | 65 | — |
| 15 | www.independent.co.uk | yes | — | yes | 923 | 67 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 16 | www.express.co.uk | yes | — | yes | 2722 | 110 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1181 | 36 | — |
| 18 | www.sofascore.com | yes | — | no | 11 | 1 | — |
| 19 | www.livescore.com | yes | — | yes | 623 | 50 | — |
| 20 | www.goal.com | yes | — | yes | 1521 | 101 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 398 | 21 | — |
| 22 | www.azlyrics.com | yes | — | yes | 966 | 85 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | yes | 1149 | 110 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 202 | 35 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 50 | 5 | — |
| 26 | convertio.co | yes | — | no | 23 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 139 | 5 | — |
| 28 | www.timeanddate.com | yes | — | yes | 96 | 9 | — |
| 29 | poki.com | yes | — | yes | 437 | 12 | — |
| 30 | www.crazygames.com | yes | — | yes | 558 | 5 | — |
| 31 | www.boredpanda.com | yes | — | yes | 680 | 84 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 32 | 9gag.com | yes | — | no | 91 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 1594 | 52 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 34 | ria.ru | yes | — | yes | 465 | 16 | — |
| 35 | www.gazeta.ru | yes | — | yes | 679 | 32 | — |
| 36 | www.kp.ru | yes | — | yes | 252 | 37 | — |
| 37 | www.sports.ru | yes | — | yes | 712 | 15 | — |
| 38 | www.blic.rs | yes | — | yes | 294 | 38 | page.hidden_iframe_after_load [suspicious] |
| 39 | www.kurir.rs | yes | — | yes | 699 | 62 | — |
| 40 | www.b92.net | yes | — | yes | 707 | 40 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 324 | 30 | — |
| 42 | www.masrawy.com | yes | — | yes | 607 | 48 | — |
| 43 | www.aljazeera.net | yes | — | yes | 403 | 24 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 315 | 29 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 427 | 38 | — |
| 47 | punchng.com | yes | — | yes | 526 | 38 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 48 | www.vanguardngr.com | yes | — | no | 11 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 427 | 42 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 467 | 48 | page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 4bf4968f2d1229b42be862a9ffb88502.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 4bf4968f2d1229b42be862a9ffb88502.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | ads.eu.criteo.com, dis.fr3.eu.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | imasdk.googleapis.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, lyr.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | 8fef346530ba97c8eea34142ba2bdc94.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | 8fef346530ba97c8eea34142ba2bdc94.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | 7e37646d5ae151098f1ba350e6df2386.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | 7e37646d5ae151098f1ba350e6df2386.safeframe.googlesyndication.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | 7e37646d5ae151098f1ba350e6df2386.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | csync-eu.smartadserver.com, eu-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | csync-eu.smartadserver.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | csync-eu.smartadserver.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | csync-eu.smartadserver.com, image6.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | 3c782a5a17ad3ebfa2b572b1243419cf.safeframe.googlesyndication.com, csync-global.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.lunamedia.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync-us-east.escalax.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, sync.rbstsystems.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, id5-sync.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, ssbsync-global.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, u-ams.4dex.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, ads.assemblyexchange.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | usync.ingage.tech, ads.assemblyexchange.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | 0a52907296a545c7bd9e3cd4dc2594f6.safeframe.googlesyndication.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | 0a52907296a545c7bd9e3cd4dc2594f6.safeframe.googlesyndication.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | 0a52907296a545c7bd9e3cd4dc2594f6.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | lenta.ru | vp.rambler.ru, mc.yandex.com |
| `page.hidden_iframe_after_load` | suspicious | lenta.ru | vp.rambler.ru, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.blic.rs | pulsembed.eu, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | ads.eu.criteo.com, dis.fr3.eu.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | b92adrs.hit.gemius.pl, ls.hit.gemius.pl |
| `page.hidden_iframe_after_load` | suspicious | punchng.com | 22c300926b375ada96d8d03ca3360886.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | punchng.com | 3c08cc3a7745cd07cf12e89ccc573721.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | punchng.com | 3c08cc3a7745cd07cf12e89ccc573721.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | punchng.com | googleads.g.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, imasdk.googleapis.com |
| `page.hidden_iframe_after_load` | suspicious | www.indiatimes.com | js-sec.indexww.com, ssum-sec.casalemedia.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
