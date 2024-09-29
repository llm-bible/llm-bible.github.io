---
layout: publication
title: What Makes For Good Visual Tokenizers For Large Language Models
authors: Wang Guangzhi, Ge Yixiao, Ding Xiaohan, Kankanhalli Mohan, Shan Ying
conference: "Arxiv"
year: 2023
bibkey: wang2023what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12223"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
We empirically investigate proper pre45;training methods to build good visual tokenizers making Large Language Models (LLMs) powerful Multimodal Large Language Models (MLLMs). In our benchmark which is curated to evaluate MLLMs visual semantic understanding and fine45;grained perception capabilities we discussed different visual tokenizers pre45;trained with dominant methods (i.e. DeiT CLIP MAE DINO) and observe that i) Fully/weakly supervised models capture more semantics than self45;supervised models but the gap is narrowed by scaling up the pre45;training dataset. ii) Self45;supervised models are better at fine45;grained perception where patch45;level supervision is particularly effective. iii) Tuning the visual tokenizer leads to the loss of semantics obtained from large45;scale pretraining which is unfavorable with relatively small45;scale instruction45;tuning dataset. Given the findings we reviewed methods that attempted to unify semantics and fine45;grained visual understanding e.g. patch45;level feature distillation with semantically45;rich targets. We obtain an intriguing insight mask45;based strategies that were once all the rage may not be applicable for obtaining good visual tokenizers. Based on this critical observation we obtain a new MLLM equipped with a tailored Good Visual Tokenizer (GVT) which exhibits strong visual comprehension capability at multiple scales. In particular without introducing extra parameters and task45;specific fine45;tuning GVT achieves superior performance on visual question answering image captioning and other fine45;grained visual understanding tasks such as object counting and multi45;class identification.
