---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-10-16T10:17:24.114Z
updated: 2024-10-22T19:54:19.909Z
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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-x-sync-studio-platform-personal-computing/"><u>[New] In 2024, X-Sync Studio Platform, Personal Computing</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-gross-income-estimates-for-youtube-star-pewdopeep/"><u>[Updated] 2024 Approved Gross Income Estimates for YouTube Star PewDoPeep</u></a></li>
<li><a href="https://win-latest.techidaily.com/effective-strategies-for-non-intrusive-batch-emailing-with-massmail-pro/"><u>Effective Strategies for Non-Intrusive Batch Emailing with MassMail Pro</u></a></li>
<li><a href="https://win-latest.techidaily.com/fugen-sie-ihrem-iphone-xxrxs-neue-tracks-hinzu-effiziente-methoden-zum-ubertragen-von-computermusik/"><u>Fügen Sie Ihrem iPhone X/XR/XS Neue Tracks Hinzu: Effiziente Methoden Zum Übertragen Von Computermusik</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-m14-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy M14 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/snip-tool-engagement-in-windows-11-for-immediate-use/"><u>Snip Tool Engagement in Windows 11 for Immediate Use</u></a></li>
<li><a href="https://some-skills.techidaily.com/streamline-your-multi-tasking-pip-settings-in-safari-for-2024/"><u>Streamline Your Multi-Tasking PIP Settings in Safari for 2024</u></a></li>
<li><a href="https://win-latest.techidaily.com/suchen-sie-verschollene-dokumente-wieder-erfolgreiche-wiederherstellung-verlorener-dateien-unter-windows-10/"><u>Suchen Sie Verschollene Dokumente Wieder: Erfolgreiche Wiederherstellung Verlorener Dateien Unter Windows 10</u></a></li>
<li><a href="https://win-latest.techidaily.com/synology-nas-backups-auf-windows-11-3-effiziente-losungen/"><u>Synology NAS-Backups Auf Windows 11: 3 Effiziente Lösungen</u></a></li>
<li><a href="https://win-studio.techidaily.com/windows-11-backup-feature-recovery-successful/"><u>Windows 11 Backup Feature Recovery Successful</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

