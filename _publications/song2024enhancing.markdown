---
layout: publication
title: 'Dreamframe: Enhancing Video Understanding Via Automatically Generated QA And Style-consistent Keyframes'
authors: Zhende Song, Chenchen Wang, Jiamu Sheng, Chi Zhang, Shengji Tang, Jiayuan Fan, Tao Chen
conference: "Arxiv"
year: 2024
bibkey: song2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.01422'}
tags: ['Reinforcement Learning', 'Multimodal Models', 'Model Architecture', 'Tools']
---
Recent large vision-language models (LVLMs) for video understanding are primarily fine-tuned with various videos scraped from online platforms. Existing datasets, such as ActivityNet, require considerable human labor for structuring and annotation before effectively utilized for tuning LVLMs. While current LVLMs are primarily trained on existing datasets in broad, general-purpose settings, adapting them to specific downstream scenarios remains challenging, as collecting and annotating task-specific videos is highly labor-intensive and time-consuming. To address this issue, we propose a three-stage framework named DreamFrame for automatically generating style-consistent keyframes and corresponding question-answer (QA) pairs to support LVLM instruction tuning. DreamFrame generates datasets in a movie-like manner. First, we utilize an LLM to generate structured movie plots including movie prior information (like overview and style), frame descriptions and plot-related QA pairs, with a story expansion strategy to mitigate context length limitations.Then, to ensure visual consistency across generated frames, we design a Style Immobilization Process which maintains consistent style through an embedding learning strategy. Finally, frame descriptions and style embeddings are integrated to produce coherent keyframes. Using DreamFrame, we construct a dataset comprising approximately 1k stylized keyframe-like videos and 100k diverse QA pairs. Extensive fine-tuned experiments on various LVLM architectures demonstrate the effectiveness of the proposed dataset. Furthermore, based on the proposed dataset, we fine-tune a new LVLM named DreamFrame-7B, which significantly surpasses the previous similar-sized LVLMs across different benchmarks.
