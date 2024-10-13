---
layout: publication
title: 'Tokenizer Choice For LLM Training: Negligible Or Crucial?'
authors: Ali Mehdi, Fromm Michael, Thellmann Klaudia, Rutmann Richard, Lübbering Max, Leveling Johannes, Klug Katrin, Ebert Jan, Doll Niclas, Buschhoff Jasper Schulze, Jain Charvi, Weber Alexander Arno, Jurkschat Lena, Abdelwahab Hammam, John Chelsea, Suarez Pedro Ortiz, Ostendorff Malte, Weinbach Samuel, Sifa Rafet, Kesselheim Stefan, Flores-herr Nicolas
conference: "Arxiv"
year: 2023
bibkey: ali2023tokenizer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08754"}
tags: ['Model Architecture', 'Pretraining Methods', 'Survey Paper', 'Tokenization', 'Training Techniques']
---
The recent success of Large Language Models (LLMs) has been predominantly
driven by curating the training dataset composition, scaling of model
architectures and dataset sizes and advancements in pretraining objectives,
leaving tokenizer influence as a blind spot. Shedding light on this
underexplored area, we conduct a comprehensive study on the influence of
tokenizer choice on LLM downstream performance by training 24 mono- and
multilingual LLMs at a 2.6B parameter scale, ablating different tokenizer
algorithms and parameterizations. Our studies highlight that the tokenizer
choice can significantly impact the model's downstream performance and training
costs. In particular, we find that the common tokenizer evaluation metrics
fertility and parity are not always predictive of model downstream performance,
rendering these metrics a questionable proxy for the model's downstream
performance. Furthermore, we show that multilingual tokenizers trained on the
five most frequent European languages require vocabulary size increases of
factor three in comparison to English. While English-centric tokenizers have
been applied to the training of multi-lingual LLMs in the past, we find that
this approach results in a severe downstream performance degradation and
additional training costs of up to 68%, due to an inefficient tokenization
vocabulary.
