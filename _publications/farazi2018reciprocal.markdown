---
layout: publication
title: 'Reciprocal Attention Fusion For Visual Question Answering'
authors: Farazi Moshiur R, Khan Salman H
conference: "Proceedings of the British Machine Vision Conference"
year: 2018
bibkey: farazi2018reciprocal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1805.04247"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Transformer']
---
Existing attention mechanisms either attend to local image grid or object level features for Visual Question Answering (VQA). Motivated by the observation that questions can relate to both object instances and their parts, we propose a novel attention mechanism that jointly considers reciprocal relationships between the two levels of visual details. The bottom-up attention thus generated is further coalesced with the top-down information to only focus on the scene elements that are most relevant to a given question. Our design hierarchically fuses multi-modal information i.e., language, object- and gird-level features, through an efficient tensor decomposition scheme. The proposed model improves the state-of-the-art single model performances from 67.9&#37; to 68.2&#37; on VQAv1 and from 65.7&#37; to 67.4&#37; on VQAv2, demonstrating a significant boost.
