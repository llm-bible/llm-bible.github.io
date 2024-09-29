---
layout: publication
title: Mmsci A Multimodal Multi-discipline Dataset For Phd-level Scientific Comprehension
authors: Li Zekun, Yang Xianjun, Choi Kyuri, Zhu Wanrong, Hsieh Ryan, Kim Hyeonjung, Lim Jin Hyuk, Ji Sungyoung, Lee Byungju, Yan Xifeng, Petzold Linda Ruth, Wilson Stephen D., Lim Woosang, Wang William Yang
conference: "Arxiv"
year: 2024
bibkey: li2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04903"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The rapid advancement of Large Language Models (LLMs) and Large Multimodal Models (LMMs) has heightened the demand for AI-based scientific assistants capable of understanding scientific articles and figures. Despite progress there remains a significant gap in evaluating models comprehension of professional graduate-level and even PhD-level scientific content. Current datasets and benchmarks primarily focus on relatively simple scientific tasks and figures lacking comprehensive assessments across diverse advanced scientific disciplines. To bridge this gap we collected a multimodal multidisciplinary dataset from open-access scientific articles published in Nature Communications journals. This dataset spans 72 scientific disciplines ensuring both diversity and quality. We created benchmarks with various tasks and settings to comprehensively evaluate LMMs capabilities in understanding scientific figures and content. Our evaluation revealed that these tasks are highly challenging many open-source models struggled significantly and even GPT-4V and GPT-4o faced difficulties. We also explored using our dataset as training resources by constructing visual instruction-following data enabling the 7B LLaVA model to achieve performance comparable to GPT-4V/o on our benchmark. Additionally we investigated the use of our interleaved article texts and figure images for pre-training LMMs resulting in improvements on the material generation task. The source dataset including articles figures constructed benchmarks and visual instruction-following data is open-sourced.
