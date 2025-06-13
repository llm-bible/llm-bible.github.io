---
layout: publication
title: 'Towards Top-down Reasoning: An Explainable Multi-agent Approach For Visual Question Answering'
authors: Zeqing Wang, Wentao Wan, Qiqing Lao, Runmeng Chen, Minjie Lang, Xiao Wang, Keze Wang, Liang Lin
conference: "Arxiv"
year: 2023
bibkey: wang2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17331"}
tags: ['Agentic', 'Tools', 'Applications', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recently, to comprehensively improve Vision Language Models (VLMs) for Visual
Question Answering (VQA), several methods have been proposed to further
reinforce the inference capabilities of VLMs to independently tackle VQA tasks
rather than some methods that only utilize VLMs as aids to Large Language
Models (LLMs). However, these methods ignore the rich common-sense knowledge
inside the given VQA image sampled from the real world. Thus, they cannot fully
use the powerful VLM for the given VQA question to achieve optimal performance.
Attempt to overcome this limitation and inspired by the human top-down
reasoning process, i.e., systematically exploring relevant issues to derive a
comprehensive answer, this work introduces a novel, explainable multi-agent
collaboration framework by leveraging the expansive knowledge of Large Language
Models (LLMs) to enhance the capabilities of VLMs themselves. Specifically, our
framework comprises three agents, i.e., Responder, Seeker, and Integrator, to
collaboratively answer the given VQA question by seeking its relevant issues
and generating the final answer in such a top-down reasoning process. The
VLM-based Responder agent generates the answer candidates for the question and
responds to other relevant issues. The Seeker agent, primarily based on LLM,
identifies relevant issues related to the question to inform the Responder
agent and constructs a Multi-View Knowledge Base (MVKB) for the given visual
scene by leveraging the build-in world knowledge of LLM. The Integrator agent
combines knowledge from the Seeker agent and the Responder agent to produce the
final VQA answer. Extensive and comprehensive evaluations on diverse VQA
datasets with a variety of VLMs demonstrate the superior performance and
interpretability of our framework over the baseline method in the zero-shot
setting without extra training cost.
