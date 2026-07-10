# StormBreaker Kernel for ASUS Zenfone Max M1 (X00P/X00PD)
![SB](/kernels/sb/assets/img/sb.jpg "SB")

> ***Disclaimer***
>
> *Your warranty is now void. We're not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed. Please do some research if you have any concerns about features included in this KERNEL before flashing it! YOU are choosing to make these modifications, and if you point the finger at us for messing up your device, we will laugh at you.*

## Introduction

StromBreaker kernel is a minimal, simple and clean kernel for the perfect balance between performance and battery life.

## Installation Instructions
- Flash zip using recovery.
- Wipe cache (_optional_)
- Reboot to system

## Downloads

| Version  | Build Date | Status   | Maintainer                                 | Downloads |
| :------- | :--------- | :------- | :----------------------------------------- | :-------- |
| 3.18-2.0 | 07/06/2020 | OFFICIAL | [@danascape](https://github.com/danascape) | [Sourceforge](https://sourceforge.net/projects/stormbreakerdevices/files/X00P/Stormbreaker-3.18-2.0-20200607-1807.zip/download)<br/> [Internet Archive](https://archive.org/download/x00p-archive/kernels/sb/Stormbreaker-3.18-2.0-20200607-1807.zip)

<details><summary><strong>Changelog</strong></summary>

- Kernel built with proton clang 11, lto enabled
- Merged April AOSP changes 
- Fixed up CPUidle and stuff 

</details>
<br/>

| Version  | Build Date | Status   | Maintainer                                 | Downloads |
| :------- | :--------- | :------- | :----------------------------------------- | :-------- |
| 3.18-2.0 | 29/06/2020 | OFFICIAL | [@danascape](https://github.com/danascape) | [Sourceforge](https://sourceforge.net/projects/stormbreakerdevices/files/X00P/Stormbreaker-3.18-2.0-20200629-1657.zip/download)<br/> [Internet Archive](https://archive.org/download/x00p-archive/kernels/sb/Stormbreaker-3.18-2.0-20200629-1657.zip)

<details><summary><strong>Changelog</strong></summary>

- EAS as base.
- Introduce s2idle to fix idle drain
- Backport RCU sync, perf
- Backport more rcu stuff 
- Backport CPU cooling thermals from 4.9

</details>

## Credits

Special thanks to [@danascape](https://github.com/danascape) as maintainer and contributor of [StormBreaker Kernel](https://github.com/stormbreaker-project) who helped the ASUS Zenfone Max M1 alive throughout the Android development community.

This archive simply preserves their work for future.