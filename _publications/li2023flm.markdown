---
layout: publication
title: FLM-101B&#58; An Open LLM And How To Train It With $100K Budget
authors: Li Xiang, Yao Yiqun, Jiang Xin, Fang Xuezhi, Meng Xuying, Fan Siqi, Han Peng, Li Jing, Du Li, Qin Bowen, Zhang Zheng, Sun Aixin, Wang Yequan
conference: "Arxiv"
year: 2023
bibkey: li2023flm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03852"}
  - {name: "Code", url: "https://huggingface.co/CofeAI/FLM-101B"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Training Techniques']
---
Large language models (LLMs) have achieved remarkable success in NLP and multimodal tasks among others. Despite these successes two main challenges remain in developing LLMs (i) high computational cost and (ii) fair and objective evaluations. In this paper we report a solution to significantly reduce LLM training cost through a growth strategy. We demonstrate that a 101B-parameter LLM with 0.31T tokens can be trained with a budget of 100K US dollars. Inspired by IQ tests we also consolidate an additional range of evaluations on top of existing evaluations that focus on knowledge-oriented abilities. These IQ evaluations include symbolic mapping rule understanding pattern mining and anti-interference. Such evaluations minimize the potential impact of memorization. Experimental results show that our model named FLM-101B trained with a budget of 100K US dollars achieves performance comparable to powerful and well-known models e.g. GPT-3 and GLM-130B especially on the additional range of IQ evaluations. The checkpoint of FLM-101B is released at https://huggingface.co/CofeAI/FLM-101B."
