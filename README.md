<h2 align="center"><img src="./figures/moonstep.png" alt="Moonstep logo" style="height: 1em; vertical-align: middle;"> One Small Step in Latent, One Giant Leap for Pixels:<br>Fast Latent Upscale Adapter for Your Diffusion Models</h2>

<div align="center">
<a href="https://razinaleksandr.github.io/" target="_blank">Aleksandr Razin</a><sup>*</sup> ·
<a href="https://www.linkedin.com/in/danil-kazancev/" target="_blank">Danil Kazantsev</a><sup>*</sup> ·
<a href="https://www.linkedin.com/in/iamakarov/" target="_blank">Ilya Makarov</a>
</div>

<p align="center">
<a href="https://github.com/vaskers5/LUA" target="_blank"><img src="https://img.shields.io/badge/Project-Page-blue" alt="Project Page"></a>
<a href="https://arxiv.org/abs/2511.10629" target="_blank"><img src="https://img.shields.io/badge/arXiv-PDF-b31b1b" alt="arXiv"></a>
<a href="https://huggingface.co/papers/2511.10629" target="_blank"><img src="https://img.shields.io/badge/HuggingFace-Paper-orange" alt="HuggingFace Paper"></a>
</p>

This repository contains the official implementation of the paper "One Small Step in Latent, One Giant Leap for Pixels: Fast Latent Upscale Adapter for Your Diffusion Models".

We present the Latent Upscaler Adapter (LUA), a lightweight module that performs super-resolution directly on the generator’s latent code before the final VAE decoding step. LUA integrates as a drop-in component, requiring no modifications to the base model or additional diffusion stages. It enables high-resolution synthesis through a single feed-forward pass in latent space, achieving comparable perceptual quality to pixel-space methods while reducing decoding and upscaling time.

<div align="center">
<img src="./figures/figure_2.png" alt="Teaser" width="80%">
</div>

<hr style="border: 0; height: 1px; background: linear-gradient(90deg, transparent, #ccc, transparent); margin: 2rem 0;">

<p align="center"><i>The code for this paper will be released here soon.</i></p>
