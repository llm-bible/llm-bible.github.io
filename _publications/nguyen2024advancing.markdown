---
layout: publication
title: Advancing Vietnamese Visual Question Answering With Transformer And Convolutional Integration
authors: Nguyen Ngoc Son, Nguyen Van Son, Le Tung
conference: "Computers and Electrical Engineering"
year: 2024
bibkey: nguyen2024advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21229"}
  - {name: "Code", url: "https://github.com/nngocson2002/ViVQA"}
tags: ['Applications', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Visual Question Answering (VQA) has recently emerged as a potential research domain captivating the interest of many in the field of artificial intelligence and computer vision. Despite the prevalence of approaches in English there is a notable lack of systems specifically developed for certain languages particularly Vietnamese. This study aims to bridge this gap by conducting comprehensive experiments on the Vietnamese Visual Question Answering (ViVQA) dataset demonstrating the effectiveness of our proposed model. In response to community interest we have developed a model that enhances image representation capabilities thereby improving overall performance in the ViVQA system. Specifically our model integrates the Bootstrapping Language-Image Pre-training with frozen unimodal models (BLIP-2) and the convolutional neural network EfficientNet to extract and process both local and global features from images. This integration leverages the strengths of transformer-based architectures for capturing comprehensive contextual information and convolutional networks for detailed local features. By freezing the parameters of these pre-trained models we significantly reduce the computational cost and training time while maintaining high performance. This approach significantly improves image representation and enhances the performance of existing VQA systems. We then leverage a multi-modal fusion module based on a general-purpose multi-modal foundation model (BEiT-3) to fuse the information between visual and textual features. Our experimental findings demonstrate that our model surpasses competing baselines achieving promising performance. This is particularly evident in its accuracy of 71.0437; on the test set of the ViVQA dataset marking a significant advancement in our research area. The code is available at https://github.com/nngocson2002/ViVQA."
