---
layout: publication
title: 'Crimson: Empowering Strategic Reasoning In Cybersecurity Through Large Language Models'
authors: Jiandong Jin, Bowen Tang, Mingxuan Ma, Xiao Liu, Yunfei Wang, Qingnan Lai, Jia Yang, Changling Zhou
conference: "Arxiv"
year: 2024
bibkey: jin2024empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.00878"}
tags: ['Fine-Tuning', 'GPT', 'RAG', 'Model Architecture', 'Security', 'Training Techniques', 'Pretraining Methods']
---
We introduces Crimson, a system that enhances the strategic reasoning
capabilities of Large Language Models (LLMs) within the realm of cybersecurity.
By correlating CVEs with MITRE ATT&CK techniques, Crimson advances threat
anticipation and strategic defense efforts. Our approach includes defining and
evaluating cybersecurity strategic tasks, alongside implementing a
comprehensive human-in-the-loop data-synthetic workflow to develop the
CVE-to-ATT&CK Mapping (CVEM) dataset. We further enhance LLMs' reasoning
abilities through a novel Retrieval-Aware Training (RAT) process and its
refined iteration, RAT-R.
  Our findings demonstrate that an LLM fine-tuned with our techniques,
possessing 7 billion parameters, approaches the performance level of GPT-4,
showing markedly lower rates of hallucination and errors, and surpassing other
models in strategic reasoning tasks. Moreover, domain-specific fine-tuning of
embedding models significantly improves performance within cybersecurity
contexts, underscoring the efficacy of our methodology. By leveraging Crimson
to convert raw vulnerability data into structured and actionable insights, we
bolster proactive cybersecurity defenses.
