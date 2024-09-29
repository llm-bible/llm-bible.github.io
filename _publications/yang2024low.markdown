---
layout: publication
title: Loretta Low45;rank Economic Tensor45;train Adaptation For Ultra45;low45;parameter Fine45;tuning Of Large Language Models
authors: Yang Yifan, Zhou Jiajun, Wong Ngai, Zhang Zheng
conference: "Arxiv"
year: 2024
bibkey: yang2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11417"}
tags: ['Efficiency And Optimization', 'Tools', 'Training Techniques']
---
Various parameter45;efficient fine45;tuning (PEFT) techniques have been proposed to enable computationally efficient fine45;tuning while maintaining model performance. However existing PEFT methods are still limited by the growing number of trainable parameters with the rapid deployment of Large Language Models (LLMs). To address this challenge we present LoRETTA an ultra45;parameter45;efficient framework that significantly reduces trainable parameters through tensor45;train decomposition. Specifically we propose two methods named 123;LoRETTA125;95;123;adp125; and 123;LoRETTA125;95;123;rep125;. The former employs tensorized adapters offering a high45;performance yet lightweight approach for the fine45;tuning of LLMs. The latter emphasizes fine45;tuning via weight parameterization with a set of small tensor factors. LoRETTA achieves comparable or better performance than most widely used PEFT methods with up to 100× fewer parameters on the LLaMA45;245;7B models. Furthermore empirical results demonstrate that the proposed method effectively improves training efficiency enjoys better multi45;task learning performance and enhances the anti45;overfitting capability. Plug45;and45;play codes built upon the Huggingface framework and PEFT library will be released.
