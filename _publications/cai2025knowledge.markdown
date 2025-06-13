---
layout: publication
title: 'Knowledge Hierarchy Guided Biological-medical Dataset Distillation For Domain LLM Training'
authors: Xunxin Cai, Chengrui Wang, Qingqing Long, Yuanchun Zhou, Meng Xiao
conference: "Arxiv"
year: 2025
bibkey: cai2025knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15108"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Training Techniques', 'Prompting', 'Distillation']
---
The rapid advancement of large language models (LLMs) in biological-medical
applications has highlighted a gap between their potential and the limited
scale and often low quality of available open-source annotated textual
datasets. In addition, the inherent complexity of the biomedical knowledge
hierarchy significantly hampers efforts to bridge this gap.Can LLMs themselves
play a pivotal role in overcoming this limitation? Motivated by this question,
we investigate this challenge in the present study.We propose a framework that
automates the distillation of high-quality textual training data from the
extensive scientific literature. Our approach self-evaluates and generates
questions that are more closely aligned with the biomedical domain, guided by
the biomedical knowledge hierarchy through medical subject headings (MeSH).
This comprehensive framework establishes an automated workflow, thereby
eliminating the need for manual intervention. Furthermore, we conducted
comprehensive experiments to evaluate the impact of our framework-generated
data on downstream language models of varying sizes. Our approach substantially
improves question-answering tasks compared to pre-trained models from the life
sciences domain and powerful close-source models represented by GPT-4. Notably,
the generated AI-Ready dataset enabled the Llama3-70B base model to outperform
GPT-4 using MedPrompt with multiple times the number of parameters. Detailed
case studies and ablation experiments underscore the significance of each
component within our framework
