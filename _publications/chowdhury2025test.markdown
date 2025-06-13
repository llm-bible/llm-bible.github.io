---
layout: publication
title: 'Aurelia: Test-time Reasoning Distillation In Audio-visual Llms'
authors: Sanjoy Chowdhury, Hanan Gani, Nishit Anand, Sayan Nag, Ruohan Gao, Mohamed Elhoseiny, Salman Khan, Dinesh Manocha
conference: "Arxiv"
year: 2025
bibkey: chowdhury2025test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23219"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Recent advancements in reasoning optimization have greatly enhanced the
performance of large language models (LLMs). However, existing work fails to
address the complexities of audio-visual scenarios, underscoring the need for
further research. In this paper, we introduce AURELIA, a novel actor-critic
based audio-visual (AV) reasoning framework that distills structured,
step-by-step reasoning into AVLLMs at test time, improving their ability to
process complex multi-modal inputs without additional training or fine-tuning.
To further advance AVLLM reasoning skills, we present AVReasonBench, a
challenging benchmark comprising 4500 audio-visual questions, each paired with
detailed step-by-step reasoning. Our benchmark spans six distinct tasks,
including AV-GeoIQ, which evaluates AV reasoning combined with geographical and
cultural knowledge. Evaluating 18 AVLLMs on AVReasonBench reveals significant
limitations in their multi-modal reasoning capabilities. Using AURELIA, we
achieve up to a 100% relative improvement, demonstrating its effectiveness.
This performance gain highlights the potential of reasoning-enhanced data
generation for advancing AVLLMs in real-world applications. Our code and data
will be publicly released at: https: //github.com/schowdhury671/aurelia.
