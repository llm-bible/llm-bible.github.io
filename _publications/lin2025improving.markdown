---
layout: publication
title: 'Improving Phishing Email Detection Performance Of Small Large Language Models'
authors: Zijie Lin, Zikang Liu, Hanbo Fan
conference: "Arxiv"
year: 2025
bibkey: lin2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00034'}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models(LLMs) have demonstrated remarkable performance on many
natural language processing(NLP) tasks and have been employed in phishing email
detection research. However, in current studies, well-performing LLMs typically
contain billions or even tens of billions of parameters, requiring enormous
computational resources. To reduce computational costs, we investigated the
effectiveness of small-parameter LLMs for phishing email detection. These LLMs
have around 3 billion parameters and can run on consumer-grade GPUs. However,
small LLMs often perform poorly in phishing email detection task. To address
these issues, we designed a set of methods including Prompt Engineering,
Explanation Augmented Fine-tuning, and Model Ensemble to improve phishing email
detection capabilities of small LLMs. We validated the effectiveness of our
approach through experiments, significantly improving both accuracy and F1
score on the SpamAssassin and CEAS\_08 datasets. Furthermore, the fine-tuned
models demonstrated strong transferability, achieving robust performance across
multiple unseen phishing datasets, outperforming traditional baselines and
approaching standard-sized LLMs.
