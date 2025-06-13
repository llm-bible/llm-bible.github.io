---
layout: publication
title: 'Pragmatic Instruction Following And Goal Assistance Via Cooperative Language-guided Inverse Planning'
authors: Tan Zhi-xuan, Lance Ying, Vikash Mansinghka, Joshua B. Tenenbaum
conference: "Arxiv"
year: 2024
bibkey: zhixuan2024pragmatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17930"}
tags: ['Agentic', 'Multimodal Models', 'Model Architecture', 'RAG', 'GPT']
---
People often give instructions whose meaning is ambiguous without further
context, expecting that their actions or goals will disambiguate their
intentions. How can we build assistive agents that follow such instructions in
a flexible, context-sensitive manner? This paper introduces cooperative
language-guided inverse plan search (CLIPS), a Bayesian agent architecture for
pragmatic instruction following and goal assistance. Our agent assists a human
by modeling them as a cooperative planner who communicates joint plans to the
assistant, then performs multimodal Bayesian inference over the human's goal
from actions and language, using large language models (LLMs) to evaluate the
likelihood of an instruction given a hypothesized plan. Given this posterior,
our assistant acts to minimize expected goal achievement cost, enabling it to
pragmatically follow ambiguous instructions and provide effective assistance
even when uncertain about the goal. We evaluate these capabilities in two
cooperative planning domains (Doors, Keys & Gems and VirtualHome), finding that
CLIPS significantly outperforms GPT-4V, LLM-based literal instruction following
and unimodal inverse planning in both accuracy and helpfulness, while closely
matching the inferences and assistive judgments provided by human raters.
