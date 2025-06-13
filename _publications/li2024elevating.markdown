---
layout: publication
title: 'EAGLE: Elevating Geometric Reasoning Through Llm-empowered Visual Instruction Tuning'
authors: Zhihao Li, Yao Du, Yang Liu, Yan Zhang, Yufang Liu, Mengdi Zhang, Xunliang Cai
conference: "Arxiv"
year: 2024
bibkey: li2024elevating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.11397'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Multimodal Models', 'Pretraining Methods']
---
Multi-modal Large Language Models have recently experienced rapid
developments and excel in various multi-modal tasks. However, they still
struggle with mathematical geometric problem solving, which requires
exceptional visual perception proficiency. Existing MLLMs mostly optimize the
LLM backbone to acquire geometric reasoning capabilities, while rarely
emphasizing improvements in visual comprehension. In this paper, we first
investigate the visual perception performance of MLLMs when facing geometric
diagrams. Our findings reveal that current MLLMs severely suffer from
inaccurate geometric perception and hallucinations. To address these
limitations, we propose EAGLE, a novel two-stage end-to-end visual enhancement
MLLM framework designed to ElevAte Geometric reasoning through LLM-Empowered
visual instruction tuning. Specifically, in the preliminary stage, we feed
geometric image-caption pairs into our MLLM that contains a fully fine-tuning
CLIP ViT and a frozen LLM, aiming to endow our model with basic geometric
knowledge. In the subsequent advanced stage, we incorporate LoRA modules into
the vision encoder and unfreeze the LLM backbone. This enables the model to
leverage the inherent CoT rationales within question-answer pairs, guiding the
MLLM to focus on nuanced visual cues and enhancing its overall perceptual
capacity. Moreover, we optimize the cross-modal projector in both stages to
foster adaptive visual-linguistic alignments. After the two-stage visual
enhancement, we develop the geometry expert model EAGLE-7B. Extensive
experiments on popular benchmarks demonstrate the effectiveness of our model.
For example, on the GeoQA benchmark, EAGLE-7B not only surpasses the exemplary
G-LLaVA 7B model by 2.9%, but also marginally outperforms the larger G-LLaVA
13B model. On the MathVista benchmark, EAGLE-7B achieves remarkable 3.8%
improvements compared with the proprietary model GPT-4V.
