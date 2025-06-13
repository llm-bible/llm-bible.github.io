---
layout: publication
title: 'Long-term Ad Memorability: Understanding & Generating Memorable Ads'
authors: Harini Si, Somesh Singh, Yaman K Singla, Aanisha Bhattacharyya, Veeky Baths, Changyou Chen, Rajiv Ratn Shah, Balaji Krishnamurthy
conference: "Arxiv"
year: 2023
bibkey: si2023long
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.00378'}
  - {name: "Code", url: 'https://behavior-in-the-wild.github.io/memorability'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code', 'Multimodal Models']
---
Despite the importance of long-term memory in marketing and brand building,
until now, there has been no large-scale study on the memorability of ads. All
previous memorability studies have been conducted on short-term recall on
specific content types like action videos. On the other hand, long-term
memorability is crucial for the advertising industry, and ads are almost always
highly multimodal. Therefore, we release the first memorability dataset,
LAMBDA, consisting of 1749 participants and 2205 ads covering 276 brands.
Running statistical tests over different participant subpopulations and ad
types, we find many interesting insights into what makes an ad memorable, e.g.,
fast-moving ads are more memorable than those with slower scenes; people who
use ad-blockers remember a lower number of ads than those who don't. Next, we
present a model, Henry, to predict the memorability of a content. Henry
achieves state-of-the-art performance across all prominent literature
memorability datasets. It shows strong generalization performance with better
results in 0-shot on unseen datasets. Finally, with the intent of memorable ad
generation, we present a scalable method to build a high-quality memorable ad
generation model by leveraging automatically annotated data. Our approach, SEED
(Self rEwarding mEmorability Modeling), starts with a language model trained on
LAMBDA as seed data and progressively trains an LLM to generate more memorable
ads. We show that the generated advertisements have 44% higher memorability
scores than the original ads. We release this large-scale ad dataset,
UltraLAMBDA, consisting of 5 million ads. Our code and the datasets, LAMBDA and
UltraLAMBDA, are open-sourced at
https://behavior-in-the-wild.github.io/memorability.
