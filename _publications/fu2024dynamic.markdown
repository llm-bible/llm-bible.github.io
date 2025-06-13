---
layout: publication
title: 'Dynamic Self-distillation Via Previous Mini-batches For Fine-tuning Small Language Models'
authors: Yao Fu, Yin Yu, Xiaotian Han, Runchao Li, Xianxuan Long, Haotian Yu, Pan Li
conference: "Arxiv"
year: 2024
bibkey: fu2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.16991"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'BERT', 'Distillation']
---
Knowledge distillation (KD) has become a widely adopted approach for
compressing large language models (LLMs) to reduce computational costs and
memory footprints. However, the availability of complex teacher models is a
prerequisite for running most KD pipelines. Thus, the traditional KD procedure
can be unachievable or budget-unfriendly, particularly when relying on
commercial LLMs like GPT4. In this regard, Self-distillation (SelfD) emerges as
an advisable alternative, enabling student models to learn without teachers'
guidance. Nonetheless, existing SelfD approaches for LMs often involve
architectural modifications, assuming the models are open-source, which may not
always be practical. In this work, we introduce a model-agnostic and
task-agnostic method named dynamic SelfD from the previous minibatch (DynSDPB),
which realizes current iterations' distillation from the last ones' generated
logits. Additionally, to address prediction inaccuracies during the early
iterations, we dynamically adjust the distillation influence and temperature
values to enhance the adaptability of fine-tuning. Furthermore, DynSDPB is a
novel fine-tuning policy that facilitates the seamless integration of existing
self-correction and self-training techniques for small language models (SLMs)
because they all require updating SLMs' parameters. We demonstrate the superior
performance of DynSDPB on both encoder-only LMs (e.g., BERT model families) and
decoder-only LMs (e.g., LLaMA model families), validating its effectiveness
across natural language understanding (NLU) and natural language generation
(NLG) benchmarks.
