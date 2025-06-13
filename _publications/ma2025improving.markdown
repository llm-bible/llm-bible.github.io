---
layout: publication
title: 'PANDAS: Improving Many-shot Jailbreaking Via Positive Affirmation, Negative Demonstration, And Adaptive Sampling'
authors: Avery Ma, Yangchen Pan, Amir-massoud Farahmand
conference: "Arxiv"
year: 2025
bibkey: ma2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01925"}
tags: ['Responsible AI', 'Model Architecture', 'Prompting', 'Attention Mechanism']
---
Many-shot jailbreaking circumvents the safety alignment of large language
models by exploiting their ability to process long input sequences. To achieve
this, the malicious target prompt is prefixed with hundreds of fabricated
conversational turns between the user and the model. These fabricated exchanges
are randomly sampled from a pool of malicious questions and responses, making
it appear as though the model has already complied with harmful instructions.
In this paper, we present PANDAS: a hybrid technique that improves many-shot
jailbreaking by modifying these fabricated dialogues with positive
affirmations, negative demonstrations, and an optimized adaptive sampling
method tailored to the target prompt's topic. Extensive experiments on AdvBench
and HarmBench, using state-of-the-art LLMs, demonstrate that PANDAS
significantly outperforms baseline methods in long-context scenarios. Through
an attention analysis, we provide insights on how long-context vulnerabilities
are exploited and show how PANDAS further improves upon many-shot jailbreaking.
