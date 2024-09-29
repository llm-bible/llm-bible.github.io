---
layout: publication
title: What Would Elsa Do Freezing Layers During Transformer Fine-Tuning
authors: Lee Jaejun, Tang Raphael, Lin Jimmy
conference: "Arxiv"
year: 2019
bibkey: lee2019what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.03090"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Pretrained transformer-based language models have achieved state of the art across countless tasks in natural language processing. These models are highly expressive comprising at least a hundred million parameters and a dozen layers. Recent evidence suggests that only a few of the final layers need to be fine-tuned for high quality on downstream tasks. Naturally a subsequent research question is how many of the last layers do we need to fine-tune In this paper we precisely answer this question. We examine two recent pretrained language models BERT and RoBERTa across standard tasks in textual entailment semantic similarity sentiment analysis and linguistic acceptability. We vary the number of final layers that are fine-tuned then study the resulting change in task-specific effectiveness. We show that only a fourth of the final layers need to be fine-tuned to achieve 90 of the original quality. Surprisingly we also find that fine-tuning all layers does not always help.
