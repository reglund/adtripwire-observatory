# Interactive exposure run, chromium — 2026-11-20

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-chromium-mena-africa`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 25; loaded 25; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 9.
- Requests observed by the sensor: 4530. Third-party registrable domains per site, counted by this script from the page's own requests: median 1; 14 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 50 (50 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 884 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.youm7.com | yes | — | yes | 666 | 49 | — |
| 2 | www.masrawy.com | yes | — | yes | 390 | 52 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 3 | www.almasryalyoum.com | yes | — | no | 12 | 1 | — |
| 4 | www.elwatannews.com | yes | — | no | 13 | 1 | — |
| 5 | www.alarabiya.net | yes | — | no | 7 | 1 | — |
| 6 | www.albayan.ae | yes | — | yes | 229 | 11 | — |
| 7 | www.alittihad.ae | yes | — | no | 162 | 12 | — |
| 8 | www.okaz.com.sa | yes | — | no | 1 | 0 | — |
| 9 | sabq.org | yes | — | no | 13 | 1 | — |
| 10 | www.alghad.com | yes | — | no | 13 | 1 | — |
| 11 | www.annahar.com | yes | — | yes | 374 | 39 | — |
| 12 | www.hespress.com | yes | — | no | 7 | 1 | — |
| 13 | www.elkhabar.com | yes | — | yes | 304 | 12 | — |
| 14 | punchng.com | yes | — | yes | 274 | 19 | — |
| 15 | www.vanguardngr.com | yes | — | no | 12 | 1 | — |
| 16 | www.legit.ng | yes | — | no | 2 | 0 | — |
| 17 | www.pulse.ng | yes | — | yes | 263 | 19 | — |
| 18 | www.nairaland.com | yes | — | no | 12 | 1 | — |
| 19 | www.tuko.co.ke | yes | — | no | 13 | 1 | — |
| 20 | nation.africa | yes | — | no | 11 | 1 | — |
| 21 | www.the-star.co.ke | yes | — | yes | 1201 | 113 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 22 | www.news24.com | yes | — | no | 12 | 1 | — |
| 23 | www.iol.co.za | yes | — | no | 8 | 1 | — |
| 24 | www.timeslive.co.za | yes | — | yes | 299 | 43 | — |
| 25 | www.sowetanlive.co.za | yes | — | no | 232 | 68 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, csync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.masrawy.com | cs.seedtag.com, ad.360yield.com |
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
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | am-match.taboola.com, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | am-match.taboola.com, us-u.openx.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | onetag-sys.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | user-sync.fwmrm.net, pbsj.bricks-co.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | am-match.taboola.com, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | am-match.taboola.com, ssum.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tempest.services.disqus.com, am-match.taboola.com |
| `page.hidden_iframe_after_load` | suspicious | www.the-star.co.ke | tempest.services.disqus.com, imprammp.taboola.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, match.adsrvr.org |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, sync.pmbmonetize.live |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, onetag-sys.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, csync.loopme.me |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, sync-tm.everesttech.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, p.rfihub.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, creativecdn.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, dsp.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, c1.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | rtb.gumgum.com, t.adx.opera.com |
| `page.hidden_iframe_after_load` | suspicious | www.sowetanlive.co.za | user-sync.fwmrm.net, pbsj.bricks-co.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
