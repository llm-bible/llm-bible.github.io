---
layout: publication
title: CodecLM Aligning Language Models with Tailored Synthetic Data
authors: Wang Zifeng, Li Chun-liang, Perot Vincent, Le Long T., Miao Jin, Zhang Zizhao, Lee Chen-yu, Pfister Tomas
conference: "Arxiv"
year: 2024
bibkey: wang2024codeclm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05875"}
tags: ['Applications', 'Pretraining Methods', 'Tools']
---
Instruction tuning has emerged as the key in aligning large language models (LLMs) with specific task instructions thereby mitigating the discrepancy between the next-token prediction objective and users actual goals. To reduce the labor and time cost to collect or annotate data by humans researchers start to explore the use of LLMs to generate instruction-aligned synthetic data. Recent works focus on generating diverse instructions and applying LLM to increase instruction complexity often neglecting downstream use cases. It remains unclear how to tailor high-quality data to elicit better instruction-following abilities in different target instruction distributions and LLMs. To this end we introduce CodecLM a general framework for adaptively generating high-quality synthetic data for LLM alignment with different downstream instruction distributions and LLMs. Drawing on the Encode-Decode principles we use LLMs as codecs to guide the data generation process. We first encode seed instructions into metadata which are concise keywords generated on-the-fly to capture the target instruction distribution and then decode metadata to create tailored instructions. We also introduce Self-Rubrics and Contrastive Filtering during decoding to tailor data-efficient samples. Extensive experiments on four open-domain instruction following benchmarks validate the effectiveness of CodecLM over the current state-of-the-arts.
