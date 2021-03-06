# Nova Video Player changelog

## Important notes:
- migrating from v3 or v4 to v2 will delete all your scraping information

## v5.x current git (unstable)
Unstable branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.

## v4.x current git (testing), current Google Play release
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.

## v3.x current git (stable)
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r20, ffmpeg 4.2.

## v4.27 Google Play release - 5/1/2020
Testing branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- ffmpeg update to 4.2.2
- dav1d update to 0.5.2
- Stability enhancement

## v4.26 Google Play release - 29/12/2019
Testing branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Better scrape result through Levenshtein result distance computation
- Stability enhancement

## v4.25 Google Play release - 26/12/2019
Testing branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Introduce stretched video format to fill entire display with video image (only way to preserve aspect ratio on recent Philips TVs!)
- Add Norwegian, Vietnamese scrape languages support
- 2020 year banners for Android TV
- Improve filename pre-processing garbage rules to improve scrape
- Prevent scrape notification to fire up when nothing is to be scraped
- Fix sftp indexing

## v5.7 SMBv2 beta release - 14/12/2019
Unstable branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Align with v4.24 with jcifs-ng on top

## v4.24 Google Play release - 14/12/2019
Testing branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Fix more shows not being scraped correctly after thetvdb.com site changes
- Rollback on jcsh upgrade yielding issues on sftp
- Fix regression in pause/play with enter key on AndroidTV
- Fix some aspect ratio issues on devices where MediaCodec returns wrong video dimensions (firetv4k, rockchip, etc.)
- Reduce bottom player UI glitch on chromebook and rockchip leanback interfaces

## v4.22 Google Play release - 8/12/2019
Testing branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Fix some shows not being scraped correctly after thetvdb.com site changes
- Fix player controller UI layout issues on tablets
- update thetvdb-java to version 2.2.0

## v4.21 Google Play release - 7/12/2019
Testing branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Faster AndroidTV display entering application
- Attempt to fix an UI glitch on Rockchip based TV boxes
- Stability enhancements

## v5.6 SMBv2 beta release - 1/12/2019
Unstable branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Fix SMBv1 guest/anonymous auth on freebox

## v4.20 Google Play release - 1/12/2019
Testing branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Stability enhancements

## v4.18 Google Play release - 22/11/2019
Testing branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Fix player crashing in Dutch due to translation error
- Fix TV shows meta data retrieval issues due to to TheTVdb.com backend changes

## v4.17 Google Play release - 18/11/2019
Testing branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Stability enhancements

## v4.16 Google Play release - 17/11/2019
Testing branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Migration to TheTVDB API v2 via thetvdb-java external library with request caching support
- Target API29 disabling scoped storage for now
- Indexing, scraping and file copy proper foreground notifications
- Stability enhancements

## v5.5 Google Play beta release - 6/11/2019
Unstable branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Fix lack of focus on last added video row at application start on leanback

## v5.4 Google Play beta release - 4/11/2019
Unstable branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Fix cursor based fragments lack of refresh after video deletion on phones/tablets

## v5.3 Google Play beta release - 3/11/2019
Unstable branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Leanback setting style for subtitles languages download
- Remove systematic video background reload in VideoDetailsFragment on leadback when back from video play
- Stability enhancements

## v5.2 Google Play beta release - 27/10/2019
Unstable branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Fix selection of torrent streaming download directory not selectable
- Indexing, scraping and file copy proper foreground notifications
- Stability enhancements

## v5.1 unstable branch release - 21/9/2019
Unstable branch: this release is based on minSDK 21, targetSDK 29, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Switch to jcifs-ng to support SMBv2/3
- Target API29 (Android Q) and disable scoped storage for now

## v4.15 Google Play release - 16/9/2019
Testing branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Fix resume point update on VideoInfoActivity and auto scraping of unknown files on network shares

## v4.14 Google Play beta release - 15/9/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.1.
- Only switch to AudioTrack instead of openSLES to solve audio/video delay on Amlogic
- Upgrade to latest version of trakt-java containing NVP upstreamed contribution
- Add support for codepade 28606 - Latin-10 or South-Eastern European for subs

## v4.13 Google Play beta release - 8/9/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Switch to AudioTrack instead of openSLES to solve audio/video delay on most devices
- Disable for now UpNext row/channel preventing display of indexed folders
- Upgrade trakt-java library to solve two ways sync

## v4.12 Google Play beta release - 29/8/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Fix HEVC decoding for some files on MTK based devices
- Do not revert on SW decoding in presence of high bitrate spike occurring on some 4k high bitrate videos

## v4.11 Google Play beta release - 28/8/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Fix coexistence with Archos Video Player

## v4.10 Google Play beta release - 22/8/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Fix video blacklisting on local storage

## v4.9 unstable branch release - 21/8/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- FFmpeg upstep to 4.2 and dav1d to 0.4.0
- Fix database crash preventing application to start on some custom ROMs

## v4.8 unstable branch release - 2/8/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Fix database crash preventing application to start on some devices

## v4.7 unstable branch release - 15/6/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Improve audio passthrough robustness
- Fix authentication issue with Trakt

## v3.11 Google Play beta release - 15/6/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r20, ffmpeg 4.2.
- Improve audio passthrough robustness

## v3.10 Google Play release - 9/6/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19c, ffmpeg 4.2.
- Fix authentication issue with Trakt

## v4.6 unstable branch release - 3/6/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r19c, ffmpeg 4.2.
- Attempt to fix UPnP playback of files containing a "/"
- Do not crash when opening non-video files in browser
- Stability improvements

## v3.9 Google Play beta release - 1/6/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19c, ffmpeg 4.2.
- Attempt to fix UPnP playback of files containing a "/"
- Do not crash when opening non-video files in browser
- Stability improvements

## v4.5 unstable branch release - 30/5/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r19c, ffmpeg 4.2.
- Fix files cannot play from external sdcard using an external player
- AndroidTV: fix EpisodesByDate week view crash in case of large TV show collection

## v3.8 Google Play release - 30/5/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19c, ffmpeg 4.2.
- Fix files cannot play from external sdcard using an external player

## v4.3 unstable branch release - 19/5/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r19c, ffmpeg 4.2.
- Scanning and scraping proper Notifications
- Add an option to force disabling stereo downmix on phones/tablets with Android version > N
- AndroidTV: add pinning on long press for all movies/tvshows
- New TV show categories for quicker browsing through large collection
- Countless TV UI improvements (roles, trailers, badges, global del/deindex, subs picker)
- New player shortcuts (A/S switch audio/sub track, U/D = volume up/down) and menu support
- Improve audio passthrough stability
- Fix sftp playback interruptions
- Make private mode persistent
- Fix cloud support (still no streaming)- AndroidTV: add poster/backdrop zoom on long press
- AndroidTV: add tvshow episodes by date view
- Fix sftp playback interruptions
- Fix an android Q DP3 crash

## v2.2 stable branch release - 19/5/2019
Stable branch: this release is based on minSDK 17, targetSDK 27, NDK-r16b, ffmpeg 3.3.x.
- New TV show categories for quicker browsing through large collection
- Countless TV UI improvements (roles, trailers, badges, global del/deindex, subs picker)
- New player shortcuts (A/S switch audio/sub track, U/D = volume up/down) and menu support
- Improve audio passthrough stability
- Fix sftp playback interruptions
- Make private mode persistent
- Fix cloud support (still no streaming)
- Fix an android Q DP3 crash

## v3.7 Google Play release - 24/5/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19c, ffmpeg 4.2.
- Fix software decoding fallback in case of error
- Re-enable downmix on phones to avoid voice channels loss on some phones
- Stability improvements
- Upgrade to latest ffmpeg and dav1d soft codecs
- Fix an android Q DP3 crash

## v4.2 API28+AndroidX beta release - 27/4/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r19c, ffmpeg 4.2.
- Option to have landscape fullscreen video on display with cutouts
- AndroidX migration
- Poster/backdrop zoom on AndroidTV via long press
- Improve stability of phone/tablet UI after API28 migration
- New A-Z orb option in All TV shows/Movies for alphabetical order browsing
- New all/not viewed orb option in All TV shows/Movies for limiting browsing to all/not viewed videos

## v3.6 Google Play beta release - 27/4/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- Upgrade to latest ffmpeg and dav1d soft codecs

## v3.5 release candidate - 17/4/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- Fix software decoding on pre-M Android versions

## v4.1 API28 beta release - 8/4/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r19, ffmpeg 4.2.
- New video overview
- Leanback style settings on AndroidTV
- Add recently added TV channels
- Improved subtitles picker wizard look
- API28 migration

## v3.3.1 Google Play beta release - 11/3/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- New TV show categories on TV interface for quicker browsing through large collection
- Countless TV UI improvements (player look and feel, roles, movies trailers, audio badges, global deleletion/de-indexation, subtitles picker, more dynamic banners)
- New player shortcuts (A/S switch audio/sub track, U/D = volume up/down) and menu support
- Improve audio passthrough stability
- Fix crash in presence of damaged sdcard
- Fix cloud support (still no streaming)
- Do not downmix to stereo on phones/tablets if Android is recent enough (N): delegate to Android

## v3.4 special SMBv2/3 test release (experimental) - 18/3/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- SMBv2/3 support via jcifs-ng
- Ability to deindex local folders

## v3.1 Google Play beta release 3/2/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- New TV show categories on TV interface for quicker browsing through large collection

## v3.0 Google Play beta release - 30/1/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- Migration from Android ndk-r17 to ndk-r19
- Add AV1 soft decoding capability through 4.2-dev ffmpeg version and dav1d codec
- Add support for x86_64 architecture
- Improve audio passthrough stability
- Make private mode persistent between application relaunches

## v2.1 Google Play public release - 20/9/2018
Stable branch: this release is based on minSDK 17, targetSDK 27, NDK-r16b, ffmpeg 3.3.x.
- Improved french translations and interfacing with crowdin service
- Stability improvements

## v2.0 Google Play public release - 7/9/2018
Stable branch: this release is based on minSDK 17, targetSDK 27, NDK-r16b, ffmpeg 3.3.x.
- Scraper improvements and bug fixes
- Issue a warning toast is hardware decoding is disabled

## v1.0 Initial Google Play public release - 26/8/2018
Compared to Archos Video Player open source release, following changes were made:
- Add support for Android P avoiding application crash at startup
- Add a "list episodes" button on tvshow episode view to quickly get to tvshow view on AndroidTV leanback version
- Add notification channels for Oreo
- Fix subtitle delay not applied on play resume when negative
- Fix floating player crash on Android version Oreo and above
- Fix loss of activity background and private mode background
- Prevent from playing a file when detecting a problem: issue a toast instead
