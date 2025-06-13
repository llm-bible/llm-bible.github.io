---
layout: publication
title: 'Ambiguity-aware In-context Learning With Large Language Models'
authors: Lingyu Gao, Aditi Chaudhary, Krishna Srinivasan, Kazuma Hashimoto, Karthik Raman, Michael Bendersky
conference: "Arxiv"
year: 2023
bibkey: gao2023ambiguity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.07900"}
tags: ['Training Techniques', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) i.e. showing LLMs only a few task-specific
demonstrations has led to downstream gains with no task-specific fine-tuning
required. However, LLMs are sensitive to the choice of prompts, and therefore a
crucial research question is how to select good demonstrations for ICL. One
effective strategy is leveraging semantic similarity between the ICL
demonstrations and test inputs by using a text retriever, which however is
sub-optimal as that does not consider the LLM's existing knowledge about that
task. From prior work (Lyu et al., 2023), we already know that labels paired
with the demonstrations bias the model predictions. This leads us to our
hypothesis whether considering LLM's existing knowledge about the task,
especially with respect to the output label space can help in a better
demonstration selection strategy. Through extensive experimentation on three
text classification tasks, we find that it is beneficial to not only choose
semantically similar ICL demonstrations but also to choose those demonstrations
that help resolve the inherent label ambiguity surrounding the test example.
Interestingly, we find that including demonstrations that the LLM previously
mis-classified and also fall on the test example's decision boundary, brings
the most performance gain.
