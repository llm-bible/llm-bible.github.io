---
layout: publication
title: 'Pixlore: A Dataset-driven Approach To Rich Image Captioning'
authors: Diego Bonilla-salvador, Marcelino Martínez-sober, Joan Vila-francés, Antonio José Serrano-lópez, Pablo Rodríguez-belenguer, Fernando Mateo
conference: "Arxiv"
year: 2023
bibkey: bonillasalvador2023dataset
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05349"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Transformer']
---
In the domain of vision-language integration, generating detailed image
captions poses a significant challenge due to the lack of curated and rich
datasets. This study introduces PixLore, a novel method that leverages Querying
Transformers through the fine-tuning of the BLIP-2 model using the LoRa method
on a standard commercial GPU. The followed approach, which involves training on
a carefully assembled dataset from state-of-the-art Computer Vision models
combined and augmented by ChatGPT, addresses the question of whether intricate
image understanding can be achieved with an ensemble of smaller-scale models,
referred to as Knowledge Stitching. Comparative evaluations against major
models such as GPT-4 and Google Bard demonstrate that PixLore-2.7B, despite
having considerably fewer parameters, is rated higher than the existing
State-of-the-Art models in over half of the assessments. Precisely, PixLore
outperform Bard and BLIP-2, which score approximately 35.18% and 27.98% lower
than PixLore in the task of image captioning. This research not only presents a
groundbreaking approach but also highlights the importance of well-curated
datasets in enhancing the performance of smaller models.
