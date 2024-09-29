---
layout: publication
title: "Be Like A Goldfish, Don't Memorize! Mitigating Memorization In Generative Llms"
authors: Hans Abhimanyu, Wen Yuxin, Jain Neel, Kirchenbauer John, Kazemi Hamid, Singhania Prajwal, Singh Siddharth, Somepalli Gowthami, Geiping Jonas, Bhatele Abhinav, Goldstein Tom
conference: "Arxiv"
year: 2024
bibkey: hans2024be
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10209"}
tags: ['Pretraining Methods', 'Training Techniques']
---
Large language models can memorize and repeat their training data causing privacy and copyright risks. To mitigate memorization we introduce a subtle modification to the next-token training objective that we call the goldfish loss. During training a randomly sampled subset of tokens are excluded from the loss computation. These dropped tokens are not memorized by the model which prevents verbatim reproduction of a complete chain of tokens from the training set. We run extensive experiments training billion-scale Llama-2 models both pre-trained and trained from scratch and demonstrate significant reductions in extractable memorization with little to no impact on downstream benchmarks.
