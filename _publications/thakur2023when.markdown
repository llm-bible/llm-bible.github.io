---
layout: publication
title: '"knowing When You Don''t Know": A Multilingual Relevance Assessment Dataset For Robust Retrieval-augmented Generation'
authors: Nandan Thakur, Luiz Bonifacio, Xinyu Zhang, Odunayo Ogundepo, Ehsan Kamalloo, David Alfonso-hermelo, Xiaoguang Li, Qun Liu, Boxing Chen, Mehdi Rezagholizadeh, Jimmy Lin
conference: "Arxiv"
year: 2023
bibkey: thakur2023when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11361"}
  - {name: "Code", url: "https://github.com/project-miracl/nomiracl"}
tags: ['Security', 'Model Architecture', 'RAG', 'GPT', 'Has Code', 'ACL']
---
Retrieval-Augmented Generation (RAG) grounds Large Language Model (LLM)
output by leveraging external knowledge sources to reduce factual
hallucinations. However, prior work lacks a comprehensive evaluation of
different language families, making it challenging to evaluate LLM robustness
against errors in external retrieved knowledge. To overcome this, we establish
NoMIRACL, a human-annotated dataset for evaluating LLM robustness in RAG across
18 typologically diverse languages. NoMIRACL includes both a non-relevant and a
relevant subset. Queries in the non-relevant subset contain passages judged as
non-relevant, whereas queries in the relevant subset include at least a single
judged relevant passage. We measure relevance assessment using: (i)
hallucination rate, measuring model tendency to hallucinate, when the answer is
not present in passages in the non-relevant subset, and (ii) error rate,
measuring model inaccuracy to recognize relevant passages in the relevant
subset.In our work, we observe that most models struggle to balance the two
capacities. Models such as LLAMA-2 and Orca-2 achieve over 88% hallucination
rate on the non-relevant subset. Mistral and LLAMA-3 hallucinate less but can
achieve up to a 74.9% error rate on the relevant subset. Overall, GPT-4 is
observed to provide the best tradeoff on both subsets, highlighting future work
necessary to improve LLM robustness. NoMIRACL dataset and evaluation code are
available at: https://github.com/project-miracl/nomiracl.
