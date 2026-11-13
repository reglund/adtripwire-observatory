# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-13

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-pixel-5`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 43.
- Requests observed by the sensor: 37982. Third-party registrable domains per site, counted by this script from the page's own requests: median 39; 9 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 211 (210 suspicious, 1 informational). Contact with documented infrastructure (rules known_infra.*): 1.
- Cumulative in this profile: 2062 detections, 8 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | — | yes | 465 | 29 | — |
| 2 | www.dagbladet.no | yes | — | yes | 809 | 36 | page.hidden_iframe_after_load [suspicious] |
| 3 | www.nettavisen.no | yes | — | yes | 700 | 46 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.tv2.no | yes | — | yes | 545 | 33 | page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | — | yes | 418 | 25 | — |
| 6 | www.seher.no | yes | — | yes | 660 | 36 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 7 | www.kk.no | yes | — | yes | 562 | 30 | page.hidden_iframe_after_load [suspicious] |
| 8 | www.dinside.no | yes | — | no | 301 | 24 | page.hidden_iframe_after_load [suspicious] |
| 9 | www.klikk.no | yes | — | yes | 746 | 45 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 10 | www.dailymail.co.uk | yes | — | no | 548 | 66 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 11 | www.thesun.co.uk | yes | — | yes | 1207 | 109 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 12 | www.mirror.co.uk | yes | — | yes | 1967 | 128 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | — | yes | 1030 | 81 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | — | yes | 655 | 64 | page.hidden_iframe_after_load [suspicious] |
| 15 | www.independent.co.uk | yes | — | yes | 1207 | 107 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 16 | www.express.co.uk | yes | — | yes | 2953 | 171 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | — | yes | 1293 | 42 | — |
| 18 | www.sofascore.com | yes | — | no | 10 | 1 | — |
| 19 | www.livescore.com | yes | — | yes | 771 | 68 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 20 | www.goal.com | yes | — | yes | 1136 | 55 | page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | — | yes | 761 | 67 | — |
| 22 | www.azlyrics.com | yes | — | yes | 6919 | 159 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | — | yes | 804 | 103 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.speedtest.net | yes | — | yes | 460 | 93 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 25 | www.ilovepdf.com | yes | — | yes | 50 | 4 | — |
| 26 | convertio.co | yes | — | no | 21 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 163 | 8 | — |
| 28 | www.timeanddate.com | yes | — | yes | 89 | 8 | — |
| 29 | poki.com | yes | — | yes | 448 | 11 | — |
| 30 | www.crazygames.com | yes | — | yes | 571 | 7 | — |
| 31 | www.boredpanda.com | yes | — | yes | 233 | 24 | — |
| 32 | 9gag.com | yes | — | no | 95 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 1458 | 82 | page.hidden_iframe_after_load [suspicious]<br>known_infra.surveillance_contact [suspicious]<br>exposure.repeated_surveillance_contact [informational] |
| 34 | ria.ru | yes | — | yes | 433 | 19 | — |
| 35 | www.gazeta.ru | yes | — | yes | 691 | 66 | — |
| 36 | www.kp.ru | yes | — | yes | 280 | 38 | — |
| 37 | www.sports.ru | yes | — | yes | 419 | 16 | — |
| 38 | www.blic.rs | yes | — | yes | 347 | 39 | — |
| 39 | www.kurir.rs | yes | — | yes | 1126 | 98 | — |
| 40 | www.b92.net | yes | — | yes | 1021 | 69 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 471 | 39 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 42 | www.masrawy.com | yes | — | yes | 656 | 95 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 43 | www.aljazeera.net | yes | — | yes | 345 | 17 | — |
| 44 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 331 | 29 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 451 | 32 | page.hidden_iframe_after_load [suspicious] |
| 47 | punchng.com | yes | — | yes | 269 | 22 | — |
| 48 | www.vanguardngr.com | yes | — | no | 11 | 1 | — |
| 49 | www.ndtv.com | yes | — | yes | 427 | 46 | page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 642 | 47 | page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.dagbladet.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | bb07d3488ef3bf75a0c0e711d02b1241.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | bb07d3488ef3bf75a0c0e711d02b1241.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.nettavisen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 12c9600ecfb9b029857bc4878c8347d0.safeframe.googlesyndication.com, inviso.rampanel.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | 194107e72b91d54110545083b0271631.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | 194107e72b91d54110545083b0271631.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | fa8ee031654a6a4248c0218b7691c756.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | fa8ee031654a6a4248c0218b7691c756.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dinside.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.klikk.no | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | elb.the-ozone-project.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | elb.the-ozone-project.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | elb.the-ozone-project.com, rtb.gumgum.com |
| `page.hidden_iframe_after_load` | suspicious | www.thesun.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | elb.the-ozone-project.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | elb.the-ozone-project.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | pbs-cs.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | pbs-cs.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | elb.the-ozone-project.com, pbs-cs.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | elb.the-ozone-project.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | www.youtube.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | ads.eu.criteo.com, dis.fr3.eu.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.foxnews.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | elb.the-ozone-project.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | bids.ws, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.independent.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | elb.the-ozone-project.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | elb.the-ozone-project.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | pbs-cs.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | pbs-cs.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | elb.the-ozone-project.com, pbs-cs.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | ads.eu.criteo.com, dis.fr3.eu.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ms-cookie-sync.presage.io, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ms-cookie-sync.presage.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | ms-cookie-sync.presage.io, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.livescore.com | prebid.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, lyr.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, sync.rbstsystems.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | sync.kueezrtb.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, u-ams.4dex.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, b1sync.outbrain.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, ms-cookie-sync.presage.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | dsp-service.monetixads.com, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.lunamedia.live |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync-us-east.escalax.io |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | ssp.api.tappx.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rt.marphezis.com, eu-rtbstack-cm.admixer.net |
| `page.hidden_iframe_after_load` | suspicious | genius.com | rt.marphezis.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | genius.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, sync-us-east.escalax.io |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, sync.lunamedia.live |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, syncingbridge.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, prebid-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, user-sync.fwmrm.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | ssp.api.tappx.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.speedtest.net | prebid.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | lenta.ru | vp.rambler.ru, ep2.adtrafficquality.google |
| `known_infra.surveillance_contact` | suspicious | lenta.ru | events.myweb3id.io |
| `exposure.repeated_surveillance_contact` | informational | lenta.ru | events.myweb3id.io |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | ads.eu.criteo.com, dis.fr3.eu.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | sync.connectad.io, pbam.orangeclickmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | sync.connectad.io, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | sync.connectad.io, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | sync.connectad.io, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | sync.connectad.io, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | sync.connectad.io, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | sync.connectad.io, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | sync.connectad.io, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | sync.connectad.io, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | pbam.orangeclickmedia.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | pbam.orangeclickmedia.com, sync.connectad.io |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | pbam.orangeclickmedia.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | pbam.orangeclickmedia.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | rt.marphezis.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | b92adrs.hit.gemius.pl, ls.hit.gemius.pl |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | prebid.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.adtarget.biz, prebid.a-mo.net |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.adtarget.biz, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.adtarget.biz, x.bidswitch.net |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | dsp-service.adtarget.biz, image8.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, sync.richaudience.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, ssp.wp.pl |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, gum.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, ssp-sync.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, ssbsync-global.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.youm7.com | m.youm7.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
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
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | public.servenobid.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cpm.vistarsagency.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ittpx.eskimi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, sync.adkernel.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, ssc-cms.33across.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, measureadv.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, public.servenobid.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | visitor.omnitagjs.com, eu-west-1-cs-rtb.openwebmp.com |
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
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, beachfront-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.sozcu.com.tr | www.youtube.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.indiatimes.com | js-sec.indexww.com, ssum-sec.casalemedia.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
