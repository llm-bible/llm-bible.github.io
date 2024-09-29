---
layout: publication
title: Understanding And Mitigating Compositional Issues In Text45;to45;image Generative Models
authors: Zarei Arman, Rezaei Keivan, Basu Samyadeep, Saberi Mehrdad, Moayeri Mazda, Kattakinda Priyatham, Feizi Soheil
conference: "Arxiv"
year: 2024
bibkey: zarei2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07844"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Merging', 'Model Architecture', 'Prompting']
---
Recent text45;to45;image diffusion45;based generative models have the stunning ability to generate highly detailed and photo45;realistic images and achieve state45;of45;the45;art low FID scores on challenging image generation benchmarks. However one of the primary failure modes of these text45;to45;image generative models is in composing attributes objects and their associated relationships accurately into an image. In our paper we investigate this compositionality45;based failure mode and highlight that imperfect text conditioning with CLIP text45;encoder is one of the primary reasons behind the inability of these models to generate high45;fidelity compositional scenes. In particular we show that (i) there exists an optimal text45;embedding space that can generate highly coherent compositional scenes which shows that the output space of the CLIP text45;encoder is sub45;optimal and (ii) we observe that the final token embeddings in CLIP are erroneous as they often include attention contributions from unrelated tokens in compositional prompts. Our main finding shows that the best compositional improvements can be achieved (without harming the models FID scores) by fine45;tuning 123;it only125; a simple linear projection on CLIPs representation space in Stable45;Diffusion variants using a small set of compositional image45;text pairs. This result demonstrates that the sub45;optimality of the CLIPs output space is a major error source. We also show that re45;weighting the erroneous attention contributions in CLIP can also lead to improved compositional performances however these improvements are often less significant than those achieved by solely learning a linear projection head highlighting erroneous attentions to be only a minor error source.
