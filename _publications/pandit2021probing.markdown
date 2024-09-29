---
layout: publication
title: "Probing For Bridging Inference In Transformer Language Models"
authors: Pandit Onkar, Hou Yufang
conference: "Arxiv"
year: 2021
bibkey: pandit2021probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.09400"}
tags: ['Attention Mechanism', 'BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
We probe pre-trained transformer language models for bridging inference. We first investigate individual attention heads in BERT and observe that attention heads at higher layers prominently focus on bridging relations in-comparison with the lower and middle layers also few specific attention heads concentrate consistently on bridging. More importantly we consider language models as a whole in our second approach where bridging anaphora resolution is formulated as a masked token prediction task (Of-Cloze test). Our formulation produces optimistic results without any fine-tuning which indicates that pre-trained language models substantially capture bridging inference. Our further investigation shows that the distance between anaphor-antecedent and the context provided to language models play an important role in the inference.
