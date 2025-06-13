---
layout: publication
title: 'Improved Alignment Of Modalities In Large Vision Language Models'
authors: Kartik Jangra, Aman Kumar Singh, Yashwani Mann, Geetanjali Rathee
conference: "Arxiv"
year: 2025
bibkey: jangra2025improved
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19508"}
tags: ['Transformer', 'Pre-Training', 'Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models']
---
Recent advancements in vision-language models have achieved remarkable
results in making language models understand vision inputs. However, a unified
approach to align these models across diverse tasks such as image captioning
and visual question answering remains a challenge. Existing methods either
require very big language models or very big datasets which is not efficient in
utilizing existing models. This paper addresses this gap and devises a training
strategy of auto-regressive vision-language models, to unify vision-language
tasks like image-captioning and visual question answering. We propose four
training stages for aligning the vision model with the language model, in other
words, the language model is given an ability to process visual inputs. We also
devise different attention masks for training transformer-based language models
that improve the quality of visual features. Further, we introduce some
findings, 1) the attention mask should not be applied on visual inputs, 2) the
Language model converges faster on AI- generated data, 3) More work should be
done in the alignment stage during the pre-training of the model, 4) the model
can easily adapt to any downstream tasks like visual question answering on
healthcare datasets like PathVQA. After training the model for one epoch for
all the stages, it outperforms large models like VILA-13 billion models on
common benchmarks like CIDEr scores on COCO and Flickr30k datasets and achieves
very close scores to GIT-2 on the same dataset despite being a much smaller
model trained on a much smaller dataset. All of the training is done using best
practices available like multi- GPU parallel training, lower-precision training
with 16-bit float numbers, faster attention (SDPA), and gradient accumulation,
and completed the training within 12 hours.
