---
layout: publication
title: 'Llmic: Romanian Foundation Language Model'
authors: Vlad-andrei Bădoiu, Mihai-valentin Dumitru, Alexandru M. Gherghescu, Alexandru Agache, Costin Raiciu
conference: "Arxiv"
year: 2025
bibkey: bădoiu2025romanian
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.07721"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Fine-Tuning']
---
Recent advances in Large Language Models (LLMs) have demonstrated remarkable
capabilities across various tasks with commercial models leading the way. While
open models usually operate at a smaller scale, they maintain competitiveness
through specialization and fine-tuning. However, a significant challenge
persists: open models often underperform in low-resource languages due to
limited representation in the training corpus. In this paper, we present LLMic,
a bilingual foundation language model designed specifically for the Romanian
Language. We document the complete process of pretraining a foundation model
for a low-resource language, including corpus construction, architecture
selection, and hyper-parameter optimization. Our evaluation demonstrates that
LLMic can be specialized for tasks in the target language, achieving results
comparable to other much larger open models. We show that fine-tuning LLMic for
language translation after the initial pretraining phase outperforms existing
solutions in English-to-Romanian translation tasks. This opens the path for
efficient large-scale processing for the Romanian language community, using the
much smaller LLMic model
