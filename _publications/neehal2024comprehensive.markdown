---
layout: publication
title: 'Ctbench: A Comprehensive Benchmark For Evaluating Language Model Capabilities In Clinical Trial Design'
authors: Nafis Neehal, Bowen Wang, Shayom Debopadhaya, Soham Dan, Keerthiram Murugesan, Vibha Anand, Kristin P. Bennett
conference: "Arxiv"
year: 2024
bibkey: neehal2024comprehensive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.17888'}
tags: ['Security', 'GPT', 'BERT', 'Model Architecture', 'Prompting']
---
CTBench is introduced as a benchmark to assess language models (LMs) in
aiding clinical study design. Given study-specific metadata, CTBench evaluates
AI models' ability to determine the baseline features of a clinical trial (CT),
which include demographic and relevant features collected at the trial's start
from all participants. These baseline features, typically presented in CT
publications (often as Table 1), are crucial for characterizing study cohorts
and validating results. Baseline features, including confounders and
covariates, are also necessary for accurate treatment effect estimation in
studies involving observational data. CTBench consists of two datasets:
"CT-Repo," containing baseline features from 1,690 clinical trials sourced from
clinicaltrials.gov, and "CT-Pub," a subset of 100 trials with more
comprehensive baseline features gathered from relevant publications. Two
LM-based evaluation methods are developed to compare the actual baseline
feature lists against LM-generated responses. "ListMatch-LM" and
"ListMatch-BERT" use GPT-4o and BERT scores (at various thresholds),
respectively, for evaluation. To establish baseline results, advanced prompt
engineering techniques using LLaMa3-70B-Instruct and GPT-4o in zero-shot and
three-shot learning settings are applied to generate potential baseline
features. The performance of GPT-4o as an evaluator is validated through
human-in-the-loop evaluations on the CT-Pub dataset, where clinical experts
confirm matches between actual and LM-generated features. The results highlight
a promising direction with significant potential for improvement, positioning
CTBench as a useful tool for advancing research on AI in CT design and
potentially enhancing the efficacy and robustness of CTs.
