---
layout: publication
title: 'Lilium: Ebay''s Large Language Models For E-commerce'
authors: Herold Christian, Kozielski Michael, Ekimov Leonid, Petrushkov Pavel, Vandenbussche Pierre-yves, Khadivi Shahram
conference: "Arxiv"
year: 2024
bibkey: herold2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12023"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
We introduce the LiLiuM series of large language models (LLMs): 1B, 7B, and
13B parameter models developed 100% in-house to fit eBay's specific needs in
the e-commerce domain. This gives eBay full control over all aspects of the
models including license, data, vocabulary, and architecture. We expect these
models to be used as a foundation for fine-tuning and instruction-tuning,
eliminating dependencies to external models.
  The LiLiuM LLMs have been trained on 3 trillion tokens of multilingual text
from general and e-commerce domain. They perform similar to the popular LLaMA-2
models on English natural language understanding (NLU) benchmarks. At the same
time, we outperform LLaMA-2 on non-English NLU tasks, machine translation and
on e-commerce specific downstream tasks.
  As part of our data mixture, we utilize the newly released RedPajama-V2
dataset for training and share our insights regarding data filtering and
deduplication. We also discuss in detail how to serialize structured data for
use in autoregressive language modeling. We provide insights on the effects of
including code and parallel machine translation data in pre-training.
Furthermore, we develop our own tokenizer and model vocabulary, customized
towards e-commerce. This way, we can achieve up to 34% speed-up in text
generation on eBay-specific downstream tasks compared to LLaMA-2.
  Finally, in relation to LLM pretraining, we show that checkpoint averaging
can further improve over the best individual model checkpoint.
