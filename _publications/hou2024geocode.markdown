---
layout: publication
title: 'Geocode-gpt: A Large Language Model For Geospatial Code Generation Tasks'
authors: Shuyang Hou, Zhangxiao Shen, Anqi Zhao, Jianyuan Liang, Zhipeng Gui, Xuefeng Guan, Rui Li, Huayi Wu
conference: "Arxiv"
year: 2024
bibkey: hou2024geocode
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17031'}
tags: ['RAG', 'Tools', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Training Techniques', 'GPT', 'Prompting', 'Pretraining Methods']
---
The increasing demand for spatiotemporal data and modeling tasks in
geosciences has made geospatial code generation technology a critical factor in
enhancing productivity. Although large language models (LLMs) have demonstrated
potential in code generation tasks, they often encounter issues such as refusal
to code or hallucination in geospatial code generation due to a lack of
domain-specific knowledge and code corpora. To address these challenges, this
paper presents and open-sources the GeoCode-PT and GeoCode-SFT corpora, along
with the GeoCode-Eval evaluation dataset. Additionally, by leveraging QLoRA and
LoRA for pretraining and fine-tuning, we introduce GeoCode-GPT-7B, the first
LLM focused on geospatial code generation, fine-tuned from Code Llama-7B.
Furthermore, we establish a comprehensive geospatial code evaluation framework,
incorporating option matching, expert validation, and prompt engineering
scoring for LLMs, and systematically evaluate GeoCode-GPT-7B using the
GeoCode-Eval dataset. Experimental results show that GeoCode-GPT outperforms
other models in multiple-choice accuracy by 9.1% to 32.1%, in code
summarization ability by 1.7% to 25.4%, and in code generation capability by
1.2% to 25.1%. This paper provides a solution and empirical validation for
enhancing LLMs' performance in geospatial code generation, extends the
boundaries of domain-specific model applications, and offers valuable insights
into unlocking their potential in geospatial code generation.
