# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-26

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-chromium-pixel-5-mena-africa`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 25; loaded 25; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 17.
- Requests observed by the sensor: 7828. Third-party registrable domains per site, counted by this script from the page's own requests: median 21; 6 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 54 (54 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 1645 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.youm7.com | yes | — | yes | 336 | 36 | — |
| 2 | www.masrawy.com | yes | — | yes | 508 | 29 | — |
| 3 | www.almasryalyoum.com | yes | — | yes | 891 | 75 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.elwatannews.com | yes | — | no | 12 | 1 | — |
| 5 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 6 | www.albayan.ae | yes | — | yes | 217 | 11 | — |
| 7 | www.alittihad.ae | yes | — | no | 170 | 13 | — |
| 8 | www.okaz.com.sa | yes | — | yes | 147 | 13 | — |
| 9 | sabq.org | yes | — | yes | 540 | 26 | — |
| 10 | www.alghad.com | yes | — | no | 13 | 1 | — |
| 11 | www.annahar.com | yes | — | yes | 442 | 43 | — |
| 12 | www.hespress.com | yes | — | yes | 142 | 18 | — |
| 13 | www.elkhabar.com | yes | — | yes | 447 | 15 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 14 | punchng.com | yes | — | yes | 279 | 21 | — |
| 15 | www.vanguardngr.com | yes | — | no | 12 | 1 | — |
| 16 | www.legit.ng | yes | — | yes | 264 | 35 | — |
| 17 | www.pulse.ng | yes | — | yes | 207 | 19 | — |
| 18 | www.nairaland.com | yes | — | no | 11 | 1 | — |
| 19 | www.tuko.co.ke | yes | — | yes | 268 | 35 | — |
| 20 | nation.africa | yes | — | no | 11 | 1 | — |
| 21 | www.the-star.co.ke | yes | — | yes | 1203 | 99 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 22 | www.news24.com | yes | — | yes | 372 | 36 | — |
| 23 | www.iol.co.za | yes | — | yes | 660 | 67 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 24 | www.timeslive.co.za | yes | — | yes | 401 | 46 | — |
| 25 | www.sowetanlive.co.za | yes | — | no | 268 | 70 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | imasdk.googleapis.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, image6.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, eu-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, ad.turn.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | csync.smartadserver.com, ssum-sec.casalemedia.com |
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
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.almasryalyoum.com | cs.seedtag.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.elkhabar.com | 1e6fa756bb2fbb1a1f9fe38bf88257e7.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.elkhabar.com | 1e6fa756bb2fbb1a1f9fe38bf88257e7.safeframe.googlesyndication.com, pagead2.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | prebid.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | user-sync.fwmrm.net, pbsj.bricks-co.com |
| `page.hidden_iframe_after_load` | suspicious | www.iol.co.za | imasdk.googleapis.com, tpc.googlesyndication.com |
| `page.hidden_iframe_after_load` | suspicious | www.iol.co.za | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | user-sync.fwmrm.net, pbsj.bricks-co.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
