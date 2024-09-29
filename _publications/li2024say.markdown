---
layout: publication
title: Say More With Less Understanding Prompt Learning Behaviors Through Gist Compression
authors: Li Xinze, Liu Zhenghao, Xiong Chenyan, Yu Shi, Yan Yukun, Wang Shuo, Yu Ge
conference: "Arxiv"
year: 2024
bibkey: li2024say
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16058"}
  - {name: "Code", url: "https://github.com/OpenMatch/Gist&#45;COCO"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Tools']
---
Large language models (LLMs) require lengthy prompts as the input context to produce output aligned with user intentions a process that incurs extra costs during inference. In this paper we propose the Gist COnditioned deCOding (Gist45;COCO) model introducing a novel method for compressing prompts which also can assist the prompt interpretation and engineering. Gist45;COCO employs an encoder45;decoder based language model and then incorporates an additional encoder as a plugin module to compress prompts with inputs using gist tokens. It finetunes the compression plugin module and uses the representations of gist tokens to emulate the raw prompts in the vanilla language model. By verbalizing the representations of gist tokens into gist prompts the compression ability of Gist45;COCO can be generalized to different LLMs with high compression rates. Our experiments demonstrate that Gist45;COCO outperforms previous prompt compression models in both passage and instruction compression tasks. Further analysis on gist verbalization results suggests that our gist prompts serve different functions in aiding language models. They may directly provide potential answers generate the chain45;of45;thought or simply repeat the inputs. All data and codes are available at https://github.com/OpenMatch/Gist&#45;COCO .
