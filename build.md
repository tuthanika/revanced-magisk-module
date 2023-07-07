YouTube: 18.19.35  
YouTube-Extended: 18.25.39  
Music (arm64-v8a): 6.08.50  
Music-Extended (arm64-v8a): 6.08.50  
Music (arm-v7a): 6.08.50  
Music-Extended (arm-v7a): 6.08.50  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: j-hc/revanced-cli-2.22.0-all.jar  
Integrations: inotia00/revanced-integrations-0.111.4.apk  
Patches: inotia00/revanced-patches-2.181.4.jar  

YouTube
==
- feat(youtube/old-quality-layout): disable preference in versions with new player flyout layout
- feat(youtube/custom-video-speed): disable preference in versions with new player flyout layout
- fix(youtube): compilation fails in ReVanced Manager
- fix(youtube/sponsorblock): patch fails when `hide-seekbar` patch is excluded https://github.com/inotia00/ReVanced_Extended/issues/1037
- feat(youtube/spoof-player-parameters): do not change parameters for 403 response in minimized playback or background playback
- feat(youtube/translations): update translation
`Chinese Simplified`, `French`, `Japanese`, `Korean`, `Polish`, `Russian`, `Vietnamese`


YouTube Music
==
- fix(music/disable-auto-captions): failed to resolve SubtitleTrackFingerprint https://github.com/inotia00/ReVanced_Extended/issues/1044
- fix(youtube/litho-filter): incorrect smali syntax
- feat(music/translations): update translation
`French`, `German`, `Polish`


Reddit
==
- feat(reddit/hide-navigation-buttons): split into `hide-discover-button`, `hide-chat-button`, `hide-create-button`
- feat(reddit/reddit-settings): preferences are added to settings only when `options.json` values are specified
(So when patching with ReVanced Manager, no switches are added to the settings. for compatibility with ReVanced Manager)
- fix(reddit/hide-comment-ads): patch is broken in old versions


Etc
==
- add support YouTube v18.25.39


※ Compatible ReVanced Manager: [RVX Manager v1.3.8 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.3.8)
[Crowdin translation]
- [European Countries](https://crowdin.com/project/revancedextendedeu)
- [Other Countries](https://crowdin.com/project/revancedextended)


---
CLI: j-hc/revanced-cli-2.22.0-all.jar  
Integrations: revanced/revanced-integrations-0.111.2.apk  
Patches: revanced/revanced-patches-2.181.0.jar  

### [2.181.0](https://github.com/revanced/revanced-patches/compare/v2.180.0...v2.181.0) (2023-07-03)
### Bug Fixes
* **infinityforreddit/change-oauth-client-id:** patch correct method ([#2564](https://github.com/revanced/revanced-patches/issues/2564)) ([f1ba16e](https://github.com/revanced/revanced-patches/commit/f1ba16ebfe2fda86af96d094481ed472eebcb4f9))
* **reddit/hide-comment-ads:** do not require integrations ([c2211d4](https://github.com/revanced/revanced-patches/commit/c2211d458d5cab030999e604a87cc1d02805b7ef))
* **reddit/sanitize-sharing-links:** update patch to support latest app version ([#2575](https://github.com/revanced/revanced-patches/issues/2575)) ([737be98](https://github.com/revanced/revanced-patches/commit/737be9815bad985328bbbead4d32f9398241eef2))
* **trakt:** bump compatibility to newer version ([#2554](https://github.com/revanced/revanced-patches/issues/2554)) ([2a2897d](https://github.com/revanced/revanced-patches/commit/2a2897dc9e81799a3318875122fc7b49692e3764))
* **youtube-music/bypass-certificate-checks:** fix fingerprint for the latest target app ([#2567](https://github.com/revanced/revanced-patches/issues/2567)) ([8eacb5b](https://github.com/revanced/revanced-patches/commit/8eacb5b5ace816da4d98b990eff0ea208691660c))
* **youtube/spoof-signature-verification:** remove auto re-enable functionality ([#2556](https://github.com/revanced/revanced-patches/issues/2556)) ([b8df8fb](https://github.com/revanced/revanced-patches/commit/b8df8fb99707fdac32e272fee8469dfeb940504d))
### Features
* **baconreader/change-oauth-client-id:** add compatibility for premium package ([#2550](https://github.com/revanced/revanced-patches/issues/2550)) ([4d1b0b4](https://github.com/revanced/revanced-patches/commit/4d1b0b442768be4f7a12de63d8b973b2ca113f23))

---  
