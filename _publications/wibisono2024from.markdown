---
layout: publication
title: 'From Unstructured Data To In-context Learning: Exploring What Tasks Can Be Learned And When'
authors: Kevin Christian Wibisono, Yixin Wang
conference: "Arxiv"
year: 2024
bibkey: wibisono2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00131"}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) like transformers demonstrate impressive
in-context learning (ICL) capabilities, allowing them to make predictions for
new tasks based on prompt exemplars without parameter updates. While existing
ICL theories often assume structured training data resembling ICL tasks (e.g.,
x-y pairs for linear regression), LLMs are typically trained unsupervised on
unstructured text, such as web content, which lacks clear parallels to tasks
like word analogy. To address this gap, we examine what enables ICL in models
trained on unstructured data, focusing on critical sequence model requirements
and training data structure. We find that many ICL capabilities can emerge
simply from co-occurrence of semantically related word pairs in unstructured
data; word analogy completion, for example, can provably arise purely through
co-occurrence modeling, using classical language models like continuous bag of
words (CBOW), without needing positional information or attention mechanisms.
However, positional information becomes crucial for logic reasoning tasks
requiring generalization to unseen tokens. Finally, we identify two cases where
ICL fails: one in logic reasoning tasks that require generalizing to new,
unseen patterns, and another in analogy completion where relevant word pairs
appear only in fixed training positions. These findings suggest that LLMs' ICL
abilities depend heavily on the structural elements within their training data.
