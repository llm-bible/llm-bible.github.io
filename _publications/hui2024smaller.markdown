---
layout: publication
title: 'Smaller Language Models Are Better Instruction Evolvers'
authors: Tingfeng Hui, Lulu Zhao, Guanting Dong, Yaqi Zhang, Hua Zhou, Sen Su
conference: "Arxiv"
year: 2024
bibkey: hui2024smaller
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11231"}
  - {name: "Code", url: "https://github.com/HypherX/Evolution-Analysis}{https://github.com/HypherX/Evolution-Analysis"}
tags: ['Fine-Tuning', 'GPT', 'Has Code', 'Model Architecture']
---
Instruction tuning has been widely used to unleash the complete potential of
large language models. Notably, complex and diverse instructions are of
significant importance as they can effectively align models with various
downstream tasks. However, current approaches to constructing large-scale
instructions predominantly favour powerful models such as GPT-4 or those with
over 70 billion parameters, under the empirical presumption that such larger
language models (LLMs) inherently possess enhanced capabilities. In this study,
we question this prevalent assumption and conduct an in-depth exploration into
the potential of smaller language models (SLMs) in the context of instruction
evolution. Extensive experiments across three scenarios of instruction
evolution reveal that smaller language models (SLMs) can synthesize more
effective instructions than LLMs. Further analysis demonstrates that SLMs
possess a broader output space during instruction evolution, resulting in more
complex and diverse variants. We also observe that the existing metrics fail to
focus on the impact of the instructions. Thus, we propose Instruction
Complex-Aware IFD (IC-IFD), which introduces instruction complexity in the
original IFD score to evaluate the effectiveness of instruction data more
accurately. Our source code is available at:
\href\{https://github.com/HypherX/Evolution-Analysis\}\{https://github.com/HypherX/Evolution-Analysis\}
