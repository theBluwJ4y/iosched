BluwJay Android App
======================


BluwJay uses BrowserStack in order to ensure that the app looks great on all screen resolutions, and that new features work as intended on all devices. You can sign up for a BrowserStack free trial account at https://www.browserstack.com/users/sign_up.

![BrowserStack_logo](https://p14.zdusercontent.com/attachment/1015988/tYLdSe3Q98gdw8N5Ib4NvTY43?token=eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..zljqh5oX9E9Jdo-SAyL67A.acmQdN4_26FYIdXUt9922dJ89Ns8BfknzI9PfKK7dRNIzNeakj8nMvFQ1iN08GK_rMQBVocrbqV4zkN6viEjHHovSztdu3XDy-C1rQYNUmjGgsPboVXWEo5jl4nwGz9BNr-mn-oeWTtr9TlJm1-E6K0x9f2_cz5ba_E-m5tP03O6CMS3dnscQI9deaeU6zM66p_vrn4RmGOiUkoZKg8cfh3Tm6FNEQDaQmFv-jRo2qDPILpL5mn3ISmz5jAwTftTWH2_LecguYNOVtTYx1J8mcCsr2Nhc4iHFFaz5q1eoAs.xRgbCGtgeCNFp_1SHN-qEQ)

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
