---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2024-10-16T17:28:38.936Z
updated: 2024-10-17T17:56:48.507Z
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
<li><a href="https://fox-direct.techidaily.com/new-fourfold-precision-in-color-capture-with-blade-cameras/"><u>[New] Fourfold Precision in Color Capture with Blade Cameras</u></a></li>
<li><a href="https://win-latest.techidaily.com/1-how-to-restore-your-lost-content-a-guide-to-retrieving-deleted-youtube-footage/"><u>1. How to Restore Your Lost Content: A Guide to Retrieving Deleted YouTube Footage</u></a></li>
<li><a href="https://win-latest.techidaily.com/backup-de-archivos-a-un-disco-duro-exterior-en-windows-11-tres-metodos-faciles/"><u>Backup De Archivos a Un Disco Duro Exterior en Windows 11: Tres Métodos Fáciles</u></a></li>
<li><a href="https://os-tips.techidaily.com/complete-guide-saving-your-data-with-android-backup-features/"><u>Complete Guide: Saving Your Data with Android Backup Features</u></a></li>
<li><a href="https://win-latest.techidaily.com/effortless-transfer-of-melodies-how-to-migrate-songs-from-your-iphone-to-a-windows-or-mac-computer-via-itunes/"><u>Effortless Transfer of Melodies: How to Migrate Songs From Your iPhone to a Windows or Mac Computer via iTunes</u></a></li>
<li><a href="https://win-latest.techidaily.com/fixing-system-image-restoration-failed-unusable-disk-detected-issues/"><u>Fixing 'System Image Restoration Failed: Unusable Disk Detected' Issues</u></a></li>
<li><a href="https://technical-tips.techidaily.com/get-the-scoop-exclusive-info-on-apples-next-event-timing-rumors-and-more-revealed/"><u>Get the Scoop: Exclusive Info on Apple's Next Event - Timing, Rumors & More Revealed</u></a></li>
<li><a href="https://win-latest.techidaily.com/guide-complet-pour-passer-de-votre-clonage-hdd-a-un-ssd-en-utilisant-une-interface-usb-tout-savoir/"><u>Guide Complet Pour Passer De Votre Clonage HDD À Un SSD en Utilisant Une Interface USB : Tout Savoir !</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-xiaomi-redmi-note-13-pro-5g-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Xiaomi Redmi Note 13 Pro 5G to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-embark-into-the-best-youtube-vr-content-ever/"><u>In 2024, Embark Into the Best YouTube VR Content Ever</u></a></li>
<li><a href="https://win-latest.techidaily.com/navigating-aol-email-complete-tutorial-on-logging-in-registering-and-downloading/"><u>Navigating AOL Email: Complete Tutorial on Logging In, Registering, and Downloading</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-reduce-excessive-usage-by-tiworkerexe/"><u>Strategies to Reduce Excessive Usage by TiWorker.exe</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/taming-oversized-windows-11-display/"><u>Taming Oversized Windows 11 Display</u></a></li>
<li><a href="https://some-guidance.techidaily.com/wmvmpeg-movavi/"><u>WMV/MPEG 파일을 원근 상호 의미 전송을 위해 인터넷 공간에서 무가스로 변환하기 - Movavi</u></a></li>
<li><a href="https://win-latest.techidaily.com/1728466234816-windows-server-2016/"><u>セキュアかつ手軽なWindows Server 2016へのデータ復旧法🔄</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815679/21290" target="_top" id="1815679">
  <img src="//a.impactradius-go.com/display-ad/21290-1815679" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815679/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

