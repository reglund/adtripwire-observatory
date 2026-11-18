# Interactive exposure run, chromium (Pixel 5 emulation) — 2026-11-18

Script: `scripts/exposure-run.mjs`. Evaluation build 0.5.0 (production indicator set, adfection-2026 2026.11.02), headless chromium, persistent profile `~/snap/chromium/common/adtripwire-exposure-profile-chromium-pixel-5-norway`, 60 s per site, consent accepted where a dialog was recognised, scrolled, one article opened. Capabilities: request_metadata, redirect_chain, response_headers, response_size, frame_ancestry, page_signals.

## Summary

- Sites: 24; loaded 24; consent clicked on 0 (no click means no dialog was recognised, or consent was already stored in this persistent profile); article opened on 22.
- Requests observed by the sensor: 11706. Third-party registrable domains per site, counted by this script from the page's own requests: median 33; 0 loaded site(s) contacted fewer than 10, which suggests few or no ad auctions ran there.
- Detections: 38 (38 suspicious). Contact with documented infrastructure (rules known_infra.*): 0.
- Cumulative in this profile: 1052 detections, 0 known-infrastructure observations, 0 high priority.

## Per site

| # | Site | Loaded | Consent clicked | Article | Requests (sensor) | 3rd-party domains (page) | Detections |
|---:|---|:-:|---|:-:|---:|---:|---|
| 1 | www.aftenposten.no | yes | — | yes | 319 | 27 | — |
| 2 | www.dagsavisen.no | yes | — | yes | 421 | 43 | page.hidden_iframe_after_load [suspicious] |
| 3 | www.abcnyheter.no | yes | — | yes | 457 | 49 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 4 | www.vl.no | yes | — | yes | 336 | 35 | — |
| 5 | www.nationen.no | yes | — | yes | 452 | 33 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 6 | www.klassekampen.no | yes | — | yes | 313 | 11 | — |
| 7 | e24.no | yes | — | yes | 545 | 28 | — |
| 8 | www.dn.no | yes | — | yes | 1307 | 46 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 9 | www.finansavisen.no | yes | — | yes | 863 | 56 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 10 | www.bt.no | yes | — | yes | 299 | 25 | — |
| 11 | www.adressa.no | yes | — | yes | 272 | 24 | — |
| 12 | www.fvn.no | yes | — | yes | 364 | 23 | — |
| 13 | www.aftenbladet.no | yes | — | yes | 296 | 27 | — |
| 14 | www.nordlys.no | yes | — | yes | 616 | 33 | page.hidden_iframe_after_load [suspicious] |
| 15 | www.itromso.no | yes | — | yes | 243 | 21 | — |
| 16 | www.sa.no | yes | — | yes | 715 | 45 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 17 | www.oa.no | yes | — | yes | 642 | 33 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 18 | www.rb.no | yes | — | yes | 754 | 33 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 19 | www.tek.no | yes | — | yes | 326 | 30 | — |
| 20 | www.side3.no | yes | — | no | 262 | 32 | — |
| 21 | www.hegnar.no | yes | — | no | 462 | 50 | page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious]<br>page.hidden_iframe_after_load [suspicious] |
| 22 | www.kk.no | yes | — | yes | 557 | 29 | page.hidden_iframe_after_load [suspicious] |
| 23 | www.seher.no | yes | — | yes | 649 | 33 | page.hidden_iframe_after_load [suspicious] |
| 24 | www.godt.no | yes | — | yes | 236 | 20 | — |

## Detections

| Rule | Severity | Site | Subject hostnames |
|---|---|---|---|
| `page.hidden_iframe_after_load` | suspicious | www.dagsavisen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | euw2-sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.abcnyheter.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.nationen.no | fb0b1b61b742c08b7ec529d64b647b0d.safeframe.googlesyndication.com, inviso.rampanel.com |
| `page.hidden_iframe_after_load` | suspicious | www.nationen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, pixel.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | euw2-sync.a-mo.net, ad.360yield.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, cm.adform.net |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | sync-eu.connectad.io, ib.adnxs.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | cdn.connectad.io, sync-eu.connectad.io |
| `page.hidden_iframe_after_load` | suspicious | www.dn.no | www.dn.no, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, btloader.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, sync.sparteo.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, ads.pubmatic.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, js-sec.indexww.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, eus.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, cm.g.doubleclick.net |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | tv.finansavisen.no, cdn.btloader.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | ms-cookie-sync.presage.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.finansavisen.no | ms-cookie-sync.presage.io, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.nordlys.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.sa.no | 4e5926d1808955c1d92f494d16941032.safeframe.googlesyndication.com, inviso.rampanel.com |
| `page.hidden_iframe_after_load` | suspicious | www.sa.no | ad.doubleclick.net, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.sa.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.oa.no | 005207a03ff8b6491f3df30e989faa5e.safeframe.googlesyndication.com, inviso.rampanel.com |
| `page.hidden_iframe_after_load` | suspicious | www.oa.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.rb.no | 3cb0af2c5a36d2a5227858f2aa7be159.safeframe.googlesyndication.com, inviso.rampanel.com |
| `page.hidden_iframe_after_load` | suspicious | www.rb.no | 3cb0af2c5a36d2a5227858f2aa7be159.safeframe.googlesyndication.com, ep2.adtrafficquality.google |
| `page.hidden_iframe_after_load` | suspicious | www.rb.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | ms-cookie-sync.presage.io, secure-assets.rubiconproject.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | ms-cookie-sync.presage.io, ssbsync.smartadserver.com |
| `page.hidden_iframe_after_load` | suspicious | www.hegnar.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.kk.no | js-sec.indexww.com, ssum-sec.casalemedia.com |
| `page.hidden_iframe_after_load` | suspicious | www.seher.no | js-sec.indexww.com, ssum-sec.casalemedia.com |

## Reading this

- Results come from the extension's own UI protocol (status and detection list), not from parsed console output, so a page cannot forge them.
- No detection of a documented host means that host did not appear in the ad auctions this profile took part in during this run; it says nothing about other profiles, networks, devices or days. The repeated-exposure rule needs three distinct days in the same profile.
- Consent recognition is heuristic; sites where consent was not clicked ran fewer or no auctions.
