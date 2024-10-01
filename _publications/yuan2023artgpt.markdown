---
layout: publication
title: 'Artgpt-4: Towards Artistic-understanding Large Vision-language Models With Enhanced Adapter'
authors: Yuan Zhengqing, He Yunhong, Wang Kun, Ye Yanfang, Sun Lichao
conference: "Arxiv"
year: 2023
bibkey: yuan2023artgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.07490"}
  - {name: "Code", url: "https://github.com/DLYuanGod/ArtGPT-4"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Has Code', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
The success of large language models (LLMs) has inspired an emerging research field of multimodal learning. However, a grand challenge of exploiting LLMs for multimodal learning is the size of pre-trained LLMs which are always with billions of parameters. To tackle this challenge, models such as MiniGPT-4 and LLaVA have been developed to fine-tune the pre-trained models using fewer parameters. Despite their promising performance, these models remain limited in their understanding of artistic imagery. To facilitate better artistic-understanding, in this paper, we propose ArtGPT-4, a pioneering large vision-language model tailored to address the limitations of existing models in artistic comprehension. The key innovation of ArtGPT-4 lies in its craft for the sophisticated challenge of artistic image comprehension, setting it apart from other models that overlook fine details for broader themes. Specifically, it works by integrating some specialized adapter layers into the LLM, enabling the model to more efficiently and effectively parse and interpret complex visual tokens, instead of fine-tuning the whole LLM as in the existing method. ArtGPT-4 has demonstrated its outstanding performance on the efficiency: utilizing a Tesla A100 device, its training can be completed in mere 2 hours with an image-text pair dataset comprising approximately 0.52M entries. Additionally, ArtGPT-4 has also achieved state-of-the-art performance on the ArtEmis and ArtEmis-v2.0 datasets as well as the benchmarks established in this work, lagging behind professional artists' descriptions by a negligible 0.15 points on a 6-point scale. The outstanding performance of ArtGPT-4 shows that it can render images with an artistic-understanding and convey the emotions they inspire, mirroring human interpretation. The code and the pre-trained model are accessible in \url\{https://github.com/DLYuanGod/ArtGPT-4\}.
