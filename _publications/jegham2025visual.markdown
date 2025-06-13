---
layout: publication
title: 'Visual Reasoning Evaluation Of Grok, Deepseek Janus, Gemini, Qwen, Mistral, And Chatgpt'
authors: Nidhal Jegham, Marwan Abdelatti, Abdeltawab Hendawi
conference: "Arxiv"
year: 2025
bibkey: jegham2025visual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.16428'}
tags: ['Ethics and Bias', 'GPT', 'Multimodal Models', 'Model Architecture']
---
Traditional evaluations of multimodal large language models (LLMs) have been
limited by their focus on single-image reasoning, failing to assess crucial
aspects like contextual understanding, reasoning stability, and uncertainty
calibration. This study addresses these limitations by introducing a novel
benchmark that integrates multi-image reasoning tasks with rejection-based
evaluation and positional bias detection. To evaluate these dimensions, we
further introduce entropy as a novel metric for quantifying reasoning
consistency across reordered answer variants. We applied this benchmark to
assess Grok 3, ChatGPT-4o, ChatGPT-o1, Gemini 2.0 Flash Experimental, DeepSeek
Janus models, Qwen2.5-VL-72B-Instruct, QVQ-72B-Preview, and Pixtral 12B across
eight visual reasoning tasks, including difference spotting and diagram
interpretation. Our findings reveal ChatGPT-o1 leading in overall accuracy
(82.5%) and rejection accuracy (70.0%), closely followed by Gemini 2.0 Flash
Experimental (70.8%). QVQ-72B-Preview demonstrated superior rejection accuracy
(85.5%). Notably, Pixtral 12B (51.7%) showed promise in specific domains,
while Janus models exhibited challenges in bias and uncertainty calibration,
reflected in low rejection accuracies and high entropy scores. High entropy
scores in Janus models (Janus 7B: 0.8392, Janus 1B: 0.787) underscore their
susceptibility to positional bias and unstable reasoning, contrasting with the
low entropy and robust reasoning of ChatGPT models. The study further
demonstrates that model size is not the sole determinant of performance, as
evidenced by Grok 3 underperformance despite its substantial parameter count.
By employing multi-image contexts, rejection mechanisms, and entropy-based
consistency metrics, this benchmark sets a new standard for evaluating
multimodal LLMs, enabling a more robust and reliable assessment of
next-generation AI systems.
