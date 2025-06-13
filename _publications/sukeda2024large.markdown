---
layout: publication
title: '70b-parameter Large Language Models In Japanese Medical Question-answering'
authors: Issey Sukeda, Risa Kishikawa, Satoshi Kodera
conference: "Arxiv"
year: 2024
bibkey: sukeda2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14882"}
tags: ['Prompting', 'Pretraining Methods', 'Training Techniques', 'Fine-Tuning']
---
Since the rise of large language models (LLMs), the domain adaptation has
been one of the hot topics in various domains. Many medical LLMs trained with
English medical dataset have made public recently. However, Japanese LLMs in
medical domain still lack its research. Here we utilize multiple 70B-parameter
LLMs for the first time and show that instruction tuning using Japanese medical
question-answering dataset significantly improves the ability of Japanese LLMs
to solve Japanese medical license exams, surpassing 50% in accuracy. In
particular, the Japanese-centric models exhibit a more significant leap in
improvement through instruction tuning compared to their English-centric
counterparts. This underscores the importance of continual pretraining and the
adjustment of the tokenizer in our local language. We also examine two slightly
different prompt formats, resulting in non-negligible performance improvement.
