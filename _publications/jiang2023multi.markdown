---
layout: publication
title: Followbench A Multi45;level Fine45;grained Constraints Following Benchmark For Large Language Models
authors: Jiang Yuxin, Wang Yufei, Zeng Xingshan, Zhong Wanjun, Li Liangyou, Mi Fei, Shang Lifeng, Jiang Xin, Liu Qun, Wang Wei
conference: "Arxiv"
year: 2023
bibkey: jiang2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20410"}
  - {name: "Code", url: "https://github.com/YJiangcm/FollowBench"}
tags: ['Applications', 'Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
The ability to follow instructions is crucial for Large Language Models (LLMs) to handle various real45;world applications. Existing benchmarks primarily focus on evaluating pure response quality rather than assessing whether the response follows constraints stated in the instruction. To fill this research gap in this paper we propose FollowBench a Multi45;level Fine45;grained Constraints Following Benchmark for LLMs. FollowBench comprehensively includes five different types (i.e. Content Situation Style Format and Example) of fine45;grained constraints. To enable a precise constraint following estimation on diverse difficulties we introduce a Multi45;level mechanism that incrementally adds a single constraint to the initial instruction at each increased level. To assess whether LLMs outputs have satisfied every individual constraint we propose to prompt strong LLMs with constraint45;evolution paths to handle challenging open45;ended instructions. By evaluating 13 closed45;source and open45;source popular LLMs on FollowBench we highlight the weaknesses of LLMs in instruction following and point towards potential avenues for future work. The data and code are publicly available at https://github.com/YJiangcm/FollowBench.
