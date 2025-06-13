---
layout: publication
title: 'Textmatch: Enhancing Image-text Consistency Through Multimodal Optimization'
authors: Yucong Luo, Mingyue Cheng, Jie Ouyang, Xiaoyu Tao, Qi Liu
conference: "Arxiv"
year: 2024
bibkey: luo2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.18185"}
  - {name: "Code", url: "https://anonymous.4open.science/r/TextMatch-F55C/"}
tags: ['Efficiency and Optimization', 'Multimodal Models', 'Tools', 'RAG', 'Has Code', 'Prompting', 'In-Context Learning']
---
Text-to-image generative models excel in creating images from text but
struggle with ensuring alignment and consistency between outputs and prompts.
This paper introduces TextMatch, a novel framework that leverages multimodal
optimization to address image-text discrepancies in text-to-image (T2I)
generation and editing. TextMatch employs a scoring strategy powered by large
language models (LLMs) and visual question-answering (VQA) models to evaluate
semantic consistency between prompts and generated images. By integrating
multimodal in-context learning and chain of thought reasoning, our method
dynamically refines prompts through iterative optimization. This process
ensures that the generated images better capture user intent of, resulting in
higher fidelity and relevance. Extensive experiments demonstrate that TextMatch
significantly improves text-image consistency across multiple benchmarks,
establishing a reliable framework for advancing the capabilities of
text-to-image generative models. Our code is available at
https://anonymous.4open.science/r/TextMatch-F55C/.
