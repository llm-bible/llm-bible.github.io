---
layout: publication
title: 'Implicit Meta-learning May Lead Language Models To Trust More Reliable Sources'
authors: Krasheninnikov Dmitrii, Krasheninnikov Egor, Mlodozeniec Bruno, Maharaj Tegan, Krueger David
conference: "Arxiv"
year: 2023
bibkey: krasheninnikov2023implicit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15047"}
  - {name: "Code", url: "https://github.com/krasheninnikov/internalization"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'Training Techniques']
---
"We demonstrate that LLMs may learn indicators of document usefulness and modulate their updates accordingly. We introduce random strings (tags) as indicators of usefulness in a synthetic fine-tuning dataset. Fine-tuning on this dataset leads to implicit meta-learning (IML): in further fine-tuning, the model updates to make more use of text that is tagged as useful. We perform a thorough empirical investigation of this phenomenon, finding (among other things) that (i) it occurs in both pretrained LLMs and those trained from scratch, as well as on a vision task, and (ii) larger models and smaller batch sizes tend to give more IML. We also use probing to examine how IML changes the way models store knowledge in their parameters. Finally, we reflect on what our results might imply about capabilities, risks, and controllability of future AI systems. Our code can be found at https://github.com/krasheninnikov/internalization."
