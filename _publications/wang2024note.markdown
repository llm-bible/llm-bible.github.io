---
layout: publication
title: 'Deepnote: Note-centric Deep Retrieval-augmented Generation'
authors: Ruobing Wang, Qingfei Zhao, Yukun Yan, Daren Zha, Yuxuan Chen, Shi Yu, Zhenghao Liu, Yixuan Wang, Shuo Wang, Xu Han, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: wang2024note
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08821"}
  - {name: "Code", url: "https://github.com/thunlp/DeepNote"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Reinforcement Learning', 'Has Code']
---
Retrieval-Augmented Generation (RAG) mitigates factual errors and
hallucinations in Large Language Models (LLMs) for question-answering (QA) by
incorporating external knowledge. However, existing adaptive RAG methods rely
on LLMs to predict retrieval timing and directly use retrieved information for
generation, often failing to reflect real information needs and fully leverage
retrieved knowledge. We develop DeepNote, an adaptive RAG framework that
achieves in-depth and robust exploration of knowledge sources through
note-centric adaptive retrieval. DeepNote employs notes as carriers for
refining and accumulating knowledge. During in-depth exploration, it uses these
notes to determine retrieval timing, formulate retrieval queries, and
iteratively assess knowledge growth, ultimately leveraging the best note for
answer generation. Extensive experiments and analyses demonstrate that DeepNote
significantly outperforms all baselines (+10.2% to +20.1%) and exhibits the
ability to gather knowledge with both high density and quality. Additionally,
DPO further improves the performance of DeepNote. The code and data are
available at https://github.com/thunlp/DeepNote.
