---
layout: publication
title: 'Reasoning-based AI For Startup Evaluation (R.A.I.S.E.): A Memory-augmented, Multi-step Decision Framework'
authors: Jack Preuveneers, Joseph Ternasky, Fuat Alican, Yigit Ihlamur
conference: "Arxiv"
year: 2025
bibkey: preuveneers2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12090"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'RAG', 'Interpretability and Explainability', 'Prompting']
---
We present a novel framework that bridges the gap between the
interpretability of decision trees and the advanced reasoning capabilities of
large language models (LLMs) to predict startup success. Our approach leverages
chain-of-thought prompting to generate detailed reasoning logs, which are
subsequently distilled into structured, human-understandable logical rules. The
pipeline integrates multiple enhancements - efficient data ingestion, a
two-step refinement process, ensemble candidate sampling, simulated
reinforcement learning scoring, and persistent memory - to ensure both stable
decision-making and transparent output. Experimental evaluations on curated
startup datasets demonstrate that our combined pipeline improves precision by
54% from 0.225 to 0.346 and accuracy by 50% from 0.46 to 0.70 compared to a
standalone OpenAI o3 model. Notably, our model achieves over 2x the precision
of a random classifier (16%). By combining state-of-the-art AI reasoning with
explicit rule-based explanations, our method not only augments traditional
decision-making processes but also facilitates expert intervention and
continuous policy refinement. This work lays the foundation for the
implementation of interpretable LLM-powered decision frameworks in high-stakes
investment environments and other domains that require transparent and
data-driven insights.
