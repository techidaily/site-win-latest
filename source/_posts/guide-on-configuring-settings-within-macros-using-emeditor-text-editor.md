---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-12-20T21:00:34.886Z
updated: 2024-12-23T16:36:22.367Z
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-steps-for-modifying-your-social-network-cover-pictorial/"><u>[New] 2024 Approved Steps for Modifying Your Social Network Cover Pictorial</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ominating-the-digital-space-5-tips-for-video-visibility-victory/"><u>[New] Dominating the Digital Space 5 Tips for Video Visibility Victory</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/1715860460774-new-internal-device-recorder-to-capture-screens-on-mate-1020-and-p-series-phones-p2010/"><u>[New] Internal Device Recorder to Capture Screens on Mate 10/20 & P Series Phones (P20/10).</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-professional-video-gear-guide-top-18-for-4k-film-for-2024/"><u>[Updated] Professional Video Gear Guide Top 18 for 4K Film for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/1-ultimate-guide-to-securing-your-pc-against-malware-insights-from-yl-computing-experts/"><u>1. Ultimate Guide to Securing Your PC Against Malware: Insights From YL Computing Experts</u></a></li>
<li><a href="https://win-latest.techidaily.com/1728469051863-win10/"><u>解析Win10自动收集错误的重新开机问题及策略</u></a></li>
<li><a href="https://win-latest.techidaily.com/bmw-m5-ultimate-high-definition-wallpaper-gallery-stunning-visuals-and-full-resolution-images-by-yl-computing/"><u>BMW M5 Ultimate High-Definition Wallpaper Gallery: Stunning Visuals & Full Resolution Images by YL Computing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/decoding-ussd-a-detailed-guide-to-unstructured-supplementary-service-communication/"><u>Decoding USSD: A Detailed Guide to Unstructured Supplementary Service Communication</u></a></li>
<li><a href="https://win-latest.techidaily.com/effective-solutions-fixing-your-scanner-issues-with-precision-expert-tips-from-yl-computing/"><u>Effective Solutions: Fixing Your Scanner Issues with Precision - Expert Tips From YL Computing</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exceptional-clarity-at-an-affordable-price-discover-hps-37-wqhdplus-ultrawide-display-with-ips-technology-ideal-for-professionals-seeking-quality-without-ol49/"><u>Exceptional Clarity at an Affordable Price: Discover HP’s 37 WQHD+ Ultrawide Display with IPS Technology, Ideal for Professionals Seeking Quality without OLED Expense</u></a></li>
<li><a href="https://win-latest.techidaily.com/high-speed-graphics-card-fans-explained-a-guide-by-yl-computing-and-yl-software-solutions/"><u>High-Speed Graphics Card Fans Explained: A Guide by YL Computing and YL Software Solutions</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-professional-audio-setup-unveiling-our-picks-for-6-excellent-mics/"><u>In 2024, Professional Audio Setup Unveiling Our Picks for 6 Excellent Mics</u></a></li>
<li><a href="https://win-solutions.techidaily.com/latest-techniques-to-update-your-minecraft-screen-drivers-effectively/"><u>Latest Techniques to Update Your Minecraft Screen Drivers Effectively</u></a></li>
<li><a href="https://win-latest.techidaily.com/mastering-mouse-preferences-customize-your-windows-device-with-yls-ultimate-guide-to-control-panel-tweaks/"><u>Mastering Mouse Preferences: Customize Your Windows Device with YL's Ultimate Guide to Control Panel Tweaks</u></a></li>
<li><a href="https://win-latest.techidaily.com/revolutionize-advertising-impact-discover-magical-results-using-massmail-for-live-radio-promotions/"><u>Revolutionize Advertising Impact: Discover Magical Results Using MassMail for Live Radio Promotions</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/scrutinizing-high-quality-brightness-in-hd-imaging/"><u>Scrutinizing High-Quality Brightness in HD Imaging</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

