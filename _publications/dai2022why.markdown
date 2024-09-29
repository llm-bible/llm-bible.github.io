---
layout: publication
title: Why Can GPT Learn In-context Language Models Implicitly Perform Gradient Descent As Meta-optimizers
authors: Dai Damai, Sun Yutao, Dong Li, Hao Yaru, Ma Shuming, Sui Zhifang, Wei Furu
conference: "Arxiv"
year: 2022
bibkey: dai2022why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10559"}
  - {name: "Code", url: "https://aka.ms/icl"}
tags: ['Attention Mechanism', 'GPT', 'Has Code', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large pretrained language models have shown surprising in-context learning (ICL) ability. With a few demonstration input-label pairs they can predict the label for an unseen input without parameter updates. Despite the great success in performance its working mechanism still remains an open question. In this paper we explain language models as meta-optimizers and understand in-context learning as implicit finetuning. Theoretically we figure out that Transformer attention has a dual form of gradient descent. On top of it we understand ICL as follows GPT first produces meta-gradients according to the demonstration examples and then these meta-gradients are applied to the original GPT to build an ICL model. We comprehensively compare the behaviors of in-context learning and explicit finetuning on real tasks to provide empirical evidence that supports our understanding. Experimental results show that in-context learning behaves similarly to explicit finetuning from multiple perspectives. Inspired by the dual form between Transformer attention and gradient descent we design a momentum-based attention by analogy with gradient descent with momentum. The improved performance over vanilla attention further supports our understanding from another perspective and more importantly shows the potential to utilize our understanding for future model design. The code is available at (url)https://aka.ms/icl\}.
