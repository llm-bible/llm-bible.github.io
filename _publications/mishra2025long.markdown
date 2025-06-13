---
layout: publication
title: 'Long-context Non-factoid Question Answering In Indic Languages'
authors: Ritwik Mishra, Rajiv Ratn Shah, Ponnurangam Kumaraguru
conference: "Arxiv"
year: 2025
bibkey: mishra2025long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13615"}
  - {name: "Code", url: "https://github.com/ritwikmishra/IndicGenQA"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Interpretability', 'Fine-Tuning', 'Transformer', 'Has Code', 'Interpretability and Explainability', 'Applications', 'Attention Mechanism']
---
Question Answering (QA) tasks, which involve extracting answers from a given
context, are relatively straightforward for modern Large Language Models (LLMs)
when the context is short. However, long contexts pose challenges due to the
quadratic complexity of the self-attention mechanism. This challenge is
compounded in Indic languages, which are often low-resource. This study
explores context-shortening techniques, including Open Information Extraction
(OIE), coreference resolution, Answer Paragraph Selection (APS), and their
combinations, to improve QA performance. Compared to the baseline of
unshortened (long) contexts, our experiments on four Indic languages (Hindi,
Tamil, Telugu, and Urdu) demonstrate that context-shortening techniques yield
an average improvement of 4% in semantic scores and 47% in token-level scores
when evaluated on three popular LLMs without fine-tuning. Furthermore, with
fine-tuning, we achieve an average increase of 2% in both semantic and
token-level scores. Additionally, context-shortening reduces computational
overhead. Explainability techniques like LIME and SHAP reveal that when the APS
model confidently identifies the paragraph containing the answer, nearly all
tokens within the selected text receive high relevance scores. However, the
study also highlights the limitations of LLM-based QA systems in addressing
non-factoid questions, particularly those requiring reasoning or debate.
Moreover, verbalizing OIE-generated triples does not enhance system
performance. These findings emphasize the potential of context-shortening
techniques to improve the efficiency and effectiveness of LLM-based QA systems,
especially for low-resource languages. The source code and resources are
available at https://github.com/ritwikmishra/IndicGenQA.
