---
layout: publication
title: 'Temporally Consistent Factuality Probing For Large Language Models'
authors: Ashutosh Bajpai, Aaryan Goyal, Atif Anwer, Tanmoy Chakraborty
conference: "Arxiv"
year: 2024
bibkey: bajpai2024temporally
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14065'}
tags: ['Reinforcement Learning', 'Agentic', 'Tools']
---
The prolific use of Large Language Models (LLMs) as an alternate knowledge
base requires them to be factually consistent, necessitating both correctness
and consistency traits for paraphrased queries. Recently, significant attempts
have been made to benchmark datasets and metrics to evaluate LLMs for these
traits. However, structural simplicity (subject-relation-object) and
contemporary association in their query formulation limit the broader
definition of factuality and consistency. In this study, we introduce TeCFaP, a
novel Temporally Consistent Factuality Probe task to expand the consistent
factuality probe in the temporal dimension. To this end, we propose TEMP-COFAC,
a high-quality dataset of prefix-style English query paraphrases. Subsequently,
we extend the definitions of existing metrics to represent consistent
factuality across temporal dimension. We experiment with a diverse set of LLMs
and find most of them performing poorly on TeCFaP. Next, we propose a novel
solution CoTSeLF (Consistent-Time-Sensitive Learning Framework) combining
multi-task instruction tuning (MT-IT) with consistent-time-sensitive
reinforcement learning (CTSRL) to improve temporally consistent factuality in
LLMs. Our experiments demonstrate the efficacy of CoTSeLF over several
baselines.
