---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-11-28T19:14:59.861Z
updated: 2024-12-01T00:49:52.826Z
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
<li><a href="https://fox-direct.techidaily.com/new-crafting-cinematic-experiences-on-your-desktop-with-windows-hdr-for-2024/"><u>[New] Crafting Cinematic Experiences on Your Desktop with Windows HDR for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-instantaneous-subscriber-tracking/"><u>[New] Instantaneous Subscriber Tracking</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-elevate-your-livestream-game-twitch-and-youtube-via-obs/"><u>[Updated] In 2024, Elevate Your Livestream Game Twitch & YouTube via OBS</u></a></li>
<li><a href="https://win-latest.techidaily.com/1728464557235-windows-11/"><u>三种办法在保留程序完整性的前提下为Windows 11进行再生产：详解</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/essential-tools-for-android-and-ios-users-seeking-playlist-extractors/"><u>Essential Tools for Android & iOS Users Seeking Playlist Extractors</u></a></li>
<li><a href="https://win-latest.techidaily.com/funktionalitat-von-xcopy-gegenuber-robocopy-analysieren-erkundung-vergleichender-aspekte-und-substitutionsmoglichkeiten/"><u>Funktionalität Von XCopy Gegenüber RoboCopy Analysieren – Erkundung Vergleichender Aspekte Und Substitutionsmöglichkeiten</u></a></li>
<li><a href="https://tech-revival.techidaily.com/sony-unveils-the-mortal-instruments-city-of-bones-dvd-release/"><u>Sony Unveils 'The Mortal Instruments: City of Bones' DVD Release</u></a></li>
<li><a href="https://win-latest.techidaily.com/synchronisez-vos-fichiers-avec-le-disque-dur-et-microsoft-onedrive-facilement-trois-methodes-rapides/"><u>Synchronisez Vos Fichiers Avec Le Disque Dur Et Microsoft OneDrive Facilement : Trois Méthodes Rapides</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ultimate-gopro-experience-in-hero9-black/"><u>The Ultimate GoPro Experience in HERO9 Black?</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/virtual-venue-video-verifier-for-2024/"><u>Virtual Venue Video Verifier for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/wiederholung-geloschter-dateien-auf-tape-diktierern-losungen-und-methoden/"><u>Wiederholung Gelöschter Dateien Auf Tape-Diktierern – Lösungen Und Methoden</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

