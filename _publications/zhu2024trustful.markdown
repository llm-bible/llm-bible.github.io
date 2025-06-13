---
layout: publication
title: 'Trustful Llms: Customizing And Grounding Text Generation With Knowledge Bases And Dual Decoders'
authors: Xiaofeng Zhu, Jaya Krishna Mandivarapu
conference: "EMNLP CustomNLP4U 2024"
year: 2024
bibkey: zhu2024trustful
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.07870'}
tags: ['Language Modeling', 'RAG', 'Security', 'GPT', 'Model Architecture', 'Applications']
---
Although people are impressed by the content generation skills of large
language models, the use of LLMs, such as ChatGPT, is limited by the domain
grounding of the content. The correctness and groundedness of the generated
content need to be based on a verified context, such as results from
Retrieval-Augmented Generation (RAG). One important issue when adapting LLMs to
a customized domain is that the generated responses are often incomplete, or
the additions are not verified and may even be hallucinated. Prior studies on
hallucination detection have focused on evaluation metrics, which are not
easily adaptable to dynamic domains and can be vulnerable to attacks like
jail-breaking. In this work, we propose 1) a post-processing algorithm that
leverages knowledge triplets in RAG context to correct hallucinations and 2) a
dual-decoder model that fuses RAG context to guide the generation process.
