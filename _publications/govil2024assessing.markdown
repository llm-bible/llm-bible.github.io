---
layout: publication
title: 'COBIAS: Assessing The Contextual Reliability Of Bias Benchmarks For Language Models'
authors: Priyanshul Govil, Hemang Jain, Vamshi Krishna Bonagiri, Aman Chadha, Ponnurangam Kumaraguru, Manas Gaur, Sanorita Dey
conference: "Arxiv"
year: 2024
bibkey: govil2024assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14889"}
tags: ['Ethics and Bias', 'Security', 'Tools', 'Bias Mitigation']
---
Large Language Models (LLMs) often inherit biases from the web data they are trained on, which contains stereotypes and prejudices. Current methods for evaluating and mitigating these biases rely on bias-benchmark datasets. These benchmarks measure bias by observing an LLM's behavior on biased statements. However, these statements lack contextual considerations of the situations they try to present. To address this, we introduce a contextual reliability framework, which evaluates model robustness to biased statements by considering the various contexts in which they may appear. We develop the Context-Oriented Bias Indicator and Assessment Score (COBIAS) to measure a biased statement's reliability in detecting bias, based on the variance in model behavior across different contexts. To evaluate the metric, we augmented 2,291 stereotyped statements from two existing benchmark datasets by adding contextual information. We show that COBIAS aligns with human judgment on the contextual reliability of biased statements (Spearman's \\(\rho = 0.65, p = 3.4 * 10^\{-60\}\\)) and can be used to create reliable benchmarks, which would assist bias mitigation works.
