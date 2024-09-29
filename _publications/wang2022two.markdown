---
layout: publication
title: Two45;stage LLM Fine45;tuning With Less Specialization And More Generalization
authors: Wang Yihan, Si Si, Li Daliang, Lukasik Michal, Yu Felix, Hsieh Cho-jui, Dhillon Inderjit S, Kumar Sanjiv
conference: "Arxiv"
year: 2022
bibkey: wang2022two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.00635"}
tags: ['Applications', 'Prompting', 'Tools', 'Training Techniques']
---
Pretrained large language models (LLMs) are general purpose problem solvers applicable to a diverse set of tasks with prompts. They can be further improved towards a specific task by fine45;tuning on a specialized dataset. However fine45;tuning usually makes the model narrowly specialized on this dataset with reduced general in45;context learning performances which is undesirable whenever the fine45;tuned model needs to handle additional tasks where no fine45;tuning data is available. In this work we first demonstrate that fine45;tuning on a single task indeed decreases LLMs general in45;context learning performance. We discover one important cause of such forgetting format specialization where the model overfits to the format of the fine45;tuned task.We further show that format specialization happens at the very beginning of fine45;tuning. To solve this problem we propose Prompt Tuning with MOdel Tuning (ProMoT) a simple yet effective two45;stage fine45;tuning framework that reduces format specialization and improves generalization.ProMoT offloads task45;specific format learning into additional and removable parameters by first doing prompt tuning and then fine45;tuning the model itself with this soft prompt attached. With experiments on several fine45;tuning tasks and 8 in45;context evaluation tasks we show that ProMoT achieves comparable performance on fine45;tuned tasks to standard fine45;tuning but with much less loss of in45;context learning performances across a board range of out45;of45;domain evaluation tasks. More importantly ProMoT can even enhance generalization on in45;context learning tasks that are semantically related to the fine45;tuned task e.g. ProMoT on En45;Fr translation significantly improves performance on other language pairs and ProMoT on NLI improves performance on summarization. Experiments also show that ProMoT can improve the generalization performance of multi45;task training.
