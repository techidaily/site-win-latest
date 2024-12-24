---
title: "How to Fix 'Replace' Functionality in EmEditor: A Comprehensive Guide"
date: 2024-12-21T02:38:56.305Z
updated: 2024-12-23T18:35:11.643Z
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
<li><a href="https://fox-direct.techidaily.com/new-darkening-brilliance-premiere-effects-for-2024/"><u>[New] Darkening Brilliance Premiere Effects for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-passive-to-profitable-8-beginners-revenue-hacks-for-youtube-for-2024/"><u>[Updated] From Passive to Profitable 8 Beginner's Revenue Hacks for YouTube for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-how-to-prepare-your-fb-content-hv-orientation-matters-for-2024/"><u>[Updated] How to Prepare Your FB Content H/V Orientation Matters for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-quick-start-combining-mac-obs-and-streamlabs-power-for-2024/"><u>[Updated] Quick Start Combining Mac, OBS & Streamlabs Power for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/1-effective-techniques-for-restoring-accidentally-erased-sticky-notes-a-step-by-step-guide/"><u>1. Effective Techniques for Restoring Accidentally Erased Sticky Notes: A Step-by-Step Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-beginner-to-expert-with-a-complete-fcp-guidebook/"><u>2024 Approved From Beginner to Expert with a Complete FCP Guidebook</u></a></li>
<li><a href="https://win-latest.techidaily.com/comment-transferer-en-douce-voie-les-photographies-de-votre-mac-vers-une-disquette-externe-strategies-efficaces/"><u>Comment Transférer en Douce Voie Les Photographies De Votre Mac Vers Une Disquette Externe : Stratégies Efficaces</u></a></li>
<li><a href="https://win-latest.techidaily.com/effortless-automated-backups-on-amazon-web-services-a-comprehensive-3-part-tutorial/"><u>Effortless Automated Backups on Amazon Web Services: A Comprehensive 3-Part Tutorial</u></a></li>
<li><a href="https://win-latest.techidaily.com/expert-guide-to-securely-rebooting-your-dell-laptop-on-windows-11-discover-the-best-4-procedures/"><u>Expert Guide to Securely Rebooting Your Dell Laptop on Windows 11 – Discover the Best 4 Procedures!</u></a></li>
<li><a href="https://win-latest.techidaily.com/fehlerbehebung-probleme-beim-wiedereinrichten-von-systemabbildern-aufgrund-von-efibios/"><u>Fehlerbehebung - Probleme Beim Wiedereinrichten Von Systemabbildern Aufgrund Von EFI/BIOS</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Lava Blaze 2? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-cricket-iphone-15-plus-for-free-by-drfone-ios/"><u>How To Unlock Cricket iPhone 15 Plus for Free</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-dell-g15-graphics-card-driver-download-and-installation-tutorial-for-windows-users/"><u>Latest Dell G15 Graphics Card Driver Download & Installation Tutorial for Windows Users</u></a></li>
<li><a href="https://win-latest.techidaily.com/recuperation-rapide-et-facile-apres-un-incident-pour-votre-serveur-windows-server-201/"><u>Récupération Rapide Et Facile Après Un Incident Pour Votre Serveur Windows Server 201</u></a></li>
<li><a href="https://win-latest.techidaily.com/solucion-implementada-fallo-en-la-configuracion-de-unidad-de-recuperacion-de-windows-11/"><u>Solución Implementada: Fallo en La Configuración De Unidad De Recuperación De Windows 11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/red-insights-setting-up-your-personalbusiness-yt-channel-mobilely-for-2024/"><u>Tailored Insights Setting Up Your Personal/Business YT Channel Mobilely for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

