---
layout: publication
title: 'Biases In Edge Language Models: Detection, Analysis, And Mitigation'
authors: Vinamra Sharma, Danilo Pietro Pau, José Cano
conference: "Arxiv"
year: 2025
bibkey: sharma2025biases
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11349'}
tags: ['Security', 'Fairness', 'Applications', 'Model Architecture', 'GPT', 'Bias Mitigation', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'Responsible AI']
---
The integration of large language models (LLMs) on low-power edge devices
such as Raspberry Pi, known as edge language models (ELMs), has introduced
opportunities for more personalized, secure, and low-latency language
intelligence that is accessible to all. However, the resource constraints
inherent in edge devices and the lack of robust ethical safeguards in language
models raise significant concerns about fairness, accountability, and
transparency in model output generation. This paper conducts a comparative
analysis of text-based bias across language model deployments on edge, cloud,
and desktop environments, aiming to evaluate how deployment settings influence
model fairness. Specifically, we examined an optimized Llama-2 model running on
a Raspberry Pi 4; GPT 4o-mini, Gemini-1.5-flash, and Grok-beta models running
on cloud servers; and Gemma2 and Mistral models running on a MacOS desktop
machine. Our results demonstrate that Llama-2 running on Raspberry Pi 4 is
43.23% and 21.89% more prone to showing bias over time compared to models
running on the desktop and cloud-based environments. We also propose the
implementation of a feedback loop, a mechanism that iteratively adjusts model
behavior based on previous outputs, where predefined constraint weights are
applied layer-by-layer during inference, allowing the model to correct bias
patterns, resulting in 79.28% reduction in model bias.
