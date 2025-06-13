---
layout: publication
title: 'In-context Demonstration Matters: On Prompt Optimization For Pseudo-supervision Refinement'
authors: Zhen-yu Zhang, Jiandong Zhang, Huaxiu Yao, Gang Niu, Masashi Sugiyama
conference: "Arxiv"
year: 2024
bibkey: zhang2024demonstration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03124"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
Large language models (LLMs) have achieved great success across diverse tasks, and fine-tuning is sometimes needed to further enhance generation quality. Most existing methods rely on human supervision or parameter retraining, both of which are costly in terms of data collection and computational resources. To handle these challenges, a direct solution is to generate ``high-confidence'' data from unsupervised downstream tasks and use them for in-context prompting or prompt optimization to refine the pseudo-supervision. However, relying solely on such data may lead to overfitting. In this paper, we leverage the in-context learning (ICL) abilities of LLMs and propose a novel approach, pseudo-supervised demonstrations aligned prompt optimization (PAPO) algorithm, which jointly refines both the prompt and the overall pseudo-supervision. The proposed learning objective ensures that the optimized prompt guides the LLM to generate consistent responses for a given input when pseudo-supervised data from the downstream task are used as demonstrations, enabling refinement over the entire pseudo-supervision. The prompt is optimized by translating gradient signals into textual critiques, which serve as feedback to iteratively refine the prompt and model responses. Theoretical analysis in a simplified classification setting shows that the refined pseudo-supervision exhibits a geometric clustering structure, helping to mitigate overfitting. Experiments on question answering, natural language inference benchmarks, and a real-world molecule optimization task, show the effectiveness of the proposed algorithm.
