---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2025-02-12T18:04:40.891Z
updated: 2025-02-19T03:09:36.883Z
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
<li><a href="https://youtube-zero.techidaily.com/iscovering-your-favorite-makeup-vloggers-on-youtube/"><u>[New] Discovering Your Favorite Makeup Vloggers on YouTube</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-livestreaming-facebook-made-simple-for-all-tech-users-for-2024/"><u>[New] Livestreaming Facebook Made Simple for All Tech Users for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/hat-is-a-parody-and-how-to-make-a-parody-video/"><u>[New] What Is a Parody and How to Make a Parody Video</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-navigating-instagram-the-essential-guide-to-mastering-reels/"><u>[Updated] Navigating Instagram The Essential Guide to Mastering Reels</u></a></li>
<li><a href="https://win-latest.techidaily.com/access-your-files-effortlessly-mastering-file-management-on-windows-with-insights-from-yl-software/"><u>Access Your Files Effortlessly: Mastering File Management on Windows with Insights From YL Software</u></a></li>
<li><a href="https://win-latest.techidaily.com/boost-your-pcs-performance-by-clearing-out-disk-cache-expert-tips-from-yl-computing/"><u>Boost Your PC's Performance by Clearing Out Disk Cache - Expert Tips From YL Computing</u></a></li>
<li><a href="https://win-latest.techidaily.com/complete-mastery-of-your-systems-control-panel-unlock-all-settings-with-yl-computings-expert-tips/"><u>Complete Mastery of Your System's Control Panel - Unlock All Settings with YL Computing’s Expert Tips</u></a></li>
<li><a href="https://win-bytes.techidaily.com/error-webpage-unavailable-why-the-link-leads-nowhere/"><u>Error: Webpage Unavailable – Why the Link Leads Nowhere</u></a></li>
<li><a href="https://win-latest.techidaily.com/how-to-stop-a-printer-operation-midway-expert-tips-from-yl-software/"><u>How to Stop a Printer Operation Midway? Expert Tips From YL Software</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/leading-ceiling-sound-solutions-the-ultimate-list-for-2e4/"><u>Leading Ceiling Sound Solutions - The Ultimate List for 2E4</u></a></li>
<li><a href="https://win-latest.techidaily.com/navigating-crypto-trends-essential-insights-from-yl-software-updates-and-analysis/"><u>Navigating Crypto Trends: Essential Insights From YL Software Updates and Analysis</u></a></li>
<li><a href="https://discover-deluxe.techidaily.com/network-printer-setup-using-windows-pc-control-panel-explained-by-professionals-at-yl-software-solutions/"><u>Network Printer Setup Using Windows PC Control Panel Explained by Professionals at YL Software Solutions</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-video-editing-essentials-top-apps-to-blur-parts-of-your-video/"><u>New 2024 Approved Video Editing Essentials Top Apps to Blur Parts of Your Video</u></a></li>
<li><a href="https://techidaily.com/samsung-can-t-play-mp4-video-files-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Samsung can't play MP4 video files</u></a></li>
<li><a href="https://win-latest.techidaily.com/step-by-step-guide-reinstalling-your-video-card-drivers-expert-advice-from-yl-computing/"><u>Step-by-Step Guide: Reinstalling Your Video Card Drivers - Expert Advice From YL Computing</u></a></li>
<li><a href="https://win-latest.techidaily.com/step-by-step-guide-replacing-defective-components-in-your-pc-expert-tips-by-yl-computing/"><u>Step-by-Step Guide: Replacing Defective Components in Your PC - Expert Tips by YL Computing</u></a></li>
<li><a href="https://win-latest.techidaily.com/step-by-step-guide-replacing-faulty-memory-modules-with-yl-computings-help/"><u>Step-by-Step Guide: Replacing Faulty Memory Modules with YL Computing's Help</u></a></li>
<li><a href="https://some-skills.techidaily.com/transform-your-phone-with-funimate-the-ultimate-apk-guide-for-2024/"><u>Transform Your Phone with Funimate - The Ultimate APK Guide for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/unravel-the-process-of-deleting-apps-with-yl-softwares-simple-methodology/"><u>Unravel the Process of Deleting Apps with YL Software's Simple Methodology</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

