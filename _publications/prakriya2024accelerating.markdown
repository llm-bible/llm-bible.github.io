---
layout: publication
title: 'Accelerating Large Language Model Pretraining Via LFR Pedagogy: Learn, Focus, And Review'
authors: Neha Prakriya, Jui-nan Yen, Cho-jui Hsieh, Jason Cong
conference: "Arxiv"
year: 2024
bibkey: prakriya2024accelerating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.06131'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Applications', 'Survey Paper', 'Pretraining Methods']
---
Traditional Large Language Model (LLM) pretraining relies on autoregressive
language modeling with randomly sampled data from web-scale datasets. Inspired
by human learning techniques like spaced repetition, we hypothesize that random
sampling leads to high training costs, lower-quality models, and significant
data forgetting. To address these inefficiencies, we propose the
Learn-Focus-Review (LFR) paradigm -- a dynamic training approach that adapts to
the model's learning progress. LFR tracks the model's learning performance
across data blocks (sequences of tokens) and prioritizes revisiting challenging
regions of the dataset that are more prone to being forgotten, enabling better
retention and more efficient learning. Using the LFR paradigm, we pretrained
Llama and GPT models on the SlimPajama and OpenWebText datasets, respectively.
These models were evaluated on downstream tasks across various domains,
including question answering, problem-solving, commonsense reasoning, language
modeling, and translation. Compared to baseline models trained on the full
datasets, LFR consistently achieved lower perplexity and higher accuracy, while
using only 5%--19% of the training tokens. Furthermore, LFR matched the
performance of industry-standard Pythia models with up to 2\\(\times\\) the
parameter count, using just 3.2% of the training tokens, demonstrating its
effectiveness and efficiency.
