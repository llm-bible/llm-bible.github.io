---
layout: publication
title: Structured Pruning Of A Bert45;based Question Answering Model
authors: Mccarley J. S., Chakravarti Rishav, Sil Avirup
conference: "Arxiv"
year: 2019
bibkey: mccarley2019structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.06360"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
The recent trend in industry45;setting Natural Language Processing (NLP) research has been to operate large 37;scale pretrained language models like BERT under strict computational limits. While most model compression work has focused on distilling a general45;purpose language representation using expensive pretraining distillation less attention has been paid to creating smaller task45;specific language representations which arguably are more useful in an industry setting. In this paper we investigate compressing BERT45; and RoBERTa45;based question answering systems by structured pruning of parameters from the underlying transformer model. We find that an inexpensive combination of task45;specific structured pruning and task45;specific distillation without the expense of pretraining distillation yields highly45;performing models across a range of speed/accuracy tradeoff operating points. We start from existing full45;size models trained for SQuAD 2.0 or Natural Questions and introduce gates that allow selected parts of transformers to be individually eliminated. Specifically we investigate (1) structured pruning to reduce the number of parameters in each transformer layer (2) applicability to both BERT45; and RoBERTa45;based models (3) applicability to both SQuAD 2.0 and Natural Questions and (4) combining structured pruning with distillation. We achieve a near45;doubling of inference speed with less than a 0.5 F145;point loss in short answer accuracy on Natural Questions.
