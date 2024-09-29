---
layout: publication
title: GECKO&#58; Generative Language Model For English, Code And Korean
authors: Oh Sungwoo, Kim Donggyu
conference: "Arxiv"
year: 2024
bibkey: oh2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15640"}
  - {name: "Code", url: "https://huggingface.co/kifai/GECKO-7B"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Model Architecture']
---
We introduce GECKO a bilingual large language model (LLM) optimized for Korean and English along with programming languages. GECKO is pretrained on the balanced high-quality corpus of Korean and English employing LLaMA architecture. In this report we share the experiences of several efforts to build a better data pipeline for the corpus and to train our model. GECKO shows great efficiency in token generations for both Korean and English despite its small size of vocabulary. We measure the performance on the representative benchmarks in terms of Korean English and Code and it exhibits great performance on KMMLU (Korean MMLU) and modest performance in English and Code even with its smaller number of trained tokens compared to English-focused LLMs. GECKO is available to the open-source community under a permissive license. We hope our work offers a research baseline and practical insights for Korean LLM research. The model can be found at https://huggingface.co/kifai/GECKO-7B"
