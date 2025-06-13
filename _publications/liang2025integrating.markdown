---
layout: publication
title: 'Integrating Large Language Models For Automated Structural Analysis'
authors: Haoran Liang, Mohammad Talebi Kalaleh, Qipei Mei
conference: "Arxiv"
year: 2025
bibkey: liang2025integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09754"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Prompting', 'In-Context Learning']
---
Automated analysis for engineering structures offers considerable potential
for boosting efficiency by minimizing repetitive tasks. Although AI-driven
methods are increasingly common, no systematic framework yet leverages Large
Language Models (LLMs) for automatic structural analysis. To address this gap,
we propose a novel framework that integrates LLMs with structural analysis
software. LLMs serve as the core engine: they parse structural descriptions
from text and translate them into executable Python scripts. Moreover, the
framework integrates the generative capabilities of LLMs with code-based finite
element (FE) tools like OpenSeesPy. It employs domain-specific prompt design
and in-context learning strategies to enhance the LLM's problem-solving
capabilities and generative stability, enabling fully automated structural
analysis from descriptive text to model outputs. In our experiments, we
introduce a well-curated small-scale benchmark dataset of 20 structural
analysis word problems (SAWPs) with ground-truth solutions and evaluate the
performance of different LLMs within our framework in solving these SAWPs. The
role of system instructions, crafted by structural engineers, is also
investigated to understand their impact on LLM-driven structural analysis.
Additionally, the generative stability of our framework is examined. Through
multiple validation experiments on the benchmark, our results demonstrate that
the proposed framework can substantially increase the level of automation in
solving SAWPs compared to traditional methods. Quantitatively, the framework,
built on GPT-4o, achieved 100% accuracy, surpassing GPT-4 (85%), Gemini 1.5 Pro
(80%), and Llama-3.3 (30%) on the test examples. Furthermore, integrating
domain-specific instructions enhanced performance by 30% on problems with
asymmetrical structural configurations.
