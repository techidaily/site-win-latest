---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2025-02-17T17:43:50.269Z
updated: 2025-02-18T21:25:53.863Z
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
<li><a href="https://youtube-lab.techidaily.com/nderstanding-the-core-of-asmr-media/"><u>[New] Understanding the Core of ASMR Media</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-essential-vr-adventures-on-oculus-devices/"><u>[Updated] Essential VR Adventures on Oculus Devices</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/enrich-your-screen-time-integrating-facebook-live-into-roku-for-2024/"><u>Enrich Your Screen Time Integrating Facebook LIVE Into Roku for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-itel-s23-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Itel S23 Devices</u></a></li>
<li><a href="https://win-latest.techidaily.com/losung-fur-den-kritischen-systemfehler-betriebssystem-nicht-gefunden-bei-acer-pcs/"><u>Lösung Für Den Kritischen Systemfehler «Betriebssystem Nicht Gefunden» Bei Acer-PCs</u></a></li>
<li><a href="https://win-latest.techidaily.com/maximize-system-efficiency-confirm-the-integrity-of-your-temporary-file-storage/"><u>Maximize System Efficiency: Confirm the Integrity of Your Temporary File Storage</u></a></li>
<li><a href="https://win-latest.techidaily.com/non-visible-reader-mouse-on-windows-11-solutions-and-fixes/"><u>Non-Visible Reader Mouse on Windows 11 - Solutions & Fixes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-chronicle-of-creation-weaving-time-lapse-animations-via-movie-maker-for-2024/"><u>The Chronicle of Creation Weaving Time-Lapse Animations via Movie Maker for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/transferer-des-informations-vers-un-ssd-wd-sans-reformatage/"><u>Transférer Des Informations Vers Un SSD WD Sans Reformatage</u></a></li>
<li><a href="https://techidaily.com/why-are-your-photos-lost-from-iphone-11-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Why are your photos lost from iPhone 11? | Stellar</u></a></li>
<li><a href="https://win-latest.techidaily.com/wiederauffinden-verlorener-spielinhalte-auf-dem-pc-erfolgreich-mit-diesen-5-strategien/"><u>Wiederauffinden Verlorener Spielinhalte Auf Dem PC: Erfolgreich Mit Diesen 5 Strategien</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

