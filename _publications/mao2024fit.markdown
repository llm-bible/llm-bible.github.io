---
layout: publication
title: 'FIT-RAG: Black-box RAG With Factual Information And Token Reduction'
authors: Yuren Mao, Xuemei Dong, Wenyi Xu, Yunjun Gao, Bin Wei, Ying Zhang
conference: "Arxiv"
year: 2024
bibkey: mao2024fit
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.14374'}
tags: ['Attention Mechanism', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Applications', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Due to the extraordinarily large number of parameters, fine-tuning Large
Language Models (LLMs) to update long-tail or out-of-date knowledge is
impractical in lots of applications. To avoid fine-tuning, we can alternatively
treat a LLM as a black-box (i.e., freeze the parameters of the LLM) and augment
it with a Retrieval-Augmented Generation (RAG) system, namely black-box RAG.
Recently, black-box RAG has achieved success in knowledge-intensive tasks and
has gained much attention. Existing black-box RAG methods typically fine-tune
the retriever to cater to LLMs' preferences and concatenate all the retrieved
documents as the input, which suffers from two issues: (1) Ignorance of Factual
Information. The LLM preferred documents may not contain the factual
information for the given question, which can mislead the retriever and hurt
the effectiveness of black-box RAG; (2) Waste of Tokens. Simply concatenating
all the retrieved documents brings large amounts of unnecessary tokens for
LLMs, which degenerates the efficiency of black-box RAG. To address these
issues, this paper proposes a novel black-box RAG framework which utilizes the
factual information in the retrieval and reduces the number of tokens for
augmentation, dubbed FIT-RAG. FIT-RAG utilizes the factual information by
constructing a bi-label document scorer. Besides, it reduces the tokens by
introducing a self-knowledge recognizer and a sub-document-level token reducer.
FIT-RAG achieves both superior effectiveness and efficiency, which is validated
by extensive experiments across three open-domain question-answering datasets:
TriviaQA, NQ and PopQA. FIT-RAG can improve the answering accuracy of
Llama2-13B-Chat by 14.3% on TriviaQA, 19.9% on NQ and 27.5% on PopQA,
respectively. Furthermore, it can save approximately half of the tokens on
average across the three datasets.
