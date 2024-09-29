---
layout: publication
title: MUFFIN: Curating Multi-faceted Instructions For Improving Instruction-following
authors: Lou Renze, Zhang Kai, Xie Jian, Sun Yuxuan, Ahn Janice, Xu Hanzi, Su Yu, Yin Wenpeng
conference: "Arxiv"
year: 2023
bibkey: lou2023curating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02436"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
In the realm of large language models (LLMs) enhancing instruction-following capability often involves curating expansive training data. This is achieved through two primary schemes i) Scaling-Inputs Amplifying (input output) pairs per task instruction aiming for better instruction adherence. ii) Scaling Input-Free Tasks Enlarging tasks each composed of an (instruction output) pair (without requiring a separate input anymore). However LLMs under Scaling-Inputs tend to be overly sensitive to inputs leading to misinterpretation or non-compliance with instructions. Conversely Scaling Input-Free Tasks demands a substantial number of tasks but is less effective in instruction following when dealing with instances in Scaling-Inputs. This work introduces MUFFIN a new scheme of instruction-following dataset curation. Specifically we automatically Scale Tasks per Input by diversifying these tasks with various input facets. Experimental results across four zero-shot benchmarks spanning both Scaling-Inputs and Scaling Input-Free Tasks schemes reveal that LLMs at various scales trained on MUFFIN generally demonstrate superior instruction-following capabilities compared to those trained on the two aforementioned schemes.
