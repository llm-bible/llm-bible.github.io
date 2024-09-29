---
layout: publication
title: Baichuanseed Sharing The Potential Of Extensive Data Collection And Deduplication By Introducing A Competitive Large Language Model Baseline
authors: Dong Guosheng, Pan Da, Sun Yiding, Zhang Shusen, Liang Zheng, Wu Xin, Shen Yanjun, Yang Fan, Sun Haoze, Li Tianpeng, Lin Mingan, Xu Jianhua, Zhang Yufan, Nie Xiaonan, Su Lei, Wang Bingning, Zhang Wentao, Mao Jiaxin, Zhou Zenan, Chen Weipeng
conference: "Arxiv"
year: 2024
bibkey: dong2024sharing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15079"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
The general capabilities of Large Language Models (LLM) highly rely on the composition and selection on extensive pretraining datasets treated as commercial secrets by several institutions. To mitigate this issue we open-source the details of a universally applicable data processing pipeline and validate its effectiveness and potential by introducing a competitive LLM baseline. Specifically the data processing pipeline consists of broad collection to scale up and reweighting to improve quality. We then pretrain a 7B model BaichuanSEED with 3T tokens processed by our pipeline without any deliberate downstream task-related optimization followed by an easy but effective supervised fine-tuning stage. BaichuanSEED demonstrates consistency and predictability throughout training and achieves comparable performance on comprehensive benchmarks with several commercial advanced large language models such as Qwen1.5 and Llama3. We also conduct several heuristic experiments to discuss the potential for further optimization of downstream tasks such as mathematics and coding.
