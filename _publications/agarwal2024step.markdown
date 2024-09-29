---
layout: publication
title: Step45;by45;step Unmasking For Parameter45;efficient Fine45;tuning Of Large Language Models
authors: Agarwal Aradhye, Ramesh Suhas K, Sengupta Ayan, Chakraborty Tanmoy
conference: "Arxiv"
year: 2024
bibkey: agarwal2024step
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14470"}
tags: ['Applications', 'Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'Pruning']
---
Fine45;tuning large language models (LLMs) on downstream tasks requires substantial computational resources. A class of parameter45;efficient fine45;tuning (PEFT) aims to mitigate these computational challenges by selectively fine45;tuning only a small fraction of the model parameters. Although computationally efficient these techniques often fail to match the performance of fully fine45;tuned models primarily due to inherent biases introduced during parameter selection. Traditional selective PEFT techniques use a fixed set of parameters based on a predefined budget (a process also known as unmasking) failing to capture parameter importance dynamically and often ending up exceeding the budget. We introduce text123;ID125;^3 a novel selective PEFT method that calculates parameter importance continually and dynamically unmasks parameters by balancing exploration and exploitation in parameter selection. Our empirical study on 15 tasks spanning natural language understanding and generative tasks demonstrates the effectiveness of our method compared to fixed45;masking45;based PEFT techniques. We analytically show that text123;ID125;^3 reduces the number of gradient updates by a factor of two enhancing computational efficiency. text123;ID125;^3 is robust to random initialization of neurons and therefore can be seamlessly integrated into existing additive and reparametrization45;based PEFT modules such as adapters and LoRA for dynamic sparsification.
