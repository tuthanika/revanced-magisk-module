YouTube-Extended: 18.27.35  
Music-Extended (arm64-v8a): 6.11.52  
TikTok: 30.5.3  
Messenger: 418.0.0.11.71  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: j-hc/revanced-cli-2.23.0-all.jar  
Integrations: ReVanced/revanced-integrations-0.114.0.apk  
Patches: ReVanced/revanced-patches-2.186.0.jar  

### [2.186.0](https://github.com/ReVanced/revanced-patches/compare/v2.185.0...v2.186.0) (2023-07-21)


### Bug Fixes

* **Tiktok - Settings:** get instruction registers dynamically ([#2676](https://github.com/ReVanced/revanced-patches/issues/2676)) ([b34e45b](https://github.com/ReVanced/revanced-patches/commit/b34e45b6dafad8e9d567ad65f58a182b8cc04676))
* **YouTube - Spoof app version:** update target app version description ([#2666](https://github.com/ReVanced/revanced-patches/issues/2666)) ([307442e](https://github.com/ReVanced/revanced-patches/commit/307442e654ff5486656319d91e4a5f5fb2b92651))
* **YouTube - Theme:** allow setting no background color ([8a4e77a](https://github.com/ReVanced/revanced-patches/commit/8a4e77a290a61a1caf93eb8bccaf728c84a3ef53))
* **YouTube - Theme:** apply custom seekbar color to shorts ([#2670](https://github.com/ReVanced/revanced-patches/issues/2670)) ([1f6fe3d](https://github.com/ReVanced/revanced-patches/commit/1f6fe3da4284fd768057ef068c7ddf88d3a11049))


### Features

* **Twitter:** remove `Hide view stats` patch ([f0d3800](https://github.com/ReVanced/revanced-patches/commit/f0d38001b34db63f212209afb91eebf59dad2b24))
* **Youtube - Theme:** add a switch to enable/disable custom seekbar color ([#2663](https://github.com/ReVanced/revanced-patches/issues/2663)) ([5c39985](https://github.com/ReVanced/revanced-patches/commit/5c39985888cdfe3acfdd8811ff9b6f80e243704e))




---
CLI: inotia00/revanced-cli-2.22.2-all.jar  
Integrations: inotia00/revanced-integrations-0.114.4.apk  
Patches: inotia00/revanced-patches-2.186.4.jar  

YouTube
==
- feat(youtube/hide-suggested-video-overlay): no longer dependent on `overlay-buttons` patches https://github.com/inotia00/ReVanced_Extended/issues/1210
- fix(youtube): remove dummy code
- fix(youtube): some fingerprints are located in the wrong path
- fix(youtube/enable-old-quality-layout): do not use low level filter anymore
- fix(youtube/hide-shorts-components): sometimes shorts shelves are not hidden
- fix(youtube/hide-suggested-actions): not hidden normally in some situations
- fix(youtube/overlay-buttons): remove unnecessary dependencies
- fix(youtube/swipe-controls): When `Press-to-swipe` is disabled, `Press-to-swipe haptic feedback` should also be disabled https://github.com/inotia00/ReVanced_Extended/issues/811
- feat(youtube/translations): update translation
`Chinese Traditional`, `French`, `German`, `Italian`, `Korean`, `Russian`, `Turkish`


Music
==
- feat(music/translations): update translation
`Vietnamese`


MicroG
==
- feat(microg): temporary suspension of support for all patches https://github.com/inotia00/ReVanced_Extended/issues/1207


Reddit
==
- feat(reddit): add `hide-place-button` patch


※ Compatible ReVanced Manager: [RVX Manager v1.4.3 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.4.3)

[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---  
