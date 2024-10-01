---
layout: publication
title: 'Breaking Language Barriers In Multilingual Mathematical Reasoning: Insights And Observations'
authors: Chen Nuo, Zheng Zinan, Wu Ning, Gong Ming, Song Yangqiu, Zhang Dongmei, Li Jia
conference: "Arxiv"
year: 2023
bibkey: chen2023breaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20246"}
tags: ['Few Shot', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
"Existing research predominantly focuses on developing powerful language learning models (LLMs) for mathematical reasoning within monolingual languages, with few explorations in preserving efficacy in a multilingual context. To bridge this gap, this paper pioneers exploring and training powerful Multilingual Math Reasoning (xMR) LLMs. Firstly, by utilizing translation, we construct the first multilingual math reasoning instruction dataset, MGSM8KInstruct, encompassing ten distinct languages, thus addressing the issue of training data scarcity in xMR tasks. Based on the collected dataset, we propose different training strategies to build powerful xMR LLMs, named MathOctopus, notably outperform conventional open-source LLMs and exhibit superiority over ChatGPT in few-shot scenarios. Notably, MathOctopus-13B reaches 47.6&#37; accuracy which exceeds ChatGPT 46.3&#37; on MGSM testset. Beyond remarkable results, we unearth several pivotal observations and insights from extensive experiments: (1) When extending the rejection sampling strategy to the multilingual context, it proves effective for model performances, albeit limited. (2) Employing parallel corpora for math Supervised Fine-Tuning (SFT) across multiple languages not only significantly enhances model performance multilingually but also elevates their monolingual performance. This indicates that crafting multilingual corpora can be regarded as a vital strategy for enhancing model performance in a specific language, especially in mathematical reasoning tasks. For instance, MathOctopus-7B improves its counterparts that trained on English from 42.2&#37; to 50.8&#37; on GSM8K testset."
