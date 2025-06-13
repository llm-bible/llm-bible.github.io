---
layout: publication
title: 'Bootpig: Bootstrapping Zero-shot Personalized Image Generation Capabilities In Pretrained Diffusion Models'
authors: Senthil Purushwalkam, Akash Gokul, Shafiq Joty, Nikhil Naik
conference: "Arxiv"
year: 2024
bibkey: purushwalkam2024bootstrapping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13974"}
tags: ['Agentic', 'Model Architecture', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Recent text-to-image generation models have demonstrated incredible success
in generating images that faithfully follow input prompts. However, the
requirement of using words to describe a desired concept provides limited
control over the appearance of the generated concepts. In this work, we address
this shortcoming by proposing an approach to enable personalization
capabilities in existing text-to-image diffusion models. We propose a novel
architecture (BootPIG) that allows a user to provide reference images of an
object in order to guide the appearance of a concept in the generated images.
  The proposed BootPIG architecture makes minimal modifications to a pretrained
text-to-image diffusion model and utilizes a separate UNet model to steer the
generations toward the desired appearance. We introduce a training procedure
that allows us to bootstrap personalization capabilities in the BootPIG
architecture using data generated from pretrained text-to-image models, LLM
chat agents, and image segmentation models. In contrast to existing methods
that require several days of pretraining, the BootPIG architecture can be
trained in approximately 1 hour. Experiments on the DreamBooth dataset
demonstrate that BootPIG outperforms existing zero-shot methods while being
comparable with test-time finetuning approaches. Through a user study, we
validate the preference for BootPIG generations over existing methods both in
maintaining fidelity to the reference object's appearance and aligning with
textual prompts.
