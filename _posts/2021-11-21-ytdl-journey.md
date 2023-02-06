---
layout: post
title: ytdl - journey
subtitle: Development of ytdl
thumbnail-img: /assets/img/logo.png
---

## [ytdl](https://github.com/sourabhkv/ytdl) ![output-onlinepngtools](https://user-images.githubusercontent.com/55890376/147201322-7cb830c8-9a47-4bbb-ad0b-d79d4c09b58a.png)
<p align="center">
<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/downloads/sourabhkv/ytdl/total?logo=GitHub">
<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/downloads/sourabhkv/ytdl/latest/total?logo=github"> <a href="https://github.com/sourabhkv/ytdl/blob/main/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/sourabhkv/ytdl"></a>
<a href="https://www.youtube.com/channel/UCdr0BYy90kbqE2AN4GU2-oQ/featured"><img alt="YouTube Channel Views" src="https://img.shields.io/youtube/channel/views/UCdr0BYy90kbqE2AN4GU2-oQ?style=social"></a>
<a href="https://github.com/sourabhkv/ytdl/commits"><img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/sourabhkv/ytdl?color=red&label=Commit" ></a> <a href="https://python.org"><img alt="python" src="https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54" ></a> <a href="https://python.org"><img alt="python" src="https://img.shields.io/badge/c%23-%23239120.svg?style=flat&logo=c-sharp&logoColor=white" ></a> <img alt="Windows" src="https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white" >
</p>
<p align="center">
<a href="https://github.com/sourabhkv/ytdl"><img alt="python" src="https://user-images.githubusercontent.com/55890376/187068580-eabf12eb-cfce-49cb-a026-664087963ffe.png" ></a>
<br>
</p>

### How development started and was carried?
This project development started with wish to download youtube physics video(Center of mass) at 240p in March,2021 because 240p quality was managable and took decent amount of mobile data compared to 360p. Many people don't have technical knowledge of how to use youtube-dl/yt-dlp command line, to make things easier to use (started to port yt-dlp/youtube-dl CLI to GUI) ,I thought of making GUI version of youtube-dl/yt-dlp for those having no knowledge about command line program. Initially it was a very basic program which lack many features as time passed encountered many bugs ; fixed it and added many features ,specially giving the live download progress in main window statusbar took almost 2 months to fix this removing black console window at startup was also challenging to fix without using `--noconsole` option.<br>
Threading helped execute many function at same time The function popens(cmd) never executed with object oriented programming (OOPs) Tkinter was easy to use and took less space compared to PySide2/PyQt5 After june, 2021 there was no update to youtube-dl. Development stopped for 3 months finally backend changed to yt-dlp During this development period many bugs were encountered and fixed , many features were added .Overall this project started in March,2021 and is active since then ,developing it was a journey with ups and downs ultimately it was fun tackling problems and come up with the solution, made me to look a wider perspective of problems and improved my problem solving skills ,hope this project will be active in future... **Need help to make this project better so that anyone with poor internet connctivity can learn something**.<br>

### Working
yt-dlp (youtube-dl for older version) searches streams available in website and displays streams. sometimes there may only be only video stream(s) available or no streams at all.Using VPN might help. User selects streams and browse location (default location in downloads could be changed). ffmpeg converts it into videos/audios. if m4a is selected audio format ffmpeg uses AtomicParsley to write metadata in m4a file. Pygame window displays live download progress (for older version).
Also Linux version work in progress.<br>
**Tools** : ffmpeg , Atomicparsley , yt-dlp , pytube, youtube-dl , powershell , bash , Inno-Setup<br>

### Thanks
Thanks to all contributors
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [ffmpeg](https://ffmpeg.org/ffmpeg.html)
- [Atomicparsley](http://atomicparsley.sourceforge.net/)
- [pytube](http://atomicparsley.sourceforge.net/)