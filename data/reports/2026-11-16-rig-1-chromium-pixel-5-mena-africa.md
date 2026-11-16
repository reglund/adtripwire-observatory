# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-16

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-chromium-pixel-5-mena-africa`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 25; loaded 25; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 17.
- Requests observed by the sensor: 9626. Third-party registrable domains per site, counted by this script from the page's own requests: median 22; 6 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 75 (75 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 1015 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.youm7.com | yes | — | yes | 380 | 35 | — |
| 2 | www.masrawy.com | yes | — | yes | 571 | 33 | — |
| 3 | www.almasryalyoum.com | yes | — | yes | 933 | 78 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.elwatannews.com | yes | — | no | 12 | 1 | — |
| 5 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 6 | www.albayan.ae | yes | — | yes | 193 | 11 | — |
| 7 | www.alittihad.ae | yes | — | no | 150 | 13 | — |
| 8 | www.okaz.com.sa | yes | — | yes | 178 | 15 | — |
| 9 | sabq.org | yes | — | yes | 561 | 27 | — |
| 10 | www.alghad.com | yes | — | no | 15 | 2 | — |
| 11 | www.annahar.com | yes | — | yes | 354 | 41 | — |
| 12 | www.hespress.com | yes | — | yes | 105 | 15 | — |
| 13 | www.elkhabar.com | yes | — | yes | 420 | 13 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | punchng.com | yes | — | yes | 294 | 22 | — |
| 15 | www.vanguardngr.com | yes | — | no | 12 | 1 | — |
| 16 | www.legit.ng | yes | — | yes | 226 | 32 | — |
| 17 | www.pulse.ng | yes | — | yes | 241 | 21 | — |
| 18 | www.nairaland.com | yes | — | no | 11 | 1 | — |
| 19 | www.tuko.co.ke | yes | — | yes | 1434 | 129 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 20 | nation.africa | yes | — | no | 12 | 1 | — |
| 21 | www.the-star.co.ke | yes | — | yes | 1733 | 112 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 22 | www.news24.com | yes | — | yes | 367 | 35 | — |
| 23 | www.iol.co.za | yes | — | yes | 643 | 97 | page.hidden_iframe_after_load [suspicious] |
| 24 | www.timeslive.co.za | yes | — | yes | 360 | 44 | — |
| 25 | www.sowetanlive.co.za | yes | — | no | 414 | 77 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | imasdk.googleapis.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | 56a39fe617692ce7e8b222b5c370e4e2.safeframe.googlesyndication.com, cdn.mediago.io |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | c15a5e50162539bbc56cdde371d1f402.safeframe.googlesyndication.com, static.admaster.cc |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, image6.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, eu-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, sync.1rx.io |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, cs.admanmedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, sync.srv.stackadapt.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, sync.ipredictive.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, beachfront-match.dotomi.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, pixel-sync.sitescout.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, match.sharethrough.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, match.prod.bidr.io |
| `page.hidden_iframe_after_load` | suspicious | www.elkhabar.com | e8514476f8412b2d6f4b4c094011b2bb.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.elkhabar.com | e8514476f8412b2d6f4b4c094011b2bb.safeframe.googlesyndication.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | cs.seedtag.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | cs-server-s2s.yellowblue.io, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | cs-server-s2s.yellowblue.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | usync.ingage.tech, id5-sync.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | usync.ingage.tech, eb2.3lift.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | usync.ingage.tech, ssbsync-global.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | usync.ingage.tech, cs-server-s2s.yellowblue.io |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | usync.ingage.tech, cs-rtb.minutemedia-prebid.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | usync.ingage.tech, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | usync.ingage.tech, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | usync.ingage.tech, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | usync.ingage.tech, ap.lijit.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | usync.ingage.tech, pbs2.cpmstar.com |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | rt.marphezis.com, u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.tuko.co.ke | b4fba0ab5cd17866a1534b02ee662daa.safeframe.googlesyndication.com, cdn.mediago.io |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | prebid.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | user-sync.fwmrm.net, pbsj.bricks-co.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | am-match.taboola.com, ssum.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tempest.services.disqus.com, imprammp.taboola.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tempest.services.disqus.com, am-match.taboola.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.iol.co.za | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | user-sync.fwmrm.net, pbsj.bricks-co.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
