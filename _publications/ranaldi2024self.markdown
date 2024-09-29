---
layout: publication
title: Self45;refine Instruction45;tuning For Aligning Reasoning In Language Models
authors: Ranaldi Leonardo, Freitas Andrè
conference: "Arxiv"
year: 2024
bibkey: ranaldi2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00402"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Reinforcement Learning', 'Training Techniques']
---
The alignments of reasoning abilities between smaller and larger Language Models are largely conducted via Supervised Fine45;Tuning (SFT) using demonstrations generated from robust Large Language Models (LLMs). Although these approaches deliver more performant models they do not show sufficiently strong generalization ability as the training only relies on the provided demonstrations. In this paper we propose the Self45;refine Instruction45;tuning method that elicits Smaller Language Models to self45;refine their abilities. Our approach is based on a two45;stage process where reasoning abilities are first transferred between LLMs and Small Language Models (SLMs) via Instruction45;tuning on demonstrations provided by LLMs and then the instructed models Self45;refine their abilities through preference optimization strategies. In particular the second phase operates refinement heuristics based on the Direct Preference Optimization algorithm where the SLMs are elicited to deliver a series of reasoning paths by automatically sampling the generated responses and providing rewards using ground truths from the LLMs. Results obtained on commonsense and math reasoning tasks show that this approach significantly outperforms Instruction45;tuning in both in45;domain and out45;domain scenarios aligning the reasoning abilities of Smaller and Larger Language Models.
