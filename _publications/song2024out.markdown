---
layout: publication
title: Out45;of45;distribution Generalization Via Composition A Lens Through Induction Heads In Transformers
authors: Song Jiajun, Xu Zhuoyan, Zhong Yiqiao
conference: "Arxiv"
year: 2024
bibkey: song2024out
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09503"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large language models (LLMs) such as GPT45;4 sometimes appear to be creative solving novel tasks often with a few demonstrations in the prompt. These tasks require the models to generalize on distributions different from those from training data 45;45; which is known as out45;of45;distribution (OOD) generalization. Despite the tremendous success of LLMs how they approach OOD generalization remains an open and underexplored question. We examine OOD generalization in settings where instances are generated according to hidden rules including in45;context learning with symbolic reasoning. Models are required to infer the hidden rules behind input prompts without any fine45;tuning. We empirically examined the training dynamics of Transformers on a synthetic example and conducted extensive experiments on a variety of pretrained LLMs focusing on a type of components known as induction heads. We found that OOD generalization and composition are tied together 45;45; models can learn rules by composing two self45;attention layers thereby achieving OOD generalization. Furthermore a shared latent subspace in the embedding (or feature) space acts as a bridge for composition by aligning early layers and later layers which we refer to as the common bridge representation hypothesis.
