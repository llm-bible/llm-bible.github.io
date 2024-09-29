---
layout: publication
title: Effective Long45;context Scaling Of Foundation Models
authors: Xiong Wenhan, Liu Jingyu, Molybog Igor, Zhang Hejia, Bhargava Prajjwal, Hou Rui, Martin Louis, Rungta Rashi, Sankararaman Karthik Abinav, Oguz Barlas, Khabsa Madian, Fang Han, Mehdad Yashar, Narang Sharan, Malik Kshitiz, Fan Angela, Bhosale Shruti, Edunov Sergey, Lewis Mike, Wang Sinong, Ma Hao
conference: "Arxiv"
year: 2023
bibkey: xiong2023effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16039"}
tags: ['GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We present a series of long45;context LLMs that support effective context windows of up to 32768 tokens. Our model series are built through continual pretraining from Llama 2 with longer training sequences and on a dataset where long texts are upsampled. We perform extensive evaluation on language modeling synthetic context probing tasks and a wide range of research benchmarks. On research benchmarks our models achieve consistent improvements on most regular tasks and significant improvements on long45;context tasks over Llama 2. Notably with a cost45;effective instruction tuning procedure that does not require human45;annotated long instruction data the 70B variant can already surpass gpt45;3.545;turbo45;16ks overall performance on a suite of long45;context tasks. Alongside these results we provide an in45;depth analysis on the individual components of our method. We delve into Llamas position encodings and discuss its limitation in modeling long dependencies. We also examine the impact of various design choices in the pretraining process including the data mix and the training curriculum of sequence lengths 45;45; our ablation experiments suggest that having abundant long texts in the pretrain dataset is not the key to achieving strong performance and we empirically verify that long context continual pretraining is more efficient and similarly effective compared to pretraining from scratch with long sequences.
