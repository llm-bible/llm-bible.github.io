---
layout: publication
title: Reason Out Your Layout&#58; Evoking The Layout Master From Large Language Models For Text-to-image Synthesis
authors: Chen Xiaohui, Liu Yongfei, Yang Yingxiang, Yuan Jianbo, You Quanzeng, Liu Li-ping, Yang Hongxia
conference: "Arxiv"
year: 2023
bibkey: chen2023reason
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17126"}
tags: ['Attention Mechanism', 'Merging', 'Model Architecture', 'Prompting', 'RAG', 'Transformer']
---
Recent advancements in text-to-image (T2I) generative models have shown remarkable capabilities in producing diverse and imaginative visuals based on text prompts. Despite the advancement these diffusion models sometimes struggle to translate the semantic content from the text into images entirely. While conditioning on the layout has shown to be effective in improving the compositional ability of T2I diffusion models they typically require manual layout input. In this work we introduce a novel approach to improving T2I diffusion models using Large Language Models (LLMs) as layout generators. Our method leverages the Chain-of-Thought prompting of LLMs to interpret text and generate spatially reasonable object layouts. The generated layout is then used to enhance the generated images composition and spatial accuracy. Moreover we propose an efficient adapter based on a cross-attention mechanism which explicitly integrates the layout information into the stable diffusion models. Our experiments demonstrate significant improvements in image quality and layout accuracy showcasing the potential of LLMs in augmenting generative image models.
