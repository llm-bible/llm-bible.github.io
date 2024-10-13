---
layout: publication
title: 'Automated Multi-language To English Machine Translation Using Generative Pre-trained Transformers'
authors: Pelofske Elijah, Urias Vincent, Liebrock Lorie M.
conference: "Arxiv"
year: 2024
bibkey: pelofske2024automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14680"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
The task of accurate and efficient language translation is an extremely
important information processing task. Machine learning enabled and automated
translation that is accurate and fast is often a large topic of interest in the
machine learning and data science communities. In this study, we examine using
local Generative Pretrained Transformer (GPT) models to perform automated zero
shot black-box, sentence wise, multi-natural-language translation into English
text. We benchmark 16 different open-source GPT models, with no custom
fine-tuning, from the Huggingface LLM repository for translating 50 different
non-English languages into English using translated TED Talk transcripts as the
reference dataset. These GPT model inference calls are performed strictly
locally, on single A100 Nvidia GPUs. Benchmark metrics that are reported are
language translation accuracy, using BLEU, GLEU, METEOR, and chrF text overlap
measures, and wall-clock time for each sentence translation. The best overall
performing GPT model for translating into English text for the BLEU metric is
ReMM-v2-L2-13B with a mean score across all tested languages of \\(0.152\\), for
the GLEU metric is ReMM-v2-L2-13B with a mean score across all tested languages
of \\(0.256\\), for the chrF metric is Llama2-chat-AYT-13B with a mean score across
all tested languages of \\(0.448\\), and for the METEOR metric is ReMM-v2-L2-13B
with a mean score across all tested languages of \\(0.438\\).
