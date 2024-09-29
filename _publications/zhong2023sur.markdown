---
layout: publication
title: Sur45;adapter Enhancing Text45;to45;image Pre45;trained Diffusion Models With Large Language Models
authors: Zhong Shanshan, Huang Zhongzhan, Wen Wushao, Qin Jinghui, Lin Liang
conference: "Arxiv"
year: 2023
bibkey: zhong2023sur
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.05189"}
  - {name: "Code", url: "https://github.com/Qrange&#45;group/SUR&#45;adapter"}
tags: ['Distillation', 'Efficiency And Optimization', 'Has Code', 'Merging', 'Prompting']
---
Diffusion models which have emerged to become popular text45;to45;image generation models can produce high45;quality and content45;rich images guided by textual prompts. However there are limitations to semantic understanding and commonsense reasoning in existing models when the input prompts are concise narrative resulting in low45;quality image generation. To improve the capacities for narrative prompts we propose a simple45;yet45;effective parameter45;efficient fine45;tuning approach called the Semantic Understanding and Reasoning adapter (SUR45;adapter) for pre45;trained diffusion models. To reach this goal we first collect and annotate a new dataset SURD which consists of more than 57000 semantically corrected multi45;modal samples. Each sample contains a simple narrative prompt a complex keyword45;based prompt and a high45;quality image. Then we align the semantic representation of narrative prompts to the complex prompts and transfer knowledge of large language models (LLMs) to our SUR45;adapter via knowledge distillation so that it can acquire the powerful semantic understanding and reasoning capabilities to build a high45;quality textual semantic representation for text45;to45;image generation. We conduct experiments by integrating multiple LLMs and popular pre45;trained diffusion models to show the effectiveness of our approach in enabling diffusion models to understand and reason concise natural language without image quality degradation. Our approach can make text45;to45;image diffusion models easier to use with better user experience which demonstrates our approach has the potential for further advancing the development of user45;friendly text45;to45;image generation models by bridging the semantic gap between simple narrative prompts and complex keyword45;based prompts. The code is released at https://github.com/Qrange&#45;group/SUR&#45;adapter.
