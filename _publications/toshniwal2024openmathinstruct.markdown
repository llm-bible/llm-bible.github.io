---
layout: publication
title: Openmathinstruct45;1 A 1.8 Million Math Instruction Tuning Dataset
authors: Toshniwal Shubham, Moshkov Ivan, Narenthiran Sean, Gitman Daria, Jia Fei, Gitman Igor
conference: "Arxiv"
year: 2024
bibkey: toshniwal2024openmathinstruct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10176"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Recent work has shown the immense potential of synthetically generated datasets for training large language models (LLMs) especially for acquiring targeted skills. Current large45;scale math instruction tuning datasets such as MetaMathQA (Yu et al. 2024) and MAmmoTH (Yue et al. 2024) are constructed using outputs from closed45;source LLMs with commercially restrictive licenses. A key reason limiting the use of open45;source LLMs in these data generation pipelines has been the wide gap between the mathematical skills of the best closed45;source LLMs such as GPT45;4 and the best open45;source LLMs. Building on the recent progress in open45;source LLMs our proposed prompting novelty and some brute45;force scaling we construct OpenMathInstruct45;1 a math instruction tuning dataset with 1.8M problem45;solution pairs. The dataset is constructed by synthesizing code45;interpreter solutions for GSM8K and MATH two popular math reasoning benchmarks using the recently released and permissively licensed Mixtral model. Our best model OpenMath45;CodeLlama45;70B trained on a subset of OpenMathInstruct45;1 achieves a score of 84.637; on GSM8K and 50.737; on MATH which is competitive with the best gpt45;distilled models. We release our code models and the OpenMathInstruct45;1 dataset under a commercially permissive license.
