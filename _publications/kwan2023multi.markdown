---
layout: publication
title: M4LE A Multi45;ability Multi45;range Multi45;task Multi45;domain Long45;context Evaluation Benchmark For Large Language Models
authors: Kwan Wai-chung, Zeng Xingshan, Wang Yufei, Sun Yusen, Li Liangyou, Shang Lifeng, Liu Qun, Wong Kam-fai
conference: "Arxiv"
year: 2023
bibkey: kwan2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19240"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Managing long sequences has become an important and necessary feature for large language models (LLMs). However it is still an open question of how to comprehensively and systematically evaluate the long45;sequence capability of LLMs. One of the reasons is that conventional and widely45;used benchmarks mainly consist of short sequences. In this paper we propose M4LE a Multi45;ability Multi45;range Multi45;task Multi45;domain benchmark for Long45;context Evaluation. M4LE is based on a diverse NLP task pool comprising 36 NLP datasets 11 task types and 12 domains. To alleviate the scarcity of tasks with naturally long sequences and incorporate multiple45;ability assessment we propose an automatic approach (but with negligible human annotations) to convert short45;sequence tasks into a unified long45;sequence scenario where LLMs have to identify single or multiple relevant spans in long contexts based on explicit or semantic hints. Specifically the scenario includes five different types of abilities (1) explicit single45;span; (2) semantic single45;span; (3) explicit multiple45;span; (4) semantic multiple45;span; and (5) global context understanding. The resulting samples in M4LE are evenly distributed from 1k to 8k input length. We conducted a systematic evaluation on 11 well45;established LLMs especially those optimized for long45;sequence inputs. Our results reveal that 1) Current LLMs struggle to understand long context particularly when tasks require multiple45;span attention. 2) Semantic retrieval task is more difficult for competent LLMs. 3) Models fine45;tuned on longer text with position interpolation have comparable performance to those using Neural Tangent Kernel (NTK) aware scaling methods without fine45;tuning. We make our benchmark publicly available to encourage future research in this challenging area.
