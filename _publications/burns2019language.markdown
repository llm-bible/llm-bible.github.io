---
layout: publication
title: 'Language Features Matter: Effective Language Representations For Vision-language Tasks'
authors: Andrea Burns, Reuben Tan, Kate Saenko, Stan Sclaroff, Bryan A. Plummer
conference: "Arxiv"
year: 2019
bibkey: burns2019language
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1908.06327'}
tags: ['Attention Mechanism', 'RAG', 'Training Techniques', 'BERT', 'Model Architecture', 'Applications', 'Multimodal Models', 'Reinforcement Learning']
---
Shouldn't language and vision features be treated equally in vision-language
(VL) tasks? Many VL approaches treat the language component as an afterthought,
using simple language models that are either built upon fixed word embeddings
trained on text-only data or are learned from scratch. We believe that language
features deserve more attention, and conduct experiments which compare
different word embeddings, language models, and embedding augmentation steps on
five common VL tasks: image-sentence retrieval, image captioning, visual
question answering, phrase grounding, and text-to-clip retrieval. Our
experiments provide some striking results; an average embedding language model
outperforms an LSTM on retrieval-style tasks; state-of-the-art representations
such as BERT perform relatively poorly on vision-language tasks. From this
comprehensive set of experiments we propose a set of best practices for
incorporating the language component of VL tasks. To further elevate language
features, we also show that knowledge in vision-language problems can be
transferred across tasks to gain performance with multi-task training. This
multi-task training is applied to a new Graph Oriented Vision-Language
Embedding (GrOVLE), which we adapt from Word2Vec using WordNet and an original
visual-language graph built from Visual Genome, providing a ready-to-use
vision-language embedding: http://ai.bu.edu/grovle.
