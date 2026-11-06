# Interactive exposure run, chromium (iPhone 15 emulation) — 2026-11-06

Script: `scripts/exposure-run.mjs`. Evaluation build 0.2.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-iphone-15`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 1 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 43.
- Requests observed by the sensor: 28151. Third-party registrable domains per site, counted by this script from the page's own requests: median 31; 8 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 89 (89 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 398 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 530 | 60 | — |
| 2 | www.dagbladet.no | yes | — | yes | 562 | 39 | — |
| 3 | www.nettavisen.no | yes | — | yes | 390 | 25 | — |
| 4 | www.tv2.no | yes | — | yes | 425 | 17 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 403 | 25 | — |
| 6 | www.seher.no | yes | — | yes | 667 | 47 | — |
| 7 | www.kk.no | yes | — | yes | 608 | 31 | — |
| 8 | www.dinside.no | yes | — | no | 331 | 23 | — |
| 9 | www.klikk.no | yes | — | yes | 433 | 35 | page.hidden_iframe_after_load [suspicious] |
| 10 | www.dailymail.co.uk | yes | — | no | 478 | 61 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 11 | www.thesun.co.uk | yes | — | yes | 1271 | 113 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 12 | www.mirror.co.uk | yes | — | yes | 1818 | 136 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 791 | 86 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | text "OK" | yes | 710 | 66 | page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 604 | 56 | — |
| 16 | www.express.co.uk | yes | — | yes | 2910 | 121 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1229 | 60 | — |
| 18 | www.sofascore.com | yes | — | no | 10 | 1 | — |
| 19 | www.livescore.com | yes | — | yes | 579 | 47 | page.hidden_iframe_after_load [suspicious] |
| 20 | www.goal.com | yes | — | yes | 1247 | 78 | page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 435 | 21 | — |
| 22 | www.azlyrics.com | yes | — | yes | 1614 | 124 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | yes | 1006 | 94 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 238 | 39 | — |
| 25 | www.ilovepdf.com | yes | — | yes | 51 | 6 | — |
| 26 | convertio.co | yes | — | no | 18 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 156 | 7 | — |
| 28 | www.timeanddate.com | yes | — | yes | 88 | 8 | — |
| 29 | poki.com | yes | — | yes | 427 | 11 | — |
| 30 | www.crazygames.com | yes | — | yes | 552 | 31 | — |
| 31 | www.boredpanda.com | yes | — | yes | 242 | 26 | — |
| 32 | 9gag.com | yes | — | no | 99 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 919 | 39 | — |
| 34 | ria.ru | yes | — | yes | 475 | 17 | — |
| 35 | www.gazeta.ru | yes | — | yes | 508 | 31 | — |
| 36 | www.kp.ru | yes | — | yes | 245 | 43 | — |
| 37 | www.sports.ru | yes | — | yes | 438 | 16 | — |
| 38 | www.blic.rs | yes | — | yes | 298 | 32 | page.hidden_iframe_after_load [suspicious] |
| 39 | www.kurir.rs | yes | — | yes | 1047 | 79 | page.hidden_iframe_after_load [suspicious] |
| 40 | www.b92.net | yes | — | yes | 679 | 59 | page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 363 | 29 | — |
| 42 | www.masrawy.com | yes | — | yes | 349 | 38 | — |
| 43 | www.aljazeera.net | yes | — | yes | 292 | 17 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 317 | 29 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 400 | 30 | — |
| 47 | punchng.com | yes | — | yes | 282 | 21 | — |
| 48 | www.vanguardngr.com | yes | — | no | 11 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 411 | 44 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 188 | 24 | — |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 2e5b71cf0dfa641507d3f4976c254587.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 2e5b71cf0dfa641507d3f4976c254587.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 2195de14018e7cc5f620041171c61f1f.safeframe.googlesyndication.com, inviso.rampanel.com |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | ams.creativecdn.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | aax-eu.amazon-adsystem.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | aax-eu.amazon-adsystem.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aeb949aa9ed2d964e651e3aa07decc42.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | aeb949aa9ed2d964e651e3aa07decc42.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | www.foxnews.com, static.foxnews.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | ac837d8804d79c01822300269649b3b3.safeframe.googlesyndication.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | ac837d8804d79c01822300269649b3b3.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | aax-eu.amazon-adsystem.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ap.lijit.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | csync-eu.smartadserver.com, image6.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, hbx.media.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, hb.trustedstack.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | aax-eu.amazon-adsystem.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8011.ads.aps.amazon-adsystem.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8011.ads.aps.amazon-adsystem.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8011.ads.aps.amazon-adsystem.com, hbx.media.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8011.ads.aps.amazon-adsystem.com, hb.trustedstack.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8011.ads.aps.amazon-adsystem.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.pixad.com.tr, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | s.console.adtarget.com.tr, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | s.console.adtarget.com.tr, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, s.console.adtarget.com.tr |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ittpx.eskimi.com, dsp-service.pixad.com.tr |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.cootlogix.com, us-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.lunamedia.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync-us-east.escalax.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.blic.rs | pks.blic.rs, ls.hit.gemius.pl |
| `page.hidden_iframe_after_load` | suspicious | www.kurir.rs | csync-eu.smartadserver.com, image6.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | b92adrs.hit.gemius.pl, ls.hit.gemius.pl |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, imasdk.googleapis.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
