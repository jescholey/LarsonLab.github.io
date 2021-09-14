---
layout: post
title:  "AI-generated Art and MRI"
author: peder
categories: [ fun ]
image: assets/images/HPBrain_MRI-Spaceship-7.png
featured:true
---
I recently went off on an exploration of generating images and art using AI, specifically generative adversarial networks (GANs).  This was first inspired by a twitter feed, https://twitter.com/images_ai?lang=en, where they provide a nice Google Colab notebook.

This method is based on text-to-image translation, so the generated art is seeding by text prompts.  The image can be gnereated starting with some random image, but also can use a seed image to guide the art.

The specific approach is "VQGAN+CLIP", which I haven't delved too deeply into, but is a text-to-image model that can produce very high resolution outputs.  More details here https://alexasteinbruck.medium.com/vqgan-clip-how-does-it-work-210a5dca5e52

So I began playing around with the CoLab notebook, here's a few fun explorations:

## MRI Spaceship

In these examples, I used a random image seed, with the prompt "MRI Spaceship".  The difference is based on the image training data (Wikiart versus ImageNet)

![MRI spaceship](../assets/images/MRI-spaceship-1.png)

![MRI spaceship](../assets/images/MRI-spaceship-2.png)

## Seeding with MRIs - Hyperpolarized Brain

Then, I tried started with this seed image

![Hyperpolarized 13C Brain MRI](../assets/images/HPBrainExample-crop.png)

And the prompt "MRI Spaceship".  The image evolved as

![Hyperpolarized 13C Brain MRI Spaceship 1](../assets/images/HPBrain_MRI-Spaceship-1.png)
![Hyperpolarized 13C Brain MRI Spaceship 2](../assets/images/HPBrain_MRI-Spaceship-2.png)
![Hyperpolarized 13C Brain MRI Spaceship 3](../assets/images/HPBrain_MRI-Spaceship-3.png)
![Hyperpolarized 13C Brain MRI Spaceship 4](../assets/images/HPBrain_MRI-Spaceship-4.png)
![Hyperpolarized 13C Brain MRI Spaceship 5](../assets/images/HPBrain_MRI-Spaceship-5.png)
![Hyperpolarized 13C Brain MRI Spaceship 6](../assets/images/HPBrain_MRI-Spaceship-6.png)
![Hyperpolarized 13C Brain MRI Spaceship 7](../assets/images/HPBrain_MRI-Spaceship-7.png)


I also tried with a prompt of something like "Moon | Volcano", but using WikiArt training:

![Hyperpolarized 13C Brain Volcano Moon](../assets/images/HPBrain_volcano-moon.png)

## Seeding with MRIs - Prostate Diffusion

This was getting fun, so I started with this seed image of a prostate diffusion weighted image:

![Prostate DWI](../assets/images/prostateDWI-input.png)

**"The moon has roots"**

![The Moon Has Roots](../assets/images/prostateDWI_The-moon-has-roots-1.png)

**"The moon has roots"**

![The Moon Has Roots](../assets/images/prostateDWI_The-moon-has-roots-2.png)

**"Moon Carrot"**

![Moon Carrot](../assets/images/prostateDWI_moon-carrot-wikiart.png)

**"Vegetables Under the Moon"**

![Vegetables under the moon](../assets/images/prostateDWI_Vegetables-under-the-moon.png)
