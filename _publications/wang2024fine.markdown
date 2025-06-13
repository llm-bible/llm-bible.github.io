---
layout: publication
title: 'Hammerbench: Fine-grained Function-calling Evaluation In Real Mobile Device Scenarios'
authors: Jun Wang, Jiamu Zhou, Muning Wen, Xiaoyun Mo, Haoyu Zhang, Qiqiang Lin, Cheng Jin, Xihuai Wang, Weinan Zhang, Qiuying Peng, Jun Wang
conference: "Arxiv"
year: 2024
bibkey: wang2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16516"}
tags: ['Agentic', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Security']
---
Evaluating the performance of LLMs in multi-turn human-agent interactions
presents significant challenges, particularly due to the complexity and
variability of user behavior. In this paper, we introduce HammerBench, a novel
benchmark framework for assessing LLMs' function-calling capabilities in
real-world, multi-turn dialogues. HammerBench simulates diverse mobile
assistant use cases, incorporating imperfect instructions, dynamic
question-answer trajectories, intent and argument shifts, and the indirect use
of external information through pronouns. To construct this benchmark, we
curate a comprehensive dataset derived from popular mobile app functionalities
and anonymized user logs, complemented by a cost-effective data generation
pipeline leveraging open-source models. HammerBench is further augmented with
fine-grained interaction snapshots and metrics, enabling detailed evaluation of
function-calling performance across individual conversational turns. We
demonstrate the effectiveness of HammerBench by evaluating several leading LLMs
and uncovering key performance trends. Our experiments reveal that different
types of parameter name errors are a significant source of failure across
different interaction scenarios, highlighting critical areas for further
improvement in LLM robustness for mobile assistant applications.
