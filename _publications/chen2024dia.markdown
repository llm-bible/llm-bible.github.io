---
layout: publication
title: 'Dia-llama: Towards Large Language Model-driven CT Report Generation'
authors: Zhixuan Chen, Luyang Luo, Yequan Bie, Hao Chen
conference: "Arxiv"
year: 2024
bibkey: chen2024dia
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16386"}
tags: ['Tools', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Prompting']
---
Medical report generation has achieved remarkable advancements yet has still
been faced with several challenges. First, the inherent imbalance in the
distribution of normal and abnormal cases may lead models to exhibit a biased
focus on normal samples, resulting in unreliable diagnoses. Second, the
frequent occurrence of common template sentences in the reports may overwhelm
the critical abnormal information. Moreover, existing works focus on 2D chest
X-rays, leaving CT report generation underexplored due to the high-dimensional
nature of CT images and the limited availability of CT-report pairs. Recently,
LLM has shown a great ability to generate reliable answers with appropriate
prompts, which shed light on addressing the aforementioned challenges. In this
paper, we propose Dia-LLaMA, a framework to adapt the LLaMA2-7B for CT report
generation by incorporating diagnostic information as guidance prompts.
Considering the high dimension of CT, we leverage a pre-trained ViT3D with
perceiver to extract the visual information. To tailor the LLM for report
generation and emphasize abnormality, we extract additional diagnostic
information by referring to a disease prototype memory bank, which is updated
during training to capture common disease representations. Furthermore, we
introduce disease-aware attention to enable the model to adjust attention for
different diseases. Experiments on the chest CT dataset demonstrated that our
proposed method outperformed previous methods and achieved state-of-the-art on
both clinical efficacy performance and natural language generation metrics. The
code will be made publically available.
