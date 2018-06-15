# Build an offline-first Android app today!

This talk is a v2 of *Journey to finding the perfect app architecture*. That talk abstract was covering too much. I have decided to break apart that talk into a few separate talks on how I build mobile apps.

The title of this talk includes "Android" but it is not limited to Android. I have titled it this to target Android specific conferences to start. I could easily do the same talk for an iOS conference by swapping some Kotlin code with Swift code :)

# Abstract

When your app is offline-first your users are able to use your app when they are offline or have a spotty network connection. There is also the added bonus of removing loading screens and having improved error handling resulting in a much faster Android app.

2 years ago, I began making all of my apps offline-first because I believe in the user experience that offline-first gives to Android app users.

At first it seemed easy to implement but as I began to write code, I discovered that building an offline-first Android app is complex. There are many design decisions to make, lots of error handling, and dozens of use cases to handle.

After lots of headaches, unstable apps, and refactoring I thought there had to be a better way. I wanted to make building offline-first Android apps easier to write then non-offline-first Android apps. I have made great strides in this goal and am ready to share my experience.

This talk goes over how to build an offline-first Android app from start to finish. I will cover:

* An overview of how offline-first Android apps are built. This section will not involve code and will be heavy on diagrams explaining the process of how to build an offline-first Android app.
* Go over a list of requirements we should have for building offline-first Android apps. Items such as: (1) notifying our users how old cached data is and (2) not draining the battery of our users while still keeping data fresh.
* How to use the open source Android library Wendy (https://github.com/levibostian/wendy-android) to push user actions to your network API. This section will be heavy on Kotlin, Room/SQL code.
* How to use the open source Android library Teller (https://github.com/levibostian/teller-android) to fetch fresh user data from your network API. This section will be heavy on Kotlin and RxJava with some LiveData, ViewModel code involved.

The goal of this talk is to help Android developers understand how to build offline-first Android apps so they feel confident knowing where to begin building their own offline-first Android apps.
