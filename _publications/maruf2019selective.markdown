---
layout: publication
title: Selective Attention For Context45;aware Neural Machine Translation
authors: Maruf Sameen, Martins André F. T., Haffari Gholamreza
conference: "Arxiv"
year: 2019
bibkey: maruf2019selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1903.08788"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Despite the progress made in sentence45;level NMT current systems still fall short at achieving fluent good quality translation for a full document. Recent works in context45;aware NMT consider only a few previous sentences as context and may not scale to entire documents. To this end we propose a novel and scalable top45;down approach to hierarchical attention for context45;aware NMT which uses sparse attention to selectively focus on relevant sentences in the document context and then attends to key words in those sentences. We also propose single45;level attention approaches based on sentence or word45;level information in the context. The document45;level context representation produced from these attention modules is integrated into the encoder or decoder of the Transformer model depending on whether we use monolingual or bilingual context. Our experiments and evaluation on English45;German datasets in different document MT settings show that our selective attention approach not only significantly outperforms context45;agnostic baselines but also surpasses context45;aware baselines in most cases.
