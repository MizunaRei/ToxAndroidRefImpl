<img src="https://raw.githubusercontent.com/zoff99/ToxAndroidRefImpl/zoff99/dev003/doc/mockup_004a.png" width="99%">

# Tox Reference Implementation for Android [TRIfA]

~~This is not a Reference Client, it's c-toxcore for Android.~~<br>
This is now also a Tox Client for Android.

### Important Notice: Since Google has changed their <a href="https://raw.githubusercontent.com/zoff99/ToxAndroidRefImpl/zoff99/dev003/images/google_play_dev_verify_02.png">Playstore policy</a> in a way that is unacceptable, soon future Versions can not be published on the Playstore anymore. Github Releases are signed with the same key as the Playstore version.

<a href="https://f-droid.org/app/com.zoffcc.applications.trifa"><img src="https://raw.githubusercontent.com/zoff99/ToxAndroidRefImpl/zoff99/dev003/images/f-droid.png" width="200"></a>
<a href="https://play.google.com/store/apps/details?id=com.zoffcc.applications.trifa"><img src="https://raw.githubusercontent.com/zoff99/ToxAndroidRefImpl/zoff99/dev003/images/playstore.png" width="200"></a>
<a href="https://github.com/zoff99/ToxAndroidRefImpl/releases/latest/download/play.trifa.apk"><img src="https://raw.githubusercontent.com/zoff99/ToxAndroidRefImpl/zoff99/dev003/images/on_github.png" width="200"></a>
<a href="https://github.com/zoff99/ToxAndroidRefImpl/releases/download/nightly/TRIfA-nightly.apk"><img src="https://raw.githubusercontent.com/zoff99/ToxAndroidRefImpl/zoff99/dev003/images/on_github_nightly.png" width="200"></a>

&nbsp;&nbsp;&nbsp;&nbsp;Looking for TRIfA Desktop version? [follow me](https://github.com/Zoxcore/trifa_material/tree/master)

Status
=
[![Android CI](https://github.com/zoff99/ToxAndroidRefImpl/workflows/Android%20CI/badge.svg)](https://github.com/zoff99/ToxAndroidRefImpl/actions?query=workflow%3A%22Android+CI%22)
[![Release](https://jitpack.io/v/zoff99/pkgs_ToxAndroidRefImpl.svg)](https://jitpack.io/#zoff99/pkgs_ToxAndroidRefImpl)
[![Last release](https://img.shields.io/github/v/release/zoff99/ToxAndroidRefImpl)](https://github.com/zoff99/ToxAndroidRefImpl/releases/latest)
[![Translations](https://hosted.weblate.org/widgets/trifa-a-tox-client-for-android/-/svg-badge.svg)](https://hosted.weblate.org/engage/trifa-a-tox-client-for-android/)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![Liberapay](https://img.shields.io/liberapay/goal/zoff.svg?logo=liberapay)](https://liberapay.com/zoff/donate)

Latest Automated Screenshots
=
<img src="https://github.com/zoff99/ToxAndroidRefImpl/releases/download/nightly/screen_shot_android_02.png" width="200">&nbsp;<img src="https://github.com/zoff99/ToxAndroidRefImpl/releases/download/nightly/screen_shot_android_03.png" width="200">&nbsp;<img src="https://github.com/zoff99/ToxAndroidRefImpl/releases/download/nightly/screen_shot_android_04.png" width="200">&nbsp;<img src="https://github.com/zoff99/ToxAndroidRefImpl/releases/download/nightly/screen_shot_android_05.png" width="200">

Automated Promotion Screenshots
=
<img src="https://github.com/zoff99/ToxAndroidRefImpl/releases/download/nightly/promo_02.png" width="200">&nbsp;<img src="https://github.com/zoff99/ToxAndroidRefImpl/releases/download/nightly/promo_03.png" width="200">

Help Translate the App in your Language
=
Use Weblate:
https://hosted.weblate.org/engage/trifa-a-tox-client-for-android/

Push Notification
=
See [PUSH_NOTIFICATION.md](./PUSH_NOTIFICATION.md)

Offline Messages
=
See [OFFLINE_MESSAGES.md](./OFFLINE_MESSAGES.md)

Does TRIfA connect to any third party servers?
=
TRIfA (excluding toxcore) uses the Google Firebase service and a third party server to deliver push notifications to other tox mobile users when they are offline. This makes it possible for Mobile devices to go into sleep mode and save battery and network bandwidth when there is no activity. Rest assured that the push notification does not contain any data, the request that comes from TRIfA includes only the FCM token of your contact(s). No ToxID, name or message data is transfered in the process.

Get in touch
=
* Join the TRIfA Tox Groupchat: <a href="https://trifagrp.tox.zoff.cc/">154b3973bd0e66304fd6179a8a54759073649e09e6e368f0334fc6ed666ab762</a><br>

Import/Export
=
See [import-export.md](./import-export.md)

Compile in Android Studio
=
**Open an existing Project:**<br>
<img src="https://github.com/zoff99/ToxAndroidRefImpl/blob/zoff99/dev003/image.png" width="400">

**and select the "android-refimpl-app" subdir:**<br>
<img src="https://github.com/zoff99/ToxAndroidRefImpl/blob/zoff99/dev003/image1.png" width="400">

<br><br>

Development Snapshot Version (Android)
=
the latest Development Snapshot can be downloaded from [here](https://github.com/zoff99/ToxAndroidRefImpl/releases/tag/nightly)

## License (Project is dual licensed, you can choose the license)

TRIfA is distributed under the terms of the GNU General Public License (version 2) or the GNU General Public License (version 3).
You may use TRIfA according to either of these licenses as is most appropriate for your project on a case-by-case basis.

See LICENSE-zzGPLv2 and LICENSE-GPLv3 for details.

Translations are under the terms of GNU General Public License (version 2 or later).

See https://hosted.weblate.org/projects/trifa-a-tox-client-for-android/android-application/#information
and https://hosted.weblate.org/projects/trifa-a-tox-client-for-android/f-droid-texts/#information

<br>
Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.
<br>
No part of this work may be used or reproduced in any manner for the purpose of training artificial intelligence technologies or systems.


