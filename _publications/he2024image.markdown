---
layout: publication
title: Pitvqa Image45;grounded Text Embedding LLM For Visual Question Answering In Pituitary Surgery
authors: He Runlong, Xu Mengya, Das Adrito, Khan Danyal Z., Bano Sophia, Marcus Hani J., Stoyanov Danail, Clarkson Matthew J., Islam Mobarakol
conference: "Arxiv"
year: 2024
bibkey: he2024image
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13949"}
  - {name: "Code", url: "https://github.com/mobarakol/PitVQA"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'Merging', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning']
---
Visual Question Answering (VQA) within the surgical domain utilizing Large Language Models (LLMs) offers a distinct opportunity to improve intra45;operative decision45;making and facilitate intuitive surgeon45;AI interaction. However the development of LLMs for surgical VQA is hindered by the scarcity of diverse and extensive datasets with complex reasoning tasks. Moreover contextual fusion of the image and text modalities remains an open research challenge due to the inherent differences between these two types of information and the complexity involved in aligning them. This paper introduces PitVQA a novel dataset specifically designed for VQA in endonasal pituitary surgery and PitVQA45;Net an adaptation of the GPT2 with a novel image45;grounded text embedding for surgical VQA. PitVQA comprises 25 procedural videos and a rich collection of question45;answer pairs spanning crucial surgical aspects such as phase and step recognition context understanding tool detection and localization and tool45;tissue interactions. PitVQA45;Net consists of a novel image45;grounded text embedding that projects image and text features into a shared embedding space and GPT2 Backbone with an excitation block classification head to generate contextually relevant answers within the complex domain of endonasal pituitary surgery. Our image45;grounded text embedding leverages joint embedding cross45;attention and contextual representation to understand the contextual relationship between questions and surgical images. We demonstrate the effectiveness of PitVQA45;Net on both the PitVQA and the publicly available EndoVis1845;VQA dataset achieving improvements in balanced accuracy of 837; and 937; over the most recent baselines respectively. Our code and dataset is available at https://github.com/mobarakol/PitVQA.
