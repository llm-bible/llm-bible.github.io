---
layout: publication
title: Instruction-following Evaluation through Verbalizer Manipulation
authors: Li Shiyang, Yan Jun, Wang Hai, Tang Zheng, Ren Xiang, Srinivasan Vijay, Jin Hongxia
conference: "Arxiv"
year: 2023
bibkey: li2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.10558"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
While instruction-tuned models have shown remarkable success in various natural language processing tasks accurately evaluating their ability to follow instructions remains challenging. Existing benchmarks primarily focus on common instructions that align well with what the model learned during training. However proficiency in responding to these instructions does not necessarily imply strong ability in instruction following. In this paper we propose a novel instruction-following evaluation protocol called verbalizer manipulation. It instructs the model to verbalize the task label with words aligning with model priors to different extents adopting verbalizers from highly aligned (e.g. outputting postive for positive sentiment) to minimally aligned (e.g. outputting negative for positive sentiment). Verbalizer manipulation can be seamlessly integrated with any classification benchmark to examine the models reliance on priors and its ability to override them to accurately follow the instructions. We conduct a comprehensive evaluation of four major model families across nine datasets employing twelve sets of verbalizers for each of them. We observe that the instruction-following abilities of models across different families and scales are significantly distinguished by their performance on less natural verbalizers. Even the strongest GPT-4 model struggles to perform better than random guessing on the most challenging verbalizer emphasizing the need for continued advancements to improve their instruction-following abilities.
