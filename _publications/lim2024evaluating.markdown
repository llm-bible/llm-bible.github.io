---
layout: publication
title: 'Evaluating Image Hallucination In Text-to-image Generation With Question-answering'
authors: Youngsun Lim, Hojun Choi, Hyunjung Shim
conference: "Arxiv"
year: 2024
bibkey: lim2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12784"}
tags: ['Agentic', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Multimodal Models']
---
Despite the impressive success of text-to-image (TTI) generation models,
existing studies overlook the issue of whether these models accurately convey
factual information. In this paper, we focus on the problem of image
hallucination, where images created by generation models fail to faithfully
depict factual content. To address this, we introduce I-HallA (Image
Hallucination evaluation with Question Answering), a novel automated evaluation
metric that measures the factuality of generated images through visual question
answering (VQA). We also introduce I-HallA v1.0, a curated benchmark dataset
for this purpose. As part of this process, we develop a pipeline that generates
high-quality question-answer pairs using multiple GPT-4 Omni-based agents, with
human judgments to ensure accuracy. Our evaluation protocols measure image
hallucination by testing if images from existing TTI models can correctly
respond to these questions. The I-HallA v1.0 dataset comprises 1.2K diverse
image-text pairs across nine categories with 1,000 rigorously curated questions
covering various compositional challenges. We evaluate five TTI models using
I-HallA and reveal that these state-of-the-art models often fail to accurately
convey factual information. Moreover, we validate the reliability of our metric
by demonstrating a strong Spearman correlation (\\(\rho\\)=0.95) with human
judgments. We believe our benchmark dataset and metric can serve as a
foundation for developing factually accurate TTI generation models. Additional
resources can be found on our project page: https://sgt-lim.github.io/I-HallA/.
