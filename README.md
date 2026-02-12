# personal-HEVC
Personal HEVC builds

First off, those looking for a great solution please see @avdvplus builds for a continuation of my original cpm build with many new features and fixes, or the CoreELEC builds for the most solid standard experience.

This area is for my personal builds and use it for simple distribution to friends and family etc. something I can point people to for my build simply.

You are welcome to try if you really want but it is as-is, as mentioned other solutions above are well supported with large communities to help.
It is at my own pace and would expect any good/useful features to make it into the more community focused builds from @avdvplus, so no need to track this.

Also note this build is for Amlogic S922X SoC.

2026-01-14 Initial planned release (2026-Jan)
-  Kodi Piers (CoreELEC 22 - LibreELEC tracking base)
-  My changes refactored for Kodi Piers, plus my other fixes from over the last few months
-  Couple of fixes from @avdvplus, includes LAV work from @SamuriHL, but not incorporating other new features like dv processor
-  Amlogic 4.9 Kernel

2026-01-30 
- Upstream tracking changes
- Personal work, including HDR PGS
- Additional cherry picks from @avdvplus, background ops idea from @MasterKeyxda, GUILib enhancements from @pannal

2026-02-03
- logging fix

2026-02-06
- minor fixes from ongoing git series restructing for upgrades - expect to complete within a few weeks/month spare time permitting.
- attempts to keep video ready just before vsync, but looks to cause OSD tearing sometimes (likley effects moving subtitles - can try pause and play to get better phase)

2026-02-07
- DTS-HD MA testing

2026-02-08
- Build from public heads, minor improvements and fixes, significantly reduce intensity of red in CoreELEC logo for OLED burn in risk

2026-02-09
- Dialogue Normalisation for True HD Atmos fix to -31 [0 dB] (Testing)

2026-02-12
- Dialogue Normalisation for AC3/EAC3 fix to -31 [0 dB] (Testing)
- UI for Dolby Dialogue Normalisation defeat
- Refresh to latest upstream heads
- Reduce Delta of sync ng (WIP)
- Minor fixes and enhancements
- Most notable user experience change is effective instant skipping, no decernable gap, MAT audio passthough still takes a little time to re-engage, FEL blanking has been fixed for a while, this tightneas eveything up.
