---
layout: publication
title: 'AI Agents May Be Worth The Hype But Not The Resources (yet): An Initial Exploration Of Machine Translation Quality And Costs In Three Language Pairs In The Legal And News Domains'
authors: Vicent Briva Iglesias, Gokhan Dogru
conference: "Arxiv"
year: 2025
bibkey: iglesias2025ai
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01560"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Efficiency and Optimization', 'Applications', 'Model Architecture']
---
Large language models (LLMs) and multi-agent orchestration are touted as the
next leap in machine translation (MT), but their benefits relative to
conventional neural MT (NMT) remain unclear. This paper offers an empirical
reality check. We benchmark five paradigms, Google Translate (strong NMT
baseline), GPT-4o (general-purpose LLM), o1-preview (reasoning-enhanced LLM),
and two GPT-4o-powered agentic workflows (sequential three-stage and iterative
refinement), on test data drawn from a legal contract and news prose in three
English-source pairs: Spanish, Catalan and Turkish. Automatic evaluation is
performed with COMET, BLEU, chrF2 and TER; human evaluation is conducted with
expert ratings of adequacy and fluency; efficiency with total input-plus-output
token counts mapped to April 2025 pricing.
  Automatic scores still favour the mature NMT system, which ranks first in
seven of twelve metric-language combinations; o1-preview ties or places second
in most remaining cases, while both multi-agent workflows trail. Human
evaluation reverses part of this narrative: o1-preview produces the most
adequate and fluent output in five of six comparisons, and the iterative agent
edges ahead once, indicating that reasoning layers capture semantic nuance
undervalued by surface metrics. Yet these qualitative gains carry steep costs.
The sequential agent consumes roughly five times, and the iterative agent
fifteen times, the tokens used by NMT or single-pass LLMs.
  We advocate multidimensional, cost-aware evaluation protocols and highlight
research directions that could tip the balance: leaner coordination strategies,
selective agent activation, and hybrid pipelines combining single-pass LLMs
with targeted agent intervention.
