# trans-resist
Digital security and protest advice for trans and LGBTQIA+ people in 2020.

## Table of contents

1. [Description, disclaimer, and usage tips ](#desc)
2. [Digital security & organizing online](#digisec)
    * [2.1 General mobile phone security](#mobilesec)
    * [2.2 Smartphone apps for communicating and organizing](#smartphone)
      * [2.2.a Signal](#signal)
      * [2.2.b Telegram](#telegram)
      * [2.2.c OTR Chat (Pidgin & Adium)](#OTRchat)
      * [2.2.d Apps to avoid for organizing](#badapps)
    * [2.3 Video chat](#vidchat)
      * [2.3.a Meet Jitsi](#jitsi)
      * [2.3.b Apps to avoid for video chat](#badvid)
    * [2.4 Secure email](#secemail)
      * [2.4.a PGP](#pgp)
      * [2.4.b Thunderbird](#thunderbird)
      * [2.4.c Secure email hosts](#mailhosts)
    * [2.5 Anonymous web browsing](#anonweb)
      * [2.5.a Tor Browser](#torbrowser)
      * [2.5.b Other browsers](#otherbrowsers)
      * [2.5.c Secure browsing behavior](#browsebehavior)
    * [2.6 VPNs](#vpn)
      * [2.6.a Free vs. Paid](freevpaidvpn)
      * [2.6.b Riseup VPN](#riseupvpn)
      * [2.6.c Firefox VPN](#firefoxvpn)
    * [2.7 Tails](#tails)
    * [2.8 Photos, Filming, Faces, and Metadata](#photosmeta)
      * [2.8.a Filming, Photos, and Documenting](#documenting)
      * [2.8.b Image-Scrubber](#imagescrubber)
      * [2.8.c Obscuracam](#obscuracam)
      * [2.8.d Scrambled EXIF](#scrambled)
    * [2.9 Behavior & opsec](#digisecbehavior)
    * [2.10 Advanced: Infrastructure, servers, and hosting](#infrastructure)
      * [2.10.a How to setup your own cloud server](#how2cloudserver)
      * [2.10.b How to install and use SSH to access a remote server](#how2ssh)
      * [2.10.c How to host a jitsi video chat instance on your server](#how2jistihost)
      * [2.10.d How to host a tor relay](#how2torrelay)
3. [Protest safety](#protestsafety)
    * [3.1 General safety](#gensafety)
    * [3.2 Binder safety](#binders)
    * [3.3 What to do if your ID doesn't match your gender](#govtid)
    * [3.4 Organizations to call if you're in trouble](#orgstocall)
      * [3.4.a Trans advocacy organizations](#transorgs)
4. [Mutual aid](#mutaid)
    * [4.1 Mutual aid groups by region](#mutaidreg)
      * [4.1.a USA](#mutaidUSA)
      * [4.1.b Canada](#mutaidCAN)
    * [4.2 Bail funds by region](#bailfunds)
5. [How to help if you can't physically go to a protest](#helpfromhome)
6. [Other Resources ](#resources)

<a name="desc"></a>
## **(1.0) Description**

This guide is intended to provide some advice and resources to help trans and LGBTQIA+ people safely navigate protests, digital security, and quarantines in 2020. This guide is specifically written with US communities in mind, but may feature advice that's applicable to other contexts, as well.

This guide isn't meant to scare you or make you extra paranoid. It's meant to be informative and approachable, and to help you decrease the amount of potential harm you are exposed to online and on the ground. 

This advice is not one-size-fits-all. Your situation is almost certainly different from anyone else's, so it's important to remember that these tips might need some tweaking to be helpful to you. You may find that some of this advice is too much trouble for you, or that it involves a trade-off that you're not willing to make. That's okay! You don't have to do anything you don't want to. We'll try to give as many options as possible so that you can pick which solution works best for you.

We are people who care about digital security, and who have devoted some part of our lives to keeping up to date with these things & teaching others how to stay safe, but _we are not experts._ Take all of this advice with a grain of salt, and always use your best judgement. 


<a name="digisec"></a>
## **(2.0) Digital security & organizing online**

The NSA recently renewed the Patriot Act, which means that the US government is free to surveil what you do and say online and over the phone. This, combined with the fact that the US govt recently said they'd like to label certain activist groups as terrorist organizations, means that we need to protect ourselves as much as we can while organizing.

In this section, you'll find some basic digital security guidance and advice for organizing online.

<a name="mobilesec"></a>
### **(2.1) General mobile phone security**

If you're planning on going to a protest, consider turning off your phone or leaving it at home, if you feel safe to do so. This is especially important if you have an Android phone, as [Android has been hacked by the police in the past.](https://money.cnn.com/2016/02/25/technology/android-apple-police-encryption/index.html) Police are also known to use [IMSI-catchers](https://www.eff.org/pages/cell-site-simulatorsimsi-catchers) to track who is present at a protest, and to use cell tower records to [see who was present at a protest that happened in the past.](https://www.nytimes.com/interactive/2019/12/19/opinion/location-tracking-cell-phone.html) Police can use some of this data even if your phone was off while you were at the protest. Messages can also be intercepted by [“stingrays,”](https://en.wikipedia.org/wiki/Stingray_phone_tracker) which pretend to be cell towers and trick your phone into connecting to them.

If you want to bring your phone with you, and if you have a farraday bag, bring it to the protest and keep your phone inside and powered off. If you don't have one, you can make one using [this guide.](https://www.instructables.com/id/EASIEST-FARADAY-PHONE-POUCH/)

If you do not feel safe leaving your phone at home, then make sure to:
  * put it in airplane mode
  * turn off location services
  * enable a strong passcode (NOT FaceID or a fingerprint ID) (Settings > Security/Privacy)
  * turn off AirDrop
  * Backup your data before you go to the protest
  * Remove any photos, files, or messages that you don't want seen by police
  * Set your phone to lock automatically after a few seconds
  * Turn off lockscreen notifications (Settings > Notifications)
  * use a secure messaging app like Signal to communicate with others

##### Downloading apps

Consider downloading [F-Droid](https://f-droid.org/en/about/) and using it to install apps on your Android phone when possible. The Google Play store can keep track of which apps you download, and can also track people in other ways. F-droid is open-source, and does not track you or your phone. It also allows you to search for and install FOSS (free and open-source software) for your phone.

If you want to install apps using F-Droid, you'll need to [install the F-Droid .apk](https://f-droid.org/en/) before you can use it to install other apps. You can install the F-Droid catalog by downloading the .apk file [directly from their website](https://f-droid.org/en/)) using your phone's browser.

##### Location services

Android phones are run on Google services, and Google tracks where you go with your phone, sometimes even when you have GPS turned off. To minimize how much Google is able to track you, [follow this guide.](https://www.theverge.com/2019/4/12/18302306/android-101-location-tracking-stop-how-to) You can also check out Google's official help article on [how to turn off location services.](https://support.google.com/accounts/answer/3467281?hl=en)

Apple can track your iPhone, too. They have an official article on how to turn off location services [here.](https://support.apple.com/en-us/HT207092)

Also make sure to turn off location tagging on any social media accounts you use regularly. This includes Instagram, Twitter, and Facebook. This is especially important if you're talking about protests on social media, but is also generally good practice to prevent getting doxxed or harassed online.

<a name="smartphone"></a>
### **(2.2) Smartphone apps for communicating and organizing**

<a name="signal"></a>
#### **(2.2.a) [Signal](https://signal.org/download/)**

Signal is a free and open source encrypted messaging app, available for Android, iPhone, and computers.

One of the biggest downsides to Signal is that it requires a phone number to sign up. However, after you've created your account, you can use any phone number for that account. That means that you can spoof (create) a fake phone number to sign up. You will need that phone number to confirm your account in the initial setup process, but once you've done that, you can delete or abandon the fake number you used to sign up.

##### [Signing up on mobile](https://support.signal.org/hc/en-us/articles/360007318691-Register-a-phone-number)

##### [Creating a temporary phone number](https://theintercept.com/2017/09/28/signal-tutorial-second-phone-number/)

##### SMS vs. Encrypted messages

Signal also allows you to send SMS messages through the app. This can be a useful function, but keep in mind that SMS messages are not encrypted, and that they can be intercepted by police with devices called [“stingrays.”](https://en.wikipedia.org/wiki/Stingray_phone_tracker) 

You can only send an encrypted Signal message to someone who is also using Signal. You can tell whether you're about to send an SMS or a Signal message by looking at the message entry box before you send a message: if it says "Signal message," then you'll send an end-to-end encrypted message through Signal. If it says "SMS message," you'll send an unencrypted SMS message through Signal.

<a name="telegram"></a>
#### **(2.2.b) [Telegram](https://telegram.org/apps)**

Telegram is a chat app that allows encrypted communication. It is free and open source. Generally, it is considered to be less secure than Signal, but sometimes it is preferred for certain features, like the ability to make bigger group chats. However, it's generally recommended that, whenever possible, you use Signal rather than Telegram for sensitive communication.

##### [Group Chats]

The thing with a group chat on telegram is that anyone can join or be invited, depending of the privacy settings of the group chat. This can be a bad thing for organizing. For example, if an undercover agent or an infiltrator convinces someone to join the group, they can see every message that's posted in the group. While this can happen in group chats on any app, the bigger maximum size of group chats on Telegram can make it harder to vet every new member. Keep this in mind when deciding whether to use Signal or Telegram to organize.

<a name="OTRchat"></a>
#### **(2.2.c) OTR Chat (Pidgin & Adium)**

##### [Pidgin (Windows)](https://adium.im/help/pgs/AdvancedFeatures-OTREncryption.html)

With the use of the pidgin-otr plugin, Pidgin allows people to use OTR (Off-the-Record) Messaging to communicate with eachother using end-to-end encrypted messages.

For instructions on how to setup Pidgin with the OTR plugin, [click here.](https://adium.im/help/pgs/AdvancedFeatures-OTREncryption.html)

##### [Adium (Mac)](https://adium.im/help/pgs/AdvancedFeatures-OTREncryption.html)

Adium allows people to communicate through end-to-end encrypted messaging with its OTR (Off-the-Record) plugin.

For instructions on how to setup Adium and its OTR plugin, [click here.] (https://adium.im/help/pgs/AdvancedFeatures-OTREncryption.html)

<a name="badapps"></a>
#### **(2.2.d) [Apps to avoid for organizing](#badapps)**

##### Messenger

Facebook Messenger isn't safe for communications. Facebook has a history of collecting data on users and sharing it with others, so don't trust them with your communications. 

Facebook Messenger does not encrypt messages or communications in a way that prevents them from being read by Facebook.

##### Discord

Discord doesn't use end-to-end encryption, which means that police or the NSA could potentially read any of your Discord messages.
Discord also has a policy which says that people should not "promote, encourage, or engage in any illegal behavior." It also does not allow the "organization, promotion, or support of violent extremism." Since the US government has recently said they'd like to declare certain activist organizations to be terrorist organizations, it would be safest to use another platform to communicate.

##### Whatsapp

Although Whatsapp uses end-to-end encryption, it's owned by Facebook. Facebook has a history of disregarding users' privacy, collecting and selling their data, and using it to influence elections. We don't trust Facebook for sensitive communication.

<a name="vidchat"></a>
### **(2.3) Video chat**

<a name="jitsi"></a>
#### **(2.3.a) [Meet Jitsi](https://meet.jit.si/)**

<a name="badvid"></a>
#### **(2.3.b) Apps to avoid for video chat**

##### Skype

Skype has claimed that they encrypt communications between users, but because their application is not open-source, it is impossible to verify whether this is true. Users can also create new accounts without any verification required for phone numbers or names, which means that it's very easy for someone to pretend to be someone else.

##### Zoom

Zoom was recently bought by Facebook, and [research by CitizenLab](https://citizenlab.ca/2020/04/move-fast-roll-your-own-crypto-a-quick-look-at-the-confidentiality-of-zoom-meetings/) shows that Zoom has shared encryption keys with others in the past, allowing people to view others' private conversations. Zoom also does not encrypt video chats with end-to-end encryption. This means that Zoom is able to decrypt and monitor calls made using the app. If you want to use a secure video chat app, use [Meet Jitsi](https://meet.jit.si/) instead.

##### Discord

Discord doesn't use end-to-end encryption, which means that police or the NSA could potentially read any of your Discord messages, listen in on voice channels, or view your video calls.
Discord also has a policy which says that people should not "promote, encourage, or engage in any illegal behavior." It also does not allow the "organization, promotion, or support of violent extremism." Since the US government has recently said they'd like to declare certain activist organizations to be terrorist organizations, it would be safest to use another platform to communicate.

<a name="secemail"></a>
### **(2.4) Secure email**

<a name="pgp"></a>
#### **(2.4.a) PGP**

<a name="thunderbird"></a>
#### **(2.4.b) Thunderbird**

<a name="mailhosts"></a>
#### **(2.4.c) Secure email hosts**

##### [Riseup.net](https://riseup.net)

Riseup.net offers end-to-end encrypted email hosting, as well as a bunch of other services. Their goal is to keep activists safe online. They are committed to never turn over any of your data to law enforcement.

To create a Riseup account, you'll need an invite code. You'll have to get an invite code from someone you know who's had a Riseup account for more than 3 months. If you have a Riseup account, you can generate a new invite code from the [invites page.](https://account.riseup.net/invites)

Once you have an account, you can login at https://mail.riseup.net/rc/ or setup an email client like Thunderbird to access your account. You can learn how to configure your email client for riseup [here.](https://riseup.net/email)

If you don't know anyone with a Riseup account, you can use one of the options below.

##### [Proton mail](https://protonmail.com/)

Proton Mail offers end-to-end encrypted email hosting. You can create an account for free, but in order to access all features of your account (like using an email client to read your mail), you'll need to pay for a full account. I tend not to trust providers that use the free/premium divide, but I don't personally have any evidence that Proton Mail is bad. Use your best judgement.

##### [Counter Mail](https://countermail.com/)
##### [Hushmail](https://www.hushmail.com/)
##### [mailfence](https://mailfence.com/)
##### [Tutanota](https://tutanota.com/) 

<a name="anonweb"></a>
### **(2.5) Anonymous web browsing**

<a name="torbrowser"></a>
#### **(2.5.a) [Tor Browser](https://www.torproject.org/download/)**

<a name="otherbrowsers"></a>
#### **(2.5.b) Other browsers**

##### Brave

##### Firefox

Firefox has recently added a bunch of new privacy-minded features to their browser. Mozilla is continuously collaborating with the Tor Project to add new ways for their browser to protect your identity. The biggest feature they offer at the moment is ad-tracking prevention, which helps prevent ad trackers from following you around the internet, collecting your information and history, and building a profile on you. 

While Firefox is the least private of any of the browsers here, it is the best option for regular, low-risk browsing. We highly recommend using it instead of Chrome or Safari. 

<a name="browsebehavior"></a>
#### **(2.5.c) Secure browsing behavior**

Browsing the internet safely and securely takes more than just an anonymizing browser. You'll need to make some changes to your regular browsing behavior, too. 

##### Search engines

Use https://duckduckgo.com instead of Google - DuckDuckGo doesn't track or record your searches. 

##### Sending files
  * small files: encrypted email, Signal
  * large files: https://send.firefox.com, https://onionshare.org/

##### Trustworthy browser extensions to protect yourself online

Privacy Badger https://www.eff.org/privacybadger 
UblockOrigin https://getublock.com/ 
HTTPS everywhere https://www.eff.org/https-everywhere

If these are the only browser extensions you use, you'll be golden. Be wary of installing browser extensions from untrusted or unknown sources.

<a name="vpn"></a>
### **(2.6) VPNs**

<a name="freevpaidvpn"></a>
#### **(2.6.a) Free vs. Paid**

<a name="riseupvpn"></a>
#### **(2.6.b) [Riseup VPN](https://riseup.net/en/vpn)**

Riseup offers a free VPN service. Their goal is to keep activists safe online. They are committed to never turn over any of your data to law enforcement.

To create a Riseup account, you'll need an invite code. You'll have to get an invite code from someone you know who's had a Riseup account for more than 3 months. If you have a Riseup account, you can generate a new invite code from the [invites page.](https://account.riseup.net/invites)

<a name="firefoxvpn"></a>
#### **(2.6.c) Firefox VPN**

<a name="tails"></a>
### **(2.7) [Tails](https://tails.boum.org/install/index.en.html)**

<a name="photosmeta"></a>
### **(2.8) Photos, filming, faces, and metadata**

When you take a photo or video on your phone, your phone automatically saves some information about when and where the photo was taken, as well as the kind of phone used to take the photo/video. This data is called 'metadata,' or more specifically, EXIF data. This data can be easily viewed by anyone, and law enforcement can use it to identify when and where a photo/video was taken. This makes it easier for law enforcement to identify who took the photo/video, or who might appear in it. 

While documenting what happens at a protest can be important, it's also important to protect the identities of protestors present in the photo or video. Luckily, there are multiple free tools you can use to erase or spoof EXIF data, and to blur/obscure faces and other identifying features.

##### Blur vs. obscure

It's important to note that obscuring a feature using a black square or other image is often much safer than simply blurring it. This is because tools exist which make un-blurring an image relatively easy. For this reason, it's generally better to obscure a feature instead of blurring it, if you can.

<a name="documenting"></a>
#### **(2.8.a) Filming and documenting safely**

<a name="imagescrubber"></a>
#### **(2.8.b) [Image-scrubber](https://everestpipkin.github.io/image-scrubber/)**

[Image-scrubber](https://everestpipkin.github.io/image-scrubber/) is a browser-based tool that allows you to remove EXIF metadata from photos and blur/obscure faces or identifying features. You can use the tool from your phone's browser, regardless of your phone's OS. The photos you edit using this tool aren't sent anywhere when you edit them: all the editing is done on your phone instead of on a remote server.

<a name="obscuracam"></a>
#### **(2.8.c) [Obscuracam](https://guardianproject.info/apps/obscuracam/)**

[Obscuracam](https://guardianproject.info/apps/obscuracam/) is an app developed by [the Guardian Project.](https://guardianproject.info/) Obscuracam allows you to remove any metadata from a photo or video. The app also has automatic face detection, which makes quickly blurring a large number of faces in a photo or video super easy.

The app is available for Android on the [Google Play store](https://play.google.com/store/apps/details?id=org.witness.sscphase1&feature=search_result) and on [F-Droid.](https://f-droid.org/en/packages/org.witness.sscphase1/) If you don't already have F-Droid installed on your phone, you'll need to [install the F-Droid .apk](https://f-droid.org/en/) before you can use it to install other apps. You can install the F-Droid store by downloading the .apk file [directly from their website](https://f-droid.org/en/)) using your phone's browser.

<a name="scrambled"></a>
#### **(2.8.d) [Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif)**

[Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif) is an app that allows you to easily remove EXIF data from a photo or video before sharing it. 

The app is available for Android on the [Google Play store](https://play.google.com/store/apps/details?id=com.jarsilio.android.scrambledeggsif&hl=en_US) and on [F-Droid](https://f-droid.org/en/packages/com.jarsilio.android.scrambledeggsif/). If you don't already have F-Droid installed on your phone, you'll need to [install the F-Droid .apk](https://f-droid.org/en/) before you can use it to install other apps. You can install the F-Droid store by downloading the .apk file [directly from their website](https://f-droid.org/en/)) using your phone's browser.

To use the app, tap the 'share' button in another app, then select Scrambled Exif from the list of options. This will tell Scrambled Exif to remove the EXIF data from your file. Once the EXIF data has been removed, another share window will open, and you'll be able to send the file using any app on your phone.

<a name="digisecbehavior"></a>
### **(2.9) Behavior and social organization**

Beware of undercover cops in your group chats and online organizing groups, but also be wary of people accusing others of being narcs/spies/undercover cops. Accusing others can be a tactic to sow distrust in a movement. 

Both of these reasons mean that sometimes it's best to organize in small groups with people you know directly and trust deeply.

Be wary of using your real name: in the US, finding someone's address with only their name is trivial, thanks to data brokers like Spokeo and Whitepages.

<a name="infrastructure"></a>
### **(2.10) Advanced: Infrastructure, servers, and hosting**

This section is for people who are willing to dig deep to learn about digital security. Beware that once you start down this path, you'll need to know A LOT to make sure the websites and resources you're building are secure. Either that, or you'll need to find a friend who knows a lot.

If you want to get started learning how to setup digital infrastructure like cloud servers, websites, and hosting resources, Digital Ocean is a great place to start. Their [documentation](https://www.digitalocean.com/community/tutorials) is a treasure trove of easy to understand instructions on how to do almost anything on a digital server. I've learned half of what I know from their user-created tutorials.

<a name="how2cloudserver"></a>
#### **(2.10.a) How to setup your own cloud server**

If you want to setup your own cloud server for whatever reason, you'll first need to:
  * pick a hosting provider and create an account with them
  * purchase a cloud server
  * setup the server
  * access the server remotely, either using SSH on your home computer, or using a terminal emulator on the host's website

If you want to get started learning how to setup a cloud server from scratch, [Digital Ocean's tutorials](https://www.digitalocean.com/community/tutorials) are a great place to start. You can find a guide for everything there. You can even access these tutorials if you don't actually use Digital Ocean's servers.

All that being said, Digital Ocean may not be the best place to host your stuff. I have no idea what their political stances are, and so I don't know what their policy is on removing content or taking down servers. As a sort of litmus test, they allow Tor relays to be installed on their servers, as long as they're not Tor exit relays (this means they're okay, but not great). Their servers are also extremely affordable compared to a lot of other services, and you have the option to start small and expand your server if you need more storage space or RAM. Do your research and decide which hosting platform is best for you.

If you're up to it, the best OS for running a cloud server is [Linux.](https://en.wikipedia.org/wiki/Linux) This is because it really gives you the most control over your server. Linux might seem intimidating, but speaking as someone who was terrified of it in the past and now uses it almost exclusively, you can ABSOLUTELY learn how to use it. If you're intimidated by terminals and Linux in general, [Ubuntu](https://ubuntu.com/) is a great Linux distribution to start with. However, if you really don't want to get into all that right now, go ahead and use whatever OS you're most comfortable with.

<a name="how2SSH"></a>
#### **(2.10.b) How to install and use SSH to access a remote server**

<a name="how2jistihost"></a>
#### **(2.10.c) How to host a Jitsi video chat instance on your server**

<a name="how2torrelay"></a>
#### **(2.10.d) How to host a tor relay**

This is a bonus, but building up the infrastructure of the Tor network helps to protect activists who need Tor to stay safe.

What is a [tor relay?](https://community.torproject.org/relay/) 
A tor relay is a 'node' through which traffic is funneled on the tor network. These nodes receive traffic on the tor network and pass it along. Any connecting using the tor network will be funneled through at least 3 nodes between the start and end point. A typical connection on the tor network looks like this:

User's PC > Guard Relay > Middle Relay > Exit Relay > Website 

In summary, the tor network runs on relays. Volunteers can setup relays on their own servers to help contribute bandwidth to the tor network.

Tor has an [official guide on how to setup a tor relay,](https://trac.torproject.org/projects/tor/wiki/TorRelayGuide) but it is unfortunately not exhaustive, and pretty out of date. It's very possible that you'll run into problems that you won't be able to solve using their guide. Luckily, they have a [mailing list](https://lists.torproject.org/cgi-bin/mailman/listinfo/tor-relays) and an IRC channel (#tor-relays on [irc.oftc.net](https://support.torproject.org/get-in-touch/#irc-help))where you can ask questions. They also have a new [relay operations hub](https://community.torproject.org/relay/) on their community site which is being updated more regularly.

<a name="protestsafety"></a>
## **(3.0) Protest Safety**

<a name="gensafety"></a>
### **(3.1) General Safety**

#### Tear Gas

[CDC Fact Sheet on Tear Gas](https://emergency.cdc.gov/agent/riotcontrol/factsheet.asp)

Tear gas can stick to face paint and makeup, so it's best to go without. Nylons and fishnets can also aggravate the effects of tear gas and other riot control agents.

#### Facial recognition tech

If you want to confuse facial recognition technology, the best tactic is to wear a face mask and glasses, and this has the added benefit of protecting you from COVID-19.

<a name="binders"></a>
### **(3.2) Binder safety**

If you wear a binder, consider leaving it at home when you go out to protest. Binders usually constrict your chest, and can make breathing more difficult when running or doing other strenuous activity. Tear gas and pepper spray often used by police at protests, and both of these agents can restrict your breathing and agravate asthma or other respiratory conditions. 

Instead, you might want to use a sports bra, since it restricts breathing less than a binder, and because it may be easier to remove if you need to. DO NOT use ACE bandages, as they are designed to constrict automatically when your body expands, and can put extra stress on  your chest and lungs. 

In general, follow the same guidelines that you would when exercising, and be sure that you can remove whatever you're wearing easily in case you're exposed to tear gas or pepper spray.

<a name="govtid"></a>
### **(3.3) What to do if your ID doesn't match your gender**

Ideas:
- backpass, if you can/want to (play along as if the gender on your ID is correct)
- bring other documents to corroborate your name, maybe? like a phone bill or utilities bill that has your name and address on it. but, could this be used against you somehow?
- know the laws in your state regarding ID, protesting, and trans rights
- have a friend with you to advocate for you

<a name="orgstocall"></a> 
### **(3.4) Organizations to call if you're in trouble**

<a name=""></a>
#### **(3.4.a) Trans advocacy organizations**

(alhpabetical by state)

<a name="mutaid"></a>
## **(4.0) Mutual aid**

<a name="mutaidreg"></a>
### **(4.1) Mutual aid groups by region**

<a name="mutaidUSA"></a>
#### **(4.1.a) USA**
(alphabetical by state)

<a name="mutaidCAN"></a>
#### **(4.1.b) Canada**

<a name="bailfunds"></a>
### **(4.2) Bail funds by region**

(alphabetical by state)

<a name="helpfromhome"></a>
## **(5.0) How to help if you can't physically go to a protest**

While showing up physically to a protest is important to a movement, not all of us are able to risk it: some of us are undocumented, some of us have vulnerable immune systems, and some of us have disabilities. There are plenty of legitimate reasons why someone might not be able to attend a protest, or why someone might not feel safe attending a protest.

###Some other ways to help organize from home:

#### Donate to a [bail fund](#bailfunds)

#### Donate to a gofundme

#### Donate to a local [BLM chapter](https://blacklivesmatter.com/chapters/)

#### Provide support for your friends who are at a protest
  * Listen to police scanners using https://www.broadcastify.com/ and relay information to someone at the protest
  * Keep an eye on social media to watch for developments
  * Ask your friends to message you when they're leaving home and when they arrive home safe
  * If your home is near a protest location, consider offering to let people use your bathroom or refill waterbottles

<a name="resources"></a>
## **(6.0) Other resources**

[From Beirut to Minneapolis](https://github.com/frombeirutwithlove/ProtestTips/blob/master/WhatToDo.md)
  * a great general guide to protest safety, written by Lebanese technologists, protesters, and activists.
  
[Anonymize your online footprint](https://docs.google.com/document/d/1615pZB11BhsR0KtvyiXfzfMUBlxZi47HzzhWHIRpxwU/edit)
  * a guide focusing on how to anonymize and reduce your online footprint, at home and at a protest.

[Hacking//Hustling: Doxxing Prevention Harm Reduction Training](https://hackinghustling.org/doxxing-prevention-harm-reduction-training/)
  * a guide and video workshop designed for LGBTQIA+ people, sex workers, and protestors.
  
[EFF (Electronic Frontier Foundation)](https://www.eff.org/)
  * [Digital Security Tips for Protestors (2016)](https://www.eff.org/deeplinks/2016/11/digital-security-tips-for-protesters)
    * a guide by the Electronic Frontier Foundation (EFF) on how to take care of your digital security at a protest. This guide was written in 2016, so it may be out of date.
  * [Attending a Protest (2019)](https://ssd.eff.org/en/module/attending-protest)
    * another guide by the Electronic Frontier Foundation (EFF) on how to protect yourself at a protest. This guide was last edited in 2019.
  * [Surveillance Self-Defense](https://ssd.eff.org/en/module-categories/further-learning)
    * a series of guides by EFF on digital security and self defense against surveillance. Covers topics like encryption, social networks, VPNs, and malware.

[VICE: How to Protest Without Sacrificing Your Digital Privacy](https://www.vice.com/en_us/article/gv59jb/guide-protect-digital-privacy-during-protest?d)
  * a guide by Vice on how to increase your digital privacy while you're at a protest.

[National Lawyers Guild (NLG)](https://www.nlg.org/resources/)
  * resources including ["Know Your Rights"](https://www.nlg.org/know-your-rights/) in multiple languages. They also provide [legal support](https://www.nlg.org/massdefenseprogram/) to protestors around the nation, and offer support hotlines in multiple states. Their national hotline number is 888-654-3265 - consider writing this number on your arm in sharpie if you go to a protest.

[The National Center for Transgender Equality](https://transequality.org/)
  * [Know Your Rights](https://transequality.org/know-your-rights)
    * Resources explaining what rights you have as a trans person in the US. Topics covered include airport security, government documents, housing, employment, and healthcare. 
  * [ID Documents Center](https://transequality.org/documents)
    * Includes information on how to change your name on legal documents, IDs, and records in the US.
  * [Trans Legal Services Network](https://transequality.org/issues/resources/trans-legal-services-network-directory)
    * Includes links to trans-centric legal services by state. Most are focused around getting help with legal name and gender marker changes.
