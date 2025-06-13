---
layout: publication
title: 'Fine-tuning And Evaluating Open-source Large Language Models For The Army Domain'
authors: Daniel C. Ruiz, John Sell
conference: "Arxiv"
year: 2024
bibkey: ruiz2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.20297'}
tags: ['ACL', 'RAG', 'Training Techniques', 'Tools', 'Applications', 'Fine-Tuning', 'Pretraining Methods']
---
In recent years, the widespread adoption of Large Language Models (LLMs) has
sparked interest in their potential for application within the military domain.
However, the current generation of LLMs demonstrate sub-optimal performance on
Army use cases, due to the prevalence of domain-specific vocabulary and jargon.
In order to fully leverage LLMs in-domain, many organizations have turned to
fine-tuning to circumvent the prohibitive costs involved in training new LLMs
from scratch. In light of this trend, we explore the viability of adapting
open-source LLMs for usage in the Army domain in order to address their
existing lack of domain-specificity. Our investigations have resulted in the
creation of three distinct generations of TRACLM, a family of LLMs fine-tuned
by The Research and Analysis Center (TRAC), Army Futures Command (AFC). Through
continuous refinement of our training pipeline, each successive iteration of
TRACLM displayed improved capabilities when applied to Army tasks and use
cases. Furthermore, throughout our fine-tuning experiments, we recognized the
need for an evaluation framework that objectively quantifies the Army
domain-specific knowledge of LLMs. To address this, we developed MilBench, an
extensible software framework that efficiently evaluates the Army knowledge of
a given LLM using tasks derived from doctrine and assessments. We share
preliminary results, models, methods, and recommendations on the creation of
TRACLM and MilBench. Our work significantly informs the development of LLM
technology across the DoD and augments senior leader decisions with respect to
artificial intelligence integration.
