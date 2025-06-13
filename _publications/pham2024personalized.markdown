---
layout: publication
title: 'Personalized Large Vision-language Models'
authors: Chau Pham, Hoang Phan, David Doermann, Yunjie Tian
conference: "Arxiv"
year: 2024
bibkey: pham2024personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.17610"}
tags: ['Tools', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Multimodal Models']
---
The personalization model has gained significant attention in image
generation yet remains underexplored for large vision-language models (LVLMs).
Beyond generic ones, with personalization, LVLMs handle interactive dialogues
using referential concepts (e.g., ``Mike and Susan are talking.'') instead of
the generic form (e.g., ``a boy and a girl are talking.''), making the
conversation more customizable and referentially friendly. In addition, PLVM is
equipped to continuously add new concepts during a dialogue without incurring
additional costs, which significantly enhances the practicality. PLVM proposes
Aligner, a pre-trained visual encoder to align referential concepts with the
queried images. During the dialogues, it extracts features of reference images
with these corresponding concepts and recognizes them in the queried image,
enabling personalization. We note that the computational cost and parameter
count of the Aligner are negligible within the entire framework. With
comprehensive qualitative and quantitative analyses, we reveal the
effectiveness and superiority of PLVM.
