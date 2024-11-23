---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2024-11-20T05:24:02.002Z
updated: 2024-11-23T01:02:14.536Z
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-the-art-of-duality-mastering-image-turnover-on-social-media-giants/"><u>[New] 2024 Approved The Art of Duality Mastering Image Turnover on Social Media Giants</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-beyond-the-box-a-list-of-non-gamebar-screen-recorders-for-2024/"><u>[New] Beyond the Box A List of Non-GameBar Screen Recorders for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-captivating-audiences-on-a-shoestring-budget-youtube-shorts-success-tips/"><u>[Updated] 2024 Approved Captivating Audiences on a Shoestring Budget – YouTube Shorts Success Tips</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-vlog-with-verve-following-in-the-footsteps-of-video-experts/"><u>[Updated] 2024 Approved Vlog with Verve Following in the Footsteps of Video Experts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-from-raw-to-refined-your-guide-to-youtube-video-edits/"><u>[Updated] From Raw to Refined Your Guide to YouTube Video Edits</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-how-to-safely-increase-your-youtube-fanbase-to-one-million/"><u>[Updated] In 2024, How to Safely Increase Your YouTube Fanbase To One Million</u></a></li>
<li><a href="https://win-latest.techidaily.com/6zu75a2q44oh44o844or44k144o844oq44g444gu44ot44kw44kk44oz5pmc44cb44ki44ox44oq44or44k544ov44o844oj44ks5pyj5yq55yyw44gz44kl44gf44kb44gu6kmz57sw44ks44kk44oj/"><u>電子メールサーバへのログイン時、アプリパスワードを有効化するための詳細ガイド</u></a></li>
<li><a href="https://win-latest.techidaily.com/5pya6ygp562w55wl77ya5pc25pwr6kkr56e76zmk55qe5pah5lu26iih5b2x5yop/"><u>最適策略：搶救被移除的文件與影像</u></a></li>
<li><a href="https://techtrends.techidaily.com/best-buys-must-have-june-2024-promotions-unbeatable-deals-and-discounts-revealed/"><u>Best Buy's Must-Have June 2024 Promotions: Unbeatable Deals & Discounts Revealed!</u></a></li>
<li><a href="https://win-latest.techidaily.com/efficient-iphone-backup-solutions-resolve-your-forever-waiting-issues/"><u>Efficient iPhone Backup Solutions - Resolve Your Forever Waiting Issues</u></a></li>
<li><a href="https://win-latest.techidaily.com/1728469757584-hdd/"><u>HDDのコピーをゼロから始める！無料プログラム集</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On HTC U23 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-latest.techidaily.com/how-to-restore-a-damaged-or-lost-partition-on-your-pc-using-the-latest-windows-11-tools-and-techniques/"><u>How to Restore a Damaged or Lost Partition on Your PC Using the Latest Windows 11 Tools and Techniques</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-art-of-color-grading-employing-luts-from-cg-central-for-2024/"><u>The Art of Color Grading Employing LUTs From CG Central for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/vier-methoden-zum-hochladen-von-iphone-bildern-auf-ein-chromebook/"><u>Vier Methoden Zum Hochladen Von iPhone-Bildern Auf Ein Chromebook</u></a></li>
<li><a href="https://win-latest.techidaily.com/1728470317758-windows-7/"><u>Windows 7 のシステム復元機能：手順ガイド</u></a></li>
<li><a href="https://win-latest.techidaily.com/windows-server-backup-restoration-successful-old-snapshots-recovered/"><u>Windows Server Backup Restoration Successful – Old Snapshots Recovered</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

