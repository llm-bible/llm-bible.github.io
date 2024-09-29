---
layout: publication
title: Training45;free Consistent Text45;to45;image Generation
authors: Tewel Yoad, Kaduri Omri, Gal Rinon, Kasten Yoni, Wolf Lior, Chechik Gal, Atzmon Yuval
conference: "Arxiv"
year: 2024
bibkey: tewel2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03286"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Text45;to45;image models offer a new level of creative flexibility by allowing users to guide the image generation process through natural language. However using these models to consistently portray the same subject across diverse prompts remains challenging. Existing approaches fine45;tune the model to teach it new words that describe specific user45;provided subjects or add image conditioning to the model. These methods require lengthy per45;subject optimization or large45;scale pre45;training. Moreover they struggle to align generated images with text prompts and face difficulties in portraying multiple subjects. Here we present ConsiStory a training45;free approach that enables consistent subject generation by sharing the internal activations of the pretrained model. We introduce a subject45;driven shared attention block and correspondence45;based feature injection to promote subject consistency between images. Additionally we develop strategies to encourage layout diversity while maintaining subject consistency. We compare ConsiStory to a range of baselines and demonstrate state45;of45;the45;art performance on subject consistency and text alignment without requiring a single optimization step. Finally ConsiStory can naturally extend to multi45;subject scenarios and even enable training45;free personalization for common objects.
