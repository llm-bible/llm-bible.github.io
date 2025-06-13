---
layout: publication
title: 'REVEAL: Multi-turn Evaluation Of Image-input Harms For Vision LLM'
authors: Madhur Jindal, Saurabh Deshpande
conference: "Arxiv"
year: 2025
bibkey: jindal2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04673"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT']
---
Vision Large Language Models (VLLMs) represent a significant advancement in
artificial intelligence by integrating image-processing capabilities with
textual understanding, thereby enhancing user interactions and expanding
application domains. However, their increased complexity introduces novel
safety and ethical challenges, particularly in multi-modal and multi-turn
conversations. Traditional safety evaluation frameworks, designed for
text-based, single-turn interactions, are inadequate for addressing these
complexities. To bridge this gap, we introduce the REVEAL (Responsible
Evaluation of Vision-Enabled AI LLMs) Framework, a scalable and automated
pipeline for evaluating image-input harms in VLLMs. REVEAL includes automated
image mining, synthetic adversarial data generation, multi-turn conversational
expansion using crescendo attack strategies, and comprehensive harm assessment
through evaluators like GPT-4o.
  We extensively evaluated five state-of-the-art VLLMs, GPT-4o, Llama-3.2,
Qwen2-VL, Phi3.5V, and Pixtral, across three important harm categories: sexual
harm, violence, and misinformation. Our findings reveal that multi-turn
interactions result in significantly higher defect rates compared to
single-turn evaluations, highlighting deeper vulnerabilities in VLLMs. Notably,
GPT-4o demonstrated the most balanced performance as measured by our
Safety-Usability Index (SUI) followed closely by Pixtral. Additionally,
misinformation emerged as a critical area requiring enhanced contextual
defenses. Llama-3.2 exhibited the highest MT defect rate (\\(16.55 %\\)) while
Qwen2-VL showed the highest MT refusal rate (\\(19.1 %\\)).
