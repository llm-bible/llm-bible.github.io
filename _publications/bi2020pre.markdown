---
layout: publication
title: PALM Pre45;training An Autoencodingamp;autoregressive Language Model For Context45;conditioned Generation
authors: Bi Bin, Li Chenliang, Wu Chen, Yan Ming, Wang Wei, Huang Songfang, Huang Fei, Si Luo
conference: "Arxiv"
year: 2020
bibkey: bi2020pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.07159"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Self45;supervised pre45;training such as BERT MASS and BART has emerged as a powerful technique for natural language understanding and generation. Existing pre45;training techniques employ autoencoding and/or autoregressive objectives to train Transformer45;based models by recovering original word tokens from corrupted text with some masked tokens. The training goals of existing techniques are often inconsistent with the goals of many language generation tasks such as generative question answering and conversational response generation for producing new text given context. This work presents PALM with a novel scheme that jointly pre45;trains an autoencoding and autoregressive language model on a large unlabeled corpus specifically designed for generating new text conditioned on context. The new scheme alleviates the mismatch introduced by the existing denoising scheme between pre45;training and fine45;tuning where generation is more than reconstructing original text. An extensive set of experiments show that PALM achieves new state45;of45;the45;art results on a variety of language generation benchmarks covering generative question answering (Rank 1 on the official MARCO leaderboard) abstractive summarization on CNN/DailyMail as well as Gigaword question generation on SQuAD and conversational response generation on Cornell Movie Dialogues.
