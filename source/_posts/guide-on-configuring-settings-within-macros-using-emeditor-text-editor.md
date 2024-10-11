---
title: Guide on Configuring Settings Within Macros Using EmEditor Text Editor
date: 2024-10-08T16:06:08.360Z
updated: 2024-10-11T16:52:07.574Z
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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-streamline-your-movie-watching-process-add-subtitles-to-wmp/"><u>[New] 2024 Approved Streamline Your Movie-Watching Process Add Subtitles to WMP</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-tips-for-effective-ppt-sharing-via-google-meet/"><u>[Updated] 2024 Approved Tips for Effective PPT Sharing via Google Meet</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-epochs-epic-journey-best-free-mmo-games-roundup-for-2024/"><u>[Updated] Epoch's Epic Journey Best Free MMO Games Roundup for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-transforming-daily-routine-into-a-social-media-journey-on-fb-for-2024/"><u>[Updated] Transforming Daily Routine Into a Social Media Journey on FB for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-digital-duo-dynamics-joining-instagram-and-tiktok-powerfully/"><u>2024 Approved Digital Duo Dynamics Joining Instagram and TikTok Powerfully</u></a></li>
<li><a href="https://data-wizards.techidaily.com/efficient-web-tools-to-mend-video-streams/"><u>Efficient Web Tools to Mend Video Streams</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-itel-a60-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Itel A60 Pattern Lock Screen</u></a></li>
<li><a href="https://win-latest.techidaily.com/get-your-favorite-episodes-from-9now-with-ease-formerly-known-as-9jumpin-downloader/"><u>Get Your Favorite Episodes From 9Now with Ease, Formerly Known as 9Jumpin Downloader!</u></a></li>
<li><a href="https://win-latest.techidaily.com/get-your-oracle-training-materials-free-course-downloads-and-educational-videos/"><u>Get Your Oracle Training Materials: Free Course Downloads and Educational Videos</u></a></li>
<li><a href="https://win-latest.techidaily.com/guide-downloading-nfhs-network-videos-efficiently-on-pc-and-macos/"><u>Guide: Downloading NFHS Network Videos Efficiently on PC & macOS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-quick-start-guide-making-your-gifs-count-as-emoji-stickers-in-telegram/"><u>In 2024, Quick-Start Guide Making Your GIFS Count as Emoji Stickers in Telegram</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-memes-kinemaster-guide/"><u>Mastering Memes KineMaster Guide</u></a></li>
<li><a href="https://win-latest.techidaily.com/multi-format-audio-converter-change-caf-files-into-wav-mp3-m4a-aiff-aac-with-just-one-tool/"><u>Multi-Format Audio Converter: Change CAF Files Into WAV, MP3, M4A, AIFF, AAC with Just One Tool</u></a></li>
<li><a href="https://win-latest.techidaily.com/securely-transfer-hot-movies-and-porn-from-mofos-as-high-quality-videos-mp4-mov-avi/"><u>Securely Transfer Hot Movies and Porn From Mofos as High-Quality Videos (MP4, MOV, AVI)</u></a></li>
<li><a href="https://win-latest.techidaily.com/step-by-step-guide-downloading-content-from-kissasianes/"><u>Step-by-Step Guide: Downloading Content From KissAsian.es</u></a></li>
<li><a href="https://win-latest.techidaily.com/step-by-step-process-of-downloading-and-transforming-raywenderlich-series-from-video-to-mp4-or-mov-on-windowsmac-os/"><u>Step-by-Step Process of Downloading and Transforming Raywenderlich Series From Video to MP4 or MOV on Windows/Mac OS</u></a></li>
<li><a href="https://win-latest.techidaily.com/step-by-step-tutorial-for-accessing-nfhs-training-footage-on-both-mac-and-windows/"><u>Step-by-Step Tutorial for Accessing NFHS Training Footage on Both Mac and Windows</u></a></li>
<li><a href="https://win-latest.techidaily.com/top-4-lynda-replacements-offering-quality-skills-training/"><u>Top 4 Lynda Replacements Offering Quality Skills Training</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-make-unforgettable-video-invitations-with-these-mobile-apps/"><u>Updated Make Unforgettable Video Invitations with These Mobile Apps</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

