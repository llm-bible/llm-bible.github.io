---
layout: publication
title: 'Text2chart31: Instruction Tuning For Chart Generation With Automatic Feedback'
authors: Fatemeh Pesaran Zadeh, Juyeon Kim, Jin-hwa Kim, Gunhee Kim
conference: "Arxiv"
year: 2024
bibkey: zadeh2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04064"}
  - {name: "Code", url: "https://github.com/fatemehpesaran310/Text2Chart31"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated strong capabilities across
various language tasks, notably through instruction-tuning methods. However,
LLMs face challenges in visualizing complex, real-world data through charts and
plots. Firstly, existing datasets rarely cover a full range of chart types,
such as 3D, volumetric, and gridded charts. Secondly, supervised fine-tuning
methods do not fully leverage the intricate relationships within rich datasets,
including text, code, and figures. To address these challenges, we propose a
hierarchical pipeline and a new dataset for chart generation. Our dataset,
Text2Chart31, includes 31 unique plot types referring to the Matplotlib
library, with 11.1K tuples of descriptions, code, data tables, and plots.
Moreover, we introduce a reinforcement learning-based instruction tuning
technique for chart generation tasks without requiring human feedback. Our
experiments show that this approach significantly enhances the model
performance, enabling smaller models to outperform larger open-source models
and be comparable to state-of-the-art proprietary models in data visualization
tasks. We make the code and dataset available at
https://github.com/fatemehpesaran310/Text2Chart31.
