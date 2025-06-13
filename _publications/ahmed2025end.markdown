---
layout: publication
title: 'End-to-end Training For Text-to-image Synthesis Using Dual-text Embeddings'
authors: Yeruru Asrar Ahmed, Anurag Mittal
conference: "Arxiv"
year: 2025
bibkey: ahmed2025end
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.01507'}
tags: ['Multimodal Models', 'Training Techniques', 'Tools']
---
Text-to-Image (T2I) synthesis is a challenging task that requires modeling
complex interactions between two modalities ( i.e., text and image). A common
framework adopted in recent state-of-the-art approaches to achieving such
multimodal interactions is to bootstrap the learning process with pre-trained
image-aligned text embeddings trained using contrastive loss. Furthermore,
these embeddings are typically trained generically and reused across various
synthesis models. In contrast, we explore an approach to learning text
embeddings specifically tailored to the T2I synthesis network, trained in an
end-to-end fashion. Further, we combine generative and contrastive training and
use two embeddings, one optimized to enhance the photo-realism of the generated
images, and the other seeking to capture text-to-image alignment. A
comprehensive set of experiments on three text-to-image benchmark datasets
(Oxford-102, Caltech-UCSD, and MS-COCO) reveal that having two separate
embeddings gives better results than using a shared one and that such an
approach performs favourably in comparison with methods that use text
representations from a pre-trained text encoder trained using a discriminative
approach. Finally, we demonstrate that such learned embeddings can be used in
other contexts as well, such as text-to-image manipulation.
