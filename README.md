# trans-resist
Advice and resources on digital security, protesting, organizing, and strategizing for trans and LGBTQIA+ people in 2020.

## Table of contents

1. [Description, disclaimer, and usage tips ](#desc)
2. [Digital security & organizing online](#digisec)
    * [2.1 General mobile phone security](#mobilesec)
    * [2.2 Smartphone apps for communicating and organizing](#smartphone)
      * [2.2.a Signal](#signal)
      * [2.2.b Telegram](#telegram)
      * [2.2.c Apps to avoid for organizing](#badapps)
    * [2.3 OTR Chat for desktop computers ](#OTRchat)
    * [2.4 Video chat](#vidchat)
      * [2.4.a Meet Jitsi](#jitsi)
      * [2.4.b Apps to avoid for video chat](#badvid)
    * [2.5 Secure email](#secemail)
      * [2.5.a PGP](#pgp)
      * [2.5.b Thunderbird](#thunderbird)
      * [2.5.c Secure email hosts](#mailhosts)
    * [2.6 Anonymous web browsing](#anonweb)
      * [2.6.a Tor Browser](#torbrowser)
      * [2.6.b Other browsers](#otherbrowsers)
      * [2.6.c Secure browsing behavior](#browsebehavior)
    * [2.7 VPNs](#vpn)
      * [2.7.a Free vs. Paid](freevpaidvpn)
      * [2.7.b Riseup VPN](#riseupvpn)
      * [2.7.c Firefox VPN](#firefoxvpn)
    * [2.8 Tails](#tails)
    * [2.9 Photos, Filming, Faces, and Metadata](#photosmeta)
      * [2.9.a Filming, Photos, and Documenting](#documenting)
      * [2.9.b Image-Scrubber](#imagescrubber)
      * [2.9.c Obscuracam](#obscuracam)
      * [2.9.d Scrambled EXIF](#scrambled)
      * [2.9.e Signal Blur](#signalblur)
    * [2.10 Behavior & opsec](#digisecbehavior)
    * [2.11 Advanced: Infrastructure, servers, and hosting](#infrastructure)
      * [2.11.a How to setup your own cloud server](#how2cloudserver)
      * [2.11.b How to install and use SSH to access a remote server](#how2ssh)
      * [2.11.c How to host a jitsi video chat instance on your server](#how2jistihost)
      * [2.11.d How to host a tor relay](#how2torrelay)
      * [2.11.e How to make and host an onionsite](#makeonion)
3. [Protest safety](#protestsafety)
    * [3.1 General safety](#gensafety)
    * [3.2 Binder safety](#binders)
    * [3.3 First Aid](#firstaid)
    * [3.4 What to do if your ID doesn't match your gender](#govtid)
    * [3.5 What to do if you are arrested](#ifurarrested)
    * [3.6 Organizations to call if you're in trouble](#orgstocall)
      * [3.6.a Trans advocacy organizations](#transorgs)
      * [3.6.b Bail funds by region](#bailfunds)
4. [Mutual aid](#mutaid)
    * [4.1 Mutual aid groups by region](#mutaidreg)
      * [4.1.a USA](#mutaidUSA)
      * [4.1.b Canada](#mutaidCAN)
5. [How to help if you can't physically go to a protest](#helpfromhome)
6. [Other Resources ](#resources)

<a name="desc"></a>
## **(1.0) Description**

This guide is intended to provide some advice and resources to help LGBTQIA+ people safely navigate protests against racism and police brutality, learn about digital security, and make it through quarantines in 2020. This guide does not have a ton of trans specific resources which we hope to change over time. We do know that police are often perpetrators of violence against trans people.  This is written in memory of our community members murdered by the police like Tony McDade and Kiwi Herring.  Their voices are left out often when talking about the intersectional impact of anti-Blackness, transphophia, and partriarchy.  This guide is also specifically written with US communities in mind, but may feature advice that's applicable to other contexts, as well.

This guide isn't meant to scare you or make you extra paranoid. It's meant to be informative and approachable, and to help you decrease the amount of potential harm you are exposed to online and on the ground. 

This advice is not one-size-fits-all. Your situation is almost certainly different from anyone else's, so it's important to remember that these tips might need some tweaking to be helpful to you. You may find that some of this advice is too much trouble for you, or that it involves a trade-off that you're not willing to make. That's okay! You don't have to do anything you don't want to. We'll try to give as many options as possible so that you can pick which solution works best for you.

We are people who care about digital security, and who have devoted some part of our lives to keeping up to date with these things & teaching others how to stay safe, but _we are not experts._ Take all of this advice with a grain of salt, and always use your best judgement. 

**Be sure to check out the incredible [BLM Guide](https://www.notion.so/BLM-Guide-fac525a6d1324d458d15bdc4fec98661) for tips, advice, and resources on how to organize safely in the US.**

We'd also like to recommend [From Beirut to Minneapolis](https://github.com/frombeirutwithlove/ProtestTips/blob/master/WhatToDo.md), a guide to general protest safety written by some trusted folks who're Lebanese protesters, activists, and technologists. We've adapted some of their advice here. 

[List of BLM chapters](https://blacklivesmatter.com/chapters/)

[Ways You Can Help](https://blacklivesmatters.carrd.co/)

[Google Map of protests](https://www.google.com/maps/d/viewer?mid=1W3fsF5-Mz3_KaBgVt2pU8BDY5GkawUN_&ll=9.101946528762323%2C-54.848781100000004&z=2)

---

<a name="digisec"></a>
## **(2.0) Digital security & organizing online**

The NSA recently renewed the Patriot Act, which means that the US government is free to surveil what you do and say online and over the phone. This, combined with the fact that the US govt recently said they'd like to label certain activist groups as terrorist organizations, means that we need to protect ourselves as much as we can while organizing.

In this section, you'll find some basic digital security guidance and advice for organizing online.

<a name="mobilesec"></a>
### **(2.1) General mobile phone security**

If you're planning on going to a protest, consider turning off your phone or leaving it at home, if you feel safe to do so. This is especially important if you have an Android phone, as [Android has been hacked by the police in the past.](https://money.cnn.com/2016/02/25/technology/android-apple-police-encryption/index.html) Police are also known to use [IMSI-catchers](https://www.eff.org/pages/cell-site-simulatorsimsi-catchers) to track who is present at a protest, and to use cell tower records to [see who was present at a protest that happened in the past.](https://www.nytimes.com/interactive/2019/12/19/opinion/location-tracking-cell-phone.html) Police can use some of this data even if your phone was off while you were at the protest. Messages can also be intercepted by [“stingrays,”](https://en.wikipedia.org/wiki/Stingray_phone_tracker) which pretend to be cell towers and trick your phone into connecting to them.

If you want to bring your phone with you, and if you have a farraday bag, bring it to the protest and keep your phone inside and powered off. If you don't have one, you can make one using [this guide.](https://www.instructables.com/id/EASIEST-FARADAY-PHONE-POUCH/)

**If you do not feel safe leaving your phone at home, then make sure to:**
  * put it in airplane mode
  * turn off location services
  * enable a strong passcode (NOT FaceID or a fingerprint ID) (Settings > Security/Privacy)
  * turn off AirDrop
  * Backup your data before you go to the protest
  * Remove any photos, files, or messages that you don't want seen by police
  * Set your phone to lock automatically after a few seconds
  * Turn off lockscreen notifications (Settings > Notifications)
  * use a secure messaging app like Signal to communicate with others

#### Downloading apps

Consider downloading [F-Droid](https://f-droid.org/en/about/) and using it to install apps on your Android phone when possible. The Google Play store can keep track of which apps you download, and can also track people in other ways. F-droid is open-source, and does not track you or your phone. It also allows you to search for and install FOSS (free and open-source software) for your phone.

If you want to install apps using F-Droid, you'll need to [install the F-Droid .apk](https://f-droid.org/en/) before you can use it to install other apps. You can install the F-Droid catalog by downloading the .apk file [directly from their website](https://f-droid.org/en/) using your phone's browser.

#### Location services

Android phones are run on Google services, and Google tracks where you go with your phone, sometimes even when you have GPS turned off. To minimize how much Google is able to track you, [follow this guide.](https://www.theverge.com/2019/4/12/18302306/android-101-location-tracking-stop-how-to) You can also check out Google's official help article on [how to turn off location services.](https://support.google.com/accounts/answer/3467281?hl=en)

Apple can track your iPhone, too. They have an official article on how to turn off location services [here.](https://support.apple.com/en-us/HT207092)

Also make sure to turn off location tagging on any social media accounts you use regularly. This includes Instagram, Twitter, and Facebook. This is especially important if you're talking about protests on social media, but is also generally good practice to prevent getting doxxed or harassed online.

---

<a name="smartphone"></a>
### **(2.2) Smartphone apps for communicating and organizing**

<a name="signal"></a>
### **(2.2.a) [Signal](https://signal.org/download/)**

Signal is a free and open source encrypted messaging app, available for Android, iPhone, and computers.

You can install Signal for your phone [here.](https://signal.org/install)

One of the biggest downsides to Signal is that it requires a phone number to sign up. However, after you've created your account, you can use any phone number for that account. That means that you can spoof (create) a fake phone number to sign up. You will need that phone number to confirm your account in the initial setup process, but once you've done that, you can delete or abandon the fake number you used to sign up.

* [How to sign up on mobile](https://support.signal.org/hc/en-us/articles/360007318691-Register-a-phone-number)
* [Creating a temporary phone number for signup](https://theintercept.com/2017/09/28/signal-tutorial-second-phone-number/)

#### SMS vs. Encrypted messages

Signal also allows you to send SMS messages through the app. This can be a useful function, but keep in mind that SMS messages are not encrypted, and that they can be intercepted by police with devices called [“stingrays.”](https://en.wikipedia.org/wiki/Stingray_phone_tracker) 

You can only send an encrypted Signal message to someone who is also using Signal. You can tell whether you're about to send an SMS or a Signal message by looking at the message entry box before you send a message: if it says "Signal message," then you'll send an end-to-end encrypted message through Signal. If it says "SMS message," you'll send an unencrypted SMS message through Signal.

If you want to disable sending and receiving SMS and MMS messages in Signal, tap the vertical ellipsis icon in the top right of the main app, then tap 'Settings.' Next, select 'SMS and MMS' and make sure that the first option in the menu shows 'SMS Disabled.' If it does not, then tap the first option in the menu and disable SMS.

#### Sending photos

You can take a photo directly within the Signal app and then send it to someone using Signal messaging. The benefit of this is that the photo will not be saved automatically to your phone's unencrypted storage. However, anyone who receives the image can download the image to their phone's regular unencrypted storage and then send it to others, so be aware of that possiblity.

If you want to send an image over Signal, make sure that you first remove any EXIF data from it using one of the [image scrubbers](#photosmeta) that we've linked in this guide. This will make it harder for someone who gets the image file to determine where and when it was taken. If the photo includes any faces in it, we also recommend that you obscure them using the same tools before you share them over Signal.

Signal also added the ability to [blur and obscure portions of photos directly in the app.](https://signal.org/blog/blur-tools/)

#### Disappearing messages

You can set Signal messages to be deleted automatically after a certain amount of time. This will delete the messages from the phone/device of everyone in the conversation. This can be useful if you're worried that someone might get a hold of your phone and be able to look at your messages that way. 

To turn on disappearing messages in a Signal conversation, first open the conversation in Signal. Then, tap the vertical ellipsis icon in the top right corner and select 'Disappearing messages.' From there, you'll be able to set how much time you want messages to remain before they are deleted. To turn off disappearing messages, follow the same steps and select 'Off' from the menu.

Keep in mind that disappearing messages also makes it easier for someone to gaslight you, as any evidence of the conversation will have disappeared. It's important to weigh this against the importance of deleting messages for privacy.

#### Locking access to Signal with a passcode

You can set Signal to require a passcode to open it. This can serve as an extra level of protection to keep people from looking at your messages on your phone. 

To setup a screen lock for Signal, tap the vertical ellipsis icon in the top right corner of the main app. Then, select 'Privacy' from the menu. From there, you can toggle 'Screen lock' on or off. You can also adjust the 'Screen lock activity timeout' to tell Signal to automatically lock your screen again after a certain amount of inactivity.

#### More help

  * If you need more help with Signal, you can visit their official support page [here.](https://support.signal.org/hc/en-us)
  * If you have more questions about Signal's security, you can read more [here.](https://support.signal.org/hc/en-us/categories/360000674811-Security)


<a name="telegram"></a>
### **(2.2.b) [Telegram](https://telegram.org/apps)**

Telegram is a chat app that allows encrypted communication. It is free and open-source. Generally, it is considered to be less secure than Signal, but sometimes it is preferred for certain features, like the ability to make bigger group chats, or the ability to sign up without sharing your phone number.

Telegram is a good second choice if you don't want to use Signal for any reason.

#### Group Chats

The thing with a group chat on telegram is that anyone can join or be invited, depending of the privacy settings of the group chat. This can be a bad thing for organizing. For example, if an undercover agent or an infiltrator convinces someone to join the group, they can see every message that's posted in the group. While this can happen in group chats on any app, the bigger maximum size of group chats on Telegram can make it harder to vet every new member. Keep this in mind when deciding whether to use Signal or Telegram to organize.

<a name="badapps"></a>
### **(2.2.c) Apps to avoid for organizing**

#### Messenger

Facebook Messenger isn't safe for communications. Facebook has a history of collecting data on users and sharing it with others, so don't trust them with your communications. 

Facebook Messenger does not encrypt messages or communications in a way that prevents them from being read by Facebook.

#### Discord

Discord doesn't use end-to-end encryption, which means that police or the NSA could potentially read any of your Discord messages.

Discord also has a policy which says that people should not "promote, encourage, or engage in any illegal behavior." It also does not allow the "organization, promotion, or support of violent extremism." Since the US government has recently said they'd like to declare certain activist organizations to be terrorist organizations, it would be safest to use another platform to communicate.

#### Whatsapp

Although Whatsapp uses end-to-end encryption, it's owned by Facebook. Facebook has a history of disregarding users' privacy, collecting and selling their data, and using it to influence elections. We don't trust Facebook for sensitive communication.

[Here's a good piece from 2016](https://securityinabox.org/en/blog/2016-05-23/why-we-still-recommend-signal-over-whatsapp-even-though-they-both-use-end-to-end-encryption) on why Signal is still better than Whatsapp, even though they both use end-to-end encryption.

---

<a name="OTRchat"></a>
### **(2.3) OTR Chat for desktop computers (Pidgin & Adium)**

OTR Chat uses end-to-end encryption to secure your conversations. 

### [Pidgin (Windows)](https://otr.cypherpunks.ca/)

With the use of the pidgin-otr plugin, Pidgin allows people to use OTR (Off-the-Record) Messaging to communicate with eachother using end-to-end encrypted messages.

  * [Instructions on how to setup Pidgin with the OTR plugin](https://otr.cypherpunks.ca/)

### [Adium (Mac)](https://adium.im/help/pgs/AdvancedFeatures-OTREncryption.html)

Adium allows people to communicate through end-to-end encrypted messaging with its OTR (Off-the-Record) plugin.

  * [Instructions on how to setup Adium and its OTR plugin](https://adium.im/help/pgs/AdvancedFeatures-OTREncryption.html)

---

<a name="vidchat"></a>
### **(2.4) Video chat**

<a name="jitsi"></a>
### **(2.4.a) [Meet Jitsi](https://meet.jit.si/)**

[Meet Jitsi](https://meet.jit.si/) is a free and open-source video chat platform that uses end-to-end encryption. To our knowledge, it's currently the most secure and trustworthy video chat platform available.

To open up a video chat room, go to meet.jit.si and enter a name for the room. Try to make it difficult to guess. Then, give the URL for the room to the people you'd like to chat with. The URL will look something like this: `meet.jit.si/yourroomnamehere`

You can add a password to the room once you've entered it by clicking 'Add password' at the bottom right corner of the screen, or by clicking the 'i' icon in the bottom right, then clicking 'Add password.'

Note that by default, your video and audio will be automatically enabled when you enter the room. So, if you don't want to be seen or heard, make sure you disconnect or cover your camera and/or microphone before you enter the room. The person who creates the room can also adjust the settings when they enter the room to make sure that video and audio are not automatically enabled for people who join the room. To edit these settings, click the vertical ellipsis in the bottom right corner of the screen, then select 'Settings,' then 'More,' and tick the boxes labelled "Everyone starts muted" (for audio) and "Everyone starts hidden" (for video).

Meet Jitsi is also available as an app called Jitsi Meet on [Apple](https://apps.apple.com/us/app/jitsi-meet/id1165103905) and [Android](https://play.google.com/store/apps/details?id=org.jitsi.meet&hl=en) devices. 

You can also download Jitsi Meet on Android using F-Droid [here.](https://f-droid.org/en/packages/org.jitsi.meet/) If you don't already have F-Droid installed on your phone, you'll need to install it before you can use it to install other apps. You can install the F-Droid catalog by downloading the .apk file [directly from their website](https://f-droid.org/en/)) using your phone's browser.

<a name="badvid"></a>
### **(2.4.b) Apps to avoid for video chat**

#### Skype

Skype has claimed that they encrypt communications between users, but because their application is not open-source, it is impossible to verify whether this is true. Users can also create new accounts without any verification required for phone numbers or names, which means that it's very easy for someone to pretend to be someone else.

#### Zoom

[Research by CitizenLab](https://citizenlab.ca/2020/04/move-fast-roll-your-own-crypto-a-quick-look-at-the-confidentiality-of-zoom-meetings/) shows that Zoom has shared encryption keys with others in the past, allowing people to view others' private conversations. Zoom also does not encrypt video chats with end-to-end encryption. This means that Zoom is able to decrypt and monitor calls made using the app. If you want to use a secure video chat app, use [Meet Jitsi](https://meet.jit.si/) instead.

#### Discord

Discord doesn't use end-to-end encryption, which means that police or the NSA could potentially read any of your Discord messages, listen in on voice channels, or view your video calls.
Discord also has a policy which says that people should not "promote, encourage, or engage in any illegal behavior." It also does not allow the "organization, promotion, or support of violent extremism." Since the US government has recently said they'd like to declare certain activist organizations to be terrorist organizations, it would be safest to use another platform to communicate.

---

<a name="secemail"></a>
### **(2.5) Secure email**

Unencrypted email can be intercepted while it's in transit, and anyone who catches one of these unencrypted emails in transit can read it and open its attachments. Luckily, there are tools which allow you to encrypt your email using end-to-end encryption.

[End-to-end encryption](https://en.wikipedia.org/wiki/End-to-end_encryption) encodes a file so that it can only be read by the intended sender and recipient. The intended sender and recipient each have their own unique encryption keys which allow them to decode and read the encrypted file. This means that even if someone logs into your email from another computer, if they don't have your encryption key, they won't be able to read the encrypted email. 

Even if YOU login to your email from another computer where your encryption key is not loaded into your email client, you will not be able to read your encrypted emails. This is important to consider when you decide whether or not to encrypt your email. For example, since I use encryption for my email, I can't read those encrypted emails on my phone. This can be obnoxious, but sometimes it's worth the trouble.

<a name="pgp"></a>
### **(2.5.a) PGP**

[PGP stands for "Pretty Good Privacy,"](https://en.wikipedia.org/wiki/Pretty_Good_Privacy) and that's a great description. It's the most common encryption method for things like email, files, and whole-disk encryption. It can also be sort of a headache to understand when you first start using it. Most people use GnuPG to apply PGP encryption to things.

If you want to encrypt your email, you'll need to use a few pieces of software:
  * [Thunderbird](https://www.thunderbird.net/en-US/)
  * [GnuPG](https://www.gnupg.org/)
  * [Enigmail](https://addons.thunderbird.net/en-US/thunderbird/addon/enigmail/)

In order to encrypt your email, you'll first need to generate a PGP key pair, which will include both a private and a public key. You can do this with [GnuPG.](https://www.gnupg.org/)

Your *private* key is YOURS ALONE, and you should never share it with anyone. Your *public* key is the key you will share with others so that they can decrypt your email or other communications. Someone with your public key will be able to read encrypted emails that you send to them, but NOT encrypted emails that you send to or receive from other people. This is because you need both the sender's and the receiver's key in order to decrypt an email. 

You can upload your public keys to a [public key server](https://ssd.eff.org/en/glossary/public-key-servers) (like the [MIT public key server](https://pgp.mit.edu/)) so that people can easily find your key. Email clients like Thunderbird with Enigmail can also automatically search for a public key associated with an email address, which makes communicating with someone new SO much easier.

I personally had a lot of trouble setting up PGP, so if someone else has better instructions or resources on how to do it, please let me know!

<a name="thunderbird"></a>
#### **(2.5.b) Thunderbird**

Thunderbird is a free email client that allows encryption through the plugin Enigmail.

[This official help article from Mozilla](https://support.mozilla.org/en-US/kb/digitally-signing-and-encrypting-messages) walks you through the process of setting up PGP to be used with Thunderbird for email encryption.

<a name="mailhosts"></a>
#### **(2.5.c) Secure email hosts**

If you want to make sure your email files are stored on a secure server, you can make an account with a host that uses end-to-end encryption to store your email files. Alternatively, you can use POP3 to access your email, which means that your emails will only be stored locally on your computer, and not on a remote server. However, keep in mind that using POP3 also means that you won't be able to access your previously read emails from anywhere. If you want to be able to access your email anywhere, and to do it securely, we recommend you use IMAP and create an account with one of the hosts listed below.

It can also be a good idea to make a new free email account for every new account, as this can help keep someone from piecing together your identity based on your email address. If you do this, make sure to use unique email account usernames and passwords.

#### [Riseup.net](https://riseup.net)

Riseup.net offers end-to-end encrypted email hosting, as well as a bunch of other services. Their goal is to keep activists safe online. They are committed to never turn over any of your data to law enforcement. They also allow you to delete all of your data and your account if you ever need to.

To create a Riseup account, you'll need an invite code. You'll have to get an invite code from someone you know who's had a Riseup account for more than 3 months. If you have a Riseup account, you can generate a new invite code from the [invites page.](https://account.riseup.net/invites)

Once you have an account, you can login at https://mail.riseup.net/rc/ or setup an email client like Thunderbird to access your account. You can learn how to configure your email client for riseup [here.](https://riseup.net/email)

If you don't know anyone with a Riseup account, you can use one of the options below.

#### Other email options
* [Proton mail](https://protonmail.com/)
* [Counter Mail](https://countermail.com/)
* [Hushmail](https://www.hushmail.com/)
* [Mailfence](https://mailfence.com/)
* [Tutanota](https://tutanota.com/) 

---

<a name="anonweb"></a>
### **(2.6) Anonymous web browsing**

Normally, when you access the internet using a web browser, your IP address is visible to the server where the website is hosted. However, there are multiple tools you can use to hide your IP and other identifying information. Some of these tools include [Tor Browser](#torbrowser), [Tails](#tails), and [VPNs](#vpn).

<a name="torbrowser"></a>
### **(2.6.a) [Tor Browser](https://www.torproject.org/download/)**

Tor Browser helps you protect your anonymity by anonymizing your internet browser traffic.

You can download [Tor Browser here.](https://www.torproject.org/download/)

You can find guides on how to use Tor Browser [here.](https://tb-manual.torproject.org/)

Tor works by sending your traffic through three random servers (also known as relays) in the Tor network. The last relay in the circuit (the “exit relay”) then sends the traffic out onto the public Internet. This means that anyone who looks at your activity from the point of view of the website will see the exit relay's IP address, not yours. For a more in-depth explanation of how the tor network works, check out the [Tor Project website.](https://tb-manual.torproject.org/about/)

Anyone who looks at your web activity on either end (your ISP or the website provider) will be able to tell that you're using Tor Browser, but they won't be able to see what you did with Tor Browser. Some countries will use this to prevent people from accessing Tor Browser. If you need help [circumventing](https://tb-manual.torproject.org/circumvention/) a block on Tor Browser, you can try using a [bridge or a pluggable transport.](https://tb-manual.torproject.org/bridges/), both of which are built directly into Tor Browser. 

Tor Browser also helps prevent against [fingerprinting](https://en.wikipedia.org/wiki/Device_fingerprint) by making your browser look incredibly average. However, it's important to make sure that you do not resize the Tor Browser window, as doing so makes your browser fingerprint more unique. You can test to see how strong your fingerprinting defense is [with EFF's tool Panopticlick,](https://panopticlick.eff.org/) but keep in mind that this testing tool is not foolproof or perfect.

When using Tor Browser, you'll need to change some of your normal browsing behavior to keep your privacy protections as strong as possible:
  * do not resize the Tor Browser window
  * do not download things from the browser if possible, and do not torrent while using the tor network
  * enable the included NoScript browser add-on
  * adjust the security level as necessary by clicking the shield icon next to the URL bar
  * do not use Tor Browser to access social media accounts or other accounts that can link you to your identity
  * avoid sitting near surveillance cameras when using Tor Browser, as their video footage can be used to link you to your web activity
  * do not use a VPN at the same time as Tor Browser
  
Tor Browser also lets you view [onion sites.](https://en.wikipedia.org/wiki/.onion) An onion site is any website that uses a '.onion' domain. Most onion links consist of at least 16 random characters, followed by '.onion.' An onion site is *only* accessible via Tor Browser, and onion sites are not listed publicly the way that most regular websites are. That means that the most reliable way for someone to find an onion site is to be given the onion link by someone else. This makes it easier to control who sees your website, and is especially useful if you don't want your website to be easily accessible or searchable. 

One of the main contributors to Tor created [GhostWriter,](https://ghostwriter.sh/) an open-source tool that allows you to easily create an onion site and host it on onionshare.org or on your computer. To learn how to get started, check the [GhostWriter wiki on Github.](https://github.com/hiromipaw/ghostwriter)

<a name="otherbrowsers"></a>
### **(2.6.b) Other browsers**

#### [Brave](https://brave.com/)

Brave (https://brave.com/) is a browser that uses the tor network, blocks ad-trackers, and other tools to protect your privacy. 

#### Firefox

Firefox has recently added a bunch of new privacy-minded features to their browser. Mozilla is continuously collaborating with the Tor Project to add new ways for their browser to protect your identity. The biggest feature they offer at the moment is ad-tracking prevention, which helps prevent ad trackers from following you around the internet, collecting your information and history, and building a profile on you. 

While Firefox is the least private of any of the browsers here, it is the best option for regular, low-risk browsing. We highly recommend using it instead of Chrome or Safari. 

<a name="browsebehavior"></a>
### **(2.6.c) Secure browsing behavior**

Browsing the internet safely and securely takes more than just an anonymizing browser. You'll need to make some changes to your regular browsing behavior, too. 

#### Search engines

Use https://duckduckgo.com instead of Google - DuckDuckGo doesn't track or record your searches. 

#### Sending files
  * small files: encrypted email, Signal
  * large files: https://onionshare.org/, https://send.firefox.com
    * onionshare allows you to send files over an encrypted tor network connection. Onionshare also encrypts your files for you. It is the most secure option for sending large files directly. 
    * Firefox Send also allows you to send files and encrypts them for you automatically, but if you want to send anything larger than 1GB, secure your download link with a password, or set the link to work for multiple days or downloads, you'll need to create an account with them, which may make it easier for others to trace your activity to your identity.

#### Trustworthy browser extensions to protect yourself online

Privacy Badger https://www.eff.org/privacybadger 
UblockOrigin https://getublock.com/ 
HTTPS everywhere https://www.eff.org/https-everywhere

If these are the only browser extensions you use, you'll be golden. Be wary of installing browser extensions from untrusted or unknown sources.

---

<a name="vpn"></a>
### **(2.7) VPNs**

A [VPN](https://ssd.eff.org/en/module/choosing-vpn-thats-right-you) is a tool that allows you to pass your internet traffic through another server. This sort of works like a basic disguise, because if anyone takes a quick look at who was accessing a certain website at a specific time, and they see your traffic, they'll see your VPN's IP address instead of your own. VPNs also encrypt your web traffic, which makes it harder for an onlooker to see what you're doing online. However, keep in mind that a VPN is not as secure as an anonymizing tool like [Tor Browser](#torbrowser) or [Tails.](#tails)

It's important to do your research before choosing a VPN provider, as some VPN providers are not opposed to turning over data to the police when prompted. For help picking a VPN, check out [EFF's guide here.](https://ssd.eff.org/en/module/choosing-vpn-thats-right-you)

<a name="freevpaidvpn"></a>
### **(2.7.a) Free vs. Paid**

Free VPNs can sometimes be less trustworthy, because some of them pay for their server costs by selling people's data. 

That being said, there's not really anything keeping a paid VPN provider from doing the same thing. 

However, because it can be expensive for a VPN provider to maintain their servers, sometimes you really do get what you pay for.

<a name="riseupvpn"></a>
### **(2.7.b) [Riseup VPN](https://riseup.net/en/vpn)**

Riseup offers a free VPN service. Their goal is to keep activists safe online. They are committed to never turn over any of your data to law enforcement.

To create a Riseup account, you'll need an invite code. You'll have to get an invite code from someone you know who's had a Riseup account for more than 3 months. If you have a Riseup account, you can generate a new invite code from the [invites page.](https://account.riseup.net/invites)

Because Riseup is a non-profit and volunteer-run organization, their servers are paid for with donations from volunteers. This also means that their server capacity isn't huge, and sometimes, their servers get overloaded. This is just something to keep in mind.

Personally, I trust Riseup more than any of the other providers on this list, and they are my first choice for a VPN.

<a name="firefoxvpn"></a>
### **(2.7.c) Firefox VPN**

Firefox offers a paid VPN service for $4.99 USD/month. Mozilla is generally fairly trustworthy, and has a track record of taking care of people's security and privacy. However, the VPN service is relatively new, and I'm not sure if it's been audited yet to verify its security and privacy practices. 

#### Other paid VPN providers

I can't recommend or anti-recommend any of these providers, so please [do your research before making a decision.](https://ssd.eff.org/en/module/choosing-vpn-thats-right-you)

[NordVPN](https://nordvpn.com/): price varies based on the duration of your plan, but the base monthly price is $11.95 USD/month

---

<a name="tails"></a>
### **(2.8) [Tails](https://tails.boum.org/install/index.en.html)**

[Tails](https://tails.boum.org/install/index.en.html) is "The Amnesic Incognito Live System." It is an operating system which routes all internet traffic through the [tor network,](https://en.wikipedia.org/wiki/Tor_(anonymity_network)) and leaves no trace of its use on the computer where it's used. You can install it on a USB drive and run the OS from any computer, or you can install it next to the existing OS on your computer and boot into it whenever you want privacy.

You can also install Tails in a way that allows you to save files to your Tails OS, and also encrypts the entire partition used for Tails. Otherwise, everything you do on Tails will disappear automatically when you shut down Tails.

To install Tails on a USB, you'll need a computer with at least 1.2 GB of storage space, a USB with at least 16 GB of storage space, and at least 30 minutes to run the installation process. You can [download Tails and get started here.](https://tails.boum.org/install/index.en.html)

---

<a name="photosmeta"></a>
### **(2.9) Photos, filming, faces, and metadata**

When you take a photo or video on your phone, your phone automatically saves some information about when and where the photo was taken, as well as the kind of phone used to take the photo/video. This data is called 'metadata,' or more specifically, EXIF data. This data can be easily viewed by anyone, and law enforcement can use it to identify when and where a photo/video was taken. This makes it easier for law enforcement to identify who took the photo/video, or who might appear in it. 

While documenting what happens at a protest can be important, it's also important to protect the identities of protesters present in the photo or video. Luckily, there are multiple free tools you can use to erase or spoof EXIF data, and to blur/obscure faces and other identifying features.

#### Blur vs. obscure

It's important to note that obscuring a feature using a black square or other image is often much safer than simply blurring it. This is because tools exist which make un-blurring an image relatively easy. For this reason, it's generally better to obscure a feature instead of blurring it, if you can.

<a name="documenting"></a>
### **(2.9.a) Filming and documenting safely**

<a name="imagescrubber"></a>
### **(2.9.b) [Image-scrubber](https://everestpipkin.github.io/image-scrubber/)**

[Image-scrubber](https://everestpipkin.github.io/image-scrubber/) is a browser-based tool that allows you to remove EXIF metadata from photos and blur/obscure faces or identifying features. You can use the tool from your phone's browser, regardless of your phone's OS. The photos you edit using this tool aren't sent anywhere when you edit them: all the editing is done on your phone instead of on a remote server.

<a name="obscuracam"></a>
### **(2.9.c) [Obscuracam](https://guardianproject.info/apps/obscuracam/)**

[Obscuracam](https://guardianproject.info/apps/obscuracam/) is an app developed by [the Guardian Project.](https://guardianproject.info/) Obscuracam allows you to remove any metadata from a photo or video. The app also has automatic face detection, which makes quickly blurring a large number of faces in a photo or video super easy.

The app is available for Android on the [Google Play store](https://play.google.com/store/apps/details?id=org.witness.sscphase1&feature=search_result) and on [F-Droid.](https://f-droid.org/en/packages/org.witness.sscphase1/) If you don't already have F-Droid installed on your phone, you'll need to [install the F-Droid .apk](https://f-droid.org/en/) before you can use it to install other apps. You can install the F-Droid store by downloading the .apk file [directly from their website](https://f-droid.org/en/)) using your phone's browser.

<a name="scrambled"></a>
### **(2.9.d) [Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif)**

[Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif) is an app that allows you to easily remove EXIF data from a photo or video before sharing it. 

The app is available for Android on the [Google Play store](https://play.google.com/store/apps/details?id=com.jarsilio.android.scrambledeggsif&hl=en_US) and on [F-Droid](https://f-droid.org/en/packages/com.jarsilio.android.scrambledeggsif/). If you don't already have F-Droid installed on your phone, you'll need to [install the F-Droid .apk](https://f-droid.org/en/) before you can use it to install other apps. You can install the F-Droid store by downloading the .apk file [directly from their website](https://f-droid.org/en/)) using your phone's browser.

To use the app, tap the 'share' button in another app, then select Scrambled Exif from the list of options. This will tell Scrambled Exif to remove the EXIF data from your file. Once the EXIF data has been removed, another share window will open, and you'll be able to send the file using any app on your phone.

<a name="signalblur"></a>
### **(2.9.e) [Signal Blur](https://signal.org/blog/blur-tools/)**

The latest version of [Signal](#signal) for Android and iOS includes a blur/obscure tool right in the image editor. You can tap the blur icon (looks like a checkerboard inside a circle) to apply a blur effect, or use the pen tool to draw over faces or identifying features.

You can install Signal for your phone [here.](https://signal.org/install)


---

<a name="digisecbehavior"></a>
### **(2.10) Behavior and social organization**

Beware of undercover cops in your group chats and online organizing groups, but also be wary of people accusing others of being narcs/spies/undercover cops. Accusing others can be a tactic to sow distrust in a movement. 

Both of these reasons mean that sometimes it's best to organize in small groups with people you know directly and trust deeply, or to rely on a trusted organization like [Black Lives Matter](https://blacklivesmatter.com/) for up-to-date information on local protests.

Be wary of using your chosen name or legal name: in the US, finding someone's address with only their name is trivial, thanks to data brokers.  Data Brokers are people or companies who use public records to gather personal info and contact details of people. If you've ever been arrested, recieved a ticket, gotten married, that's all public information including any personal data that you include in your social media depending on your privacy settings. These data brokers create lists of that information to sell. This invasive economy can be triggering and dangerous for Trans folks who often still have legal ties to their deadnames.

One good thing is that most data brokers reluctantly offer a process by which you can request to be taken off the lists they provide for purchase. 

It takes time to opt out but we got you by providing the resources to make that happen.  Start by looking for yourself on a data broker’s list - then search for their opt-out page and read through the process they outline for getting yourself removed.  Services like [DeleteMe](https://joindeleteme.com/help/diy-free-opt-out-guide/) offer step-by-step directions to do this work.

Here's a list of some of the major data brokers.  These links go directly to their opt out pages:

 * [Spokeo](https://www.spokeo.com/optout)
 * [Whitepages](https://www.whitepages.com/suppression_requests)
 * [Peoplesmart](https://www.peoplesmart.com/optout-go)
 * [People Finder](https://www.peoplefinders.com/manage)
 * [MyLife](https://joindeleteme.com/help/kb/how-to-remove-yourself-from-mylife/)


---

<a name="infrastructure"></a>
### **(2.11) Advanced: Infrastructure, servers, and hosting**

This section is for people who are willing to dig deep to learn about digital security. Beware that once you start down this path, you'll need to know A LOT to make sure the websites and resources you're building are secure. Either that, or you'll need to find a friend who knows a lot.

If you want to get started learning how to setup digital infrastructure like cloud servers, websites, and hosting resources, Digital Ocean is a great place to start. Their [documentation](https://www.digitalocean.com/community/tutorials) is a treasure trove of easy to understand instructions on how to do almost anything on a digital server. I've learned half of what I know from their user-created tutorials.

<a name="how2cloudserver"></a>
### **(2.11.a) How to setup your own cloud server**

If you want to setup your own cloud server for whatever reason, you'll first need to:
  * pick a hosting provider and create an account with them
  * purchase a cloud server
  * setup the server
  * access the server remotely, either using SSH on your home computer, or using a terminal emulator on the host's website

If you want to get started learning how to setup a cloud server from scratch, [Digital Ocean's tutorials](https://www.digitalocean.com/community/tutorials) are a great place to start. You can find a guide for everything there. You can even access these tutorials if you don't actually use Digital Ocean's servers.

All that being said, Digital Ocean may not be the best place to host your stuff. I have no idea what their political stances are, and so I don't know what their policy is on removing content or taking down servers. As a sort of litmus test, they allow Tor relays to be installed on their servers, as long as they're not Tor exit relays (this means they're okay, but not great). Their servers are also extremely affordable compared to a lot of other services, and you have the option to start small and expand your server if you need more storage space or RAM. Do your research and decide which hosting platform is best for you.

If you're up to it, the best OS for running a cloud server is [Linux.](https://en.wikipedia.org/wiki/Linux) This is because it really gives you the most control over your server. Linux might seem intimidating, but speaking as someone who was terrified of it in the past and now uses it almost exclusively, you can ABSOLUTELY learn how to use it. If you're intimidated by terminals and Linux in general, [Ubuntu](https://ubuntu.com/) is a great Linux distribution to start with. However, if you really don't want to get into all that right now, go ahead and use whatever OS you're most comfortable with.

<a name="how2SSH"></a>
### **(2.11.b) How to use SSH to access a remote server**

(To be added)

<a name="how2jistihost"></a>
### **(2.11.c) How to host a Jitsi video chat instance on your server**

(To be added)

<a name="how2torrelay"></a>
### **(2.11.d) How to host a tor relay**

This is a bonus, but building up the infrastructure of the Tor network helps to protect activists who need Tor to stay safe.

What is a [tor relay?](https://community.torproject.org/relay/) 
A tor relay is a 'node' through which traffic is funneled on the tor network. These nodes receive traffic on the tor network and pass it along. Any connecting using the tor network will be funneled through at least 3 nodes between the start and end point. A typical connection on the tor network looks like this:

User's PC > Guard Relay > Middle Relay > Exit Relay > Website 

In summary, the tor network runs on relays. Volunteers can setup relays on their own servers to help contribute bandwidth to the tor network.

Tor has an [official guide on how to setup a tor relay,](https://trac.torproject.org/projects/tor/wiki/TorRelayGuide) but it is unfortunately not exhaustive, and pretty out of date. It's very possible that you'll run into problems that you won't be able to solve using their guide. Luckily, they have a [mailing list](https://lists.torproject.org/cgi-bin/mailman/listinfo/tor-relays) and an IRC channel (#tor-relays on [irc.oftc.net](https://support.torproject.org/get-in-touch/#irc-help))where you can ask questions. They also have a new [relay operations hub](https://community.torproject.org/relay/) on their community site which is being updated more regularly.

<a name="makeonion"></a>
### **(2.11.e) How to make and host an onionsite**

An [onion site](https://en.wikipedia.org/wiki/.onion) is any website that uses a '.onion' domain. Most onion links consist of at least 16 random characters, followed by '.onion.' An onion site is *only* accessible via Tor Browser, and onion sites are not listed publicly the way that most regular websites are. That means that the most reliable way for someone to find an onion site is to be given the onion link by someone else. This makes it easier to control who sees your website, and is especially useful if you don't want your website to be easily accessible or searchable. 

One of the main contributors to Tor created [GhostWriter,](https://ghostwriter.sh/) an open-source tool that allows you to easily create an onion site and host it on onionshare.org or on your computer. To learn how to get started, check the [GhostWriter wiki on Github.](https://github.com/hiromipaw/ghostwriter)


---

<a name="protestsafety"></a>
## **(3.0) Protest Safety**

One of the best guides we've seen so far is [From Beirut to Minneapolis](https://github.com/frombeirutwithlove/ProtestTips/blob/master/WhatToDo.md), written by Lebanese protesters, technologists, and activists based on their experiences with the ongoing protests in Lebanon. We've adapted some of their tips here, and added some of our own. We really recommend you read through their guide for some of the best protest safety advice. They also provide advice on what to bring to a protest, what to wear, and how to organize safely.

The [BLM Guide](https://www.notion.so/BLM-Guide-fac525a6d1324d458d15bdc4fec98661) also has tips on how to stay safe while organizing.

Be aware that arrests are happening at these protests: people are being arrested simply for being present. If you do not want to risk getting arrested for any reason, you may want to consider staying home and [providing support from there.](#helpfromhome)

<a name="gensafety"></a>
### **(3.1) General Safety**

#### Tear Gas

[CDC Fact Sheet on Tear Gas](https://emergency.cdc.gov/agent/riotcontrol/factsheet.asp)

Tear gas can stick to face paint and makeup, so it's best to go without. Nylons and fishnets can also aggravate the effects of tear gas and other riot control agents.

If tear gas is deployed, move upwind (in the opposite direction from where the wind is blowing) and uphill as quickly as you can.

If you are wearing contacts, remove them immediately after tear gas is deployed. Be sure to remove contacts BEFORE rinsing your eyes.

##### Anti-Tear gas tactics

  * Tear gas canisters can be extinguished using water or fire extinguishers. A squirt-nozzle waterbottle can be extra effective for this. Hong Kong protesters in the Umbrella Movement have developed various techniques to neutralize tear gas canisters.
    * You can place a traffic cone over a tear gas canister to limit the spread of the chemicals, and then pour water into the hole in the traffic cone to extinguish the canister.
    * If you plan on handling tear gas canisters, WEAR HEAT RESISTANT GLOVES, as the canisters are HOT!

#### Facial recognition tech

If you want to confuse facial recognition technology, the best tactic is to wear a face mask and glasses, and this has the added benefit of protecting you from COVID-19. Don't try to do special makeup to confuse AI - this doesn't really work that well anymore, and the makeup can make tear gas stick more easily to your face. It may also make it easier for police to pick you out in a crowd.

#### LRADs 

Make sure to bring earplugs or cotton balls with you to a protest, as there have been reports of police using [Long-Range Acoustic Devices](https://en.wikipedia.org/wiki/Long_Range_Acoustic_Device) against protesters. These devices can cause hearing damage and discomfort.

---

<a name="binders"></a>
### **(3.2) Binder safety**

If you wear a binder, consider leaving it at home when you go out to protest. Binders usually constrict your chest, and can make breathing more difficult when running or doing other strenuous activity. Tear gas and pepper spray often used by police at protests, and both of these agents can restrict your breathing and agravate asthma or other respiratory conditions. 

Instead, you might want to use a sports bra, since it restricts breathing less than a binder, and because it may be easier to remove if you need to. DO NOT use ACE bandages, as they are designed to constrict automatically when your body expands, and can put extra stress on  your chest and lungs. 

In general, follow the same guidelines that you would when exercising, and be sure that you can remove whatever you're wearing easily in case you're exposed to tear gas or pepper spray.

---

<a name="firstaid"></a>
### **(3.3) First Aid**

Remember that if you're not trained to give someone medical treatment, and someone needs medical attention, then you need to get that person medical attention as soon as possible. These tips are for minor first aid, or for taking care of someone while you're waiting for an ambulance to arrive or for medical assistance from trained medical personnel.

If you want to be a medic, check out this [infographic](https://pbs.twimg.com/media/EZnTKWiVcAANUuS?format=jpg&name=large) put together by protesters from Chile, Hong Kong, and BLM.

Riot Medicine has an incredibly in-depth [downloadable PDF guide](https://riotmedicine.net/static/downloads/riot-medicine.pdf) on medical intervention.

#### Tear gas & riot control agents

[CDC fact sheet on tear gas](https://emergency.cdc.gov/agent/riotcontrol/factsheet.asp)
[Riot ID guides on how to identify riot control agents (EN, ESP, AR, FRE, GER, GRE, IT, TUR)](https://riotid.com/)

  * When dressing for the protest, try to cover as much of your skin as possible. This will help protect you from exposure to tear gas, pepper spray, and other chemical agents.
  * If you have been exposed to tear gas or other chemical agents, rinse your eyes as soon as possible. When you get home, remove your clothing and place it in a plastic bag, then place that bag in another plastic bag, being careful not to let your clothing touch other surfaces. Then, get in the shower and rinse yourself off with cold water until the burning lessens. Washing with soap and cold water should get the chemicals off your skin. Hot water can make the burning worse.
  * The CDC recommends you rinse eyes with plain, clean water.
    * When rinsing someone's eyes, rinse from the inside (near the nose) to the outside of the eye (towards the cheek). Tilt the person's head to the side so that the rinsing liquid can run down their eye and off their face.
  * Milk can be used on your skin to alleviate burning, but don't use it on your eyes. If milk gets in your eyes, rinse it out.

#### Wound care

  * If someone is bleeding severely, keep pressure on their wound, elevate the wound (if possible), and get them medical help ASAP.
  * For smaller wounds, you can follow the [Mayo Clinic guidlines here.](https://www.mayoclinic.org/first-aid/first-aid-cuts/basics/art-20056711)

#### Dehydration

  * If someone is dehydrated, they'll need to be rehydrated SLOWLY. Chugging water when you're severely dehydrated can shock your stomach and make you throw up. Encourage them to take small sips over time until they start to feel better. A straw can be helpful here.
  * Drinks with electrolytes (pedialyte, gatorade) can also help to rehydrate someone who is dehydrated.

---

<a name="govtid"></a>
### **(3.4) What to do if your ID doesn't match your gender**

It can be hard to know what to do in this situation, and the law is pretty vague and unhelpful.

Some ideas for what to do if you're arrested/accosted by police, and they ask why your ID doesn't match your gender:
  * backpass (play along as if the gender on your ID is correct), if you feel comfortable and safe doing so
  * bring other documents to corroborate your name, like a phone bill or utilities bill that has your name and address on it. However, it's possible that this could be used against you, and you might not have time to use it.
  * know the laws in your state regarding ID, protesting, and trans rights
  * have a friend with you to advocate for you, record video or audio, and act as a witness
  * avoid confrontations with the police, and avoid arrest as much as possible. If you don't want to get arrested, then you can back out if things start going south.

<a name="ifurarrested"></a>
### **(3.5) What to do if you are arrested**

This advice comes from the [ACLU's "Protesters' Rights" document.](https://www.aclu.org/know-your-rights/protesters-rights/?initms_aff=nat&initms_chan=soc&utm_medium=soc&initms=200531_kyr_tw&utm_source=tw&utm_campaign=&utm_content=200531_freespeech_kyr&ms_aff=nat&ms_chan=soc&ms=200531_kyr_tw)
 
  * Stay calm. Make sure to keep your hands visible. Don’t argue, resist, or obstruct the police, even if you believe they are violating your rights. Point out that you are not disrupting anyone else’s activity and that the First Amendment protects your actions.
  * Ask if you are free to leave. If the officer says yes, calmly walk away.
  * If you are under arrest, you have a right to ask why. Otherwise, say you wish to remain silent and ask for a lawyer immediately. Don’t say anything or sign anything without a lawyer.
  * You have the right to make a local phone call, and if you’re calling your lawyer, police are not allowed to listen.
  * You never have to consent to a search of yourself or your belongings. If you do explicitly consent, it can affect you later in court.
  * Police may “pat down” your clothing if they suspect you have a weapon and may search you after an arrest.
  * Police officers may not confiscate or demand to view your photographs or video without a warrant, nor may they delete data under any circumstances. However, they may order citizens to cease activities that are truly interfering with legitimate law enforcement operations.


<a name="orgstocall"></a> 
### **(3.6) Organizations to call if you're in trouble**

Many legal aid organizations cannot provide legal advice over the phone. If you can, do research into organizations before going to a protest so that you know who you can call if you're arrested. 

  * Make sure you have the phone number of a trusted contact written on your arm in sharpie before you go to a protest.
  * Consider writing the nubmer for a bail fund on your arm before you go to a protest.

<a name=""></a>
### **(3.6.a) Trans advocacy organizations**

(alhpabetical by state)

**California (CA):**
  * [TGI Justice:](http://www.tgijp.org/) http://www.tgijp.org/
    * [Donate:](http://www.tgijp.org/donate.html) http://www.tgijp.org/donate.html

**New York (NY):**
  * [Silvia Rivera Law Project:](https://srlp.org/) https://srlp.org/
  * [Transgender Legal Defense & Education Fund:](https://transgenderlegal.org/) https://transgenderlegal.org/
  


<a name="bailfunds"></a>
### **(3.6.b) Bail funds by region**

Some bail funds will also help you through the release process, and provide some support after you've been released.

(alphabetical by state)

**National:**
  * [LGBTQ Freedom Fund](https://www.lgbtqfund.org/) 
    * [Website:](https://www.lgbtqfund.org/) https://www.lgbtqfund.org/
    * [Donate:](https://www.lgbtqfund.org/donate-1) https://www.lgbtqfund.org/donate-1
    * [Contact:](https://www.lgbtqfund.org/our-impact) https://www.lgbtqfund.org/our-impact
    
  * [The Bail Project](https://bailproject.org/)
    * [Website:](https://bailproject.org/) https://bailproject.org/
    * [Donate:](https://secure.givelively.org/donate/the-bail-project) https://secure.givelively.org/donate/the-bail-project
    
  * [Restoring Justice Community Bail Fund](https://www.restoringjustice.org/bail)
    * [Website:](https://www.restoringjustice.org/bail) https://www.restoringjustice.org/bail
    * [Donate:](https://www.restoringjustice.org/give) https://www.restoringjustice.org/give
    
**Connecticut (CT):**
  * [Connecticut Bail Fund](https://www.ctbailfund.org/)
    * [Website:](https://www.ctbailfund.org/) https://www.ctbailfund.org/
    * [Donate:](https://ctbailfund.z2systems.com/np/clients/ctbailfund/donation.jsp) https://ctbailfund.z2systems.com/np/clients/ctbailfund/donation.jsp
    
**Illinois (IL):**
  * Chicago Community Bond Fund 
    * *Currently not accepting new requests for help paying bond at this time.* However, they are still available to help people arrested for protesting, in coordination with the [National Lawyers Guild of Chicago.](https://nlgchicago.org/) If you need legal representation, they ask that you call NLG of Chicago at 773-309-1198.
    * [Website:](https://chicagobond.org/) https://chicagobond.org/
    * [Donate:](https://chicagobond.org/donate/) https://chicagobond.org/donate/
    * [Request help:](https://chicagobond.org/the-revolving-fund-2/) https://chicagobond.org/the-revolving-fund-2/
  
**Kentucky (KY):**
  * Louisville Community Bail Fund
    * Exists not only to bail out folks, but to provide post-release support to get them from jail, fed and to a situation of safety. LCBF also maintains a focus on preventative measures for those targeted by law enforcement and threatened with incarceration.
    * [Facebook group:](https://www.facebook.com/groups/1977488899150776) https://www.facebook.com/groups/1977488899150776
    * [Donate:](https://actionnetwork.org/fundraising/louisville-community-bail-fund/) https://actionnetwork.org/fundraising/louisville-community-bail-fund/
    
**North Carolina (NC):**
  * [Forsyth County Bail Fund](https://forsythcountycbf.org/)
    * [Website:](https://forsythcountycbf.org/) https://forsythcountycbf.org/
    
**Pennsylvania (PA):**
  * [Philadelphia Bail Fund](https://www.phillybailfund.org/)
    * [Website:](https://www.phillybailfund.org/) https://www.phillybailfund.org/
    * [Donate:](https://www.phillybailfund.org/donate) https://www.phillybailfund.org/donate
  * [Dauphin County Bail Fund](https://dauphincountybailfund.org/)
    * [Website:](https://dauphincountybailfund.org/) https://dauphincountybailfund.org/
    * [Donate:](https://dauphincountybailfund.org/donate/) https://dauphincountybailfund.org/donate/
    * [Request Help:](https://dauphincountybailfund.org/request-help/) https://dauphincountybailfund.org/request-help/
  * [Bukit Bail Fund of Pittsburgh](https://www.bukitbailfund.org/)
    * [Website:](https://www.bukitbailfund.org/) https://www.bukitbailfund.org/
    * [Donate:](https://www.bukitbailfund.org/donate) https://www.bukitbailfund.org/donate
    
**Washington State (WA):**
  * [Black Lives Matter Seattle Freedom Fund](https://blacklivesseattle.org/bail-fund/)
    * [Website:](https://blacklivesseattle.org/bail-fund/) https://blacklivesseattle.org/bail-fund/
    * [Donate to the BLM Seattle chapter:](https://blacklivesseattle.org/donate/) https://blacklivesseattle.org/donate/
  * [Northwest Community Bail Fund](https://www.nwcombailfund.org/)
    * NCBF provides cash bail for those who are unable to pay due to poverty, are charged with crimes in King and Snohomish Counties, and have no other holds.
    * [Website:](https://www.nwcombailfund.org/) https://www.nwcombailfund.org/
    * [Donate:](https://donorbox.org/ncbf) https://donorbox.org/ncbf
    * [Request Help (google form):](https://docs.google.com/forms/d/e/1FAIpQLSdezm3QHDjN8psqNpw5KDCz4FXO1wTNz9QKh_-OuX_KhaThXg/viewform) https://docs.google.com/forms/d/e/1FAIpQLSdezm3QHDjN8psqNpw5KDCz4FXO1wTNz9QKh_-OuX_KhaThXg/viewform

---

<a name="mutaid"></a>
## **(4.0) Mutual aid**

<a name="mutaidreg"></a>
### **(4.1) Mutual aid groups by region**

<a name="mutaidUSA"></a>
### **(4.1.a) USA**
(alphabetical by state)

**National:**
  * [National COVID-19 Mutual Aid document (Google Docs):](https://docs.google.com/document/d/1dpMzMzsA83jbVEXS8m7QKOtK4nj6gIUk1U1t6P4wShY/edit) https://docs.google.com/document/d/1dpMzMzsA83jbVEXS8m7QKOtK4nj6gIUk1U1t6P4wShY/edit
  * [It's Going Down - Resources for Mutual Aid Organizing:](https://itsgoingdown.org/autonomous-groups-are-mobilizing-mutual-aid-initiatives-to-combat-the-coronavirus/) https://itsgoingdown.org/autonomous-groups-are-mobilizing-mutual-aid-initiatives-to-combat-the-coronavirus/

**California (CA):**
  * [Los Angeles Covid-19 Mutual Aid Network (Gofundme):](https://www.gofundme.com/f/covid19-mutual-aid-network) https://www.gofundme.com/f/covid19-mutual-aid-network

**Georgia (GA):**
  * [Metro Atlanta Mutual Fund (website):](https://www.atlantamutualaid.org/) https://www.atlantamutualaid.org/

**Kentucky (KY):**
  * [Louisville Mutual Aid (Gofundme):](https://www.gofundme.com/f/louisville-mutual-aid-a-new-world-is-possible) https://www.gofundme.com/f/louisville-mutual-aid-a-new-world-is-possible

**Massachusetts (MA):**
  * [Boston Solidarity Supply Distro (fundrazr):](https://fundrazr.com/f1dTp3?ref=ab_00qJXsXpLia00qJXsXpLia)  https://fundrazr.com/f1dTp3?ref=ab_00qJXsXpLia00qJXsXpLia

**Missouri (MO):**
  * [St. Louis Mutual Aid (Donorbox):](https://donorbox.org/stl-mutual-aid-fund) https://donorbox.org/stl-mutual-aid-fund
  
**Minnesota (MN):**
  * [Minneapolis Defend Glendale & Public Housing Coalition (Action Network):](https://actionnetwork.org/fundraising/public-goods/) https://actionnetwork.org/fundraising/public-goods/

**New Mexico (NM):**
  * [Fight For Our Lives - ABQ Mutual Aid (website):](http://www.ffol.org/mutualaid.html) http://www.ffol.org/mutualaid.html

**New York (NY):**
  * [Richmond (Paypal):](https://www.paypal.me/richmondmutualaid) https://www.paypal.me/richmondmutualaid
  * [Mutual Aid NYC (Website):](https://mutualaid.nyc/get-involved/donate/) https://mutualaid.nyc/get-involved/donate/
 
**Ohio (OH):**
  * [Cleveland Pandemic Response - COVID-19 Community Hub (website)](https://cleveland.recovers.org/) https://cleveland.recovers.org/
  
**Pennsylvania (PA):**
  * [Mutual Aid Philadelphia (Paypal):](https://www.paypal.com/pools/c/8oNSd8W8KH) https://www.paypal.com/pools/c/8oNSd8W8KH

**Utah (UT):**
  * [Salt Lake Valley COVID Mutual Aid](https://www.covid19mutualaidslc.com/) https://www.covid19mutualaidslc.com/

**Washington State (WA):**
  * [Seattle COVID-19 Survival Fund for the People (Gofundme):](https://www.gofundme.com/f/covid19-survival-fund-for-the-people) https://www.gofundme.com/f/covid19-survival-fund-for-the-people

**Washington, DC :**
  * [East Of The River Mutual Aid Fund (Gofundme)](https://www.gofundme.com/f/blmcovid) https://www.gofundme.com/f/blmcovid

<a name="mutaidCAN"></a>
### **(4.1.b) Canada**
  * Toronto, ON:
    * [The 519 (website):](https://www.the519.org/) https://www.the519.org/
    
  * Montreal, QC:
    * [Taking What We Need (Facebook group):](https://www.facebook.com/takingwhatweneed/) https://www.facebook.com/takingwhatweneed/

---

<a name="helpfromhome"></a>
## **(5.0) How to help if you can't physically go to a protest**

While showing up physically to a protest is important to a movement, not all of us are able to risk it: some of us are undocumented, some of us have vulnerable immune systems, and some of us have disabilities. There are plenty of legitimate reasons why someone might not be able to attend a protest, or why someone might not feel safe attending a protest.

### Some other ways to help organize from home:
  * [Ways You Can Help](https://blacklivesmatters.carrd.co/)
    * Includes a map of protests, links to petitions you can sign, numbers you can call, places to donate, resources for white people to use to educate themselves, and more.
  * Donate to a [bail fund](#bailfunds)
  * [Split a donation between 70+ community bail funds, mutual aid funds, and racial justice organizers:](https://secure.actblue.com/donate/bail_funds_george_floyd) https://secure.actblue.com/donate/bail_funds_george_floyd
  * Donate to a gofundme
    * [Gofundme made by George Floyd's family:](https://www.gofundme.com/f/georgefloyd) https://www.gofundme.com/f/georgefloyd
    * [Gofundme made by George Floyd's sister:](https://www.gofundme.com/f/george-floyd-bigfloyd) https://www.gofundme.com/f/george-floyd-bigfloyd
    * [Gofundme made by Breonna Taylor's familky:](https://www.gofundme.com/f/9v4q2-justice-for-breonna-taylor) https://www.gofundme.com/f/9v4q2-justice-for-breonna-taylor
  * Donate to a local [BLM chapter](https://blacklivesmatter.com/chapters/): https://blacklivesmatter.com/chapters/
  * Provide support for your friends who are at a protest
    * Listen to police scanners using https://www.broadcastify.com/ and relay information to someone at the protest
    * Keep an eye on social media to watch for developments
    * Ask your friends to message you when they're leaving home and when they arrive home safe
    * If your home is near a protest location, consider offering to let people use your bathroom or refill waterbottles
    * If you feel comfortable doing so, and especially if you benefit from white privilege, shelter protesters in your home if they are fleeing police violence

---

<a name="resources"></a>
## **(6.0) Other resources**

### Black Lives Matter

[BLM Guide](https://www.notion.so/BLM-Guide-fac525a6d1324d458d15bdc4fec98661)
  * Has resources on how to organize, strategize, and protest, and how to stay safe while doing it.

[List of BLM chapters](https://blacklivesmatter.com/chapters/)

[Ways You Can Help](https://blacklivesmatters.carrd.co/)

[Google Map of protests](https://www.google.com/maps/d/viewer?mid=1W3fsF5-Mz3_KaBgVt2pU8BDY5GkawUN_&ll=9.101946528762323%2C-54.848781100000004&z=2)

### Protest safety and advice

[From Beirut to Minneapolis (EN)](https://github.com/frombeirutwithlove/ProtestTips/blob/master/WhatToDo.md)
  * a great general guide to protest safety, written by Lebanese technologists, protesters, and activists.

### Digital Security

[Anonymize your online footprint (EN)](https://pastebin.com/TPgtvmVB)
  * a guide focusing on how to anonymize and reduce your online footprint, at home and at a protest.

[Hacking//Hustling: Doxxing Prevention Harm Reduction Training (EN)](https://hackinghustling.org/doxxing-prevention-harm-reduction-training/)
  * a guide and video workshop designed for LGBTQIA+ people, sex workers, and protesters.

[EFF (Electronic Frontier Foundation)](https://www.eff.org/)
  * [Digital Security Tips for Protesters (EN) (2016)](https://www.eff.org/deeplinks/2016/11/digital-security-tips-for-protesters)
    * a guide by the Electronic Frontier Foundation (EFF) on how to take care of your digital security at a protest. This guide was written in 2016, so it may be out of date.
  * [Attending a Protest (EN) (2019)](https://ssd.eff.org/en/module/attending-protest)
    * another guide by the Electronic Frontier Foundation (EFF) on how to protect yourself at a protest. This guide was last edited in 2019.
  * [Surveillance Self-Defense (EN)](https://ssd.eff.org/en/module-categories/further-learning)
    * a series of guides by EFF on digital security and self defense against surveillance. Covers topics like encryption, social networks, VPNs, and malware.
  * [Protecting Your Privacy if Your Phone is Taken Away](https://www.eff.org/deeplinks/2020/06/protecting-your-privacy-if-your-phone-taken-away)

[VICE: How to Protest Without Sacrificing Your Digital Privacy (EN)](https://www.vice.com/en_us/article/gv59jb/guide-protect-digital-privacy-during-protest?d)
  * a guide by Vice on how to increase your digital privacy while you're at a protest.   
 
  
### Legal resources  

[Twitter thread of lawyers providing pro-bono assistance for protesters](https://twitter.com/riyakatariax/status/1266856139536207872?s=21)

[American Civil Liberties Union (ACLU)](https://www.aclu.org/)
  * [Guide for legal observers (EN)](https://www.aclusc.org/sites/default/files/wysiwyg/legal_observers_final_new_branding.pdf)
  * Protester's Rights document
    * English: https://www.aclu.org/know-your-rights/protesters-rights/
    * Español: https://www.aclu.org/know-your-rights/derechos-de-los-manifestantes

[United We Dream](https://unitedwedream.org/)
  * ["Know your rights; know your power" (EN, ESP, +)](https://unitedwedream.org/heretostay/know-your-power/)
  * How to verify online reports of ICE raids/Cómo verificar reportes en línea sobre las redadas de ICE
    * [English](https://unitedwedream.org/wp-content/uploads/2019/09/RealOrRumor_VerifyRaids_20190819.pdf)
    * [Español](https://unitedwedream.org/wp-content/uploads/2020/03/ES_VerificarLasRedades_v1_0_20190829-1.pdf)

[The Legal Aid Society's "What to Expect If You're Arrested" document (EN)](https://www.legalaidnyc.org/get-help/arrests-policing/what-to-expect-if-youre-arrested/)

[Silvia Rivera Law Project: Resources for TGNCI people & communities during COVID-19](https://srlp.org/covid-19-resources/)
  * Includes general information on COVID-19, information on [how to change your name & gender markers while offices are shut down,](http://www.srlp.org/changeid-covid19/) information on [housing rights](https://dc37blog.wordpress.com/2020/03/30/ny-housing-updates-eviction-and-foreclosure-moratorium-covid-19-discrimination-nycha-section-8-rent-hardships/) and [rent strikes,](https://docs.google.com/document/d/1Va2a6ilp7O2iIBQUMxXFSOwxqep6jSjHp8Gd8O9WuTY/edit?fbclid=IwAR2bNLm6En8g5v7NPo4IahVL8d5S4HEihtwHrczNKzNN4mhclnNgJ9VkXRE) information on immigration rights for trans people (in [English](https://srlp.org/wp-content/uploads/2018/02/kyr-immgr-eng-color-v2.pdf) and [Spanish](https://srlp.org/wp-content/uploads/2018/02/kyr-immgr-span-color-v2.pdf)), information on how to access TGNCI healthcare, and resources for incarcerated people and their communities. Much of the information is specifically for people living in New York.

[National Lawyers Guild (NLG)](https://www.nlg.org/resources/)
  * resources including ["Know Your Rights" (EN, ESP, +)](https://www.nlg.org/know-your-rights/) in multiple languages. They also provide [legal support](https://www.nlg.org/massdefenseprogram/) to protesters around the nation, and offer support hotlines in multiple states. Their national hotline number is 888-654-3265 - consider writing this number on your arm in sharpie if you go to a protest.
[Southern Poverty Law Center](https://www.splcenter.org/)

[The National Center for Transgender Equality](https://transequality.org/)
  * [Know Your Rights (EN)](https://transequality.org/know-your-rights)
    * Resources explaining what rights you have as a trans person in the US. Topics covered include airport security, government documents, housing, employment, and healthcare. 
  * [ID Documents Center (EN)](https://transequality.org/documents)
    * Includes information on how to change your name on legal documents, IDs, and records in the US.
  * [Trans Legal Services Network (EN)](https://transequality.org/issues/resources/trans-legal-services-network-directory)
    * Includes links to trans-centric legal services by state. Most are focused around getting help with legal name and gender marker changes.

### Mental health

[Therapy Resources for People of Color/Queer Folx](https://docs.google.com/document/d/1dWShg0TZ7nJz5YJsCa1DyGCGTJMrUEd8du5vC6boVhs/mobilebasic)

[Black Girls Smile](https://www.blackgirlssmile.org/resources)
  * A list of mental health resources for black folks and people of color.

[Black Emotional and Mental Health Collective](https://www.beam.community/bvtn)
  * Their black virtual therapist directory lists licensed Black therapists who are certified to provide telemental health services.

[National Queer & Trans Therapists of Color Network](https://www.nqttcn.com/)
  * a healing justice organization committed to transforming mental health for queer and trans people of color (QTPoC). They have a directory of QTPOC mental health practitioners, and provide resources for practitioner development.



