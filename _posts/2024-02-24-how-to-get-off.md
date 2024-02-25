---
layout: post
author: Adam
---

![Front gate at the Croft](/assets/images/DSC_0078.jpeg "Front gate at the Croft")

## PC

If you own a:

- Laptop
- All-in-one
- Large tower that you can't carry around with you

Get rid of it. Replace it with a SFF (Small Form Factor) PC such as a Mac Mini. You should be able to throw it into a bag and take it around with you, but you shouldn't be able to use it without all of the following components:

- Power supply
- Monitor
- Keyboard
- Mouse

If you have all of these at home, get rid of at least one so your machine can't be used there. All of the above components can be found in public places such as your university library, or office at work.

Depending on how much you rely on having a PC, you might even be able to get away with not replacing it with anything at all. Some people's information work can be taken care of entirely using some combination of a smartphone, the library, a university campus, and the office.

## Phone

### iPhone

1. Turn on Screen Time.

2. Go to Content Restrictions > Allowed Apps, and turn off Safari and the App Store.

3. Get a friend or family member (your 'accountability partner') to lock your Screen Time settings with a 4-digit passcode that they'll remember. If you don't have anybody you can entrust with this (or don't feel comfortable doing so), get an Android phone (e.g., a Fairphone).

### Android

Get the [Universal Android Debloater](https://github.com/0x192/universal-android-debloater). Using the UAD is quite an involved process, so you'll need to read the instructions first. If you have a phone manufactured by Google or Fairphone, use the UAD to uninstall at least `com.android.chrome` and `com.android.vending` (the Play Store). If you have a phone from a different manufacturer, it's likely to have some weird apps preinstalled (e.g., Facebook, a custom web browser/app store, etc.). Locate these and uninstall them too.

If you want to take a step further towards turning your phone back into a phone, bear with me. Flash [LineageOS](https://lineageos.org/) to your phone and use the UAD to remove `org.lineageos.jelly` (the web browser). You'll be able to get some apps as `.apk` files straight from the publisher, such as [Signal](https://signal.org/android/apk/) and [Aegis](https://github.com/beemdevelopment/Aegis/releases/tag/v2.2.2), or from [F-Droid](https://f-droid.org/), a free and open-source app store. Note that if you depend on any Play Store apps, they might not work (and Google apps won't work at all). If you need one or two, use [Aurora Store](https://aurorastore.org/). If you really need Google apps, try [LineageOS for MicroG](https://lineage.microg.org/).

Depending on your requirements, you can even [build LineageOS](https://wiki.lineageos.org/devices/bacon/build/) yourself and exclude `jelly`. You will need to be reasonably good with computers to do this.

### "Feature Phone"

Forget it. Get an iPhone or Fairphone.

### Facebook Messenger

Get rid of it. Unlike most other instant messaging apps, Messenger contains its own web browser, so even if you've removed your phone's browser, you can open any link simply by sending it to yourself and clicking on it.

