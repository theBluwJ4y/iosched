BluwJay Android App
======================

# Features

The app displays a list of conference events - sessions, office hours, app
reviews, codelabs, etc. - and allows the user to filter these events by event
types and by topics (Android, Firebase, etc.). Users can see details about
events, and they can star events that interest them. Conference attendees can
reserve events to guarantee a seat.

# Development Environment

The app is written entirely in Kotlin and uses the Gradle build system.

To build the app, use the `gradlew build` command or use "Import Project" in
Android Studio. A canary or stable version >= 3.2 of Android Studio is
required and may be downloaded
[here](https://developer.android.com/studio/archive).


## Kotlin

We made an early decision to rewrite the app from scratch to bring it in line
with our thinking about modern Android architecture. Using Kotlin for the
rewrite was an easy choice: we liked Kotlin's expressive, concise, and
powerful syntax; we found that Kotlin's support for safety features for
nullability and immutability made our code more resilient; and we leveraged the
enhanced functionality provided by
[Android Ktx extensions](https://developer.android.com/kotlin/ktx).
