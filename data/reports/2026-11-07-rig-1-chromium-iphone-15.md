# Interactive exposure run, chromium (iPhone 15 emulation) — 2026-11-07

Script: `scripts/exposure-run.mjs`. Evaluation build 0.3.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-iphone-15`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 50; loaded 50; consent clicked on 25 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 44.
- Requests observed by the sensor: 30534. Third-party registrable domains per site, counted by this script from the page's own requests: median 31; 7 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 52 (52 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 52 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.vg.no | yes | selector button.sp_choice_type_11 | yes | 548 | 34 | — |
| 2 | www.dagbladet.no | yes | selector button.sp_choice_type_11 | yes | 561 | 48 | — |
| 3 | www.nettavisen.no | yes | selector button.sp_choice_type_11 | yes | 623 | 34 | — |
| 4 | www.tv2.no | yes | selector button.sp_choice_type_11 | yes | 530 | 29 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 5 | www.finn.no | yes | selector button.sp_choice_type_11 | yes | 395 | 26 | — |
| 6 | www.seher.no | yes | selector button.sp_choice_type_11 | yes | 653 | 40 | — |
| 7 | www.kk.no | yes | selector button.sp_choice_type_11 | yes | 606 | 38 | — |
| 8 | www.dinside.no | yes | — | no | 274 | 23 | — |
| 9 | www.klikk.no | yes | selector button.sp_choice_type_11 | yes | 385 | 28 | — |
| 10 | www.dailymail.co.uk | yes | text "Accept" | no | 820 | 89 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 11 | www.thesun.co.uk | yes | selector button.sp_choice_type_11 | yes | 1393 | 94 | — |
| 12 | www.mirror.co.uk | yes | selector .qc-cmp2-summary-buttons button[mode=primary] | yes | 1677 | 111 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 13 | nypost.com | yes | selector #onetrust-accept-btn-handler | yes | 835 | 88 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | www.foxnews.com | yes | — | yes | 638 | 66 | — |
| 15 | www.independent.co.uk | yes | — | yes | 864 | 66 | — |
| 16 | www.express.co.uk | yes | selector .qc-cmp2-summary-buttons button[mode=primary] | yes | 2873 | 139 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.flashscore.com | yes | selector #onetrust-accept-btn-handler | yes | 1539 | 46 | — |
| 18 | www.sofascore.com | yes | — | no | 12 | 1 | — |
| 19 | www.livescore.com | yes | selector #onetrust-accept-btn-handler | yes | 819 | 53 | — |
| 20 | www.goal.com | yes | selector button.sp_choice_type_11 | yes | 1123 | 70 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 21 | www.espn.com | yes | selector #onetrust-accept-btn-handler | yes | 487 | 21 | — |
| 22 | www.azlyrics.com | yes | selector #CybotCookiebotDialogBodyButtonAccept | yes | 1128 | 87 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 23 | genius.com | yes | selector #onetrust-accept-btn-handler | no | 154 | 26 | — |
| 24 | www.speedtest.net | yes | selector #onetrust-accept-btn-handler | yes | 259 | 41 | — |
| 25 | www.ilovepdf.com | yes | — | yes | 51 | 5 | — |
| 26 | convertio.co | yes | — | no | 24 | 5 | — |
| 27 | www.online-convert.com | yes | — | yes | 165 | 7 | — |
| 28 | www.timeanddate.com | yes | — | yes | 92 | 8 | — |
| 29 | poki.com | yes | selector .qc-cmp2-summary-buttons button[mode=primary] | yes | 442 | 11 | — |
| 30 | www.crazygames.com | yes | selector button.sp_choice_type_11 | yes | 568 | 7 | — |
| 31 | www.boredpanda.com | yes | selector button#didomi-notice-agree-button | yes | 1198 | 128 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 32 | 9gag.com | yes | — | no | 92 | 3 | — |
| 33 | lenta.ru | yes | — | yes | 1207 | 38 | — |
| 34 | ria.ru | yes | — | yes | 497 | 19 | — |
| 35 | www.gazeta.ru | yes | — | yes | 556 | 30 | — |
| 36 | www.kp.ru | yes | — | yes | 262 | 36 | — |
| 37 | www.sports.ru | yes | — | yes | 449 | 16 | — |
| 38 | www.blic.rs | yes | — | yes | 269 | 28 | page.hidden_iframe_after_load [suspicious] |
| 39 | www.kurir.rs | yes | — | yes | 1001 | 59 | — |
| 40 | www.b92.net | yes | selector button#didomi-notice-agree-button | yes | 954 | 51 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 41 | www.youm7.com | yes | — | yes | 398 | 31 | — |
| 42 | www.masrawy.com | yes | — | yes | 358 | 41 | — |
| 43 | www.aljazeera.net | yes | selector #onetrust-accept-btn-handler | yes | 436 | 20 | — |
| 44 | www.alarabiya.net | yes | — | yes | 171 | 15 | — |
| 45 | www.hurriyet.com.tr | yes | — | yes | 326 | 30 | — |
| 46 | www.sozcu.com.tr | yes | — | yes | 415 | 31 | — |
| 47 | punchng.com | yes | — | yes | 303 | 23 | — |
| 48 | www.vanguardngr.com | yes | — | yes | 303 | 23 | — |
| 49 | www.ndtv.com | yes | — | yes | 438 | 46 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 50 | www.indiatimes.com | yes | — | yes | 363 | 28 | — |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 971c2e4a21c59ea5af281b7a29481503.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 971c2e4a21c59ea5af281b7a29481503.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | 971c2e4a21c59ea5af281b7a29481503.safeframe.googlesyndication.com, visitanalytics.userreport.com |
| `page.hidden_iframe_after_load` | suspicious | www.tv2.no | aee43ce9cce6ea329b3ffb57b4e09588.safeframe.googlesyndication.com, inviso.rampanel.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | csync-eu.smartadserver.com, image6.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | csync-eu.smartadserver.com, eu-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | csync-eu.smartadserver.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | csync-eu.smartadserver.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dailymail.co.uk | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.mirror.co.uk | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | cdd12e78a0997e77cd44342c04154103.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | cdd12e78a0997e77cd44342c04154103.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | be83fbd09e07fbaaf51bacfabc8718f2.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | be83fbd09e07fbaaf51bacfabc8718f2.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | nypost.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | 74d481724158308412b17f7e79bfd679.safeframe.googlesyndication.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | 74d481724158308412b17f7e79bfd679.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.express.co.uk | 74d481724158308412b17f7e79bfd679.safeframe.googlesyndication.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | am-match.taboola.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | am-match.taboola.com, us-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | am-match.taboola.com, ssum.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.goal.com | am-match.taboola.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, hbx.media.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, hb.trustedstack.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, googleads.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | web-cf-event-cell8012.ads.aps.amazon-adsystem.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.azlyrics.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.boredpanda.com | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.blic.rs | pks.blic.rs, ls.hit.gemius.pl |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | ads.eu.criteo.com, dis.fr3.eu.criteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.b92.net | b92adrs.hit.gemius.pl, ls.hit.gemius.pl |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, aax-eu.amazon-adsystem.com |
| `page.hidden_iframe_after_load` | suspicious | www.ndtv.com | www.ndtv.com, imasdk.googleapis.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
