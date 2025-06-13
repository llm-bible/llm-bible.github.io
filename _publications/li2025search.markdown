---
layout: publication
title: 'Search-o1: Agentic Search-enhanced Large Reasoning Models'
authors: Xiaoxi Li, Guanting Dong, Jiajie Jin, Yuyao Zhang, Yujia Zhou, Yutao Zhu, Peitian Zhang, Zhicheng Dou
conference: "Arxiv"
year: 2025
bibkey: li2025search
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.05366"}
  - {name: "Code", url: "https://github.com/sunnynexus/Search-o1"}
tags: ['Tools', 'Agentic', 'RAG', 'Reinforcement Learning', 'Has Code']
---
Large reasoning models (LRMs) like OpenAI-o1 have demonstrated impressive
long stepwise reasoning capabilities through large-scale reinforcement
learning. However, their extended reasoning processes often suffer from
knowledge insufficiency, leading to frequent uncertainties and potential
errors. To address this limitation, we introduce \textbf\{Search-o1\}, a
framework that enhances LRMs with an agentic retrieval-augmented generation
(RAG) mechanism and a Reason-in-Documents module for refining retrieved
documents. Search-o1 integrates an agentic search workflow into the reasoning
process, enabling dynamic retrieval of external knowledge when LRMs encounter
uncertain knowledge points. Additionally, due to the verbose nature of
retrieved documents, we design a separate Reason-in-Documents module to deeply
analyze the retrieved information before injecting it into the reasoning chain,
minimizing noise and preserving coherent reasoning flow. Extensive experiments
on complex reasoning tasks in science, mathematics, and coding, as well as six
open-domain QA benchmarks, demonstrate the strong performance of Search-o1.
This approach enhances the trustworthiness and applicability of LRMs in complex
reasoning tasks, paving the way for more reliable and versatile intelligent
systems. The code is available at
\url\{https://github.com/sunnynexus/Search-o1\}.
