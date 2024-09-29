---
layout: publication
title: Evaluating Language Model Context Windows\: A "working Memory" Test And Inference-time Correction
authors: Dsouza Amanda, Glaze Christopher, Shin Changho, Sala Frederic
conference: "Arxiv"
year: 2024
bibkey: dsouza2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03651"}
  - {name: "Code", url: "https://github.com/snorkel-ai/long-context-eval"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models are prominently used in real-world applications often tasked with reasoning over large volumes of documents. An exciting development in this space is models boasting extended context capabilities with some accommodating over 2 million tokens. Such long context model capabilities remain uncertain in production systems motivating the need to benchmark their performance on real world use cases. We address this challenge by proposing SWiM an evaluation framework that addresses the limitations of standard tests. Testing the framework on eight long context models we find that even strong models such as GPT-4 and Claude 3 Opus degrade in performance when information is present in the middle of the context window (lost-in-the-middle effect). Next in addition to our benchmark we propose medoid voting a simple but effective training-free approach that helps alleviate this effect by generating responses a few times each time randomly permuting documents in the context and selecting the medoid answer. We evaluate medoid voting on single document QA tasks achieving up to a 2437; lift in accuracy. Our code is available at https://github.com/snorkel-ai/long-context-eval."
