---
layout: publication
title: EAGLE Elevating Geometric Reasoning Through Llm45;empowered Visual Instruction Tuning
authors: Li Zhihao, Du Yao, Liu Yang, Zhang Yan, Liu Yufang, Zhang Mengdi, Cai Xunliang
conference: "Arxiv"
year: 2024
bibkey: li2024elevating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11397"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'RAG', 'Tools']
---
Multi45;modal Large Language Models have recently experienced rapid developments and excel in various multi45;modal tasks. However they still struggle with mathematical geometric problem solving which requires exceptional visual perception proficiency. Existing MLLMs mostly optimize the LLM backbone to acquire geometric reasoning capabilities while rarely emphasizing improvements in visual comprehension. In this paper we first investigate the visual perception performance of MLLMs when facing geometric diagrams. Our findings reveal that current MLLMs severely suffer from inaccurate geometric perception and hallucinations. To address these limitations we propose EAGLE a novel two45;stage end45;to45;end visual enhancement MLLM framework designed to ElevAte Geometric reasoning through LLM45;Empowered visual instruction tuning. Specifically in the preliminary stage we feed geometric image45;caption pairs into our MLLM that contains a fully fine45;tuning CLIP ViT and a frozen LLM aiming to endow our model with basic geometric knowledge. In the subsequent advanced stage we incorporate LoRA modules into the vision encoder and unfreeze the LLM backbone. This enables the model to leverage the inherent CoT rationales within question45;answer pairs guiding the MLLM to focus on nuanced visual cues and enhancing its overall perceptual capacity. Moreover we optimize the cross45;modal projector in both stages to foster adaptive visual45;linguistic alignments. After the two45;stage visual enhancement we develop the geometry expert model EAGLE45;7B. Extensive experiments on popular benchmarks demonstrate the effectiveness of our model. For example on the GeoQA benchmark EAGLE45;7B not only surpasses the exemplary G45;LLaVA 7B model by 2.937; but also marginally outperforms the larger G45;LLaVA 13B model. On the MathVista benchmark EAGLE45;7B achieves remarkable 3.837; improvements compared with the proprietary model GPT45;4V.
