---
layout: publication
title: 'Review-then-refine: A Dynamic Framework For Multi-hop Question Answering With Temporal Adaptability'
authors: Xiangsen Chen, Xuming Hu, Nan Tang
conference: "Arxiv"
year: 2024
bibkey: chen2024review
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15101"}
tags: ['RAG', 'Applications', 'Survey Paper', 'Tools']
---
Retrieve-augmented generation (RAG) frameworks have emerged as a promising
solution to multi-hop question answering(QA) tasks since it enables large
language models (LLMs) to incorporate external knowledge and mitigate their
inherent knowledge deficiencies. Despite this progress, existing RAG
frameworks, which usually follows the retrieve-then-read paradigm, often
struggle with multi-hop QA with temporal information since it has difficulty
retrieving and synthesizing accurate time-related information. To address the
challenge, this paper proposes a novel framework called review-then-refine,
which aims to enhance LLM performance in multi-hop QA scenarios with temporal
information. Our approach begins with a review phase, where decomposed
sub-queries are dynamically rewritten with temporal information, allowing for
subsequent adaptive retrieval and reasoning process. In addition, we implement
adaptive retrieval mechanism to minimize unnecessary retrievals, thus reducing
the potential for hallucinations. In the subsequent refine phase, the LLM
synthesizes the retrieved information from each sub-query along with its
internal knowledge to formulate a coherent answer. Extensive experimental
results across multiple datasets demonstrate the effectiveness of our proposed
framework, highlighting its potential to significantly improve multi-hop QA
capabilities in LLMs.
