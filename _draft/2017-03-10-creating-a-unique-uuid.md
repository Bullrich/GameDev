---
layout: post
title:  "Creating a unique and precise UUID"
date:   2017-03-10
categories:  
- java
- android
---
I got handed the task of creating a [truly unique UUID](https://en.wikipedia.org/wiki/Universally_unique_identifier) because it looks like the Android ID resets some times. This UUID should be the same for every app we use, but should reset if the phone is reseted.