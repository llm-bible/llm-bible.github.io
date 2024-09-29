---
layout: publication
title: HMT Hierarchical Memory Transformer For Long Context Language Processing
authors: He Zifan, Qin Zongyue, Prakriya Neha, Sun Yizhou, Cong Jason
conference: "Arxiv"
year: 2024
bibkey: he2024hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06067"}
  - {name: "Code", url: "https://github.com/OswaldHe/HMT&#45;pytorch"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Transformer45;based large language models (LLM) have been widely used in language processing applications. However most of them restrict the context window that permits the model to attend to every token in the inputs. Previous works in recurrent models can memorize past tokens to enable unlimited context and maintain effectiveness. However they have flat memory architectures which have limitations in selecting and filtering information. Since humans are good at learning and self45;adjustment we speculate that imitating brain memory hierarchy is beneficial for model memorization. We propose the Hierarchical Memory Transformer (HMT) a novel framework that enables and improves models long45;context processing ability by imitating human memorization behavior. Leveraging memory45;augmented segment45;level recurrence we organize the memory hierarchy by preserving tokens from early input token segments passing memory embeddings along the sequence and recalling relevant information from history. Evaluating general language modeling (Wikitext45;103 PG45;19) and question45;answering tasks (PubMedQA) we show that HMT steadily improves the long45;context processing ability of context45;constrained and long45;context models. With an additional 0.537; 45; 237; of parameters HMT can easily plug in and augment future LLMs to handle long context effectively. Our code is open45;sourced on Github https://github.com/OswaldHe/HMT&#45;pytorch.
