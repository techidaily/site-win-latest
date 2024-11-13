---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-11-11T00:04:41.787Z
updated: 2024-11-12T18:03:17.085Z
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
<li><a href="https://win-latest.techidaily.com/no-pierdas-tus-datos-como-recuperar-archivos-desaparecidos-de-una-unidad-flash-usb-con-estos-5-pasos-sencillos/"><u>¡No Pierdas Tus Datos! Cómo Recuperar Archivos Desaparecidos De Una Unidad Flash USB Con Estos 5 Pasos Sencillos</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/utorial-purging-your-youtube-download-history-for-2024/"><u>[New] Tutorial Purging Your YouTube Download History for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-vacation-adventures-reimagined-this-years-top-classics-for-2024/"><u>[New] Vacation Adventures Reimagined This Year's Top Classics for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-walking-into-tomorrow-the-premier-vr-treadmills-reviewed-for-2024/"><u>[Updated] Walking Into Tomorrow The Premier VR Treadmills Reviewed for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-grid-gurus-find-the-ultimate-photo-organizing-apps/"><u>2024 Approved Grid Gurus Find the Ultimate Photo Organizing Apps</u></a></li>
<li><a href="https://win-latest.techidaily.com/1728501832122-aomei-backupper/"><u>如何使用AOMEI Backupper創建伺服器映像版本 - 教學課程</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/best-recommended-free-video-player-apps-for-windows-1011-with-universal-file-compatibility/"><u>Best Recommended Free Video Player Apps for Windows 10/11 with Universal File Compatibility</u></a></li>
<li><a href="https://win-latest.techidaily.com/erfolgreiches-backup-fur-das-iphone-die-verwendung-von-itunes-erklart/"><u>Erfolgreiches Backup Für Das iPhone: Die Verwendung Von iTunes Erklärt</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-acquiring-permissions-from-trustedinstaller-for-safe-file-editing/"><u>Guide to Acquiring Permissions From TrustedInstaller for Safe File Editing</u></a></li>
<li><a href="https://win-latest.techidaily.com/optimal-performance-and-cost-to-ssd-or-hdd-for-your-windows-operating-system/"><u>Optimal Performance and Cost: To SSD or HDD for Your Windows Operating System?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/precision-in-capturing-an-expert-obs-skype-guide/"><u>Precision in Capturing An Expert OBS Skype Guide</u></a></li>
<li><a href="https://win-latest.techidaily.com/titre-seo-faites-fonctionner-votre-chiffrement-de-maniere-efficace-sans-attendre-avec-bitlocker-trouvez-des-alternatives-rapides-ici/"><u>Titre SEO : Faites Fonctionner Votre Chiffrement De Manière Efficace Sans Attendre Avec BitLocker - Trouvez Des Alternatives Rapides Ici !</u></a></li>
<li><a href="https://win-latest.techidaily.com/windows-11-bitlocker8/"><u>Windows 11 BitLockerアンチエンクリプション手順：8コツ</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105869/7443" target="_top" id="2105869">
  <img src="//a.impactradius-go.com/display-ad/7443-2105869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

