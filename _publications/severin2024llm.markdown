---
layout: publication
title: 'LLM-KT: A Versatile Framework For Knowledge Transfer From Large Language Models To Collaborative Filtering'
authors: Nikita Severin, Aleksei Ziablitsev, Yulia Savelyeva, Valeriy Tashchilin, Ivan Bulychev, Mikhail Yushkov, Artem Kushneruk, Amaliya Zaryvnykh, Dmitrii Kiselev, Andrey Savchenko, Ilya Makarov
conference: "Arxiv"
year: 2024
bibkey: severin2024llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00556'}
tags: ['RAG', 'Tools']
---
We present LLM-KT, a flexible framework designed to enhance collaborative
filtering (CF) models by seamlessly integrating LLM (Large Language
Model)-generated features. Unlike existing methods that rely on passing
LLM-generated features as direct inputs, our framework injects these features
into an intermediate layer of any CF model, allowing the model to reconstruct
and leverage the embeddings internally. This model-agnostic approach works with
a wide range of CF models without requiring architectural changes, making it
adaptable to various recommendation scenarios. Our framework is built for easy
integration and modification, providing researchers and developers with a
powerful tool for extending CF model capabilities through efficient knowledge
transfer. We demonstrate its effectiveness through experiments on the MovieLens
and Amazon datasets, where it consistently improves baseline CF models.
Experimental studies showed that LLM-KT is competitive with the
state-of-the-art methods in context-aware settings but can be applied to a
broader range of CF models than current approaches.
