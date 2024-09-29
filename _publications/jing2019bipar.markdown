---
layout: publication
title: BiPaR A Bilingual Parallel Dataset for Multilingual and Cross-lingual Reading Comprehension on Novels
authors: Jing Yimin, Xiong Deyi, Zhen Yan
conference: "Arxiv"
year: 2019
bibkey: jing2019bipar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.05040"}
tags: ['Applications', 'BERT', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
This paper presents BiPaR a bilingual parallel novel-style machine reading comprehension (MRC) dataset developed to support multilingual and cross-lingual reading comprehension. The biggest difference between BiPaR and existing reading comprehension datasets is that each triple (Passage Question Answer) in BiPaR is written parallelly in two languages. We collect 3667 bilingual parallel paragraphs from Chinese and English novels from which we construct 14668 parallel question-answer pairs via crowdsourced workers following a strict quality control procedure. We analyze BiPaR in depth and find that BiPaR offers good diversification in prefixes of questions answer types and relationships between questions and passages. We also observe that answering questions of novels requires reading comprehension skills of coreference resolution multi-sentence reasoning and understanding of implicit causality etc. With BiPaR we build monolingual multilingual and cross-lingual MRC baseline models. Even for the relatively simple monolingual MRC on this dataset experiments show that a strong BERT baseline is over 30 points behind human in terms of both EM and F1 score indicating that BiPaR provides a challenging testbed for monolingual multilingual and cross-lingual MRC on novels. The dataset is available at https://multinlp.github.io/BiPaR/.
