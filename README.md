- [MoneyPrinterPlus](#moneyprinterplus)
- [Video Tutorial](#Video Tutorial)
- [Interface Overview](#Interface Overview)
- [Implemented Functions](#Implemented Functions)
- [Functions to be implemented](#Functions to be implemented)
- [Example Demonstration](#Example Demonstration)
- [How to use](#How to use)
- [Environmental Requirements](#Environmental Requirements)
- [Installation](#Installation)
- [Run](#Run)
- [Basic Configuration](#Basic Configuration)
- [AI Video](#ai Video)
- [Generate Video Copy](#Generate Video Copy)
- [Video Dubbing and Background Music](#Video Dubbing and Background Music)
- [Video Configuration](#Video Configuration)
- [Subtitle Configuration](#Subtitle Configuration)
- [Generate Video](#Generate Video)
- [Common Problems and Solutions](#Common Problems and Solutions)
- [Discussion Group](#Discussion Group)
- [Series of Tutorials](#Series of Tutorials)

# MoneyPrinterPlus

This is a project that makes money easily.

In the era of short videos, whoever controls the traffic controls the money!

So I share this carefully crafted MoneyPrinter project with you.

**It can: use AI big model technology to batch generate various short videos with one click. **

**It can: mix and cut short videos with one click, batch generating short videos is not a dream. **

**It can: automatically publish videos to Douyin, Kuaishou, Xiaohongshu, and Video Account. **

Making money has never been so easy!

If you find it useful, please give me a star! ![Github stars](https://img.shields.io/github/stars/ddean2009/MoneyPrinterPlus.svg)

# Video tutorial

## Brief introduction

https://www.bilibili.com/video/BV16VVGefEp1/?spm_id_from=333.999.0.0&vd_source=a563b6c970df6e7665845c15089bd618

## Detailed introduction

https://www.bilibili.com/video/BV1JKgYe5ERF/?pop_share=1&vd_source=a563b6c970df6e7665845c15089bd618

## Introduction to batch short video generation

https://www.bilibili.com/video/BV1v43eekECn/?spm_id_from=333.999.0.0&vd_source=a563b6c970df6e7665845c15089bd618

# Graphic series tutorials

[Introduction to moneyPrinterPlus](https://mp.weixin.qq.com/s/0p9T_WFJ_yXcj74TgI7iMw)

[Detailed tutorial on how to use moneyPrinterPlus](https://mp.weixin.qq.com/s/fAdws2grcZknG8VLQfjMjg)

[Detailed configuration tutorial on how to use moneyPrinterPlus Alibaba Cloud](https://mp.weixin.qq.com/s?__biz=MzIxMTI0NzcyMQ==&mid=2650935498&idx=1&sn=7d29a350f36e14686252e9a22d8fce23&chksm=8cae87ccbbd90edaea45b595ec4028b91e464061c0a 2f37f1f15e97f593fd7b51edba765ed6e&cur_album_id=1821975747683532806&scene=189#wechat_redirect)

[moneyPrinterPlus Tencent Cloud detailed configuration and usage tutorial](https://mp.weixin.qq.com/s/VaI-Fy7dDz9dlW5tGM4mhg)

[moneyPrinterPlus Microsoft Cloud detailed configuration and usage tutorial](https://mp.weixin.qq.com/s/4p6MuDcwIurpVwkcQlWoDA)

[Heavy! Free one-click batch mixing tool is here, tens of thousands of short videos a day is not a dream](https://mp.weixin.qq.com/s/gUB18fTwRUvo9dSgk0DXLg)

# Interface Overview

## 1. AI Video Batch Mixing Tool

![image-20240628153020140](https://flydean-1301049335.cos.ap-guangzhou.myqcloud.com/img/202406281530983.png)

Introduction:
[Heavy! Free one-click batch mixing tool is here, tens of thousands of short videos a day is not a dream](https://mp.weixin.qq.com/s/gUB18fTwRUvo9dSgk0DXLg)

## 2. AI Video Generator

![image-20240628153041166](https://flydean-1301049335.cos.ap-guangzhou.myqcloud.com/img/202406281530864.png)

## 3. Batch Video Automatic Upload Tool

![](auto_video_publish.gif)

# Update Preview

* Video Mixing Function is Now Available! ! ! !

* This week, we will consider launching the video automatic publishing tool, so stay tuned! ! ! !

# Update List

- 20240628 Major Update! Support batch video mixing, batch generate a large number of non-repetitive short videos!!!!!!

- 20240620 Optimize the video synthesis effect to make the video end more natural.

- 20240619 Voice recognition and voice synthesis **support Tencent Cloud**. Need to enable Tencent Cloud speech synthesis and speech recognition
- 20240615 Speech recognition and speech synthesis **support Alibaba Cloud**. Need to enable Alibaba Cloud intelligent voice interaction function--must enable speech synthesis and recording file recognition (fast version)
- 20240614 Resource library supports pixabay, supports voice audition function, and fixes some bugs

# Implemented functions

- [x] Batch video mixing, batch output of a large number of non-repetitive short videos
- [x] Support local material selection (support various materials mp4, jpg, png), support various resolutions.
- [x] Large model access to OpenAI, Azure, Kimi, Qianfan, Baichuan, Tongyi Qwen, DeepSeek,
- [x] Support **Azure** voice function
- [x] Support **Alibaba Cloud** voice function
- [x] Support **Tencent Cloud** voice function
- [x] Support 100+ different voice types
- [x] Support voice audition function
- [x] Support 30+ types of **video transition effects**
- [x] Support video generation of different resolutions, sizes and ratios
- [x] Support voice selection and speech speed adjustment
- [x] Support background music
- [x] Support background music volume adjustment
- [x] Support custom subtitles
- [x] Cover the mainstream AI large model tools on the market

# Functions to be implemented

- [] Support local voice and subtitle recognition model
- [] Support more ways to obtain video resources
- [] Support more video transition effects
- [] Support more subtitle effects
- [] Videos are automatically published in batches to various video platforms
- [] Access stable diffusion, AI image generation, and synthetic video
- [] Access Sora and other AI video large model tools to automatically generate videos

# Example display

<table>
<thead>
<tr>
<th align="center">Vertical screen</th>
<th align="center">Horizontal screen</th>
<th align="center">Square</th>
</tr>
</thead>
<tr>
<td align="center"><video src="https://github.com/ddean2009/MoneyPrinterPlus/assets/13955545/d96e5e50-cfe7-4f55-a0db-75f3ac28b39f"></video></td>
<td align="center"><video src="https://github.com/ddean2009/MoneyPrinterPlus/assets/13955545/714b122d-d857-4132-bdd3-9f07c9aa787b"></video></td>
<td align="center"><video src="https://github.com/ddean2009/MoneyPrinterPlus/assets/13955545/2ec748c2-8145-4178-ae48-a3114290addd"></video></td>
</tr>
</table>

# Usage

## Environment requirements

- Python 3.10+
- ffmpeg 6.0+
- LLM api key
- Azure Speech Service (https://speech.microsoft.com/portal)
- Or Alibaba Cloud Intelligent Voice Function (https://nls-portal.console.aliyun.com/overview)
- Or Tencent Cloud Voice Technology Function (https://console.cloud.tencent.com/asr)

> Remember! ! ! ! ! Be sure to install ffmpeg and add the ffmpeg path to the environment variable.

## Installation

1. Make sure you have a Python 3.10+ operating environment. If it is Windows, make sure the python path has been installed and added to PATH.
2. Make sure you have a ffmpeg 6.0+ operating environment. If it is Windows, make sure the ffmpeg path has been installed and added to PATH. Friends who have not installed ffmpeg, please install the corresponding version through https://ffmpeg.org/.
3. If both python and ffmpeg environments are available. Then you can install the dependency package through pip.

```bash
pip install -r requirements.txt
```

## Run

Use the following command to run the program:

```bash
streamlit run gui.py
```

You can see the log information of the program running in the log file.

There is a browser address in it, and you can access the program by opening this address through the browser.

After opening, you will see the following interface:

![image-20240612135131890](https://flydean-1301049335.cos.ap-guangzhou.myqcloud.com/img/202406121351010.png)

There are currently three configurations on the left, namely basic configuration, AI video and mixed video (under development).

### Basic configuration

#### 1. Resource library

Current resource support:

* pexels: [www.pexels.com](https://www.pexels.com/) **Pexels** is a world-renowned free image and video material website.

* pixabay: [pixabay.com](https://pixabay.com/)

You need to register a key on the corresponding website to implement API calls.

> Other resource libraries will be added in the future. Such as ([videvo.net](https://www.videvo.net), [videezy.com](https://www.videezy.com), etc.)
>
>

#### 2. Audio library

Currently, text-to-speech and speech recognition functions support:

1. Azure's cognitive-services service.
2. Alibaba Cloud's intelligent voice interaction
3. Tencent Cloud voice technology function (https://console.cloud.tencent.com/asr)

* Azure:

You need to register a key at https://speech.microsoft.com/portal.

Azure is free for new users for 1 year. The cost is also relatively cheap.

* Alibaba Cloud:

You need to activate the service at https://nls-portal.console.aliyun.com/overview and add a project.

Need to activate
