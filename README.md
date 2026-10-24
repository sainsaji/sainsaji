<div align="center">

<img src="banner.svg" width="100%" alt="Sain Saji - PS5 media, GPU, reverse engineering"/>

<br/>

![Followers](https://img.shields.io/github/followers/sainsaji?style=for-the-badge&color=0070f3&labelColor=050816)
![EVO Player stars](https://img.shields.io/github/stars/sainsaji/EVO-PLAYER-PS5?style=for-the-badge&label=EVO%20Player%20stars&color=ff2d9b&labelColor=050816)
![Profile views](https://komarev.com/ghpvc/?username=sainsaji&style=for-the-badge&color=7c3aed&label=VIEWS)

</div>

## 👋 About me

I build low-level media and graphics software for the PS5. I work close to the hardware: GPU command buffers, hardware video decoders, audio output and shaders. I also reverse engineer system libraries to find out how the console really does things, then write it up so others can use it.

## 🎬 EVO Player

[**EVO-PLAYER-PS5**](https://github.com/sainsaji/EVO-PLAYER-PS5) is a native media player for jailbroken PS5 (firmware 12.70), shipped as an app module. It is written in C++ against the PS5 Payload SDK.

| | |
|---|---|
| **Video** | Hardware decode through `sceVideodec2`, with an FFmpeg fallback. 4K HEVC Main10 and AV1 work. |
| **Audio** | Bitstream passthrough (AC-3) straight to your receiver. |
| **Picture** | GPU upscaling with FSR1 and Anime4K, in several quality levels. |
| **UI** | Its own screens, drawn on bare-metal `sceAgc` with RmlUi. No system UI toolkit. |
| **Sources** | Built-in IPTV, Xtream, Emby, Jellyfin, Stremio and Nuvio providers. |
| **Tooling** | Remote control over the network, a host-side UI renderer, and a Docker toolchain for repeatable builds. |

## 🔬 Research

- [**PS5-Audio-Passthrough-Research**](https://github.com/sainsaji/PS5-Audio-Passthrough-Research): how to send raw Dolby and DTS audio from a PS5 app to a receiver.
- [**ps5-upscalar-research**](https://github.com/sainsaji/ps5-upscalar-research): notes and tools on upscaling on the PS5 GPU.

## 🧰 Other projects

- [**ColabBlenderRender**](https://github.com/sainsaji/ColabBlenderRender): render Blender scenes on Google Colab.
- [**ESP32_Simulator**](https://github.com/sainsaji/ESP32_Simulator): an ESP32 simulator in C++.
- [**MPC-BE**](https://github.com/sainsaji/MPC-BE): my fork of the Windows media player.

## 🛠️ Tech

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Focus areas:** video and audio decode, GPU rendering (sceAgc, shaders), reverse engineering, homebrew and embedded.

## 📫 Reach me

Open an issue on any repo above, or email [sain.sajix@gmail.com](mailto:sain.sajix@gmail.com).

<div align="center">

<sub>If EVO Player is useful to you, a star on the repo helps a lot.</sub>

</div>
