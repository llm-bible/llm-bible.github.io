---
layout: publication
title: 'MARAGE: Transferable Multi-model Adversarial Attack For Retrieval-augmented Generation Data Extraction'
authors: Xiao Hu, Eric Liu, Weizhou Wang, Xiangyu Guo, David Lie
conference: "Arxiv"
year: 2025
bibkey: hu2025transferable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04360"}
tags: ['Security', 'Model Architecture', 'Efficiency and Optimization', 'Tools', 'RAG', 'Prompting']
---
Retrieval-Augmented Generation (RAG) offers a solution to mitigate
hallucinations in Large Language Models (LLMs) by grounding their outputs to
knowledge retrieved from external sources. The use of private resources and
data in constructing these external data stores can expose them to risks of
extraction attacks, in which attackers attempt to steal data from these private
databases. Existing RAG extraction attacks often rely on manually crafted
prompts, which limit their effectiveness. In this paper, we introduce a
framework called MARAGE for optimizing an adversarial string that, when
appended to user queries submitted to a target RAG system, causes outputs
containing the retrieved RAG data verbatim. MARAGE leverages a continuous
optimization scheme that integrates gradients from multiple models with
different architectures simultaneously to enhance the transferability of the
optimized string to unseen models. Additionally, we propose a strategy that
emphasizes the initial tokens in the target RAG data, further improving the
attack's generalizability. Evaluations show that MARAGE consistently
outperforms both manual and optimization-based baselines across multiple LLMs
and RAG datasets, while maintaining robust transferability to previously unseen
models. Moreover, we conduct probing tasks to shed light on the reasons why
MARAGE is more effective compared to the baselines and to analyze the impact of
our approach on the model's internal state.
