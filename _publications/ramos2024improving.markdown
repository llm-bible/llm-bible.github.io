---
layout: publication
title: 'Grammamt: Improving Machine Translation With Grammar-informed In-context Learning'
authors: Rita Ramos, Everlyn Asiko Chimoto, Maartje Ter Hoeve, Natalie Schluter
conference: "Arxiv"
year: 2024
bibkey: ramos2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18702"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
We introduce GrammaMT, a grammatically-aware prompting approach for machine translation that uses Interlinear Glossed Text (IGT), a common form of linguistic description providing morphological and lexical annotations for source sentences. GrammaMT proposes three prompting strategies: gloss-shot, chain-gloss and model-gloss. All are training-free, requiring only a few examples that involve minimal effort to collect, and making them well-suited for low-resource setups. Experiments show that GrammaMT enhances translation performance on open-source instruction-tuned LLMs for various low- to high-resource languages across three benchmarks: (1) the largest IGT corpus, (2) the challenging 2023 SIGMORPHON Shared Task data over endangered languages, and (3) even in an out-of-domain setting with FLORES. Moreover, ablation studies reveal that leveraging gloss resources could substantially boost MT performance (by over 17 BLEU points) if LLMs accurately generate or access input sentence glosses.
