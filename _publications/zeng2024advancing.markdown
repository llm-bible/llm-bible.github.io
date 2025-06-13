---
layout: publication
title: 'Advancing Multimodal Large Language Models In Chart Question Answering With Visualization-referenced Instruction Tuning'
authors: Xingchen Zeng, Haichuan Lin, Yilin Ye, Wei Zeng
conference: "Arxiv"
year: 2024
bibkey: zeng2024advancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.20174'}
  - {name: "Code", url: 'https://github.com/zengxingchen/ChartQA-MLLM'}
tags: ['Has Code', 'Applications', 'Training Techniques', 'Merging', 'Multimodal Models']
---
Emerging multimodal large language models (MLLMs) exhibit great potential for
chart question answering (CQA). Recent efforts primarily focus on scaling up
training datasets (i.e., charts, data tables, and question-answer (QA) pairs)
through data collection and synthesis. However, our empirical study on existing
MLLMs and CQA datasets reveals notable gaps. First, current data collection and
synthesis focus on data volume and lack consideration of fine-grained visual
encodings and QA tasks, resulting in unbalanced data distribution divergent
from practical CQA scenarios. Second, existing work follows the training recipe
of the base MLLMs initially designed for natural images, under-exploring the
adaptation to unique chart characteristics, such as rich text elements. To fill
the gap, we propose a visualization-referenced instruction tuning approach to
guide the training dataset enhancement and model development. Specifically, we
propose a novel data engine to effectively filter diverse and high-quality data
from existing datasets and subsequently refine and augment the data using
LLM-based generation techniques to better align with practical QA tasks and
visual encodings. Then, to facilitate the adaptation to chart characteristics,
we utilize the enriched data to train an MLLM by unfreezing the vision encoder
and incorporating a mixture-of-resolution adaptation strategy for enhanced
fine-grained recognition. Experimental results validate the effectiveness of
our approach. Even with fewer training examples, our model consistently
outperforms state-of-the-art CQA models on established benchmarks. We also
contribute a dataset split as a benchmark for future research. Source codes and
datasets of this paper are available at
https://github.com/zengxingchen/ChartQA-MLLM.
