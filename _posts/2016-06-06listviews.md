---
layout: post
title: implementing list view as explained by Derek Banas 
---

Runtime errors are the worst. I was using Derek Bantors as example to do my own implementaion of listviews 

with a customized row layout.

I did everything just as Derek Banas did. However,

I kept getting a bug in my Main_Activity.

I had tried everything there were no underlined lines anywhere,

when built there was no error but when I run the app I got the dialog box that says " Unfortunately , App has failed to start"

After two hours of frustration I discovered that I needn't have added LinearLayout to my row_layout.xml file.

What you need to bear in mind when using these YouTube tutorials is that the Tutors  made these videos a while back thus they 

use versions of Android Studio that are older than yours.As a result they're Android Studios might ignore some errors that ours won't.

In my case Derek's Emulator could ignore the linearlayout code in the Row_Layout.xml and mine did not.
