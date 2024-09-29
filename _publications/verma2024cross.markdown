---
layout: publication
title: Cross45;modal Projection In Multimodal Llms Doesnt Really Project Visual Attributes To Textual Space
authors: Verma Gaurav, Choi Minje, Sharma Kartik, Watson-daniels Jamelle, Oh Sejoon, Kumar Srijan
conference: "Arxiv"
year: 2024
bibkey: verma2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16832"}
tags: ['Applications', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models']
---
Multimodal large language models (MLLMs) like LLaVA and GPT45;4(V) enable general45;purpose conversations about images with the language modality. As off45;the45;shelf MLLMs may have limited capabilities on images from domains like dermatology and agriculture they must be fine45;tuned to unlock domain45;specific applications. The prevalent architecture of current open45;source MLLMs comprises two major modules an image45;language (cross45;modal) projection network and a large language model. It is desirable to understand the roles of these two modules in modeling domain45;specific visual attributes to inform the design of future models and streamline the interpretability efforts on the current models. To this end via experiments on 4 datasets and under 2 fine45;tuning settings we find that as the MLLM is fine45;tuned it indeed gains domain45;specific visual capabilities but the updates do not lead to the projection extracting relevant domain45;specific visual attributes. Our results indicate that the domain45;specific visual attributes are modeled by the LLM even when only the projection is fine45;tuned. Through this study we offer a potential reinterpretation of the role of cross45;modal projections in MLLM architectures. Project webpage https://claws&#45;lab.github.io/projection&#45;in&#45;MLLMs/
