---
title: Sampling with Diffusion Generative Models Using CLIP
subtitle: 2023 Artificial Intelligence (AI) Project Presentation
date: 2023-12-28
image:
  focal_point: 'center'
---

I worked on a project that involved training a diffusion model to generate images from text.

<!--more-->

**Image Generation Project Using Diffusion Model**

Recently, I worked on a project that involved training a Diffusion Model to generate images from text. The Diffusion Model learns the process of gradually adding noise to existing data until it becomes complete noise. This process is called the forward process, and it allows the model to learn the 𝑞 values between 𝑥_𝑡−1 and 𝑥_𝑡.

In the sampling process, images are generated through the reverse process, where the learned 𝑞 values are used to infer 𝑝 values. However, the generated images are random, so additional techniques are required to create images that align with user preferences. Thus, Diffusion Sampling refers to the sampling process that utilizes the model.



**How to generate an image that the user wants**

In the Diffusion Model, the primary method for generating images that meet user expectations is through the use of guidance. This approach involves providing additional information, represented as 𝑦, about the desired image during the reverse process. By doing so, it helps the model generate images that more closely align with what the user envisions.

In my project, I used CLIP as the classifier for the Diffusion model and sampled the embedding values for each class as 𝑦. For example, when I input "white and red car" as 𝑦 and observed the sampling result, I noticed that the information about the "white and red car" was not properly reflected. Why did such a result occur? I analyzed the cause based on the following three reasons:



Incorrect training of the CLIP/Diffusion Model


The car's color is fixed depending on the composition due to the characteristics of the dataset


The image sizes of the Diffusion model and CLIP are different



It has been truly fascinating to learn various things while working on this project and solving problems through experiments. I plan to keep working hard to further develop it in the future.
