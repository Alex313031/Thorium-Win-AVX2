![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/alex313031/thorium-avx2?label=Version%3A) &nbsp;![GitHub](https://img.shields.io/github/license/alex313031/thorium?color=green&label=License%3A) &nbsp;![GitHub commit activity](https://img.shields.io/github/commit-activity/w/alex313031/thorium-avx2?color=blueviolet&label=Commit%20Activity%3A) &nbsp;![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/ChromiumBrowser?style=social)

# Thorium-AVX2
## Repo to serve AVX2 builds of Thorium!

<img src="https://github.com/Alex313031/Thorium-AVX2/blob/main/ThoriumLogo.png">

 - I made this seperate from my other Thorium repos, to serve AVX2 builds of Thorium and keep them organized and seperated from normal AVX builds.
This repo will primarily host Windows builds, but occasionally I will also put out an AVX2 linux build. NOTE: To build for AVX2 see Building below.

The other Thorium repos :

Main repo that hosts the source code for all platforms and serves linux builds > https://github.com/Alex313031/Thorium

Windows repo that serves windows builds (the source code there is out of date and was merged with the main repo above) > https://github.com/Alex313031/Thorium-Win

Special repo which serves MacOS builds for x64 and M1 ARM64, as well as other architectures like ARM32 for the Raspberry Pi, Tigerlake, SSE4, Bulldozer, and experimental Android builds > https://github.com/Alex313031/Thorium-Special \

Another related project I'm trying to share is my ChromiumOS builds with Codecs, Kernel 5.10, firmware, and extra packages > https://github.com/Alex313031/ChromiumOS

## Building
Follow the building instructions in the main Thorium repo, however copy the 'build' directory in this repo over `//chromium/src/build` after running `./trunk` and `./setup` in the main repo, but of course before compiling.

*Thanks for using Thorium!*

<img src="https://github.com/Alex313031/Thorium/blob/main/logos/STAGING/Thorium90_502.jpg" width="200">
