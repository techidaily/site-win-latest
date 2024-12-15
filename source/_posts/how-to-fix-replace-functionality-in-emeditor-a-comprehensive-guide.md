---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2024-12-12T05:26:31.609Z
updated: 2024-12-15T15:14:43.514Z
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
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-top-10-free-apps-for-crafting-youtube-channel-graphics/"><u>[Updated] 2024 Approved Top 10 Free Apps for Crafting YouTube Channel Graphics</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-superior-5-social-sites-redefining-connectivity/"><u>[Updated] Superior 5 Social Sites, Redefining Connectivity</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-top-10-best-webcam-covers-for-2024/"><u>[Updated] Top 10 Best Webcam Covers for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/10-with-yls-guidance-yl-tech-solutions/"><u>10 with YL's Guidance | YL Tech Solutions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-cutting-edge-text-configuration-techniques/"><u>2024 Approved Cutting-Edge Text Configuration Techniques</u></a></li>
<li><a href="https://win-latest.techidaily.com/access-your-files-effortlessly-mastering-file-management-on-windows-with-insights-from-yl-software/"><u>Access Your Files Effortlessly: Mastering File Management on Windows with Insights From YL Software</u></a></li>
<li><a href="https://win-latest.techidaily.com/can-a-registry-cleaner-solve-your-windows-issues-uncover-the-truth-with-yl-softwares-expert-insight/"><u>Can a Registry Cleaner Solve Your Windows Issues? Uncover the Truth with YL Software’s Expert Insight</u></a></li>
<li><a href="https://win-latest.techidaily.com/complete-mastery-of-your-systems-control-panel-unlock-all-settings-with-yl-computings-expert-tips/"><u>Complete Mastery of Your System's Control Panel - Unlock All Settings with YL Computing’s Expert Tips</u></a></li>
<li><a href="https://win-latest.techidaily.com/enhance-computer-speed-and-health-by-mastering-disk-defrag-strategies-tips-and-tricks-by-yl-software/"><u>Enhance Computer Speed and Health by Mastering Disk Defrag Strategies - Tips & Tricks by YL Software</u></a></li>
<li><a href="https://win-latest.techidaily.com/how-to-stop-a-printer-operation-midway-expert-tips-from-yl-software/"><u>How to Stop a Printer Operation Midway? Expert Tips From YL Software</u></a></li>
<li><a href="https://extra-support.techidaily.com/intova-edge-x-action-camera-review-for-2024/"><u>Intova Edge X Action Camera Review for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/navigating-crypto-trends-essential-insights-from-yl-software-updates-and-analysis/"><u>Navigating Crypto Trends: Essential Insights From YL Software Updates and Analysis</u></a></li>
<li><a href="https://fox-useful.techidaily.com/norton-ghost-anwendung-fur-windows-11-8-und-7-schritt-fur-schritt-anleitung/"><u>Norton Ghost Anwendung Für Windows 11, 8 Und 7: Schritt-Für-Schritt Anleitung</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcome-frequent-airpods-iphone-disconnections-with-these-proven-11-strategies/"><u>Overcome Frequent AirPods-iPhone Disconnections With These Proven 11 Strategies</u></a></li>
<li><a href="https://techidaily.com/remove-the-lock-of-nokia-c210-by-drfone-android-unlock-android-unlock/"><u>Remove the lock of Nokia C210</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/screenflow-mastery-for-mac-users-a-critical-look/"><u>ScreenFlow Mastery for Mac Users – A Critical Look</u></a></li>
<li><a href="https://win-latest.techidaily.com/step-by-step-guide-replacing-defective-components-in-your-pc-expert-tips-by-yl-computing/"><u>Step-by-Step Guide: Replacing Defective Components in Your PC - Expert Tips by YL Computing</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-epic-launcher-on-w11-solutions-present/"><u>Uninstalling Epic Launcher on W11 - Solutions Present</u></a></li>
<li><a href="https://win-latest.techidaily.com/unravel-the-process-of-deleting-apps-with-yl-softwares-simple-methodology/"><u>Unravel the Process of Deleting Apps with YL Software's Simple Methodology</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

