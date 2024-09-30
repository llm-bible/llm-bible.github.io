---
layout: publication
title: 'Navigating Uncertainty: Optimizing API Dependency For Hallucination Reduction In Closed-book Question Answering'
authors: Erbacher Pierre, Falissar Louis, Guigue Vincent, Soulier Laure
conference: "Arxiv"
year: 2024
bibkey: erbacher2024navigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.01780"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
While Large Language Models (LLM) are able to accumulate and restore knowledge they are still prone to hallucination. Especially when faced with factual questions LLM cannot only rely on knowledge stored in parameters to guarantee truthful and correct answers. Augmenting these models with the ability to search on external information sources such as the web is a promising approach to ground knowledge to retrieve information. However searching in a large collection of documents introduces additional computational/time costs. An optimal behavior would be to query external resources only when the LLM is not confident about answers. In this paper we propose a new LLM able to self-estimate if it is able to answer directly or needs to request an external tool. We investigate a supervised approach by introducing a hallucination masking mechanism in which labels are generated using a close book question-answering task. In addition we propose to leverage parameter-efficient fine-tuning techniques to train our model on a small amount of data. Our model directly provides answers for (78.2) of the known queries and opts to search for (77.2) of the unknown ones. This results in the API being utilized only (62) of the time.
