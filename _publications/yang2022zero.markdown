---
layout: publication
title: Zero45;shot Video Question Answering Via Frozen Bidirectional Language Models
authors: Yang Antoine, Miech Antoine, Sivic Josef, Laptev Ivan, Schmid Cordelia
conference: "Arxiv"
year: 2022
bibkey: yang2022zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.08155"}
  - {name: "Code", url: "https://github.com/antoyang/FrozenBiLM"}
tags: ['Applications', 'BERT', 'GPT', 'Has Code', 'Language Modeling', 'Masked Language Model', 'Pretraining Methods', 'Training Techniques']
---
Video question answering (VideoQA) is a complex task that requires diverse multi45;modal data for training. Manual annotation of question and answers for videos however is tedious and prohibits scalability. To tackle this problem recent methods consider zero45;shot settings with no manual annotation of visual question45;answer. In particular a promising approach adapts frozen autoregressive language models pretrained on Web45;scale text45;only data to multi45;modal inputs. In contrast we here build on frozen bidirectional language models (BiLM) and show that such an approach provides a stronger and cheaper alternative for zero45;shot VideoQA. In particular (i) we combine visual inputs with the frozen BiLM using light trainable modules (ii) we train such modules using Web45;scraped multi45;modal data and finally (iii) we perform zero45;shot VideoQA inference through masked language modeling where the masked text is the answer to a given question. Our proposed approach FrozenBiLM outperforms the state of the art in zero45;shot VideoQA by a significant margin on a variety of datasets including LSMDC45;FiB iVQA MSRVTT45;QA MSVD45;QA ActivityNet45;QA TGIF45;FrameQA How2QA and TVQA. It also demonstrates competitive performance in the few45;shot and fully45;supervised setting. Our code and models are publicly available at https://github.com/antoyang/FrozenBiLM.
