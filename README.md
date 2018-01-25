
Android WearNotifications Sample
===================================

Sample demonstrates best practices for using NotificationStyle Notifications (Inbox,
            BigPicture, BigText, and Messaging) for both Mobile apps and native/local Android Wear
            apps. It also covers Notifications on Wear 1.+ and Wear 2.0.

Introduction
------------

Steps for trying out the sample:
* Compile and install the mobile app onto your mobile device or emulator (for mobile
scenario).
* Compile and install the wearable app onto your Wear device or emulator (for Wear
scenario).

This sample demonstrate best practices for using [NotificationStyle][1]
[Notifications][2] for two scenarios:

1. Launching Notifications from a Mobile app WITHOUT a native Android Wear app.
Notifications appear both on mobile and Wear (bridged to appear like a local/native
Wear app).

2. Launching Notifications from a Native/Local Android Wear app. Notifications only
appear on Wear device.

The Mobile and Wear apps demonstrate [BigTextStyle][3], [BigPictureStyle][4],
[InboxStyle][5], and [MessagingStyle][6] Notifications.

Although there are two apps (Mobile and Wear) running, each should be looked at as a
separate experience. That is, neither app uses nor relies on the other.

They are packaged together simply to show both scenarios in one easy sample.

Both apps also cover the Notifications being displayed on Wear 1.+ and/or Wear 2.0 and
using some of the new features of Wear 2.0 (inline actions).

[1]: https://developer.android.com/reference/android/support/v4/app/NotificationCompat.Style.html
[2]: https://developer.android.com/reference/android/support/v4/app/NotificationCompat.html
[3]: https://developer.android.com/reference/android/support/v4/app/NotificationCompat.BigTextStyle.html
[4]: https://developer.android.com/reference/android/support/v4/app/NotificationCompat.BigPictureStyle.html
[5]: https://developer.android.com/reference/android/support/v4/app/NotificationCompat.InboxStyle.html
[6]: https://developer.android.com/reference/android/support/v4/app/NotificationCompat.MessagingStyle.html

Pre-requisites
--------------

- Android SDK 26
- Android Build Tools v27.0.2
- Android Support Repository

Screenshots
-------------

<img src="screenshots/mobile-1.png" height="400" alt="Screenshot"/> <img src="screenshots/mobile-2.png" height="400" alt="Screenshot"/> <img src="screenshots/wear-1.png" height="400" alt="Screenshot"/> <img src="screenshots/wear-2.png" height="400" alt="Screenshot"/> 

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

Support
-------

- Google+ Community: https://plus.google.com/communities/105153134372062985968
- Stack Overflow: http://stackoverflow.com/questions/tagged/android

If you've found an error in this sample, please file an issue:
https://github.com/googlesamples/android-WearNotifications

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2017 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
