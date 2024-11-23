---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-11-17T18:53:30.088Z
updated: 2024-11-22T18:47:44.431Z
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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-journey-to-crafting-a-unique-alphanumeric-marker-for-tiktok/"><u>[New] 2024 Approved Journey to Crafting a Unique Alphanumeric Marker for TikTok</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-no-cost-android-facetime-replacements-ranked/"><u>[Updated] 2024 Approved No-Cost Android FaceTime Replacements Ranked</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-charting-a-course-for-youtube-success-viewer-numbers-and-income-for-2024/"><u>[Updated] Charting a Course for YouTube Success Viewer Numbers and Income for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/9-effective-strategies-for-mobile-optimized-email-campaigns-enhance-subscriber-engagement-using-massmail-tools/"><u>9 Effective Strategies for Mobile-Optimized Email Campaigns: Enhance Subscriber Engagement Using MassMail Tools</u></a></li>
<li><a href="https://win-latest.techidaily.com/automatic-folder-synchronization-techniques-for-macos-a-comprehensive-guide/"><u>Automatic Folder Synchronization Techniques for macOS: A Comprehensive Guide</u></a></li>
<li><a href="https://win-latest.techidaily.com/effective-viral-marketing-techniques-for-2009-how-to-leverage-tell-a-friend-methods-using-massmail-software/"><u>Effective Viral Marketing Techniques for 2009: How to Leverage Tell-a-Friend Methods Using Massmail Software</u></a></li>
<li><a href="https://buynow-help.techidaily.com/explore-the-enhanced-capabilities-of-the-newly-launched-cycwagen-cargo-electric-bike/"><u>Explore the Enhanced Capabilities of the Newly Launched CycWagen Cargo Electric Bike</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-oneplus-ace-2v-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from OnePlus Ace 2V to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-apple-iphone-13-pro-max-location-without-installing-software-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track Apple iPhone 13 Pro Max Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-photoshop-for-beginners-top-editing-hacks-revealed/"><u>In 2024, Photoshop For Beginners Top Editing Hacks Revealed</u></a></li>
<li><a href="https://win-latest.techidaily.com/maximize-conversion-rates-discover-the-best-call-to-action-phrases-for-higher-sales-via-email-powered-by-massmail-solutions/"><u>Maximize Conversion Rates: Discover the Best Call-to-Action Phrases for Higher Sales via Email | Powered by Massmail Solutions</u></a></li>
<li><a href="https://win-latest.techidaily.com/professionelle-back-up-strategien-fur-aomei-backupper-nutzer/"><u>Professionelle Back-Up-Strategien Für AOMEI Backupper Nutzer</u></a></li>
<li><a href="https://win-latest.techidaily.com/protecting-information-integrity-comprehensive-instructions-for-pre-factory-reset-system-backups-on-computers/"><u>Protecting Information Integrity: Comprehensive Instructions for Pre-Factory Reset System Backups on Computers</u></a></li>
<li><a href="https://change-location.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://win-latest.techidaily.com/windowssd/"><u>Windows上最理想的克隆SD卡(活动)工具分析</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

