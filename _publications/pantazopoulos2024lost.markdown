---
layout: publication
title: Lost In Space Probing Fine-grained Spatial Understanding In Vision And Language Resamplers
authors: Pantazopoulos Georgios, Suglia Alessandro, Lemon Oliver, Eshghi Arash
conference: "Arxiv"
year: 2024
bibkey: pantazopoulos2024lost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.13594"}
tags: ['Applications', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
An effective method for combining frozen large language models (LLM) and visual encoders involves a resampler module that creates a visual prompt which is provided to the LLM along with the textual prompt. While this approach has enabled impressive performance across many coarse-grained tasks like image captioning and visual question answering more fine-grained tasks that require spatial understanding have not been thoroughly examined. In this paper we use (textit)diagnostic classifiers to measure the extent to which the visual prompt produced by the resampler encodes spatial information. Our results show that this information is largely absent from the resampler output when kept frozen during training of the classifiers. However when the resampler and classifier are trained jointly we observe a significant performance boost. This shows that the compression achieved by the resamplers can in principle encode the requisite spatial information but that more object-aware objectives are needed at the pretraining stage to facilitate this capability
