---
layout: publication
title: Pyramid Coder Hierarchical Code Generator for Compositional Visual Question Answering
authors: Shen Ruoyue, Inoue Nakamasa, Shinoda Koichi
conference: "Arxiv"
year: 2024
bibkey: shen2024pyramid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20563"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'Tools', 'Training Techniques']
---
Visual question answering (VQA) is the task of providing accurate answers to natural language questions based on visual input. Programmatic VQA (PVQA) models have been gaining attention recently. These use large language models (LLMs) to formulate executable programs that address questions requiring complex visual reasoning. However there are challenges in enabling LLMs to comprehend the usage of image processing modules and generate relevant code. To overcome these challenges this paper introduces PyramidCoder a novel prompting framework for PVQA models. PyramidCoder consists of three hierarchical levels each serving a distinct purpose query rephrasing code generation and answer aggregation. Notably PyramidCoder utilizes a single frozen LLM and pre-defined prompts at each level eliminating the need for additional training and ensuring flexibility across various LLM architectures. Compared to the state-of-the-art PVQA model our approach improves accuracy by at least 0.5 on the GQA dataset 1.4 on the VQAv2 dataset and 2.9 on the NLVR2 dataset.
