---
layout: publication
title: 'Tricy: Trigger-guided Data-to-text Generation With Intent Aware Attention-copy'
authors: Vibhav Agarwal, Sourav Ghosh, Harichandana Bss, Himanshu Arora, Barath Raj Kandur Raja
conference: "IEEE/ACM Transactions on Audio Speech and Language Processing vol. 32 pp. 1173-1184 2024"
year: 2024
bibkey: agarwal2024trigger
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.01714'}
tags: ['Attention Mechanism', 'Language Modeling', 'RAG', 'Training Techniques', 'Model Architecture', 'Applications', 'Tools', 'GPT']
---
Data-to-text (D2T) generation is a crucial task in many natural language
understanding (NLU) applications and forms the foundation of task-oriented
dialog systems. In the context of conversational AI solutions that can work
directly with local data on the user's device, architectures utilizing large
pre-trained language models (PLMs) are impractical for on-device deployment due
to a high memory footprint. To this end, we propose TrICy, a novel lightweight
framework for an enhanced D2T task that generates text sequences based on the
intent in context and may further be guided by user-provided triggers. We
leverage an attention-copy mechanism to predict out-of-vocabulary (OOV) words
accurately. Performance analyses on E2E NLG dataset (BLEU: 66.43%, ROUGE-L:
70.14%), WebNLG dataset (BLEU: Seen 64.08%, Unseen 52.35%), and our Custom
dataset related to text messaging applications, showcase our architecture's
effectiveness. Moreover, we show that by leveraging an optional trigger input,
data-to-text generation quality increases significantly and achieves the new
SOTA score of 69.29% BLEU for E2E NLG. Furthermore, our analyses show that
TrICy achieves at least 24% and 3% improvement in BLEU and METEOR respectively
over LLMs like GPT-3, ChatGPT, and Llama 2. We also demonstrate that in some
scenarios, performance improvement due to triggers is observed even when they
are absent in training.
