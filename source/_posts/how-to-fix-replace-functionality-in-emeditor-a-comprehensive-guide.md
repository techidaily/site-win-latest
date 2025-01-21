---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2025-01-16T08:46:03.591Z
updated: 2025-01-21T10:00:22.476Z
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
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-fast-fixes-streamlining-your-gotomeeting-record-keeping/"><u>[Updated] 2024 Approved Fast Fixes Streamlining Your GoToMeeting Record Keeping</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-how-can-you-create-animated-facebook-ads-with-high-roi/"><u>2024 Approved How Can You Create Animated Facebook Ads With High ROI?</u></a></li>
<li><a href="https://extra-information.techidaily.com/cinematic-illumination-a-filmmakers-path-to-stunning-colors-for-2024/"><u>Cinematic Illumination A Filmmaker's Path to Stunning Colors for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/das-problem-des-itunes-verbundes-bei-iphone-1413-und-wie-man-es-behebt-ein-blick-auf-fonebackup/"><u>Das Problem Des iTunes-Verbundes Bei iPhone 14/13 Und Wie Man Es Behebt - Ein Blick Auf FoneBackup</u></a></li>
<li><a href="https://win-latest.techidaily.com/how-to-support-and-protect-young-writers-a-parents-guide-using-massmail-for-content-creation-management/"><u>How to Support and Protect Young Writers: A Parent's Guide Using Massmail for Content Creation Management</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-guiding-steps-for-effective-gopro-time-lapse-capture/"><u>In 2024, Guiding Steps for Effective GoPro Time-Lapse Capture</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-price-estimation-guide-for-music-video-production/"><u>In 2024, Price Estimation Guide for Music Video Production</u></a></li>
<li><a href="https://win-latest.techidaily.com/mastering-email-communication-strategies-a-selection-of-premium-instructional-resources-backed-by-massmail-pros/"><u>Mastering Email Communication Strategies: A Selection of Premium Instructional Resources Backed by MassMail Pros</u></a></li>
<li><a href="https://win-latest.techidaily.com/step-by-step-guide-setting-up-system-protection-with-restore-points-on-windows-server-2008-r2/"><u>Step-by-Step Guide: Setting Up System Protection with Restore Points on Windows Server 2008 R2</u></a></li>
<li><a href="https://discover-community.techidaily.com/switch-your-default-browser-search-engine-on-windows-10-a-step-by-step-guide-techsolutions/"><u>Switch Your Default Browser Search Engine on Windows 10: A Step-by-Step Guide - TechSolutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-files-to-win-os-standards-max-156/"><u>Tailoring Your Files to Win OS Standards (Max 156)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/top-rated-gaming-headphones-in-depth-reviews-by-tech-experts-pcmag/"><u>Top-Rated Gaming Headphones : In-Depth Reviews by Tech Experts | PCMag</u></a></li>
<li><a href="https://win-latest.techidaily.com/transfer-videoinhalte-von-einem-usb-flash-laufwerk-zu-ios-geraten-wie-dem-iphone-und-ipad/"><u>Transfer Videoinhalte Von Einem USB-Flash-Laufwerk Zu iOS-Geräten Wie Dem iPhone Und iPad.</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-rotate-resize-and-refine-top-10-online-video-editors/"><u>Updated 2024 Approved Rotate, Resize, and Refine Top 10 Online Video Editors</u></a></li>
<li><a href="https://win-latest.techidaily.com/vaio-pc/"><u>VAIO PC 処分時に必要なデータ破棄手順 - 詳しい解説</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

