---
layout: publication
title: 'Improving Physics Reasoning In Large Language Models Using Mixture Of Refinement Agents'
authors: Raj Jaiswal, Dhruv Jain, Harsh Parimal Popat, Avinash Anand, Abhishek Dharmadhikari, Atharva Marathe, Rajiv Ratn Shah
conference: "Arxiv"
year: 2024
bibkey: jaiswal2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.00821'}
tags: ['Agentic', 'GPT', 'Tools', 'Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) demonstrate remarkable capabilities in various
reasoning tasks. However, they encounter significant challenges when it comes
to scientific reasoning, particularly in physics, which requires not only
mathematical reasoning but also factual and conceptual understanding. When
addressing complex physics problems, LLMs typically face three key issues:
problem miscomprehension, incorrect concept application, and computational
errors. While each of these problems can be addressed individually, there is a
need for a generalized approach that can tackle all three issues
simultaneously. To address this, we introduce Mixture of Refinement Agents
(MoRA), a novel agentic refinement framework that iteratively refines the LLM
generated base solution by correcting the aforementioned errors, resulting in a
significant performance improvement for open-source LLMs. Our approach aims to
bridge the gap between opensource LLMs and GPT-4o by utilizing the latter as
error identifier to guide these refinement agents. We evaluate our approach on
the SciEval and MMLU subsets along with our own physics dataset (PhysicsQA).
MoRA significantly improves the performance of Llama-3-70B and Gemma-2-27B on
these datasets, achieving up to a 16% increase in final answer accuracy.
