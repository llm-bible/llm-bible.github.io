---
layout: publication
title: Tricy: Trigger-guided Data-to-text Generation With Intent Aware Attention-copy
authors: Agarwal Vibhav, Ghosh Sourav, Bss Harichandana, Arora Himanshu, Raja Barath Raj Kandur
conference: "IEEE/ACM Transactions on Audio Speech and Language Processing vol."
year: 2024
bibkey: agarwal2024trigger
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01714"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques']
---
Data-to-text (D2T) generation is a crucial task in many natural language understanding (NLU) applications and forms the foundation of task-oriented dialog systems. In the context of conversational AI solutions that can work directly with local data on the users device architectures utilizing large pre-trained language models (PLMs) are impractical for on-device deployment due to a high memory footprint. To this end we propose TrICy a novel lightweight framework for an enhanced D2T task that generates text sequences based on the intent in context and may further be guided by user-provided triggers. We leverage an attention-copy mechanism to predict out-of-vocabulary (OOV) words accurately. Performance analyses on E2E NLG dataset (BLEU 66.4337; ROUGE-L 70.1437;) WebNLG dataset (BLEU Seen 64.0837; Unseen 52.3537;) and our Custom dataset related to text messaging applications showcase our architectures effectiveness. Moreover we show that by leveraging an optional trigger input data-to-text generation quality increases significantly and achieves the new SOTA score of 69.2937; BLEU for E2E NLG. Furthermore our analyses show that TrICy achieves at least 2437; and 337; improvement in BLEU and METEOR respectively over LLMs like GPT-3 ChatGPT and Llama 2. We also demonstrate that in some scenarios performance improvement due to triggers is observed even when they are absent in training.
