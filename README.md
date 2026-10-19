# Petal Voice

Personal audiobook player based on **Voice by Paul Woitaschek and contributors**, from [upstream tag 26.10.3-5410003](https://github.com/PaulWoitaschek/Voice/tree/26.10.3-5410003). Original copyright, GPL license and third-party notices are retained. This is an unofficial personal edition; no upstream endorsement is implied.

Cozy-inspired browsing uses author cover cards → series cover stacks → books in numeric order, with standalone books under their author and persistent author/series/title search. A shared series includes every author’s volumes. Existing playback, bookmarks and settings remain available.

[Releases](https://github.com/ClownChowder/petal-voice/releases) include the APK and **full corresponding source** as `petal-voice-source.zip`, including Gradle wrapper, build configuration, notices and tests. This repository is the release index; GitHub’s automatic source ZIP is not the application source. Use the explicitly attached source archive.

## Install and update

Android package: `app.petalvoice`. Install alongside official Voice; the upstream signing key is unavailable, so this edition cannot update its original package. Obtainium source: `https://github.com/ClownChowder/petal-voice`; exact APK filter: `^petal-voice\.apk$`.

Build the source with `./gradlew :app:assembleFreeDebug --no-scan`. Use the same personal signing key for subsequent updates. Signing keys, personal app data and audiobook files are not published. The free variant excludes analytics.

## Credits

See [CREDITS.txt](CREDITS.txt) and [LICENSE.md](LICENSE.md). About retains prominent original-author credit. Cover-stack navigation is inspired by the user’s customized [Cozy](https://github.com/geigi/cozy); the Android Compose implementation is new.
