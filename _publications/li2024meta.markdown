---
layout: publication
title: Meta In-Context Learning Makes Large Language Models Better Zero and Few-Shot Relation Extractors
authors: Li Guozheng, Wang Peng, Liu Jiajun, Guo Yikai, Ji Ke, Shang Ziyu, Xu Zijie
conference: "Arxiv"
year: 2024
bibkey: li2024meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17807"}
tags: ['Few Shot', 'Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Relation extraction (RE) is an important task that aims to identify the relationships between entities in texts. While large language models (LLMs) have revealed remarkable in-context learning (ICL) capability for general zero and few-shot learning recent studies indicate that current LLMs still struggle with zero and few-shot RE. Previous studies are mainly dedicated to design prompt formats and select good examples for improving ICL-based RE. Although both factors are vital for ICL if one can fundamentally boost the ICL capability of LLMs in RE the zero and few-shot RE performance via ICL would be significantly improved. To this end we introduce (eta n-ontext learning of LLMs for elation xtraction) a new meta-training framework for zero and few-shot RE where an LLM is tuned to do ICL on a diverse collection of RE datasets (i.e. learning to learn in context for RE). Through meta-training the model becomes more effectively to learn a new RE task in context by conditioning on a few training examples with no parameter updates or task-specific templates at inference time enabling better zero and few-shot task generalization. We experiment on various LLMs with different model scales and 12 public RE datasets and then evaluate it on unseen RE benchmarks under zero and few-shot settings. delivers comparable or superior performance compared to a range of baselines including supervised fine-tuning and typical in-context learning methods. We find that the gains are particular significant for larger model scales and using a diverse set of the meta-training RE datasets is key to improvements. Empirically we show that can transfer the relation semantic knowledge via relation label name during inference on target RE datasets.
