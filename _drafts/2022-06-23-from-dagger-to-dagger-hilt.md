---
layout: post
title:  "From Dagger to Dagger Hilt"
date:   2022-06-23 21:10:13 +0200
categories: mobile android
tag: dev android dagger hilt mobile
---

## Abstract

During the 2019's Android Dev Summit conference, Google announced that it would stop the development of Dagger-Android and officially recommended to use pure Dagger 2 instead. Few times after those announces Dagger-Hilt was announced and presented as "a standard way to incorporate Dagger dependency injection into an Android application." On the 5th of May 2021 Dagger Hilt 1.0.0 was released. 

I recently took the decision to give it a go as Dagger 2 is a powerful but yet difficult tool to understand and setup and did not really want to change the setup it already took me time to master. 

I started using Hilt in a small internal app, a simple tool without the scope of an important production app. Once confident that Hilt would improve our production app I started the refactoring of the dependency injection code to follow Dagger-Hilt's template. 

**With this blog post I'd like to share my experience with Dagger-Hilt with two integration examples**: 
  
  * From scratch in a new project 
  * Refactoring of an important project already using Dagger 2 

I will discuss pros and cons of Dagger-Hilt and what does it brings to the table. 

## References

  * [Slides - From Dagger to Dagger Hilt](https://speakerdeck.com/robincaroff/from-dagger-to-dagger-hilt)
  * [Video (en) - Android Makers 2022](https://youtu.be/CYyWHY3jmDQ)
  * [Video (fr) - Mobilis in Mobile 2022](https://youtu.be/w6c3K_Rw7zw)
  * [Official Dagger Hilt documentation](https://dagger.dev/hilt/)
  * [Android Developer - Dependency injection with Hilt](https://developer.android.com/training/dependency-injection/hilt-android)