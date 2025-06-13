---
layout: publication
title: 'One Language, Many Gaps: Evaluating Dialect Fairness And Robustness Of Large Language Models In Reasoning Tasks'
authors: Fangru Lin, Shaoguang Mao, Emanuele La Malfa, Valentin Hofmann, Adrian De Wynter, Xun Wang, Si-qing Chen, Michael Wooldridge, Janet B. Pierrehumbert, Furu Wei
conference: "Arxiv"
year: 2024
bibkey: lin2024one
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11005"}
  - {name: "Code", url: "https://github.com/fangru-lin/redial_dialect_robustness_fairness"}
tags: ['Security', 'Model Architecture', 'Fairness', 'Tools', 'Reinforcement Learning', 'GPT', 'Bias Mitigation', 'Ethics and Bias', 'Has Code']
---
Language is not monolithic. While benchmarks, including those designed for
multiple languages, are often used as proxies to evaluate the performance of
Large Language Models (LLMs), they tend to overlook the nuances of
within-language variation, and thus fail to model the experience of speakers of
non-standard dialects. Focusing on African American Vernacular English (AAVE),
we present the first study aimed at objectively assessing the fairness and
robustness of LLMs in handling dialects in canonical reasoning tasks, including
algorithm, math, logic, and integrated reasoning. We introduce \textbf\{ReDial\}
(\textbf\{Re\}asoning with \textbf\{Dial\}ect Queries), a benchmark containing
1.2K+ parallel query pairs in Standardized English and AAVE. We hire AAVE
speakers, including experts with computer science backgrounds, to rewrite seven
popular benchmarks, such as HumanEval and GSM8K. With ReDial, we evaluate
widely used LLMs, including GPT, Claude, Llama, Mistral, and the Phi model
families. Our findings reveal that \textbf\{almost all of these widely used
models show significant brittleness and unfairness to queries in AAVE\}. Our
work establishes a systematic and objective framework for analyzing LLM bias in
dialectal queries. Moreover, it highlights how mainstream LLMs provide unfair
service to dialect speakers in reasoning tasks, laying a critical foundation
for relevant future research. Code and data can be accessed at
https://github.com/fangru-lin/redial_dialect_robustness_fairness.
