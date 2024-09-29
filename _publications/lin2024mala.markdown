---
layout: publication
title: MaLA-500 Massive Language Adaptation of Large Language Models
authors: Lin Peiqin, Ji Shaoxiong, Tiedemann Jörg, Martins André F. T., Schütze Hinrich
conference: "Arxiv"
year: 2024
bibkey: lin2024mala
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13303"}
tags: ['In Context Learning', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Large language models (LLMs) have advanced the state of the art in natural language processing. However their predominant design for English or a limited set of languages creates a substantial gap in their effectiveness for low-resource languages. To bridge this gap we introduce MaLA-500 a novel large language model designed to cover an extensive range of 534 languages. To train MaLA-500 we employ vocabulary extension and continued pretraining on LLaMA 2 with Glot500-c. Our intrinsic evaluation demonstrates that MaLA-500 is better at predicting the given texts of low-resource languages than existing multilingual LLMs. Moreover the extrinsic evaluation of in-context learning shows that MaLA-500 outperforms previous LLMs on SIB200 and Taxi1500 by a significant margin i.e. 11.68 and 4.82 marco-average accuracy across languages. We release MaLA-500 at https://huggingface.co/MaLA-LM
