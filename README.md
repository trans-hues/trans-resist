# trans-resist
Digital security and protest advice for trans and LGBTQIA+ people in 2020.

## Table of contents

1. [Description, disclaimer, and usage tips ](#desc)
2. [Other Resources ](#resources)
3. [Digital security & organizing online](#digisec)
    * [3.1 General mobile phone security](#mobilesec)
    * [3.2 Smartphone apps for communicating and organizing](#smartphone)
      * [3.2.a Signal](#signal)
      * [3.2.b Telegram](#telegram)
      * [3.2.c Apps to avoid for organizing](#badapps)
    * [3.3 Video chat](#vidchat)
      * [3.3.a Meet Jitsi](#jitsi)
    * [3.4 Secure email](#secemail)
      * [3.4.a PGP](#pgp)
      * [3.4.b Thunderbird](#thunderbird)
      * [3.4.c Secure email hosts](#mailhosts)
    * [3.5 Anonymous web browsing](#anonweb)
      * [3.5.a Tor Browser](#torbrowser)
      * [3.5.b Other browsers](#otherbrowsers)
      * [3.5.c Secure browsing behavior](#browsebehavior)
    * [3.6 VPNs](#vpn)
      * [3.6.a Free vs. Paid](freevpaidvpn)
      * [3.6.b Riseup VPN](#riseupvpn)
      * [3.6.c Firefox VPN](#firefoxvpn)
    * [3.7 Tails](#tails)
    * [3.8 Photos, Filming, Faces, and Metadata](#photosmeta)
      * [3.8.a Filming, Photos, and Documenting](#documenting)
      * [3.8.b Image-Scrubber](#imagescrubber)
      * [3.8.c Obscuracam](#obscuracam)
      * [3.8.d Scrambled EXIF](#scrambled)
    * [3.9 Behavior & opsec](#digisecbehavior)
    * [3.10 Advanced: Infrastructure, servers, and hosting](#infrastructure)
      * [3.10.a How to setup your own cloud server](#how2cloudserver)
      * [3.10.b How to install and use SSH to access a remote server](#how2ssh)
      * [3.10.c How to host a jitsi video chat instance on your server](#how2jistihost)
      * [3.10.d How to host a tor relay](#how2torrelay)
4. [Protest safety](#protestsafety)
    * [4.1 General safety](#gensafety)
    * [4.2 Binding safety](#binders)
    * [4.3 What to do if your ID doesn't match your gender](#govtid)
    * [4.4 Organizations to call if you're in trouble](#orgstocall)
      * [4.4.a Trans advocacy organizations](#transorgs)
5. [Mutual aid](#mutaid)
    * [5.1 Mutual aid groups by region](#mutaidreg)
      * [5.1.a USA](#mutaidUSA)
      * [5.1.b Canada](#mutaidCAN)

<a name="desc"></a>
## 1. Description

This guide is intended to provide some advice and resources to help trans and LGBTQIA+ people safely navigate protests, digital security, and quarantines in 2020. This guide is specifically written with US communities in mind, but may feature advice that's applicable to other contexts, as well.

I am not an expert! Take all of this advice with a grain of salt, and use your best judgement. 
This advice is not one-size-fits-all! Your situation is almost certainly different from anyone else's, so it's important to remember that these tips might need some tweaking to be helpful to you.

<a name="resources"></a>
## 2. Other resources

[From Beirut to Minneapolis](https://github.com/frombeirutwithlove/ProtestTips/blob/master/WhatToDo.md)
  * a great general guide to protest safety, written by Lebanese technologists, protesters, and activists.

[The National Center for Transgender Equality: Know Your Rights](https://transequality.org/know-your-rights)
  * Resources explaining what rights you have as a trans person in the US. Topics covered include airport security, government documents, housing, employment, and healthcare.
  
[The National Center for Transgender Equality: ID Documents Center](https://transequality.org/documents)
  * Includes information on how to change your name on legal documents, IDs, and records in the US.
  
[The National Center for Transgender Equality: Trans Legal Services Network](https://transequality.org/issues/resources/trans-legal-services-network-directory)
  * Includes links to trans-centric legal services by state. Most are focused around getting help with legal name and gender marker changes.

<a name="digisec"></a>
## 3. Digital security & organizing online

The NSA recently renewed the Patriot Act, which means that the US government is free to surveil what you do and say online. This, combined with the fact that the US govt recently labelled more groups as terrorist organizations, means that we need to protect ourselves as much as we can while organizing.

In this section, you'll find some basic digital security guidance and advice for organizing online.

<a name="mobilesec"></a>
### 3.1 General mobile phone security

<a name="smartphone"></a>
### 3.2 Smartphone apps for communicating and organizing

<a name="signal"></a>
#### 3.2.a [Signal](https://signal.org/download/)

Signal is a free and open source encrypted messaging app, available for Android, iPhone, and computers.

One of the biggest downsides to Signal is that it requires a phone number to sign up. However, after you've created your account, you can use any phone number for that account. That means that you can spoof (create) a fake phone number to sign up. You will need that phone number to confirm your account in the initial setup process, but once you've done that, you can delete or abandon the fake number you used to sign up.

##### [Signing up on mobile](https://support.signal.org/hc/en-us/articles/360007318691-Register-a-phone-number)

   1. Install and open the latest update of Signal on your Android or iOS device.
   2. Enter and confirm your phone number.
   3. Tap Register.
   4. Wait for the SMS verification code to arrive. Alternatively, you can request a verification call if you can not receive SMS. After the timer finishes counting down, tap Call or I didn't get a code > Call me instead.
   5. If the verification code is not automatically detected, it can be entered manually and submitted. 
   6. You can start messaging and calling as soon as the registration process is complete. 

<a name="telegram"></a>
#### 3.2.b [Telegram](https://telegram.org/apps)

Telegram is a chat app that allows encrypted communication. It is free and open source. Generally, it is considered to be less secure than Signal, but sometimes it is preferred for certain features, like the ability to make bigger group chats. However, it's generally recommended that, whenever possible, you use Signal rather than Telegram for sensitive communication.

##### [Group Chats]

The thing with a group chat on telegram is that anyone can join or be invited, depending of the privacy settings of the group chat. This can be a bad thing for organizing. For example, if an undercover agent or an infiltrator convinces someone to join the group, they can see every message that's posted in the group. While this can happen in group chats on any app, the bigger maximum size of group chats on Telegram can make it harder to vet every new member. Keep this in mind when deciding whether to use Signal or Telegram to organize.

<a name="badapps"></a>
#### 3.2.c [Apps to avoid for organizing](#badapps)

##### Messenger

##### Discord

##### Whatsapp

##### Skype

##### Zoom

<a name="vidchat"></a>
### 3.3 Video chat

<a name="jitsi"></a>
#### 3.3.a Meet Jitsi

<a name="secemail"></a>
### 3.4 Secure email

<a name="pgp"></a>
#### 3.4.a PGP

<a name="thunderbird"></a>
#### 3.4.b Thunderbird

<a name="mailhosts"></a>
#### 3.4.c Secure email hosts

##### [Riseup.net](https://riseup.net)

Riseup.net offers end-to-end encrypted email hosting, as well as a bunch of other services. Their goal is to keep activists safe online. They are committed to never turn over any of your data to law enforcement.

To create a Riseup account, you'll need an invite code. You'll have to get an invite code from someone you know who's had a Riseup account for more than 3 months. If you have a Riseup account, you can generate a new invite code from the [invites page.](https://account.riseup.net/invites)

Once you have an account, you can login at https://mail.riseup.net/rc/ or setup an email client like Thunderbird to access your account. You can learn how to configure your email client for riseup [here.](https://riseup.net/email)

##### [Proton mail](https://protonmail.com/)

Proton Mail offers end-to-end encrypted email hosting. You can create an account for free, but in order to access all features of your account (like using an email client to read your mail), you'll need to pay for a full account.

<a name="anonweb"></a>
### 3.5 Anonymous web browsing

<a name="torbrowser"></a>
#### 3.5.a [Tor Browser](https://www.torproject.org/download/)

<a name="otherbrowsers"></a>
#### 3.5.b Other browsers

##### Brave

##### Firefox Focus

<a name="browsebehavior"></a>
#### 3.5.c Secure browsing behavior

Browsing the internet safely and securely takes more than just an anonymizing browser. You'll need to make some changes to your regular browsing behavior, too. 

##### Search engines

duckduckgo vs. google

##### Downloading apps

fdroid v. google play

<a name="vpn"></a>
### 3.6 VPNs

<a name="freevpaidvpn"></a>
#### 3.6.a Free vs. Paid

<a name="riseupvpn"></a>
#### 3.6.b [Riseup VPN](https://riseup.net/en/vpn)

Riseup offers a free VPN service. Their goal is to keep activists safe online. They are committed to never turn over any of your data to law enforcement.

To create a Riseup account, you'll need an invite code. You'll have to get an invite code from someone you know who's had a Riseup account for more than 3 months. If you have a Riseup account, you can generate a new invite code from the [invites page.](https://account.riseup.net/invites)

<a name="firefoxvpn"></a>
#### 3.6.c Firefox VPN

<a name="tails"></a>
### 3.7 [Tails](https://tails.boum.org/install/index.en.html)

<a name="photosmeta"></a>
### 3.8 Photos, filming, faces, and metadata

When you take a photo or video on your phone, your phone automatically saves some information about when and where the photo was taken, as well as the kind of phone used to take the photo/video. This data is called 'metadata,' or more specifically, EXIF data. This data can be easily viewed by anyone, and law enforcement can use it to identify when and where a photo/video was taken. This makes it easier for law enforcement to identify who took the photo/video, or who might appear in it. 

While documenting what happens at a protest can be important, it's also important to protect the identities of protestors present in the photo or video. Luckily, there are multiple free tools you can use to erase or spoof EXIF data, and to blur/obscure faces and other identifying features.

##### Blur vs. obscure

It's important to note that obscuring a feature using a black square or other image is often much safer than simply blurring it. This is because tools exist which make un-blurring an image relatively easy. For this reason, it's generally better to obscure a feature instead of blurring it, if you can.

<a name="documenting"></a>
#### 3.8.a Filming and documenting safely

<a name="imagescrubber"></a>
#### 3.8.b [Image-scrubber](https://everestpipkin.github.io/image-scrubber/)

[Image-scrubber](https://everestpipkin.github.io/image-scrubber/) is a browser-based tool that allows you to remove EXIF metadata from photos and blur/obscure faces or identifying features. You can use the tool from your phone's browser, regardless of your phone's OS. The photos you edit using this tool aren't sent anywhere when you edit them: all the editing is done on your phone instead of on a remote server.

<a name="obscuracam"></a>
#### 3.8.c [Obscuracam](https://guardianproject.info/apps/obscuracam/)

[Obscuracam](https://guardianproject.info/apps/obscuracam/) is an app developed by [the Guardian Project.](https://guardianproject.info/) Obscuracam allows you to remove any metadata from a photo or video. The app also has automatic face detection, which makes quickly blurring a large number of faces in a photo or video super easy.

The app is available for Android on the [Google Play store](https://play.google.com/store/apps/details?id=org.witness.sscphase1&feature=search_result) and on [fdroid.](https://f-droid.org/en/packages/org.witness.sscphase1/) If you don't already have fdroid installed on your phone, you'll need to [install the fdroid .apk](https://f-droid.org/en/) before you can use it to install other apps. You can install the fdroid store by downloading the .apk file [directly from their website](https://f-droid.org/en/)) using your phone's browser.

<a name="scrambled"></a>
#### 3.8.d [Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif)

[Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif) is an app that allows you to easily remove EXIF data from a photo or video before sharing it. 

The app is available for Android on the [Google Play store](https://play.google.com/store/apps/details?id=com.jarsilio.android.scrambledeggsif&hl=en_US) and on [fdroid](https://f-droid.org/en/packages/com.jarsilio.android.scrambledeggsif/). If you don't already have fdroid installed on your phone, you'll need to [install the fdroid .apk](https://f-droid.org/en/) before you can use it to install other apps. You can install the fdroid store by downloading the .apk file [directly from their website](https://f-droid.org/en/)) using your phone's browser.

To use the app, tap the 'share' button in another app, then select Scrambled Exif from the list of options. This will tell Scrambled Exif to remove the EXIF data from your file. Once the EXIF data has been removed, another share window will open, and you'll be able to send the file using any app on your phone.

<a name="digisecbehavior"></a>
### 3.9 Behavior & opsec

<a name="infrastructure"></a>
### 3.10 Advanced: Infrastructure, servers, and hosting

<a name="how2cloudserver"></a>
#### 3.10.a How to setup your own cloud server

<a name="how2SSH"></a>
#### 3.10.b How to install and use SSH to access a remote server

<a name="how2jistihost"></a>
#### 3.10.c How to host a Jitsi video chat instance on your server

<a name="how2torrelay"></a>
#### 3.10.d How to host a tor relay

<a name="protestsafety"></a>
## 4. Protest Safety

<a name="gensafety"></a>
### 4.1 General Safety

<a name="binders"></a>
### 4.2 Binding safety

<a name="govtid"></a>
### 4.3 What to do if your ID doesn't match your gender

Ideas:
- backpass, if you can/want to
- bring other documents to corroborate your name, maybe? like a phone bill or utilities bill that has your name and address on it. but is this bad because of address?
- know the laws in your state
- have a friend with you to advocate for you

<a name="orgstocall"></a> 
### 4.4 Organizations to call if you're in trouble

<a name=""></a>
#### 4.4.a Trans advocacy organizations

(alhpabetical by state)

#### 4.4.b Bail funds

(alphabetical by state)

<a name="mutaid"></a>
## 5. Mutual aid

<a name="mutaidreg"></a>
### 5.1 Mutual aid groups by region

<a name="mutaidUSA"></a>
#### 5.1.a USA
(alphabetical by state)

<a name="mutaidCAN"></a>
#### 5.1.b Canada
