---
layout: publication
title: 'Inquire, Interact, And Integrate: A Proactive Agent Collaborative Framework For Zero-shot Multimodal Medical Reasoning'
authors: Zishan Gu, Fenglin Liu, Changchang Yin, Ping Zhang
conference: "Arxiv"
year: 2024
bibkey: gu2024proactive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11640"}
tags: ['Agentic', 'Multimodal Models', 'Applications', 'Tools']
---
The adoption of large language models (LLMs) in healthcare has attracted
significant research interest. However, their performance in healthcare remains
under-investigated and potentially limited, due to i) they lack rich
domain-specific knowledge and medical reasoning skills; and ii) most
state-of-the-art LLMs are unimodal, text-only models that cannot directly
process multimodal inputs. To this end, we propose a multimodal medical
collaborative reasoning framework \textbf\{MultiMedRes\}, which incorporates a
learner agent to proactively gain essential information from domain-specific
expert models, to solve medical multimodal reasoning problems. Our method
includes three steps: i) \textbf\{Inquire\}: The learner agent first decomposes
given complex medical reasoning problems into multiple domain-specific
sub-problems; ii) \textbf\{Interact\}: The agent then interacts with
domain-specific expert models by repeating the ``ask-answer'' process to
progressively obtain different domain-specific knowledge; iii)
\textbf\{Integrate\}: The agent finally integrates all the acquired
domain-specific knowledge to accurately address the medical reasoning problem.
We validate the effectiveness of our method on the task of difference visual
question answering for X-ray images. The experiments demonstrate that our
zero-shot prediction achieves state-of-the-art performance, and even
outperforms the fully supervised methods. Besides, our approach can be
incorporated into various LLMs and multimodal LLMs to significantly boost their
performance.
