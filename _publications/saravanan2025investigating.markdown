---
layout: publication
title: 'Investigating Mechanisms For In-context Vision Language Binding'
authors: Darshana Saravanan, Makarand Tapaswi, Vineet Gandhi
conference: "Arxiv"
year: 2025
bibkey: saravanan2025investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22200"}
tags: ['Prompting', 'Multimodal Models']
---
To understand a prompt, Vision-Language models (VLMs) must perceive the image, comprehend the text, and build associations within and across both modalities. For instance, given an 'image of a red toy car', the model should associate this image to phrases like 'car', 'red toy', 'red object', etc. Feng and Steinhardt propose the Binding ID mechanism in LLMs, suggesting that the entity and its corresponding attribute tokens share a Binding ID in the model activations. We investigate this for image-text binding in VLMs using a synthetic dataset and task that requires models to associate 3D objects in an image with their descriptions in the text. Our experiments demonstrate that VLMs assign a distinct Binding ID to an object's image tokens and its textual references, enabling in-context association.
