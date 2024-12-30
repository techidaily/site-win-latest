---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2024-12-25T02:12:35.132Z
updated: 2024-12-30T02:22:22.974Z
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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-excellent-apps-for-streamlined-igtv-vertical-cuts/"><u>[New] In 2024, Excellent Apps for Streamlined IGTV Vertical Cuts</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-transform-streams-into-premium-4k-videos-easily/"><u>[Updated] 2024 Approved Transform Streams Into Premium 4K Videos Easily</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-focal-points-the-most-superior-camera-lens-rankings-2024/"><u>[Updated] Focal Points The Most Superior Camera Lens Rankings 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-ingenious-ways-to-change-song-duration-in-spotify/"><u>[Updated] Ingenious Ways to Change Song Duration in Spotify</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-superstar-creators-the-highest-paid-ones/"><u>[Updated] Superstar Creators The Highest Paid Ones</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-cutting-edge-tactics-for-polishing-your-social-media-vids-on-instagram/"><u>2024 Approved Cutting-Edge Tactics for Polishing Your Social Media Vids on Instagram</u></a></li>
<li><a href="https://win-latest.techidaily.com/diagnosing-ram-and-rom-issues-expert-tips-from-yl-computings-latest-guide/"><u>Diagnosing RAM and ROM Issues: Expert Tips From YL Computing's Latest Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-nvidia-geforce-mx150-drivers-on-windows-pcs/"><u>Download & Update: NVIDIA GeForce MX150 Drivers on Windows PCs</u></a></li>
<li><a href="https://win-latest.techidaily.com/effective-strategies-for-purchasing-and-safely-storing-your-digital-assets-insights-from-yl-computing/"><u>Effective Strategies for Purchasing & Safely Storing Your Digital Assets: Insights From YL Computing</u></a></li>
<li><a href="https://win-latest.techidaily.com/exploring-pros-and-cons-a-comprehensive-guide-to-cryptocurrency-investments-by-yl-computing/"><u>Exploring Pros & Cons: A Comprehensive Guide to Cryptocurrency Investments by YL Computing</u></a></li>
<li><a href="https://win-latest.techidaily.com/high-quality-cat-wallpapers-images-backgrounds-and-photographs-by-yl-computing/"><u>High-Quality Cat Wallpapers: Images, Backgrounds & Photographs by YL Computing</u></a></li>
<li><a href="https://win-luxury.techidaily.com/identifying-key-hardware-issues-behind-blue-screen-errors-insights-from-yl-computing/"><u>Identifying Key Hardware Issues Behind Blue Screen Errors - Insights From YL Computing</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/snap-sharing-made-simple-camera-roll-to-social-now/"><u>Snap Sharing Made Simple Camera Roll to Social Now</u></a></li>
<li><a href="https://win-latest.techidaily.com/top-tools-and-applications-to-optimize-your-pc-by-stopping-unwanted-background-tasks-recommendations-from-yl-computing/"><u>Top Tools and Applications to Optimize Your PC by Stopping Unwanted Background Tasks - Recommendations From YL Computing</u></a></li>
<li><a href="https://win-latest.techidaily.com/troubleshooting-your-non-charging-laptop-battery-expert-advice-from-yl-computing/"><u>Troubleshooting Your Non-Charging Laptop Battery - Expert Advice From YL Computing</u></a></li>
<li><a href="https://win-latest.techidaily.com/unveiling-the-exclusive-complimentary-pcdj-dex-3-le-your-premier-choice-for-free-dj-programming/"><u>Unveiling the Exclusive, Complimentary PCDJ DEX 3 LE: Your Premier Choice for Free DJ Programming</u></a></li>
<li><a href="https://win-latest.techidaily.com/verify-your-printer-setup-a-comprehensive-guide-to-ensuring-proper-installation-yl-computing/"><u>Verify Your Printer Setup: A Comprehensive Guide to Ensuring Proper Installation - YL Computing</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

