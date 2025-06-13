---
layout: publication
title: 'To Retrieve Or Not To Retrieve? Uncertainty Detection For Dynamic Retrieval Augmented Generation'
authors: Kaustubh D. Dhole
conference: "Arxiv"
year: 2025
bibkey: dhole2025retrieve
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.09292'}
tags: ['Reinforcement Learning', 'RAG', 'Applications']
---
Retrieval-Augmented Generation equips large language models with the
capability to retrieve external knowledge, thereby mitigating hallucinations by
incorporating information beyond the model's intrinsic abilities. However, most
prior works have focused on invoking retrieval deterministically, which makes
it unsuitable for tasks such as long-form question answering. Instead,
dynamically performing retrieval by invoking it only when the underlying LLM
lacks the required knowledge can be more efficient. In this context, we delve
deeper into the question, "To Retrieve or Not to Retrieve?" by exploring
multiple uncertainty detection methods. We evaluate these methods for the task
of long-form question answering, employing dynamic retrieval, and present our
comparisons. Our findings suggest that uncertainty detection metrics, such as
Degree Matrix Jaccard and Eccentricity, can reduce the number of retrieval
calls by almost half, with only a slight reduction in question-answering
accuracy.
