---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2025-01-17T08:20:48.709Z
updated: 2025-01-21T09:47:20.510Z
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
<li><a href="https://article-files.techidaily.com/new-in-2024-photographys-new-frontier-toolwiz-app-detailed-review-2023-edition/"><u>[New] In 2024, Photography's New Frontier Toolwiz App - Detailed Review, 2023 Edition</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-rapid-reference-green-screen-basics/"><u>[Updated] 2024 Approved Rapid Reference Green Screen Basics</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-uncovering-invisible-challenges-in-vr/"><u>2024 Approved Uncovering Invisible Challenges in VR</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/evaluating-the-asus-rt-ac68u-a-perfect-blend-of-speed-and-security-in-modern-5g-wi-fi-technology/"><u>Evaluating the Asus RT-AC68U: A Perfect Blend of Speed and Security in Modern 5G Wi-Fi Technology</u></a></li>
<li><a href="https://discover-great.techidaily.com/how-to-speed-up-your-sluggish-computer-expert-tips-from-yl-computing-and-yl-software/"><u>How to Speed Up Your Sluggish Computer: Expert Tips From YL Computing & YL Software</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Google Pixel 7a | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prevent-cross-site-tracking-on-xiaomi-14-ultra-and-browser-drfone-by-drfone-virtual-android/"><u>In 2024, Prevent Cross-Site Tracking on Xiaomi 14 Ultra and Browser | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-top-8-smooth-capture-tools-reviewed/"><u>In 2024, Top 8 Smooth Capture Tools Reviewed</u></a></li>
<li><a href="https://win-latest.techidaily.com/localizar-tus-videos-perdidos-en-la-pc-y-iphone-metodos-de-recuperacion-efectivos/"><u>Localizar Tus Videos Perdidos en La PC Y iPhone, Métodos De Recuperación Efectivos</u></a></li>
<li><a href="https://win-latest.techidaily.com/ultimate-guide-resolving-ipad-and-itunes-synchronization-problems-in-top-7-methods/"><u>Ultimate Guide: Resolving iPad and iTunes Synchronization Problems in Top 7 Methods</u></a></li>
<li><a href="https://win-latest.techidaily.com/wie-man-eine-physische-festplatte-erfolgreich-mit-vmware-esxi-verbindet/"><u>Wie Man Eine Physische Festplatte Erfolgreich Mit VMware ESXi Verbindet</u></a></li>
<li><a href="https://win-latest.techidaily.com/wiederherstellung-von-versehentlich-geloschten-kindle-e-books-4-bewahrte-strategien/"><u>Wiederherstellung Von Versehentlich Gelöschten Kindle-E-Books: 4 Bewährte Strategien</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

