---
layout: publication
title: 'Building Multimodal AI Chatbots'
authors: Lee Min Young
conference: "Arxiv"
year: 2023
bibkey: lee2023building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03512"}
  - {name: "Code", url: "https://github.com/minniie/multimodal_chat.git"}
tags: ['BERT', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
This work aims to create a multimodal AI system that chats with humans and shares relevant photos. While earlier works were limited to dialogues about specific objects or scenes within images recent works have incorporated images into open-domain dialogues. However their response generators are unimodal accepting text input but no image input thus prone to generating responses contradictory to the images shared in the dialogue. Therefore this work proposes a complete chatbot system using two multimodal deep learning models an image retriever that understands texts and a response generator that understands images. The image retriever implemented by ViT and BERT selects the most relevant image given the dialogue history and a database of images. The response generator implemented by ViT and GPT-2/DialoGPT generates an appropriate response given the dialogue history and the most recently retrieved image. The two models are trained and evaluated on PhotoChat an open-domain dialogue dataset in which a photo is shared in each session. In automatic evaluation the proposed image retriever outperforms existing baselines VSE++ and SCAN with Recall@1/5/10 of 0.1/0.3/0.4 and MRR of 0.2 when ranking 1000 images. The proposed response generator also surpasses the baseline Divter with PPL of 16.9 BLEU-1/2 of 0.13/0.03 and Distinct-1/2 of 0.97/0.86 showing a significant improvement in PPL by -42.8 and BLEU-1/2 by +0.07/0.02. In human evaluation with a Likert scale of 1-5 the complete multimodal chatbot system receives higher image-groundedness of 4.3 and engagingness of 4.3 along with competitive fluency of 4.1 coherence of 3.9 and humanness of 3.1 when compared to other chatbot variants. The source code is available at https://github.com/minniie/multimodal\_chat.git."
