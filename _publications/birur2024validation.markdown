---
layout: publication
title: 'VERA: Validation And Enhancement For Retrieval Augmented Systems'
authors: Nitin Aravind Birur, Tanay Baswa, Divyanshu Kumar, Jatan Loya, Sahil Agarwal, Prashanth Harshangi
conference: "Arxiv"
year: 2024
bibkey: birur2024validation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.15364'}
tags: ['Language Modeling', 'RAG', 'Training Techniques', 'Applications', 'Tools']
---
Large language models (LLMs) exhibit remarkable capabilities but often
produce inaccurate responses, as they rely solely on their embedded knowledge.
Retrieval-Augmented Generation (RAG) enhances LLMs by incorporating an external
information retrieval system, supplying additional context along with the query
to mitigate inaccuracies for a particular context. However, accuracy issues
still remain, as the model may rely on irrelevant documents or extrapolate
incorrectly from its training knowledge. To assess and improve the performance
of both the retrieval system and the LLM in a RAG framework, we propose
\textbf\{VERA\} (\textbf\{V\}alidation and \textbf\{E\}nhancement for
\textbf\{R\}etrieval \textbf\{A\}ugmented systems), a system designed to: 1)
Evaluate and enhance the retrieved context before response generation, and 2)
Evaluate and refine the LLM-generated response to ensure precision and minimize
errors. VERA employs an evaluator-cum-enhancer LLM that first checks if
external retrieval is necessary, evaluates the relevance and redundancy of the
retrieved context, and refines it to eliminate non-essential information.
Post-response generation, VERA splits the response into atomic statements,
assesses their relevance to the query, and ensures adherence to the context.
Our experiments demonstrate VERA's remarkable efficacy not only in improving
the performance of smaller open-source models, but also larger state-of-the art
models. These enhancements underscore VERA's potential to produce accurate and
relevant responses, advancing the state-of-the-art in retrieval-augmented
language modeling. VERA's robust methodology, combining multiple evaluation and
refinement steps, effectively mitigates hallucinations and improves retrieval
and response processes, making it a valuable tool for applications demanding
high accuracy and reliability in information generation. .
