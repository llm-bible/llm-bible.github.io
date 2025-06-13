---
layout: publication
title: 'ALR\(^2\): A Retrieve-then-reason Framework For Long-context Question Answering'
authors: Huayang Li, Pat Verga, Priyanka Sen, Bowen Yang, Vijay Viswanathan, Patrick Lewis, Taro Watanabe, Yixuan Su
conference: "Arxiv"
year: 2024
bibkey: li2024retrieve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03227"}
tags: ['Tools', 'Applications']
---
The context window of large language models (LLMs) has been extended
significantly in recent years. However, while the context length that the LLM
can process has grown, the capability of the model to accurately reason over
that context degrades noticeably. This occurs because modern LLMs often become
overwhelmed by the vast amount of information in the context; when answering
questions, the model must identify and reason over relevant evidence sparsely
distributed throughout the text. To alleviate the challenge of long-context
reasoning, we develop a retrieve-then-reason framework, enabling LLMs to reason
over relevant evidence collected during an intermediate retrieval step. We find
that modern LLMs struggle to accurately retrieve relevant facts and instead,
often hallucinate "retrieved facts", resulting in flawed reasoning and the
production of incorrect answers. To address these issues, we introduce ALR\\(^2\\),
a method that augments the long-context reasoning capability of LLMs via an
explicit two-stage procedure, i.e., aligning LLMs with the objectives of both
retrieval and reasoning. We demonstrate the efficacy of ALR\\(^2\\) for mitigating
performance degradation in long-context reasoning tasks. Through extensive
experiments on long-context QA benchmarks, we find our method to outperform
competitive baselines by large margins, achieving at least 8.4 and 7.9 EM gains
on the long-context versions of HotpotQA and SQuAD datasets, respectively.
