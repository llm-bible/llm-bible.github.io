---
layout: publication
title: MAQA A Multimodal QA Benchmark for Negation
authors: Li Judith Yue, Jansen Aren, Huang Qingqing, Lee Joonseok, Ganti Ravi, Kuzmin Dima
conference: "Arxiv"
year: 2023
bibkey: li2023maqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.03238"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Multimodal learning can benefit from the representation power of pretrained Large Language Models (LLMs). However state-of-the-art transformer based LLMs often ignore negations in natural language and there is no existing benchmark to quantitatively evaluate whether multimodal transformers inherit this weakness. In this study we present a new multimodal question answering (QA) benchmark adapted from labeled music videos in AudioSet (Gemmeke et al. 2017) with the goal of systematically evaluating if multimodal transformers can perform complex reasoning to recognize new concepts as negation of previously learned concepts. We show that with standard fine-tuning approach multimodal transformers are still incapable of correctly interpreting negation irrespective of model size. However our experiments demonstrate that augmenting the original training task distributions with negated QA examples allow the model to reliably reason with negation. To do this we describe a novel data generation procedure that prompts the 540B-parameter PaLM model to automatically generate negated QA examples as compositions of easily accessible video tags. The generated examples contain more natural linguistic patterns and the gains compared to template-based task augmentation approach are significant.
