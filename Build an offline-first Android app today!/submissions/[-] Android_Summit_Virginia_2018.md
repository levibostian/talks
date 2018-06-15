# Title

Build an offline-first Android app today!

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

# Short bio

Indie dev and startup freelancer at Curiosity IO.

Levi is an indie Android and iOS app developer. With a love for entrepreneurship and programming, he has spent the past 5 years building and launching dozens of mobile apps with startups. Beyond Android development, Levi is passionate about startups, minimalism, veganism, the environment, productivity, and living a good work/life balance. he/him

# Speaking experience?

Yes. EntreFEST 2017 - Iowa City, Iowa, United States. https://www.youtube.com/watch?v=UX_kRelOmf0

I have given a handful of talks about entrepreneurship at conferences, but no talks about my other passion: programming.
