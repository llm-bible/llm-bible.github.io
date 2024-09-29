---
layout: publication
title: Woodpecker Hallucination Correction For Multimodal Large Language Models
authors: Shukang Yin, Chaoyou Fu, Sirui Zhao, Tong Xu, Hao Wang, Dianbo Sui, Yunhang Shen, Ke Li, Xing Sun, Enhong Chen
conference: "Arxiv"
year: 2023
bibkey: yin2023hallucination
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2310.16045v1"}
  - {name: "Code", url: "https://github.com/BradyFU/Woodpecker"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Tools', 'Training Techniques']
---
Hallucination is a big shadow hanging over the rapidly evolving Multimodal Large Language Models (MLLMs) referring to the phenomenon that the generated text is inconsistent with the image content. In order to mitigate hallucinations existing studies mainly resort to an instruction45;tuning manner that requires retraining the models with specific data. In this paper we pave a different way introducing a training45;free method named Woodpecker. Like a woodpecker heals trees it picks out and corrects hallucinations from the generated text. Concretely Woodpecker consists of five stages key concept extraction question formulation visual knowledge validation visual claim generation and hallucination correction. Implemented in a post45;remedy manner Woodpecker can easily serve different MLLMs while being interpretable by accessing intermediate outputs of the five stages. We evaluate Woodpecker both quantitatively and qualitatively and show the huge potential of this new paradigm. On the POPE benchmark our method obtains a 30.6637;/24.3337; improvement in accuracy over the baseline MiniGPT45;4/mPLUG45;Owl. The source code is released at https://github.com/BradyFU/Woodpecker.
