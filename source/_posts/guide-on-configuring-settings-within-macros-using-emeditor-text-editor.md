---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-10-11T17:29:15.092Z
updated: 2024-10-17T16:31:49.646Z
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
<li><a href="https://fox-cloud.techidaily.com/new-enhancing-your-nba-viewing-with-smart-techniques/"><u>[New] Enhancing Your NBA Viewing with Smart Techniques</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/outube-master-of-moneymaking-skills-for-2024/"><u>[New] YouTube Master of Moneymaking Skills for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-the-insider-guide-to-simplifying-character-voice-modification-pubg-for-2024/"><u>[Updated] The Insider Guide to Simplifying Character Voice Modification (PUBG) for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-enhancing-visual-storytelling-on-instagram-with-loops/"><u>2024 Approved Enhancing Visual Storytelling on Instagram With Loops</u></a></li>
<li><a href="https://win-latest.techidaily.com/windows-11-0x8000ffff/"><u>簡單懶人指南，如何修復Windows 11 0X8000ffff錯誤（三大解決法）</u></a></li>
<li><a href="https://win-latest.techidaily.com/cpanel/"><u>CPanelを使用したメールの安全なバックアップ手順とその他の選択肢</u></a></li>
<li><a href="https://win-latest.techidaily.com/expert-tips-on-restoring-lost-data-in-inoperative-external-storage-devices/"><u>Expert Tips on Restoring Lost Data in Inoperative External Storage Devices</u></a></li>
<li><a href="https://win-latest.techidaily.com/harness-instantaneous-database-insights-using-oracle-sql-developers-live-monitoring-feature/"><u>Harness Instantaneous Database Insights Using Oracle SQL Developer's Live Monitoring Feature</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-htc-vive-unveiled-mastering-your-3d-world/"><u>In 2024, HTC Vive Unveiled Mastering Your 3D World</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/next-weeks-new-iphones-optimize-your-charge-with-innovative-anker-accessories-tips-from-zdnet/"><u>Next Week's New iPhones? Optimize Your Charge with Innovative Anker Accessories - Tips From ZDNet!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-issues-with-inactive-mic-on-the-turtle-beach-elite-atlas-controller/"><u>Resolving Issues with Inactive Mic on the Turtle Beach Elite Atlas Controller</u></a></li>
<li><a href="https://program-issues.techidaily.com/success-story-resolving-persistent-black-screen-problems-in-discords-share-feature/"><u>Success Story: Resolving Persistent Black Screen Problems in Discord's Share Feature</u></a></li>
<li><a href="https://win-latest.techidaily.com/techniques-pour-editer-une-brouillon-dun-fichier-microsoft-word-sans-acces-a-la-licence-conseils-exhaustifs/"><u>Techniques Pour Éditer Une Brouillon D'un Fichier Microsoft Word Sans Accès À La Licence : Conseils Exhaustifs</u></a></li>
<li><a href="https://win-latest.techidaily.com/tuto-de-fabrication-dun-peripherique-amovible-amorcable-sous-windows-server-2022-methodes-etape-par-etape/"><u>Tuto De Fabrication D'un Périphérique Amovible Amorçable Sous Windows Server 2022 : Méthodes Étape Par Étape</u></a></li>
<li><a href="https://win-latest.techidaily.com/understanding-the-distinctions-a-guide-to-system-image-recovery-versus-system-restore/"><u>Understanding the Distinctions: A Guide to System Image Recovery versus System Restore</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-from-camera-to-computer-a-beginners-guide-to-editing-canon-videos/"><u>Updated In 2024, From Camera to Computer A Beginners Guide to Editing Canon Videos</u></a></li>
<li><a href="https://win-latest.techidaily.com/1728463452737-windows/"><u>Windows環境における不要ファイルの見つかり方</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037338/7443" target="_top" id="2037338">
  <img src="//a.impactradius-go.com/display-ad/7443-2037338" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037338/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

