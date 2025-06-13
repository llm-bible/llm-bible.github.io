---
layout: publication
title: 'Llms Are Also Effective Embedding Models: An In-depth Overview'
authors: Chongyang Tao, Tao Shen, Shen Gao, Junshuo Zhang, Zhen Li, Zhengwei Tao, Shuai Ma
conference: "Arxiv"
year: 2024
bibkey: tao2024llms
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12591'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Security', 'Model Architecture', 'Tools', 'Training Techniques', 'BERT', 'GPT', 'Prompting', 'Multimodal Models', 'Survey Paper', 'Reinforcement Learning', 'Ethics and Bias']
---
Large language models (LLMs) have revolutionized natural language processing
by achieving state-of-the-art performance across various tasks. Recently, their
effectiveness as embedding models has gained attention, marking a paradigm
shift from traditional encoder-only models like ELMo and BERT to decoder-only,
large-scale LLMs such as GPT, LLaMA, and Mistral. This survey provides an
in-depth overview of this transition, beginning with foundational techniques
before the LLM era, followed by LLM-based embedding models through two main
strategies to derive embeddings from LLMs. 1) Direct prompting: We mainly
discuss the prompt designs and the underlying rationale for deriving
competitive embeddings. 2) Data-centric tuning: We cover extensive aspects that
affect tuning an embedding model, including model architecture, training
objectives, data constructions, etc. Upon the above, we also cover advanced
methods, such as handling longer texts, and multilingual and cross-modal data.
Furthermore, we discuss factors affecting choices of embedding models, such as
performance/efficiency comparisons, dense vs sparse embeddings, pooling
strategies, and scaling law. Lastly, the survey highlights the limitations and
challenges in adapting LLMs for embeddings, including cross-task embedding
quality, trade-offs between efficiency and accuracy, low-resource,
long-context, data bias, robustness, etc. This survey serves as a valuable
resource for researchers and practitioners by synthesizing current
advancements, highlighting key challenges, and offering a comprehensive
framework for future work aimed at enhancing the effectiveness and efficiency
of LLMs as embedding models.
