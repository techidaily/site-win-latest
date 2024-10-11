---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2024-10-04T17:07:41.544Z
updated: 2024-10-11T17:06:09.160Z
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
<li><a href="https://article-posts.techidaily.com/updated-syncopate-screen-a-beginners-guide-to-mobile-video-making/"><u>[Updated] Syncopate Screen A Beginner's Guide to Mobile Video Making</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-top-8-high-definition-5k-display-options-for-you-for-2024/"><u>[Updated] Top 8 High-Definition 5K Display Options for You for 2024</u></a></li>
<li><a href="https://discover-help.techidaily.com/1-efficiently-compress-your-high-resolution-4k-and-27k-gopro-footage-without-losing-picture-clarity/"><u>1) Efficiently Compress Your High-Resolution 4K & 2.7K GoPro Footage Without Losing Picture Clarity</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-building-captivating-instagram-feed-layouts/"><u>2024 Approved Building Captivating Instagram Feed Layouts</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/all-you-need-to-know-about-mega-greninja-for-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://win-latest.techidaily.com/great-news-from-southwest-airlines-all-are-welcome-just-not-mr-microsoft/"><u>Great News From Southwest Airlines: All Are Welcome, Just Not Mr. Microsoft!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-itel-a60s-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Itel A60s? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/jumpstart-to-joyous-animation-a-guide-in-movie-maker-world-for-2024/"><u>Jumpstart to Joyous Animation A Guide in Movie Maker World for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/massive-downtime-how-and-why-microsoft-365-suffered-widespread-issues-affecting-users-worldwide-digitaldigest/"><u>Massive Downtime: How and Why Microsoft 365 Suffered Widespread Issues Affecting Users Worldwide | DigitalDigest</u></a></li>
<li><a href="https://win-latest.techidaily.com/mastering-file-protection-step-by-step-file-history-setup-in-windows-10-and-11-tips-from-zdnet/"><u>Mastering File Protection: Step-by-Step File History Setup in Windows 10 and 11 - Tips From ZDNet</u></a></li>
<li><a href="https://win-latest.techidaily.com/microsoft-boosts-employee-creativity-with-enhanced-teams-features-insights-from-zdnet/"><u>Microsoft Boosts Employee Creativity with Enhanced Teams Features – Insights From ZDNet</u></a></li>
<li><a href="https://win-latest.techidaily.com/microsoft-claims-engineers-adoration-for-windows-11-exploring-the-tech-communitys-favorite-os/"><u>Microsoft Claims Engineers' Adoration for Windows 11: Exploring the Tech Community's Favorite OS</u></a></li>
<li><a href="https://win-latest.techidaily.com/singapore-legal-tech-set-to-adopt-microsoft-copilot-an-exclusive-insight/"><u>Singapore Legal Tech Set to Adopt Microsoft Copilot: An Exclusive Insight</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-instructions-for-upgrading-the-epson-wf-7720-printer-driver-in-windows-environment/"><u>Step-by-Step Instructions for Upgrading the Epson WF-7720 Printer Driver in Windows Environment</u></a></li>
<li><a href="https://win-latest.techidaily.com/the-arrival-of-groundbreaking-windows-on-arm-applications-why-it-matters-tech-insights/"><u>The Arrival of Groundbreaking Windows on ARM Applications - Why It Matters | Tech Insights</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

