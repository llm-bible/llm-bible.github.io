---
layout: publication
title: Facts2story: Controlling Text Generation By Key Facts
authors: Orbach Eyal Bar Ilan University, Goldberg Yoav Bar Ilan University And Allen Institute For Artificial Intelligence
conference: "Arxiv"
year: 2020
bibkey: orbach2020controlling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.04332"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent advancements in self-attention neural network architectures have raised the bar for open-ended text generation. Yet while current methods are capable of producing a coherent text which is several hundred words long attaining control over the content that is being generated -- as well as evaluating it -- are still open questions. We propose a controlled generation task which is based on expanding a sequence of facts expressed in natural language into a longer narrative. We introduce human-based evaluation metrics for this task as well as a method for deriving a large training dataset. We evaluate three methods on this task based on fine-tuning pre-trained models. We show that while auto-regressive unidirectional Language Models such as GPT2 produce better fluency they struggle to adhere to the requested facts. We propose a plan-and-cloze model (using fine-tuned XLNet) which produces competitive fluency while adhering to the requested content.
