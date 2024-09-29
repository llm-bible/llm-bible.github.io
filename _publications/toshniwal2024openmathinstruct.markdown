---
layout: publication
title: Openmathinstruct-1 A 1.8 Million Math Instruction Tuning Dataset
authors: Toshniwal Shubham, Moshkov Ivan, Narenthiran Sean, Gitman Daria, Jia Fei, Gitman Igor
conference: "Arxiv"
year: 2024
bibkey: toshniwal2024openmathinstruct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10176"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Recent work has shown the immense potential of synthetically generated datasets for training large language models (LLMs) especially for acquiring targeted skills. Current large-scale math instruction tuning datasets such as MetaMathQA (Yu et al. 2024) and MAmmoTH (Yue et al. 2024) are constructed using outputs from closed-source LLMs with commercially restrictive licenses. A key reason limiting the use of open-source LLMs in these data generation pipelines has been the wide gap between the mathematical skills of the best closed-source LLMs such as GPT-4 and the best open-source LLMs. Building on the recent progress in open-source LLMs our proposed prompting novelty and some brute-force scaling we construct OpenMathInstruct-1 a math instruction tuning dataset with 1.8M problem-solution pairs. The dataset is constructed by synthesizing code-interpreter solutions for GSM8K and MATH two popular math reasoning benchmarks using the recently released and permissively licensed Mixtral model. Our best model OpenMath-CodeLlama-70B trained on a subset of OpenMathInstruct-1 achieves a score of 84.637; on GSM8K and 50.737; on MATH which is competitive with the best gpt-distilled models. We release our code models and the OpenMathInstruct-1 dataset under a commercially permissive license.
