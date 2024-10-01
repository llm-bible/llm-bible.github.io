---
layout: publication
title: 'Understanding And Mitigating Compositional Issues In Text-to-image Generative Models'
authors: Zarei Arman, Rezaei Keivan, Basu Samyadeep, Saberi Mehrdad, Moayeri Mazda, Kattakinda Priyatham, Feizi Soheil
conference: "Arxiv"
year: 2024
bibkey: zarei2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07844"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
'Recent text-to-image diffusion-based generative models have the stunning ability to generate highly detailed and photo-realistic images and achieve state-of-the-art low FID scores on challenging image generation benchmarks. However, one of the primary failure modes of these text-to-image generative models is in composing attributes, objects, and their associated relationships accurately into an image. In our paper, we investigate this compositionality-based failure mode and highlight that imperfect text conditioning with CLIP text-encoder is one of the primary reasons behind the inability of these models to generate high-fidelity compositional scenes. In particular, we show that (i) there exists an optimal text-embedding space that can generate highly coherent compositional scenes which shows that the output space of the CLIP text-encoder is sub-optimal, and (ii) we observe that the final token embeddings in CLIP are erroneous as they often include attention contributions from unrelated tokens in compositional prompts. Our main finding shows that the best compositional improvements can be achieved (without harming the model''s FID scores) by fine-tuning \{\it only\} a simple linear projection on CLIP''s representation space in Stable-Diffusion variants using a small set of compositional image-text pairs. This result demonstrates that the sub-optimality of the CLIP''s output space is a major error source. We also show that re-weighting the erroneous attention contributions in CLIP can also lead to improved compositional performances, however these improvements are often less significant than those achieved by solely learning a linear projection head, highlighting erroneous attentions to be only a minor error source.'
