---
layout: publication
title: 'Stochastok: Improving Fine-grained Subword Understanding In Llms'
authors: Anya Sims, Thom Foster, Klara Kaleb, Tuan-duy H. Nguyen, Joseph Lee, Jakob N. Foerster, Yee Whye Teh, Cong Lu
conference: "Arxiv"
year: 2025
bibkey: sims2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01687"}
  - {name: "Code", url: "https://github.com/anyasims/stochastok"}
tags: ['Tokenization', 'Training Techniques', 'Pretraining Methods', 'Has Code']
---
Subword-level understanding is integral to numerous tasks, including understanding multi-digit numbers, spelling mistakes, abbreviations, rhyming, and wordplay. Despite this, current large language models (LLMs) still often struggle with seemingly simple subword-level tasks like How many 'r's in 'strawberry'?. A key factor behind these failures is tokenization which obscures the fine-grained structure of words. Current alternatives, such as character-level and dropout tokenization methods, significantly increase computational costs and provide inconsistent improvements. In this paper we revisit tokenization and introduce StochasTok, a simple, efficient stochastic tokenization scheme that randomly splits tokens during training, allowing LLMs to 'see' their internal structure. Our experiments show that pretraining with StochasTok substantially improves LLMs' downstream performance across multiple subword-level language games, including character counting, substring identification, and math tasks. Furthermore, StochasTok's simplicity allows seamless integration at any stage of the training pipeline; and we demonstrate that post-training with StochasTok can instill improved subword understanding into existing pretrained models, thus avoiding costly pretraining from scratch. These dramatic improvements achieved with a minimal change suggest StochasTok holds exciting potential when applied to larger, more capable models. Code open-sourced at: https://github.com/anyasims/stochastok.
