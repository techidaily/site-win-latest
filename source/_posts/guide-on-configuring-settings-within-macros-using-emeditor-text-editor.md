---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-12-11T19:54:55.444Z
updated: 2024-12-14T19:05:26.964Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/6fa8c212e32cacf403b164cddaa0641d8c8c9740158f0e616afbd57801dea413.jpg
---

## Guide on Configuring Settings Within Macros Using EmEditor Text Editor

September 14, 2009 at 11:49 pm [#7639](https://tools.techidaily.com/emeditor/products/) 

[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")

Keymaster

> dw7832 wrote:  
> I’m currently struggling to set the properties of the active configuration of a file in a macro:
> 
> // toggle show spaces  
> if (document.Config.Mark.ShowSpaces) {  
> document.Config.Mark.ShowSpaces = false;  
> } else {  
> document.Config.Mark.ShowSpaces = true;  
> }
> 
> and
> 
> with (document.Config.Indent) {   
> TabColumns = 4;  
> InsertSpaces = true;  
> WrapIndent = true; }  
> document.Config.Save();
> 
> Neither of these give an error message but when alert()-ing the properties they are not changed nor does EmEditor act like they’ve changed. Can anybody shed any light?
> 
> Thank you in advance.

 Please try this way:
  

	cfg = document.Config;  

	if (cfg.Mark.ShowSpaces) {  

	cfg.Mark.ShowSpaces = false;  

	} else {  

	cfg.Mark.ShowSpaces = true;  

	cfg.Save();

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
<li><a href="https://facebook-record-videos.techidaily.com/updated-expert-strategies-to-maximize-income-with-video-ads-on-youtube/"><u>[Updated] Expert Strategies to Maximize Income with Video Ads on Youtube</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-next-gen-cameras-revealed-top-10-s-videographers/"><u>[Updated] In 2024, Next-Gen Cameras Revealed - Top 10 'S Videographers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-quick-steps-to-screen-recording-via-ezvid-video-creator-for-2024/"><u>[Updated] Quick Steps to Screen Recording via Ezvid Video Creator for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-windows-users-take-note-camcorders-guide-ahead/"><u>[Updated] Windows Users, Take Note Camcorders Guide Ahead</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-maximizing-twitter-budget-efficiency-in-ad-spends/"><u>2024 Approved Maximizing Twitter Budget Efficiency in Ad Spends</u></a></li>
<li><a href="https://win-latest.techidaily.com/ds-3-yl-software/"><u>DS 3 컴퓨터 확장기 사진, 이미지 또는 배경 그림 | YL Software 링크 쿡백</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-tips-for-performing-a-fresh-start-on-your-dell-notebook/"><u>Expert Tips for Performing a Fresh Start on Your Dell Notebook</u></a></li>
<li><a href="https://win-latest.techidaily.com/how-to-fix-when-your-windows-fails-to-detect-the-external-hdd-a-guide-by-yl-computing/"><u>How To Fix When Your Windows Fails To Detect The External HDD: A Guide by YL Computing</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-vivo-s18-pro-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-unveiling-the-syma-x5c-a-beginners-prime-drone-choice/"><u>In 2024, Unveiling the Syma X5C A Beginner’s Prime Drone Choice</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/my-podcast-blueprint-powered-by-ai/"><u>My Podcast Blueprint, Powered by AI</u></a></li>
<li><a href="https://win-latest.techidaily.com/solving-screen-issue-alerts-expert-tips-by-yl-computings-specialized-software-tools/"><u>Solving Screen Issue Alerts: Expert Tips by YL Computing's Specialized Software Tools</u></a></li>
<li><a href="https://win-latest.techidaily.com/troubleshooting-eerie-printer-noises-insights-and-solutions-for-smoother-printing-guided-by-yl-software/"><u>Troubleshooting Eerie Printer Noises: Insights and Solutions for Smoother Printing - Guided by YL Software</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

