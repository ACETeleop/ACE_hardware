<h1 align="center"> ACE: A Cross-platform Visual-Exoskeletons
for Low-Cost Dexterous Teleoperation </h1>

<p align="center">
    <a href="https://aaronyang1223.github.io/" style="font-size: 20px;">
        Shiqi Yang
    </a>
    ·
    <a href="https://minghuanliu.com" style="font-size: 20px;">
        Minghuan Liu
    </a>
    ·
    <a href="https://yzqin.github.io" style="font-size: 20px;">
        Yuzhe Qin
    </a>
    ·
    <a href="https://dingry.github.io" style="font-size: 20px;">
        Runyu Ding
    </a>
    ·
    <a href="https://ace-teleop.github.io" style="font-size: 20px;">
        Jialong Li
    </a>
    <br>
    <a href="https://chengxuxin.github.io" style="font-size: 20px;">
        Xuxin Cheng
    </a>
    ·
    <a href="https://rchalyang.github.io" style="font-size: 20px;">
        Ruihan Yang
    </a>
    ·
    <a href="https://www.cs.cmu.edu/~shayi/" style="font-size: 20px;">
        Sha Yi
    </a>
    ·
    <a href="https://xiaolonw.github.io" style="font-size: 20px;">
        Xiaolong Wang
    </a>
</p>

<p align="center">
    <img src="./src/UCSanDiegoLogo-BlueGold.png" height="50">
</p>

<p align="center">
<h3 align="center"><a href="https://ace-teleop.github.io/">Website</a> | <a href="http://arxiv.org/abs/2408.11805">arXiv</a> | <a href="https://github.com/ACETeleop/ACETeleop">Software</a> </h3>
  <div align="center"></div>
</p>

<p align="center">
<img src="./src/sim_demo.webp" width="80%"/>
</p>

## Introduction
The repository contains all the hardware for **ACE**. If you have already built your **ACE**, please see https://github.com/ACETeleop/ACETeleop for software setup and usage.

## Modular Structure

ACE is organized into modular parts to simplify assembly and customization. The following parts are currently supported:

- **ARM**: Includes two sizes for flexibility in different use cases.
- **BASE**: Offers both desktop and mobile base options to suit various operational environments.
- **CAM MOUNT**: Two DoF camera mount; note that the left and right mounts are different.
- **LINK**: Encompasses the linkage parts that connect various modules together.
- **SUP**: This part is optional. It provides a better placement for the ACE arm when not in use, and assists with donning and doffing during operation.
- **WRIST**: Includes two sizes. Note that `wrist_1` is best printed with soft material (TPU 95A); if unavailable, this part can be omitted.

Each part has its own folder with the necessary components, making it easy to find and print the required STL files. M stands for mid size, and L stands for large size.

## Assembly Instructions
[![Watch the video](https://img.youtube.com/vi/L7fhZ4woVpM/maxresdefault.jpg)](https://youtu.be/L7fhZ4woVpM)

Complete instructions can be found [here](https://docs.google.com/document/d/1sStEXkSqi03mnFAGhRTtuU14KrGu1ZqmN78boORJfaI/edit#heading=h.yjlslrppv3gx).

## Notes
- The installation of the left and right arms has slight differences; they are symmetrical, so please pay attention.
- If you would like access to the source files (SolidWorks or Onshape), please feel free to contact me.
- If you encounter any issues during assembly, kindly open a GitHub issue.

## Contribution
If you've made any improvements to **ACE**, please contribute by submitting a pull request. Let's make it better together!

## Acknowlegments
This code base refers a lot to many previous amazing works like [BunnyVisionPro](https://github.com/Dingry/bunny_teleop_server), [OpenTeleVision](https://github.com/OpenTeleVision/TeleVision), [GELLO](https://github.com/wuphilipp/gello_software). Also, the codes are built on some superior public project, such as [pinocchio](https://github.com/stack-of-tasks/pinocchio) and [dex-retargeting](https://github.com/dexsuite/dex-retargeting).
