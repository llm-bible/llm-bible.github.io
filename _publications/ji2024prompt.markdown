---
layout: publication
title: 'Prompt-a-video: Prompt Your Video Diffusion Model Via Preference-aligned LLM'
authors: Yatai Ji, Jiacheng Zhang, Jie Wu, Shilong Zhang, Shoufa Chen, Chongjian Ge, Peize Sun, Weifeng Chen, Wenqi Shao, Xuefeng Xiao, Weilin Huang, Ping Luo
conference: "Arxiv"
year: 2024
bibkey: ji2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15156"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Text-to-video models have made remarkable advancements through optimization
on high-quality text-video pairs, where the textual prompts play a pivotal role
in determining quality of output videos. However, achieving the desired output
often entails multiple revisions and iterative inference to refine
user-provided prompts. Current automatic methods for refining prompts encounter
challenges such as Modality-Inconsistency, Cost-Discrepancy, and Model-Unaware
when applied to text-to-video diffusion models. To address these problem, we
introduce an LLM-based prompt adaptation framework, termed as Prompt-A-Video,
which excels in crafting Video-Centric, Labor-Free and Preference-Aligned
prompts tailored to specific video diffusion model. Our approach involves a
meticulously crafted two-stage optimization and alignment system. Initially, we
conduct a reward-guided prompt evolution pipeline to automatically create
optimal prompts pool and leverage them for supervised fine-tuning (SFT) of the
LLM. Then multi-dimensional rewards are employed to generate pairwise data for
the SFT model, followed by the direct preference optimization (DPO) algorithm
to further facilitate preference alignment. Through extensive experimentation
and comparative analyses, we validate the effectiveness of Prompt-A-Video
across diverse generation models, highlighting its potential to push the
boundaries of video generation.
