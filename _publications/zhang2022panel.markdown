---
layout: publication
title: 'Poe: A Panel Of Experts For Generalized Automatic Dialogue Assessment'
authors: Chen Zhang, Luis Fernando D'haro, Qiquan Zhang, Thomas Friedrichs, Haizhou Li
conference: "Arxiv"
year: 2022
bibkey: zhang2022panel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.08992"}
tags: ['Agentic', 'Model Architecture', 'Few-Shot', 'RAG', 'Pretraining Methods', 'Transformer', 'Fine-Tuning']
---
Chatbots are expected to be knowledgeable across multiple domains, e.g. for
daily chit-chat, exchange of information, and grounding in emotional
situations. To effectively measure the quality of such conversational agents, a
model-based automatic dialogue evaluation metric (ADEM) is expected to perform
well across multiple domains. Despite significant progress, an ADEM that works
well in one domain does not necessarily generalize to another. This calls for a
dedicated network architecture for domain generalization. To tackle the
multi-domain dialogue evaluation task, we propose a Panel of Experts (PoE), a
multitask network that consists of a shared transformer encoder and a
collection of lightweight adapters. The shared encoder captures the general
knowledge of dialogues across domains, while each adapter specializes in one
specific domain and serves as a domain expert. To validate the idea, we
construct a high-quality multi-domain dialogue dataset leveraging data
augmentation and pseudo-labeling. The PoE network is comprehensively assessed
on 16 dialogue evaluation datasets spanning a wide range of dialogue domains.
It achieves state-of-the-art performance in terms of mean Spearman correlation
over all the evaluation datasets. It exhibits better zero-shot generalization
than existing state-of-the-art ADEMs and the ability to easily adapt to new
domains with few-shot transfer learning.
