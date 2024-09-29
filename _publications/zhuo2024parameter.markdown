---
layout: publication
title: Astraios Parameter45;efficient Instruction Tuning Code Large Language Models
authors: Zhuo Terry Yue, Zebaze Armel, Suppattarachai Nitchakarn, Von Werra Leandro, De Vries Harm, Liu Qian, Muennighoff Niklas
conference: "Arxiv"
year: 2024
bibkey: zhuo2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00788"}
tags: ['Applications', 'Fine Tuning', 'Security']
---
The high cost of full45;parameter fine45;tuning (FFT) of Large Language Models (LLMs) has led to a series of parameter45;efficient fine45;tuning (PEFT) methods. However it remains unclear which methods provide the best cost45;performance trade45;off at different model scales. We introduce Astraios a suite of 28 instruction45;tuned OctoCoder models using 7 tuning methods and 4 model sizes up to 16 billion parameters. Through investigations across 5 tasks and 8 different datasets encompassing both code comprehension and code generation tasks we find that FFT generally leads to the best downstream performance across all scales and PEFT methods differ significantly in their efficacy based on the model scale. LoRA usually offers the most favorable trade45;off between cost and performance. Further investigation into the effects of these methods on both model robustness and code security reveals that larger models tend to demonstrate reduced robustness and less security. At last we explore the relationships among updated parameters cross45;entropy loss and task performance. We find that the tuning effectiveness observed in small models generalizes well to larger models and the validation loss in instruction tuning can be a reliable indicator of overall downstream performance.
