---
layout: publication
title: Paragraph45;to45;image Generation With Information45;enriched Diffusion Model
authors: Wu Weijia, Li Zhuang, He Yefei, Shou Mike Zheng, Shen Chunhua, Cheng Lele, Li Yan, Gao Tingting, Zhang Di, Wang Zhongyuan
conference: "Arxiv"
year: 2023
bibkey: wu2023paragraph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.14284"}
tags: ['Applications', 'Fine Tuning', 'Merging', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Text45;to45;image (T2I) models have recently experienced rapid development achieving astonishing performance in terms of fidelity and textual alignment capabilities. However given a long paragraph (up to 512 words) these generation models still struggle to achieve strong alignment and are unable to generate images depicting complex scenes. In this paper we introduce an information45;enriched diffusion model for paragraph45;to45;image generation task termed ParaDiffusion which delves into the transference of the extensive semantic comprehension capabilities of large language models to the task of image generation. At its core is using a large language model (e.g. Llama V2) to encode long45;form text followed by fine45;tuning with LORA to alignthe text45;image feature spaces in the generation task. To facilitate the training of long45;text semantic alignment we also curated a high45;quality paragraph45;image pair dataset namely ParaImage. This dataset contains a small amount of high45;quality meticulously annotated data and a large45;scale synthetic dataset with long text descriptions being generated using a vision45;language model. Experiments demonstrate that ParaDiffusion outperforms state45;of45;the45;art models (SD XL DeepFloyd IF) on ViLG45;300 and ParaPrompts achieving up to 1537; and 4537; human voting rate improvements for visual appeal and text faithfulness respectively. The code and dataset will be released to foster community research on long45;text alignment.
