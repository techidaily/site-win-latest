---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-12-24T19:54:01.447Z
updated: 2024-12-29T20:38:09.098Z
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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-conquer-video-quality-with-best-3-transcoder-methods-for-zoom/"><u>[New] 2024 Approved Conquer Video Quality with Best 3 Transcoder Methods for Zoom</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-essential-knowledge-how-io-screen-recorder-works/"><u>[Updated] 2024 Approved Essential Knowledge How Io Screen Recorder Works</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-poll-power-play-best-election-strategy-games/"><u>[Updated] 2024 Approved Poll Power Play Best Election Strategy Games</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-facebooks-flash-video-frenzy/"><u>[Updated] Facebook's Flash Video Frenzy</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-quick-guide-to-the-ifunny-meme-application/"><u>[Updated] In 2024, Quick Guide to the iFunny Meme Application</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-schedule-smarter-the-art-of-youtube-content-timing/"><u>[Updated] In 2024, Schedule Smarter The Art of YouTube Content Timing</u></a></li>
<li><a href="https://win-latest.techidaily.com/complete-step-by-step-process-on-moving-your-favorite-spotify-tunes-to-apple-music/"><u>Complete Step-by-Step Process on Moving Your Favorite Spotify Tunes to Apple Music</u></a></li>
<li><a href="https://win-latest.techidaily.com/emeditor-pro-v1110-preview-release-advanced-text-editing-software/"><u>EmEditor Pro V11.1.0 Preview Release - Advanced Text Editing Software</u></a></li>
<li><a href="https://win-latest.techidaily.com/error-404-the-missing-webpage-what-to-do-when-content-cant-be-located/"><u>Error 404: The Missing Webpage – What To Do When Content Can't Be Located</u></a></li>
<li><a href="https://some-guidance.techidaily.com/kostenlose-umwandlung-von-wmv-in-flac-online-durch-movavi-schnelle-losung/"><u>Kostenlose Umwandlung Von WMV in FLAC Online Durch Movavi - Schnelle Lösung!</u></a></li>
<li><a href="https://win-latest.techidaily.com/reposicion-del-archivo-descartado-accidentalmente-en-las-versiones-actuales-de-windows-10-y-11/"><u>Reposición Del Archivo Descartado Accidentalmente en Las Versiones Actuales De Windows (10 Y 11)</u></a></li>
<li><a href="https://win-latest.techidaily.com/ricostruisci-file-scomparsi-dal-tuo-disco-di-stato-con-facili-passaggi-guida/"><u>Ricostruisci File Scomparsi Dal Tuo Disco Di Stato Con Facili Passaggi Guida.</u></a></li>
<li><a href="https://win-latest.techidaily.com/the-essentials-of-maintaining-a-pristine-email-database-insights-from-massmail/"><u>The Essentials of Maintaining a Pristine Email Database: Insights From MassMail</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-evolution-of-software-development-agnes-ros-perspective-with-atlassian-featured-on-zdnet/"><u>The Evolution of Software Development: Agnes Ro's Perspective with Atlassian | Featured on ZDNet</u></a></li>
<li><a href="https://win-latest.techidaily.com/troubleshooting-the-volume-shadow-copy-failure-in-windows-10-7-and-8-expert-solutions/"><u>Troubleshooting the Volume Shadow Copy Failure in Windows 10, 7, and 8: Expert Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

