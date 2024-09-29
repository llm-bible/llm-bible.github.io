---
layout: publication
title: Landmark Attention Random45;access Infinite Context Length For Transformers
authors: Mohtashami Amirkeivan, Jaggi Martin
conference: "Arxiv"
year: 2023
bibkey: mohtashami2023landmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.16300"}
  - {name: "Code", url: "https://github.com/epfml/landmark&#45;attention/"}
tags: ['Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
While Transformers have shown remarkable success in natural language processing their attention mechanisms large memory requirements have limited their ability to handle longer contexts. Prior approaches such as recurrent memory or retrieval45;based augmentation have either compromised the random45;access flexibility of attention (i.e. the capability to select any token in the entire context) or relied on separate mechanisms for relevant context retrieval which may not be compatible with the models attention. In this paper we present a novel approach that allows access to the complete context while retaining random45;access flexibility closely resembling running attention on the entire context. Our method uses a landmark token to represent each block of the input and trains the attention to use it for selecting relevant blocks enabling retrieval of blocks directly through the attention mechanism instead of by relying on a separate mechanism. Our approach seamlessly integrates with specialized data structures and the systems memory hierarchy enabling processing of arbitrarily long context lengths. We demonstrate that our method can obtain comparable performance with Transformer45;XL while significantly reducing the number of retrieved tokens in each step. Finally we show that fine45;tuning LLaMA 7B with our method successfully extends its context length capacity to over 32k tokens allowing for inference at the context lengths of GPT45;4. We release the implementation of landmark attention and the code to reproduce our experiments at https://github.com/epfml/landmark&#45;attention/.
