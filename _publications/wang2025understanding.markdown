---
layout: publication
title: 'LEANCODE: Understanding Models Better For Code Simplification Of Pre-trained Large Language Models'
authors: Yan Wang, Ling Ding, Tien N Nguyen, Shaohua Wang, Yanan Zheng
conference: "Arxiv"
year: 2025
bibkey: wang2025understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14759"}
tags: ['Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism']
---
Large Language Models for code often entail significant computational complexity, which grows significantly with the length of the input code sequence. We propose LeanCode for code simplification to reduce training and prediction time, leveraging code contexts in utilizing attention scores to represent the tokens' importance. We advocate for the selective removal of tokens based on the average context-aware attention scores rather than average scores across all inputs. LeanCode uses the attention scores of `CLS' tokens within the encoder for classification tasks, such as code search. It also employs the encoder-decoder attention scores to determine token significance for sequence-to-sequence tasks like code summarization. Our evaluation shows LeanCode's superiority over the SOTAs DietCode and Slimcode, with improvements of 60% and 16% for code search, and 29% and 27% for code summarization, respectively.
