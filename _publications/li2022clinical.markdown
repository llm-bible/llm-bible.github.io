---
layout: publication
title: Clinical45;longformer And Clinical45;bigbird Transformers For Long Clinical Sequences
authors: Li Yikuan, Wehbe Ramsey M., Ahmad Faraz S., Wang Hanyin, Luo Yuan
conference: "Arxiv"
year: 2022
bibkey: li2022clinical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.11838"}
  - {name: "Code", url: "https://github.com/luoyuanlab/Clinical&#45;Longformer]"}
  - {name: "Code", url: "https://huggingface.co/yikuan8/Clinical&#45;Longformer]"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Transformers45;based models such as BERT have dramatically improved the performance for various natural language processing tasks. The clinical knowledge enriched model namely ClinicalBERT also achieved state45;of45;the45;art results when performed on clinical named entity recognition and natural language inference tasks. One of the core limitations of these transformers is the substantial memory consumption due to their full self45;attention mechanism. To overcome this long sequence transformer models e.g. Longformer and BigBird were proposed with the idea of sparse attention mechanism to reduce the memory usage from quadratic to the sequence length to a linear scale. These models extended the maximum input sequence length from 512 to 4096 which enhanced the ability of modeling long45;term dependency and consequently achieved optimal results in a variety of tasks. Inspired by the success of these long sequence transformer models we introduce two domain enriched language models namely Clinical45;Longformer and Clinical45;BigBird which are pre45;trained from large45;scale clinical corpora. We evaluate both pre45;trained models using 10 baseline tasks including named entity recognition question answering and document classification tasks. The results demonstrate that Clinical45;Longformer and Clinical45;BigBird consistently and significantly outperform ClinicalBERT as well as other short45;sequence transformers in all downstream tasks. We have made our source code available at https://github.com/luoyuanlab/Clinical&#45;Longformer] the pre45;trained models available for public download at https://huggingface.co/yikuan8/Clinical&#45;Longformer].
