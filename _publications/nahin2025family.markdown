---
layout: publication
title: 'Titullms: A Family Of Bangla Llms With Comprehensive Benchmarking'
authors: Shahriar Kabir Nahin, Rabindra Nath Nandi, Sagor Sarker, Quazi Sarwar Muhtaseem, Md Kowsher, Apu Chandraw Shill, Md Ibrahim, Mehadi Hasan Menon, Tareq Al Muntasir, Firoj Alam
conference: "Arxiv"
year: 2025
bibkey: nahin2025family
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11187"}
tags: ['Training Techniques', 'Pretraining Methods']
---
In this paper, we present TituLLMs, the first large pretrained Bangla LLMs,
available in 1b and 3b parameter sizes. Due to computational constraints during
both training and inference, we focused on smaller models. To train TituLLMs,
we collected a pretraining dataset of approximately ~37 billion tokens. We
extended the Llama-3.2 tokenizer to incorporate language- and culture-specific
knowledge, which also enables faster training and inference. There was a lack
of benchmarking datasets to benchmark LLMs for Bangla. To address this gap, we
developed five benchmarking datasets. We benchmarked various LLMs, including
TituLLMs, and demonstrated that TituLLMs outperforms its initial multilingual
versions. However, this is not always the case, highlighting the complexities
of language adaptation. Our work lays the groundwork for adapting existing
multilingual open models to other low-resource languages. To facilitate broader
adoption and further research, we have made the TituLLMs models and
benchmarking datasets publicly available
(https://huggingface.co/collections/hishab/titulm-llama-family-6718d31fc1b83529276f490a).
