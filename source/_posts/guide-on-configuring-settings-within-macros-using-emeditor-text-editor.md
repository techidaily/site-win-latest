---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-10-22T23:08:44.554Z
updated: 2024-10-29T07:12:44.219Z
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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-zdsoft-capture-master-overview-and-evaluation/"><u>[New] In 2024, ZDSoft Capture Master Overview & Evaluation</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-snatching-twitter-laughter-3-pc-techniques-for-2024/"><u>[Updated] Snatching Twitter Laughter 3 PC Techniques for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-a-step-by-step-approach-to-popularizing-instagram-posts/"><u>2024 Approved A Step-by-Step Approach to Popularizing Instagram Posts</u></a></li>
<li><a href="https://win-latest.techidaily.com/comment-resoudre-le-probleme-dun-scanneur-incompatible-avec-windows-11/"><u>Comment Résoudre Le Problème D'un Scanneur Incompatible Avec Windows 11 ?</u></a></li>
<li><a href="https://win-answers.techidaily.com/cyberpunk-2077-stability-hacks-effective-fixes-for-pc-gaming-issues-solved/"><u>Cyberpunk 2077 Stability Hacks: Effective Fixes for PC Gaming Issues [SOLVED]</u></a></li>
<li><a href="https://win-latest.techidaily.com/die-beeindruckendsten-losungen-zum-sichern-und-wiederherstellen-von-outlook-pst-dateien/"><u>Die Beeindruckendsten Lösungen Zum Sichern Und Wiederherstellen Von Outlook PST Dateien</u></a></li>
<li><a href="https://win-latest.techidaily.com/effizientes-wiederherstellungsprogramm-von-aomei-professionell-und-intuitiv-fur-windows-nutzer/"><u>Effizientes Wiederherstellungsprogramm Von AOMEI - Professionell Und Intuitiv Für Windows-Nutzer</u></a></li>
<li><a href="https://win-latest.techidaily.com/how-to-fix-the-invalid-directory-name-error-on-windows-11-a-step-by-step-guide/"><u>How to Fix the 'Invalid Directory Name' Error on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Oppo Find N3 Flip? | Dr.fone</u></a></li>
<li><a href="https://win-latest.techidaily.com/overcoming-errors-how-to-fix-acronis-backup-unable-to-access-disk-issues/"><u>Overcoming Errors: How to Fix 'Acronis Backup Unable to Access Disk' Issues</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streamlining-video-calls-leveraging-zoom-on-windows-10-pcs-for-2024/"><u>Streamlining Video Calls Leveraging Zoom on Windows 10 PCs for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/uberziehbare-methoden-zum-verschieben-von-icloud-fotos-auf-verschiedene-gerate/"><u>Überziehbare Methoden Zum Verschieben Von iCloud-Fotos Auf Verschiedene Geräte</u></a></li>
<li><a href="https://change-location.techidaily.com/where-is-the-best-place-to-catch-dratini-on-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Vivo X100 Pro | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

