---
layout: publication
title: 'A Library Of LLM Intrinsics For Retrieval-augmented Generation'
authors: Marina Danilevsky, Kristjan Greenewald, Chulaka Gunasekara, Maeda Hanafi, Lihong He, Yannis Katsis, Krishnateja Killamsetty, Yatin Nandwani, Lucian Popa, Dinesh Raghu, Frederick Reiss, Vraj Shah, Khoi-nguyen Tran, Huaiyu Zhu, Luis Lastras
conference: "Arxiv"
year: 2025
bibkey: danilevsky2025library
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11704"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
In the developer community for large language models (LLMs), there is not yet
a clean pattern analogous to a software library, to support very large scale
collaboration. Even for the commonplace use case of Retrieval-Augmented
Generation (RAG), it is not currently possible to write a RAG application
against a well-defined set of APIs that are agreed upon by different LLM
providers. Inspired by the idea of compiler intrinsics, we propose some
elements of such a concept through introducing a library of LLM Intrinsics for
RAG. An LLM intrinsic is defined as a capability that can be invoked through a
well-defined API that is reasonably stable and independent of how the LLM
intrinsic itself is implemented. The intrinsics in our library are released as
LoRA adapters on HuggingFace, and through a software interface with clear
structured input/output characteristics on top of vLLM as an inference
platform, accompanied in both places with documentation and code. This article
describes the intended usage, training details, and evaluations for each
intrinsic, as well as compositions of multiple intrinsics.
