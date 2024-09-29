---
layout: publication
title: CDLM Cross45;document Language Modeling
authors: Caciularu Avi, Cohan Arman, Beltagy Iz, Peters Matthew E., Cattan Arie, Dagan Ido
conference: "Arxiv"
year: 2021
bibkey: caciularu2021cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.00406"}
  - {name: "Code", url: "https://github.com/aviclu/CDLM"}
tags: ['Attention Mechanism', 'BERT', 'Has Code', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
We introduce a new pretraining approach geared for multi45;document language modeling incorporating two key ideas into the masked language modeling self45;supervised objective. First instead of considering documents in isolation we pretrain over sets of multiple related documents encouraging the model to learn cross45;document relationships. Second we improve over recent long45;range transformers by introducing dynamic global attention that has access to the entire input to predict masked tokens. We release CDLM (Cross45;Document Language Model) a new general language model for multi45;document setting that can be easily applied to downstream tasks. Our extensive analysis shows that both ideas are essential for the success of CDLM and work in synergy to set new state45;of45;the45;art results for several multi45;text tasks. Code and models are available at https://github.com/aviclu/CDLM.
