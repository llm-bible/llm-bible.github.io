---
layout: publication
title: Why Can GPT Learn In45;context Language Models Implicitly Perform Gradient Descent As Meta45;optimizers
authors: Dai Damai, Sun Yutao, Dong Li, Hao Yaru, Ma Shuming, Sui Zhifang, Wei Furu
conference: "Arxiv"
year: 2022
bibkey: dai2022why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10559"}
  - {name: "Code", url: "https://aka.ms/icl&#125;"}
tags: ['Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large pretrained language models have shown surprising in45;context learning (ICL) ability. With a few demonstration input45;label pairs they can predict the label for an unseen input without parameter updates. Despite the great success in performance its working mechanism still remains an open question. In this paper we explain language models as meta45;optimizers and understand in45;context learning as implicit finetuning. Theoretically we figure out that Transformer attention has a dual form of gradient descent. On top of it we understand ICL as follows GPT first produces meta45;gradients according to the demonstration examples and then these meta45;gradients are applied to the original GPT to build an ICL model. We comprehensively compare the behaviors of in45;context learning and explicit finetuning on real tasks to provide empirical evidence that supports our understanding. Experimental results show that in45;context learning behaves similarly to explicit finetuning from multiple perspectives. Inspired by the dual form between Transformer attention and gradient descent we design a momentum45;based attention by analogy with gradient descent with momentum. The improved performance over vanilla attention further supports our understanding from another perspective and more importantly shows the potential to utilize our understanding for future model design. The code is available at url123;https://aka.ms/icl&#125;.
