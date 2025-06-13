---
layout: publication
title: 'Backdoorllm: A Comprehensive Benchmark For Backdoor Attacks And Defenses On Large Language Models'
authors: Yige Li, Hanxun Huang, Yunhan Zhao, Xingjun Ma, Jun Sun
conference: "Arxiv"
year: 2024
bibkey: li2024comprehensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12798"}
  - {name: "Code", url: "https://www.mlsafety.org/safebench/winners,"}
  - {name: "Code", url: "https://safe.ai/.),"}
  - {name: "Code", url: "https://github.com/bboylyg/BackdoorLLM"}
tags: ['Responsible AI', 'Applications', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Security', 'Training Techniques', 'Has Code']
---
Generative large language models (LLMs) have achieved state-of-the-art results on a wide range of tasks, yet they remain susceptible to backdoor attacks: carefully crafted triggers in the input can manipulate the model to produce adversary-specified outputs. While prior research has predominantly focused on backdoor risks in vision and classification settings, the vulnerability of LLMs in open-ended text generation remains underexplored. To fill this gap, we introduce BackdoorLLM (Our BackdoorLLM benchmark was awarded First Prize in the SafetyBench competition, https://www.mlsafety.org/safebench/winners, organized by the Center for AI Safety, https://safe.ai/.), the first comprehensive benchmark for systematically evaluating backdoor threats in text-generation LLMs. BackdoorLLM provides: (i) a unified repository of benchmarks with a standardized training and evaluation pipeline; (ii) a diverse suite of attack modalities, including data poisoning, weight poisoning, hidden-state manipulation, and chain-of-thought hijacking; (iii) over 200 experiments spanning 8 distinct attack strategies, 7 real-world scenarios, and 6 model architectures; (iv) key insights into the factors that govern backdoor effectiveness and failure modes in LLMs; and (v) a defense toolkit encompassing 7 representative mitigation techniques. Our code and datasets are available at https://github.com/bboylyg/BackdoorLLM. We will continuously incorporate emerging attack and defense methodologies to support the research in advancing the safety and reliability of LLMs.
