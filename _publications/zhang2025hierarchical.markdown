---
layout: publication
title: 'Himate: A Hierarchical Multi-agent Framework For Machine Translation Evaluation'
authors: Shijie Zhang, Renhao Li, Songsheng Wang, Philipp Koehn, Min Yang, Derek F. Wong
conference: "Arxiv"
year: 2025
bibkey: zhang2025hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16281"}
  - {name: "Code", url: "https://anonymous.4open.science/r/HiMATE-Anony"}
tags: ['Agentic', 'Tools', 'RAG', 'Has Code', 'Applications']
---
The advancement of Large Language Models (LLMs) enables flexible and interpretable automatic evaluations. In the field of machine translation evaluation, utilizing LLMs with translation error annotations based on Multidimensional Quality Metrics (MQM) yields more human-aligned judgments. However, current LLM-based evaluation methods still face challenges in accurately identifying error spans and assessing their severity. In this paper, we propose HiMATE, a Hierarchical Multi-Agent Framework for Machine Translation Evaluation. We argue that existing approaches inadequately exploit the fine-grained structural and semantic information within the MQM hierarchy. To address this, we develop a hierarchical multi-agent system grounded in the MQM error typology, enabling granular evaluation of subtype errors. Two key strategies are incorporated to further mitigate systemic hallucinations within the framework: the utilization of the model's self-reflection capability and the facilitation of agent discussion involving asymmetric information. Empirically, HiMATE outperforms competitive baselines across different datasets in conducting human-aligned evaluations. Further analyses underscore its significant advantage in error span detection and severity assessment, achieving an average F1-score improvement of 89% over the best-performing baseline. We make our code and data publicly available at https://anonymous.4open.science/r/HiMATE-Anony.
