---
layout: publication
title: 'Anah-v2: Scaling Analytical Hallucination Annotation Of Large Language Models'
authors: Yuzhe Gu, Ziwei Ji, Wenwei Zhang, Chengqi Lyu, Dahua Lin, Kai Chen
conference: "Arxiv"
year: 2024
bibkey: gu2024anah
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04693"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Applications']
---
Large language models (LLMs) exhibit hallucinations in long-form
question-answering tasks across various domains and wide applications. Current
hallucination detection and mitigation datasets are limited in domains and
sizes, which struggle to scale due to prohibitive labor costs and insufficient
reliability of existing hallucination annotators. To facilitate the scalable
oversight of LLM hallucinations, this paper introduces an iterative
self-training framework that simultaneously and progressively scales up the
hallucination annotation dataset and improves the accuracy of the hallucination
annotator. Based on the Expectation Maximization (EM) algorithm, in each
iteration, the framework first applies a hallucination annotation pipeline to
annotate a scaled dataset and then trains a more accurate hallucination
annotator on the dataset. This new hallucination annotator is adopted in the
hallucination annotation pipeline used for the next iteration. Extensive
experimental results demonstrate that the finally obtained hallucination
annotator with only 7B parameters surpasses the performance of GPT-4 and
obtains new state-of-the-art hallucination detection results on HaluEval and
HalluQA by zero-shot inference. Such an annotator can not only evaluate the
hallucination levels of various LLMs on the large-scale dataset but also help
to mitigate the hallucination of LLMs generations, with the Natural Language
Inference (NLI) metric increasing from 25% to 37% on HaluEval.
