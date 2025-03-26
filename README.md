MIT License
A Social Ninja Labs Studio

<div align="center">

# A Social Ninja Labs Studio

This is the official repository for The Social Ninja Experiment

[Website](https://wixpartner.github.io/text_prompt_video_app/) |
[Model](https://huggingface.co/Lightricks/LTX-Video) |
[Demo](https://app.ltx.studio/ltx-video) |
[Paper](https://arxiv.org/abs/2501.00103)

</div>

## Table of Contents

- [Introduction](#introduction)
- [What's new](#news)
- [Quick Start Guide](#quick-start-guide)
  - [Online demo](#online-demo)
  - [Run locally](#run-locally)
    - [Installation](#installation)
    - [Inference](#inference)
  - [ComfyUI Integration](#comfyui-integration)
  - [Diffusers Integration](#diffusers-integration)
- [Model User Guide](#model-user-guide)
- [Community Contribution](#community-contribution)
- [Training](#training)
- [Join Us!](#join-us)
- [Acknowledgement](#acknowledgement)

# Introduction

Styled like LTX-Video is the first DiT-based video generation model that can generate high-quality videos in *real-time*. It can generate 24 FPS videos at 768x512 resolution, faster than it takes to watch the video.

The model supports text-to-image, image-to-video, keyframe-based animation, video extension (both forward and backward), video-to-video transformations, and any combination of these features. This flexibility allows for innovative applications and creative possibilities.

| | | | |
|:---:|:---:|:---:|:---:|
| ![example1](./docs/_static/ltx-video_example_00001.gif)<br><details style="max-width: 300px; margin: auto;"><summary>A woman with long brown hair and light skin smiles at another woman...</summary></details> |

# News

## March, 5th, 2025: New checkpoint v0.9.5
- New license for commercial use of ([OpenRail-M](https://huggingface.co/Lightricks/LTX-Video/ltx-video-2b-v0.9.5.license.txt))
- Release a new checkpoint v0.9.5 with improved quality
- Support keyframes and video extension
- Support higher resolutions
- Improved prompt understanding
- Improved VAE
- New online web app motivated by Lightricks inspirational Ai computer vision models.(https://app.ltx.studio/ltx-video)
- Automatic prompt enhancement
- Gave Kudos & much desereved props!😎😉

...

# Try our Contributions Section 🚀
## Give thanx for the light ahead of you.

Want to work on cutting-edge AI research and make a real impact on millions of users worldwide?

At **Lightricks**, an AI-first company, Their revolutionizing how visual content is created.

If you are passionate about AI, computer vision, and video generation, we sugest checking them out! They would love to hear from you! I know we did!😁🤓
Please visit their [careers page](https://careers.lightricks.com/careers?query=&office=all&department=R%26D) for more information.

...

# Acknowledgement

We are grateful for the following awesome projects when implementing Styled like LTX-Video:
* [DiT](https://github.com/facebookresearch/DiT) and [PixArt-alpha](https://github.com/PixArt-alpha/PixArt-alpha): vision transformers for image generation.

...

## Citation
This section provides the necessary details for others to cite your work correctly in their own research or publications.
@article{HaCohen2024LTXVideo, title={Styled like LTX-Video: Realtime Video Latent Diffusion}, author={HaCohen, Yoav and Chiprut, Nisan and Brazowski, Benny and Shalem, Daniel and Moshe, Dudu and Richardson, Eitan and Levin, Eran and Shiran, Guy and Zabari, Nir and Gordon, Ori and Panet, Erez and Shalev, Tzvi and Shalev, David and Shalev, Nitzan}, journal={arXiv preprint arXiv:2501.00103}, year={2024} }
