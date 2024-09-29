---
layout: publication
title: Moe45;lpr Multilingual Extension Of Large Language Models Through Mixture45;of45;experts With Language Priors Routing
authors: Zhou Hao, Wang Zhijun, Huang Shujian, Huang Xin, Han Xue, Feng Junlan, Deng Chao, Luo Weihua, Chen Jiajun
conference: "Arxiv"
year: 2024
bibkey: zhou2024moe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11396"}
  - {name: "Code", url: "https://github.com/zjwang21/MoE&#45;LPR.git"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Large Language Models (LLMs) are often English45;centric due to the disproportionate distribution of languages in their pre45;training data. Enhancing non45;English language capabilities through post45;pretraining often results in catastrophic forgetting of the ability of original languages. Previous methods either achieve good expansion with severe forgetting or slight forgetting with poor expansion indicating the challenge of balancing language expansion while preventing forgetting. In this paper we propose a method called MoE45;LPR (Mixture45;of45;Experts with Language Priors Routing) to alleviate this problem. MoE45;LPR employs a two45;stage training approach to enhance the multilingual capability. First the model is post45;pretrained into a Mixture45;of45;Experts (MoE) architecture by upcycling where all the original parameters are frozen and new experts are added. In this stage we focus improving the ability on expanded languages without using any original language data. Then the model reviews the knowledge of the original languages with replay data amounting to less than 137; of post45;pretraining where we incorporate language priors routing to better recover the abilities of the original languages. Evaluations on multiple benchmarks show that MoE45;LPR outperforms other post45;pretraining methods. Freezing original parameters preserves original language knowledge while adding new experts preserves the learning ability. Reviewing with LPR enables effective utilization of multilingual knowledge within the parameters. Additionally the MoE architecture maintains the same inference overhead while increasing total model parameters. Extensive experiments demonstrate MoE45;LPRs effectiveness in improving expanded languages and preserving original language proficiency with superior scalability. Code and scripts are freely available at https://github.com/zjwang21/MoE&#45;LPR.git.
