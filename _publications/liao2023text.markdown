---
layout: publication
title: 'Text-to-image Generation For Abstract Concepts'
authors: Liao Jiayi, Chen Xu, Fu Qiang, Du Lun, He Xiangnan, Wang Xiang, Han Shi, Zhang Dongmei
conference: "Arxiv"
year: 2023
bibkey: liao2023text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.14623"}
tags: ['Prompting', 'RAG', 'Tools', 'Uncategorized']
---
Recent years have witnessed the substantial progress of large-scale models
across various domains, such as natural language processing and computer
vision, facilitating the expression of concrete concepts. Unlike concrete
concepts that are usually directly associated with physical objects, expressing
abstract concepts through natural language requires considerable effort, which
results from their intricate semantics and connotations. An alternative
approach is to leverage images to convey rich visual information as a
supplement. Nevertheless, existing Text-to-Image (T2I) models are primarily
trained on concrete physical objects and tend to fail to visualize abstract
concepts. Inspired by the three-layer artwork theory that identifies critical
factors, intent, object and form during artistic creation, we propose a
framework of Text-to-Image generation for Abstract Concepts (TIAC). The
abstract concept is clarified into a clear intent with a detailed definition to
avoid ambiguity. LLMs then transform it into semantic-related physical objects,
and the concept-dependent form is retrieved from an LLM-extracted form pattern
set. Information from these three aspects will be integrated to generate
prompts for T2I models via LLM. Evaluation results from human assessments and
our newly designed metric concept score demonstrate the effectiveness of our
framework in creating images that can sufficiently express abstract concepts.
