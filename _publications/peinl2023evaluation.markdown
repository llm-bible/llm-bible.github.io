---
layout: publication
title: Evaluation of medium-large Language Models at zero-shot closed book generative question answering
authors: Peinl René, Wirth Johannes
conference: "Under review in ARIA"
year: 2023
bibkey: peinl2023evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11991"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'GPT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Large language models (LLMs) have garnered significant attention but the definition of large lacks clarity. This paper focuses on medium-sized language models (MLMs) defined as having at least six billion parameters but less than 100 billion. The study evaluates MLMs regarding zero-shot generative question answering which requires models to provide elaborate answers without external document retrieval. The paper introduces an own test dataset and presents results from human evaluation. Results show that combining the best answers from different MLMs yielded an overall correct answer rate of 82.7 which is better than the 60.9 of ChatGPT. The best MLM achieved 71.8 and has 33B parameters which highlights the importance of using appropriate training data for fine-tuning rather than solely relying on the number of parameters. More fine-grained feedback should be used to further improve the quality of answers. The open source community is quickly closing the gap to the best commercial models.
