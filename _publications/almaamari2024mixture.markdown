---
layout: publication
title: Mixture Of Modular Experts: Distilling Knowledge From A Multilingual Teacher Into Specialized Modular Language Models
authors: Al-maamari Mohammed, Amor Mehdi Ben, Granitzer Michael
conference: "Arxiv"
year: 2024
bibkey: almaamari2024mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19610"}
  - {name: "Code", url: "https://zenodo.org/doi/10.5281/zenodo.12677631),"}
  - {name: "Code", url: "https://github.com/padas-lab-de/multi-language-dataset-creator),"}
  - {name: "Code", url: "https://github.com/ModMaamari/mixture-modular-experts)"}
tags: ['Distillation', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
This research combines Knowledge Distillation (KD) and Mixture of Experts (MoE) to develop modular efficient multilingual language models. Key objectives include evaluating adaptive versus fixed alpha methods in KD and comparing modular MoE architectures for handling multi-domain inputs and preventing catastrophic forgetting. KD compresses large language models (LLMs) into smaller efficient models while MoE enhances modularity with specialized tasks. Experiments showed similar performance for both KD methods with marginal improvements from adaptive alpha. A combined loss approach provided more stable learning. The router trained to classify input sequences into English French German or Python achieved 99.9537; precision recall and F1 score with Logistic Regression being the most effective classifier. Evaluations of modular MoE architectures revealed that Pre-trained Language Experts (PLE) and Joint Expert Embedding Training (JEET) performed similarly while the MoE with Common Expert (MoE-CE) setup showed slightly lower performance. Including a common expert in MoE-CE improved its performance. Studies on catastrophic forgetting indicated that sequential training led to significant forgetting while single-session training with balanced batches and the MoE approach mitigated this issue. The MoE architecture preserved knowledge across multiple languages effectively. The research contributes open-sourced resources including the dataset (https://zenodo.org/doi/10.5281/zenodo.12677631), a balanced dataset creation tool (https://github.com/padas-lab-de/multi-language-dataset-creator), and the research codebase (https://github.com/ModMaamari/mixture-modular-experts)."
