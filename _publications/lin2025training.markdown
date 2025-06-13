---
layout: publication
title: 'Training Llms For Ehr-based Reasoning Tasks Via Reinforcement Learning'
authors: Jiacheng Lin, Zhenbang Wu, Jimeng Sun
conference: "Arxiv"
year: 2025
bibkey: lin2025training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24105"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability', 'Applications']
---
We present EHRMIND, a practical recipe for adapting large language models (LLMs) to complex clinical reasoning tasks using reinforcement learning with verifiable rewards (RLVR). While RLVR has succeeded in mathematics and coding, its application to healthcare contexts presents unique challenges due to the specialized knowledge and reasoning required for electronic health record (EHR) interpretation. Our pilot study on the MEDCALC benchmark reveals two key failure modes: (1) misapplied knowledge, where models possess relevant medical knowledge but apply it incorrectly, and (2) missing knowledge, where models lack essential domain knowledge. To address these cases, EHRMIND applies a two-stage solution: a lightweight supervised fine-tuning (SFT) warm-up that injects missing domain knowledge, stabilizes subsequent training, and encourages structured, interpretable outputs; followed by RLVR, which reinforces outcome correctness and refines the model's decision-making. We demonstrate the effectiveness of our method across diverse clinical applications, including medical calculations (MEDCALC), patient-trial matching (TREC CLINICAL TRIALS), and disease diagnosis (EHRSHOT). EHRMIND delivers consistent gains in accuracy, interpretability, and cross-task generalization. These findings offer practical guidance for applying RLVR to enhance LLM capabilities in healthcare settings.
