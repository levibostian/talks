# Title

Journey to finding the perfect app architecture.

# Abstract

When it comes to mobile apps, I think we can all agree apps should be fast, fun, and easy to use. They should *just work*.

To do that, there are a few best practices: (1) All data retrieved should be cached. This allows apps to have offline functionality and minimize loading screens. (2) Errors should be as helpful as possible. Help your users *solve* their issue, not just tell me, "an error has occurred".

Sure, these are the best practices, but as Android devs who have been at this for a while, we know this can be difficult. Handling the states of your app's data is a nightmare. It was common to find large and complex Activity/Fragment classes and apps that are hard to debug, hard to build/test, and prone to bugs. That is until MVVM came around.

In this talk, I want to go over my current app architecture that I use for all of my Android & iOS apps (specifically Android). My design is aiming to build (1) offline first/fully cached apps with 0 or 1 loading screens (2) helpful error messages that align with the data that caused the error (3) fast to build with great developer experience (4) and debuggable code. All while (5) minimalizing the network calls to perform.

# Additional details

I am a freelance Android & iOS developer building mobile apps for startups. Over the past 5 years of building dozens of different apps, I have been on a continuous journey to finding the "perfect app architecture" to build the best apps fast.

This talk goes over how I use MVVM as well as architecture code I have built myself to make apps offline first. The purpose of the talk is to give my thought process into the architecture I have developed to give developers who have always wanted to build apps this way an actionable thought process to go out and do it. Example: "Apps should be made offline first." <--- Developers understand this, but may not understand the thought process into *how* this could be done.

Technical topics:
* MVVM using Rx/Realm
* Offline functionality via Android Database and syncing library I wrote
* Data driven UI via "State data" library I wrote (closely resembles Groupon's Grox lib)

Talk will be "Here is a problem, here is a thought up solution, here is a coded solution" talk.

Previous talk of mine: https://www.youtube.com/watch?v=UX_kRelOmf0 at EntreFEST 2017.

Thank you so much for your consideration!

Peace and love,
Levi

# Bio

Levi is a freelance native Android & iOS developer building apps for startups. Levi believes in user-centered design to build apps that make users have fun with software. Even though he is a big geek, he also enjoys bringing in his startup experience into his development to try and build the best solution to the problem at hand.

Levi is born and raised in the Midwest and spends his time as a freelancer, a startup founder building and selling tech products, and a mentor for college students and accelerator programs.

curiosityio.com
levibostian.com
@levibostian
