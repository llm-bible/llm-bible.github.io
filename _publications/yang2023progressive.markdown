---
layout: publication
title: 'Progressive Evidence Refinement For Open-domain Multimodal Retrieval Question Answering'
authors: Shuwen Yang, Anran Wu, Xingjiao Wu, Luwei Xiao, Tianlong Ma, Cheng Jin, Liang He
conference: "Arxiv"
year: 2023
bibkey: yang2023progressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09696"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models']
---
Pre-trained multimodal models have achieved significant success in
retrieval-based question answering. However, current multimodal retrieval
question-answering models face two main challenges. Firstly, utilizing
compressed evidence features as input to the model results in the loss of
fine-grained information within the evidence. Secondly, a gap exists between
the feature extraction of evidence and the question, which hinders the model
from effectively extracting critical features from the evidence based on the
given question. We propose a two-stage framework for evidence retrieval and
question-answering to alleviate these issues. First and foremost, we propose a
progressive evidence refinement strategy for selecting crucial evidence. This
strategy employs an iterative evidence retrieval approach to uncover the
logical sequence among the evidence pieces. It incorporates two rounds of
filtering to optimize the solution space, thus further ensuring temporal
efficiency. Subsequently, we introduce a semi-supervised contrastive learning
training strategy based on negative samples to expand the scope of the question
domain, allowing for a more thorough exploration of latent knowledge within
known samples. Finally, in order to mitigate the loss of fine-grained
information, we devise a multi-turn retrieval and question-answering strategy
to handle multimodal inputs. This strategy involves incorporating multimodal
evidence directly into the model as part of the historical dialogue and
question. Meanwhile, we leverage a cross-modal attention mechanism to capture
the underlying connections between the evidence and the question, and the
answer is generated through a decoding generation approach. We validate the
model's effectiveness through extensive experiments, achieving outstanding
performance on WebQA and MultimodelQA benchmark tests.
