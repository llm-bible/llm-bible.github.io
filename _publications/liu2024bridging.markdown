---
layout: publication
title: 'Bridging Context Gaps: Leveraging Coreference Resolution For Long Contextual Understanding'
authors: Yanming Liu, Xinyue Peng, Jiannan Cao, Shi Bo, Yanxin Shen, Tianyu Du, Sheng Cheng, Xun Wang, Jianwei Yin, Xuhong Zhang
conference: "Arxiv"
year: 2024
bibkey: liu2024bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01671"}
  - {name: "Code", url: "https://github.com/OceannTwT/LQCA"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Has Code']
---
Large language models (LLMs) have shown remarkable capabilities in natural
language processing; however, they still face difficulties when tasked with
understanding lengthy contexts and executing effective question answering.
These challenges often arise due to the complexity and ambiguity present in
longer texts. To enhance the performance of LLMs in such scenarios, we
introduce the Long Question Coreference Adaptation (LQCA) method. This
innovative framework focuses on coreference resolution tailored to long
contexts, allowing the model to identify and manage references effectively. The
LQCA method encompasses four key steps: resolving coreferences within
sub-documents, computing the distances between mentions, defining a
representative mention for coreference, and answering questions through mention
replacement. By processing information systematically, the framework provides
easier-to-handle partitions for LLMs, promoting better understanding.
Experimental evaluations on a range of LLMs and datasets have yielded positive
results, with a notable improvements on OpenAI-o1-mini and GPT-4o models,
highlighting the effectiveness of leveraging coreference resolution to bridge
context gaps in question answering. Our code is public at
https://github.com/OceannTwT/LQCA.
