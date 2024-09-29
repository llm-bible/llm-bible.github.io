---
layout: publication
title: Instruction Tuning45;free Visual Token Complement For Multimodal Llms
authors: Wang Dongsheng, Cui Jiequan, Li Miaoge, Lin Wang, Chen Bo, Zhang Hanwang
conference: "Arxiv"
year: 2024
bibkey: wang2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05019"}
tags: ['Efficiency And Optimization', 'Multimodal Models', 'Tools', 'Training Techniques']
---
As the open community of large language models (LLMs) matures multimodal LLMs (MLLMs) have promised an elegant bridge between vision and language. However current research is inherently constrained by challenges such as the need for high45;quality instruction pairs and the loss of visual information in image45;to45;text training objectives. To this end we propose a Visual Token Complement framework (VTC) that helps MLLMs regain the missing visual features and thus improve response accuracy. Specifically our VTC integrates text45;to45;image generation as a guide to identifying the text45;irrelevant features and a visual selector is then developed to generate complementary visual tokens to enrich the original visual input. Moreover an iterative strategy is further designed to extract more visual information by iteratively using the visual selector without any additional training. Notably the training pipeline requires no additional image45;text pairs resulting in a desired instruction tuning45;free property. Both qualitative and quantitative experiments demonstrate the superiority and efficiency of our VTC.
