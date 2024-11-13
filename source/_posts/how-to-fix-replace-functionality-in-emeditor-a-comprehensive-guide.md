---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2024-11-08T21:48:28.979Z
updated: 2024-11-12T16:22:52.861Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/c02c898eea6d72b9e37093c851ecd855aff6005dd63a0876b47973f172914924.jpg
---

## How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide

Viewing 3 posts - 1 through 3 (of 3 total)

* Author  
Posts
* October 5, 2008 at 4:17 pm [#6319](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/f29c043a3cc5c5dac8db4e62939893e9?s=80&d=identicon&r=g)Stefan](https://www.emeditor.com/forums/users/Stefan/ "View Stefan's profile")  
Participant  
v8 beta3  
 I don’t know if this is beta related only. So i post it here. O.K.?  
 Problem:  
 Replacing with two lines in replace-box of find+replace-dialog  
 didn’t works for REPLACE ALL feature?  
 Fact:  
 I have this line:  
**Drive, Sub-command \[, Drive , Value\]**  
 I want get this lines:  
**#T=Drive**  
 **Drive, Sub-command \[, Drive , Value\]#**  
 I use regEx search  
**^(w+)(,)(.+)$**  
 and replace with  
**#T=1**  
 **123#**  
 If i now use single FIND and then REPLACE all works O.K.  
 I get:  
**#T=Drive**  
 **Drive, Sub-command \[, Drive , Value\]#**  
 Only if i use REPLACE ALL i get an bad result like  
**#T=Drive Drive, Sub-command \[, Drive , Value\]#**  
 Now i found i have to use n insteed an real linebreak in replace box:  
 Replace with: **#T=1n123#**  
 Then it works.  
 This was not logically to me  
 since we can use replace with several lines. Isn’t it?  
 So i think this is some kind of bug and i want to report it.  
 —  
 Second issue:  
 I used to test my expression by using single-Find and single-replace on the first few lines..  
 If all went O.K. i use global-Replace All  
 But this feature in EmEditor  
 replace the first few test lines again too :-o  
 I never have seen this behavior with other editors.  
 They replace all BELOW current cursor position ONLY.  
 And not the lines above.  
 Would be nice if EmEditor would do this too.  
 Or what do you think?  
 If you need more info just ask. :-D  
October 6, 2008 at 12:50 am [#6326](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> Stefan wrote:  
> v8 beta3  
> I don’t know if this is beta related only. So i post it here. O.K.?  
>  
> Problem:  
> Replacing with two lines in replace-box of find+replace-dialog  
> didn’t works for REPLACE ALL feature?  
>  
> Fact:  
> I have this line:  
> **Drive, Sub-command \[, Drive , Value\]**  
>  
> I want get this lines:  
> **#T=Drive**  
> **Drive, Sub-command \[, Drive , Value\]#**  
>  
> I use regEx search  
> **^(w+)(,)(.+)$**  
>  
> and replace with  
> **#T=1**  
> **123#**  
>  
> If i now use single FIND and then REPLACE all works O.K.  
> I get:  
> **#T=Drive**  
> **Drive, Sub-command \[, Drive , Value\]#**  
>  
> Only if i use REPLACE ALL i get an bad result like  
> **#T=Drive Drive, Sub-command \[, Drive , Value\]#**  
>  
> Now i found i have to use n insteed an real linebreak in replace box:  
> Replace with: **#T=1n123#**  
> Then it works.  
> This was not logically to me  
> since we can use replace with several lines. Isn’t it?  
> So i think this is some kind of bug and i want to report it.  
>  
> —  
>  
> Second issue:  
> I used to test my expression by using single-Find and single-replace on the first few lines..  
> If all went O.K. i use global-Replace All  
>  
> But this feature in EmEditor  
> replace the first few test lines again too :-o  
>  
> I never have seen this behavior with other editors.  
> They replace all BELOW current cursor position ONLY.  
> And not the lines above.  
> Would be nice if EmEditor would do this too.  
>  
> Or what do you think?  
> If you need more info just ask. :-D  
 I fixed your first issue. Thank you for reporting.  
 The second issue must be added as an option. It is too late for Version 8, but I might think as a new feature in future versions. Thanks!  
October 7, 2008 at 6:35 am [#6339](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/f29c043a3cc5c5dac8db4e62939893e9?s=80&d=identicon&r=g)Stefan](https://www.emeditor.com/forums/users/Stefan/ "View Stefan's profile")  
Participant  
> I fixed your first issue. Thank you for reporting.  
 Test with v8 beta4, fixed confirmed ;-) :pint:  
 Thank you Yutaka.  
 Note to others:  
 those visual, real line breaks in replace string are stored as n  
> The second issue must be added as an option.  
> It is too late for Version 8, but I might think as a new feature in future versions.  
 Thanks you.
* Author  
Posts

Viewing 3 posts - 1 through 3 (of 3 total)

* You must be logged in to reply to this topic.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-channel-creation-chronicles-the-ultimate-beauty-blogging-start-up/"><u>[New] 2024 Approved Channel Creation Chronicles The Ultimate Beauty Blogging Start-Up</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-2024-approved-simple-strategies-for-smooth-underwater-moviemaking/"><u>[New] 2024 Approved Simple Strategies for Smooth Underwater Moviemaking</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-ending-invisible-gaming-captures-in-software/"><u>[New] Ending Invisible Gaming Captures in Software</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-prime-8-instagram-managers-for-mobile-devices/"><u>[Updated] 2024 Approved Prime 8 Instagram Managers for Mobile Devices</u></a></li>
<li><a href="https://win-latest.techidaily.com/windows-10-os-3/"><u>如何在Windows 10 OS更新後回復丟失的文件 - 3道技術秘訣！</u></a></li>
<li><a href="https://win-latest.techidaily.com/backup-de-archivos-a-un-disco-duro-exterior-en-windows-11-tres-metodos-faciles/"><u>Backup De Archivos a Un Disco Duro Exterior en Windows 11: Tres Métodos Fáciles</u></a></li>
<li><a href="https://hardware-help.techidaily.com/beelink-gti1n-unveiled-meteor-lake-powered-mini-pc-featuring-external-gpu-expansion-and-built-in-145w-psu/"><u>Beelink GTi1n Unveiled: Meteor Lake-Powered Mini PC Featuring External GPU Expansion & Built-In 145W PSU</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/discover-your-rhythm-assembling-tailored-youtube-playlists-for-the-digital-age-webmobile-for-2024/"><u>Discover Your Rhythm Assembling Tailored YouTube Playlists for the Digital Age (Web/Mobile) for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/effortless-transfer-of-melodies-how-to-migrate-songs-from-your-iphone-to-a-windows-or-mac-computer-via-itunes/"><u>Effortless Transfer of Melodies: How to Migrate Songs From Your iPhone to a Windows or Mac Computer via iTunes</u></a></li>
<li><a href="https://win-latest.techidaily.com/fixing-system-image-restoration-failed-unusable-disk-detected-issues/"><u>Fixing 'System Image Restoration Failed: Unusable Disk Detected' Issues</u></a></li>
<li><a href="https://win-latest.techidaily.com/guide-complet-pour-passer-de-votre-clonage-hdd-a-un-ssd-en-utilisant-une-interface-usb-tout-savoir/"><u>Guide Complet Pour Passer De Votre Clonage HDD À Un SSD en Utilisant Une Interface USB : Tout Savoir !</u></a></li>
<li><a href="https://youtube-web.techidaily.com/izing-content-understanding-youtubes-cpm/"><u>Monetizing Content Understanding YouTube's CPM</u></a></li>
<li><a href="https://article-files.techidaily.com/sdr-to-hdri-pioneers-expert-tips-and-techniques/"><u>SDR to HDRI Pioneers Expert Tips and Techniques</u></a></li>
<li><a href="https://win-latest.techidaily.com/1728466234816-windows-server-2016/"><u>セキュアかつ手軽なWindows Server 2016へのデータ復旧法🔄</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576477/17382" target="_top" id="1576477">
  <img src="//a.impactradius-go.com/display-ad/17382-1576477" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576477/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

