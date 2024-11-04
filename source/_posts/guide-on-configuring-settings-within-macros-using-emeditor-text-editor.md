---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-11-02T21:42:58.985Z
updated: 2024-11-04T00:43:16.505Z
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-technique-for-anonymous-footage-via-image-smoothing/"><u>[New] 2024 Approved Technique for Anonymous Footage via Image Smoothing</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-superior-green-tech-in-video-production-for-2024/"><u>[New] Superior Green Tech in Video Production for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-full-screen-pro-excellence-4-precise-pc-and-mac-tools/"><u>[Updated] Full Screen Pro Excellence 4 Precise PC & Mac Tools</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-realme-v30-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Realme V30 PC | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-guide-to-prolonging-gopro-power-source-lifespan/"><u>A Guide to Prolonging GoPro Power Source Lifespan</u></a></li>
<li><a href="https://extra-resources.techidaily.com/finding-cost-effective-buys-on-gopros/"><u>Finding Cost-Effective Buys on GoPros</u></a></li>
<li><a href="https://win-latest.techidaily.com/fix-your-synology-cloud-sync-problems-today-all-documents-now-up-to-date/"><u>Fix Your Synology Cloud Sync Problems Today! All Documents Now Up-to-Date</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-nubia-red-magic-9-proplus-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Nubia Red Magic 9 Pro+ to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://win-latest.techidaily.com/la-top-lista-di-programmi-per-il-ripristino-e-la-manutenzione-dei-disco-solidi-adata/"><u>La Top Lista Di Programmi per Il Ripristino E La Manutenzione Dei Disco Solidi Adata</u></a></li>
<li><a href="https://win-latest.techidaily.com/page-unavailable-error-code-n-404/"><u>Page Unavailable - Error Code N° 404</u></a></li>
<li><a href="https://win-latest.techidaily.com/set-up-auto-purge-for-expired-backups-on-windows-server-systems/"><u>Set Up Auto-Purge for Expired Backups on Windows Server Systems</u></a></li>
<li><a href="https://win-latest.techidaily.com/simple-solutions-restore-windows-11s-defender-functionality-in-three-steps/"><u>Simple Solutions: Restore Windows 11'S Defender Functionality in Three Steps</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/the-ultimate-screen-recorders-guide-trusted-recommendations-for-2024/"><u>The Ultimate Screen Recorders Guide - Trusted Recommendations for 2024</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-itel-a60-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Itel A60</u></a></li>
<li><a href="https://win-latest.techidaily.com/top-rated-100-free-file-recovery-apps-how-to-safely-get-and-install-on-windows-1110/"><u>Top Rated 100% Free File Recovery Apps: How to Safely Get and Install on Windows 11/10</u></a></li>
<li><a href="https://win-latest.techidaily.com/undrukkan-gratis-pemulihan-file-windows-11-dan-10-kumpulkan-semua-hiburan/"><u>Undrukkan Gratis: Pemulihan File Windows 11 Dan 10 - Kumpulkan Semua Hiburan</u></a></li>
<li><a href="https://win-latest.techidaily.com/user-friendly-and-streamlined-backup-solutions-for-vmware-vsphere-basics/"><u>User-Friendly & Streamlined Backup Solutions for VMware vSphere Basics</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151893/7443" target="_top" id="2151893">
  <img src="//a.impactradius-go.com/display-ad/7443-2151893" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151893/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

