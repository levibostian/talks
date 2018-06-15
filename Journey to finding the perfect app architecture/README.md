# Journey to finding the perfect app architecture.

I have not given this talk yet, but I hope to. I have been extremely excited about this topic for the past ~6 months now :)

**Update:** After being rejected for 4 conferences, I have decided to ditch this topic and redefine it. I have received amazing feedback from conference organizers on my submission saying that, "There is no such thing as perfect" and "This topic is covering too much at one talk". This talk has been rewritten to become, *Build an offline-first Android app today!*.

# Abstract

When it comes to mobile apps, I think we can all agree apps should be fast, fun, and easy to use. They should *just work*.

To do that, there are a few best practices: (1) All data retrieved should be cached. This allows apps to have offline functionality and minimize loading screens. (2) Errors should be as helpful as possible. Help your users *solve* their issue, not just tell me, "an error has occurred".

Sure, these are the best practices, but as Android devs who have been at this for a while, we know this can be difficult. Handling the states of your app's data is a nightmare. It was common to find large and complex Activity/Fragment classes and apps that are hard to debug, hard to build/test, and prone to bugs. That is until MVVM came around.

In this talk, I want to go over my current app architecture that I use for all of my Android & iOS apps (specifically Android). My design is aiming to build (1) offline first/fully cached apps with 0 or 1 loading screens (2) helpful error messages that align with the data that caused the error (3) fast to build with great developer experience (4) and debuggable code. All while (5) minimalizing the network calls to perform.
