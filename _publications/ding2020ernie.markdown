---
layout: publication
title: "Ernie-doc: A Retrospective Long-document Modeling Transformer"
authors: Ding Siyu, Shang Junyuan, Wang Shuohuan, Sun Yu, Tian Hao, Wu Hua, Wang Haifeng
conference: "Arxiv"
year: 2020
bibkey: ding2020ernie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.15688"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Transformers are not suited for processing long documents due to their quadratically increasing memory and time consumption. Simply truncating a long document or applying the sparse attention mechanism will incur the context fragmentation problem or lead to an inferior modeling capability against comparable model sizes. In this paper we propose ERNIE-Doc a document-level language pretraining model based on Recurrence Transformers. Two well-designed techniques namely the retrospective feed mechanism and the enhanced recurrence mechanism enable ERNIE-Doc which has a much longer effective context length to capture the contextual information of a complete document. We pretrain ERNIE-Doc to explicitly learn the relationships among segments with an additional document-aware segment-reordering objective. Various experiments were conducted on both English and Chinese document-level tasks. ERNIE-Doc improved the state-of-the-art language modeling result of perplexity to 16.8 on WikiText-103. Moreover it outperformed competitive pretraining models by a large margin on most language understanding tasks such as text classification and question answering.
