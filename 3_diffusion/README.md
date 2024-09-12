# [[M2L2024](https://www.m2lschool.org/home)] Tutorial 3: Diffusion Models

**Authors:** 
[Virginia Aglietti](https://www.linkedin.com/in/virginia-aglietti-a80321a4/?originalSubdomain=uk) and [Ira Ktena](https://www.linkedin.com/in/ira-ktena-phd-12b04b58)

--- 

In this tutorial, we will have a single running colab covering three practicals. Please start with the beginner section of each practical, and then move on to the intermediate section.

## Practical 1: Forward Diffusion Process - Introducing Noise Schedulers

In this practical, you will implement the forward diffusion process where you will design noise schedulers to corrupt the original image to map the image to the noise space, in a tractable manner.

### Outline
- [Beginner] Implement a linear noise schedule. This introduces the process of adding noise to images
- [Intermediate] Replace the linear schedule with a cosine noise schedule
- [Advanced] Implement another noise schedule from the literature

## Practical 2: Backward Diffusion Process - Defining a model architecture

In this practical, you will implement the backward diffusion process where you will design a neural network architecture that will map the noise back to the original image.

### Outline
- [Beginner] Implement a UNet that does not take into account time embeddings
- [Intermediate] Implement a UNet NN with time embeddings

## Practical 3: Inference
In this practical, you will implement algorithms to generate images using a trained diffusion model.

### Outline
- [Beginner] Implement the backward inference process 
- [Intermediate] Improve the backward inference process  using steering


### Notebooks

Tutorial: [![Open In 
Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.sandbox.google.com/github/M2Lschool/tutorials2024/blob/main/3_diffusion/diffusion.ipynb)

Solution: [![Open In 
Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.sandbox.google.com/github/M2Lschool/tutorials2024/blob/main/3_diffusion/diffusion_solved.ipynb)

---
