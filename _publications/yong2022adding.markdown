---
layout: publication
title: 'BLOOM+1: Adding Language Support To BLOOM For Zero-shot Prompting'
authors: Yong Zheng-xin, Schoelkopf Hailey, Muennighoff Niklas, Aji Alham Fikri, Adelani David Ifeoluwa, Almubarak Khalid, Bari M Saiful, Sutawika Lintang, Kasai Jungo, Baruwa Ahmed, Winata Genta Indra, Biderman Stella, Raff Edward, Radev Dragomir, Nikoulina Vassilina
conference: "Arxiv"
year: 2022
bibkey: yong2022adding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.09535"}
  - {name: "Code", url: "https://github.com/bigscience-workshop/multilingual-modeling"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
'The BLOOM model is a large publicly available multilingual language model, but its pretraining was limited to 46 languages. To extend the benefits of BLOOM to other languages without incurring prohibitively large costs, it is desirable to adapt BLOOM to new languages not seen during pretraining. In this work, we apply existing language adaptation strategies to BLOOM and benchmark its zero-shot prompting performance on eight new languages in a resource-constrained setting. We find language adaptation to be effective at improving zero-shot performance in new languages. Surprisingly, we find that adapter-based finetuning is more effective than continued pretraining for large models. In addition, we discover that prompting performance is not significantly affected by language specifics, such as the writing system. It is primarily determined by the size of the language adaptation data. We also add new languages to BLOOMZ, which is a multitask finetuned version of BLOOM capable of following task instructions zero-shot. We find including a new language in the multitask fine-tuning mixture to be the most effective method to teach BLOOMZ a new language. We conclude that with sufficient training data language adaptation can generalize well to diverse languages. Our code is available at https://github.com/bigscience-workshop/multilingual-modeling.'
