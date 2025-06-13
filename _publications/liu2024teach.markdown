---
layout: publication
title: 'Teach Multimodal Llms To Comprehend Electrocardiographic Images'
authors: Ruoqi Liu, Yuelin Bai, Xiang Yue, Ping Zhang
conference: "Arxiv"
year: 2024
bibkey: liu2024teach
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19008"}
tags: ['RAG', 'Multimodal Models', 'Reinforcement Learning']
---
The electrocardiogram (ECG) is an essential non-invasive diagnostic tool for
assessing cardiac conditions. Existing automatic interpretation methods suffer
from limited generalizability, focusing on a narrow range of cardiac
conditions, and typically depend on raw physiological signals, which may not be
readily available in resource-limited settings where only printed or digital
ECG images are accessible. Recent advancements in multimodal large language
models (MLLMs) present promising opportunities for addressing these challenges.
However, the application of MLLMs to ECG image interpretation remains
challenging due to the lack of instruction tuning datasets and well-established
ECG image benchmarks for quantitative evaluation. To address these challenges,
we introduce ECGInstruct, a comprehensive ECG image instruction tuning dataset
of over one million samples, covering a wide range of ECG-related tasks from
diverse data sources. Using ECGInstruct, we develop PULSE, an MLLM tailored for
ECG image comprehension. In addition, we curate ECGBench, a new evaluation
benchmark covering four key ECG image interpretation tasks across nine
different datasets. Our experiments show that PULSE sets a new
state-of-the-art, outperforming general MLLMs with an average accuracy
improvement of 15% to 30%. This work highlights the potential of PULSE to
enhance ECG interpretation in clinical practice.
