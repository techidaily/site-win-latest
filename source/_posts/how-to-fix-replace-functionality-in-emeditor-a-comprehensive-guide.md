---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2024-10-28T22:10:29.018Z
updated: 2024-11-03T23:39:39.689Z
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-sound-surprises-10-androidios-audio-twisters/"><u>[New] 2024 Approved Sound Surprises 10 Android/iOS Audio Twisters</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-original-movie-recording-dissection-and-substitute-series/"><u>[Updated] 2024 Approved Original Movie Recording Dissection & Substitute Series</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-essential-tips-for-gif-creation/"><u>[Updated] Essential Tips for GIF Creation</u></a></li>
<li><a href="https://win-latest.techidaily.com/1728466735604-google/"><u>「Google ドライブ」のエラーごみ箱からデータ回収 - 失われたファイル再生手順</u></a></li>
<li><a href="https://app-tips.techidaily.com/essential-unbiased-insight-a-complete-airwatch-reviews-for-informed-decision-making/"><u>Essential Unbiased Insight: A Complete AirWatch Reviews for Informed Decision Making</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/guide-facile-enregistrer-le-sous-systeme-windows-11-sur-un-support-amovible-usb/"><u>Guide Facile: Enregistrer Le Sous-Système Windows 11 Sur Un Support Amovible USB</u></a></li>
<li><a href="https://win-latest.techidaily.com/keine-sorge-mehr-funfzehn-tipps-um-verlorene-apps-auf-ihrem-desktop-mit-windows-11-8-oder-7-wiederherzustellen/"><u>Keine Sorge Mehr! Fünfzehn Tipps, Um Verlorene Apps Auf Ihrem Desktop Mit Windows 11, 8 Oder 7 Wiederherzustellen</u></a></li>
<li><a href="https://win-latest.techidaily.com/localizar-tus-videos-perdidos-en-la-pc-y-iphone-metodos-de-recuperacion-efectivos/"><u>Localizar Tus Videos Perdidos en La PC Y iPhone, Métodos De Recuperación Efectivos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-double-click-with-these-simple-windows-adjustments/"><u>Optimize Your Double-Click with These Simple Windows Adjustments</u></a></li>
<li><a href="https://win-latest.techidaily.com/quick-start-to-writing-windows-server-2019-iso-on-usb-learn-both-techniques/"><u>Quick Start to Writing Windows Server 2019 ISO on USB - Learn Both Techniques</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/tantalizing-talks-the-allure-of-spanish-dialogue/"><u>Tantalizing Talks: The Allure of Spanish Dialogue</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-rated-magsafe-power-solutions-comprehensive-testing-and-reviews-by-tech-gurus-zdnet/"><u>Top-Rated MagSafe Power Solutions : Comprehensive Testing & Reviews by Tech Gurus | ZDNET</u></a></li>
<li><a href="https://win-latest.techidaily.com/ultimate-guide-resolving-ipad-and-itunes-synchronization-problems-in-top-7-methods/"><u>Ultimate Guide: Resolving iPad and iTunes Synchronization Problems in Top 7 Methods</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-youtube-lives-thumbnail-code-for-2024/"><u>Unlocking YouTube Live's Thumbnail Code for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/wie-man-eine-physische-festplatte-erfolgreich-mit-vmware-esxi-verbindet/"><u>Wie Man Eine Physische Festplatte Erfolgreich Mit VMware ESXi Verbindet</u></a></li>
<li><a href="https://win-latest.techidaily.com/wiederherstellung-von-versehentlich-geloschten-kindle-e-books-4-bewahrte-strategien/"><u>Wiederherstellung Von Versehentlich Gelöschten Kindle-E-Books: 4 Bewährte Strategien</u></a></li>
<li><a href="https://win-latest.techidaily.com/windows-7erecovery/"><u>Windows 7のeRecovery管理ツール - 最適化されたエラー修正アプリ</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918703/19272" target="_top" id="1918703">
  <img src="//a.impactradius-go.com/display-ad/19272-1918703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918703/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

