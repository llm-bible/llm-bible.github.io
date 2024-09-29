---
layout: publication
title: Muse Text45;to45;image Generation Via Masked Generative Transformers
authors: Chang Huiwen, Zhang Han, Barber Jarred, Maschinot Aj, Lezama Jose, Jiang Lu, Yang Ming-hsuan, Murphy Kevin, Freeman William T., Rubinstein Michael, Li Yuanzhen, Krishnan Dilip
conference: "Arxiv"
year: 2023
bibkey: chang2023text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.00704"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
We present Muse a text45;to45;image Transformer model that achieves state45;of45;the45;art image generation performance while being significantly more efficient than diffusion or autoregressive models. Muse is trained on a masked modeling task in discrete token space given the text embedding extracted from a pre45;trained large language model (LLM) Muse is trained to predict randomly masked image tokens. Compared to pixel45;space diffusion models such as Imagen and DALL45;E 2 Muse is significantly more efficient due to the use of discrete tokens and requiring fewer sampling iterations; compared to autoregressive models such as Parti Muse is more efficient due to the use of parallel decoding. The use of a pre45;trained LLM enables fine45;grained language understanding translating to high45;fidelity image generation and the understanding of visual concepts such as objects their spatial relationships pose cardinality etc. Our 900M parameter model achieves a new SOTA on CC3M with an FID score of 6.06. The Muse 3B parameter model achieves an FID of 7.88 on zero45;shot COCO evaluation along with a CLIP score of 0.32. Muse also directly enables a number of image editing applications without the need to fine45;tune or invert the model inpainting outpainting and mask45;free editing. More results are available at https://muse&#45;model.github.io
