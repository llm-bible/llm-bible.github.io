---
layout: publication
title: Improving Generalization In Task45;oriented Dialogues With Workflows And Action Plans
authors: Raimondo Stefania, Pal Christopher, Liu Xiaotian, Vazquez David, Palacios Hector
conference: "Arxiv"
year: 2023
bibkey: raimondo2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.01729"}
tags: ['Agentic', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Task45;oriented dialogue is difficult in part because it involves understanding user intent collecting information from the user executing API calls and generating helpful and fluent responses. However for complex tasks one must also correctly do all of these things over multiple steps and in a specific order. While large pre45;trained language models can be fine45;tuned end45;to45;end to create multi45;step task45;oriented dialogue agents that generate fluent text our experiments confirm that this approach alone cannot reliably perform new multi45;step tasks that are unseen during training. To address these limitations we augment the dialogue contexts given to textmd123;text2text125; transformers with known textit123;valid workflow names125; and textit123;action plans125;. Action plans consist of sequences of actions required to accomplish a task and are encoded as simple sequences of keywords (e.g. verify45;identity pull45;up45;account reset45;password etc.). We perform extensive experiments on the Action45;Based Conversations Dataset (ABCD) with T545;small base and large models and show that such models a) are able to more readily generalize to unseen workflows by following the provided plan and b) are able to generalize to executing unseen actions if they are provided in the plan. In contrast models are unable to fully accomplish new multi45;step tasks when they are not provided action plan information even when given new valid workflow names.
