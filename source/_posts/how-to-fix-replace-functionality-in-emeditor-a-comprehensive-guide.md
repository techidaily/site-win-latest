---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2024-10-27T00:23:54.691Z
updated: 2024-10-29T04:03:47.088Z
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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-editors-picks-top-budget-friendly-online-tools/"><u>[New] 2024 Approved Editor's Picks Top Budget-Friendly Online Tools</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-harmonic-headstarts-curated-spots-with-the-best-music-picks/"><u>[New] Harmonic Headstarts Curated Spots with the Best Music Picks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-augmenting-your-stardew-experience-with-seven-top-mods/"><u>[Updated] Augmenting Your Stardew Experience with Seven Top Mods</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-easy-to-use-apps-for-idevice-screen-capturing/"><u>[Updated] Easy-to-Use Apps for iDevice Screen Capturing</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-x-professional-audio-toolkit-personal-computing/"><u>[Updated] X-Professional Audio Toolkit, Personal Computing</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/create-a-soundtracked-slideshow-on-your-mac-for-dynamic-presentations/"><u>Create a Soundtracked Slideshow on Your Mac for Dynamic Presentations</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-tips-and-tools-for-a-flourishing-garden-insights-from-zdnet/"><u>Essential Tips & Tools for a Flourishing Garden - Insights From ZDNet</u></a></li>
<li><a href="https://win-latest.techidaily.com/expert-tips-on-restoring-information-from-an-sd-card-configured-as-devices-built-in-storage/"><u>Expert Tips on Restoring Information From an SD Card Configured as Device’s Built-In Storage</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-xiaomi-redmi-k70-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Xiaomi Redmi K70? | Dr.fone</u></a></li>
<li><a href="https://win-latest.techidaily.com/set-up-auto-purge-for-expired-backups-on-windows-server-systems/"><u>Set Up Auto-Purge for Expired Backups on Windows Server Systems</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/standard-youtube-license-vs-creative-commons/"><u>Standard YouTube License Vs. Creative Commons</u></a></li>
<li><a href="https://win-latest.techidaily.com/top-rated-100-free-file-recovery-apps-how-to-safely-get-and-install-on-windows-1110/"><u>Top Rated 100% Free File Recovery Apps: How to Safely Get and Install on Windows 11/10</u></a></li>
<li><a href="https://win-latest.techidaily.com/undrukkan-gratis-pemulihan-file-windows-11-dan-10-kumpulkan-semua-hiburan/"><u>Undrukkan Gratis: Pemulihan File Windows 11 Dan 10 - Kumpulkan Semua Hiburan</u></a></li>
<li><a href="https://win-latest.techidaily.com/user-friendly-and-streamlined-backup-solutions-for-vmware-vsphere-basics/"><u>User-Friendly & Streamlined Backup Solutions for VMware vSphere Basics</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151854/7443" target="_top" id="2151854">
  <img src="//a.impactradius-go.com/display-ad/7443-2151854" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151854/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

