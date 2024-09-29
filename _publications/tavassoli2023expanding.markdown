---
layout: publication
title: Expanding Frozen Vision-language Models Without Retraining: Towards Improved Robot Perception
authors: Tavassoli Riley, Amani Mani, Akhavian Reza
conference: "Arxiv"
year: 2023
bibkey: tavassoli2023expanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.16493"}
tags: ['Applications', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Vision-language models (VLMs) have shown powerful capabilities in visual question answering and reasoning tasks by combining visual representations with the abstract skill set large language models (LLMs) learn during pretraining. Vision while the most popular modality to augment LLMs with is only one representation of a scene. In human-robot interaction scenarios robot perception requires accurate scene understanding by the robot. In this paper we define and demonstrate a method of aligning the embedding spaces of different modalities (in this case inertial measurement unit (IMU) data) to the vision embedding space through a combination of supervised and contrastive training enabling the VLM to understand and reason about these additional modalities without retraining. We opt to give the model IMU embeddings directly over using a separate human activity recognition model that feeds directly into the prompt to allow for any nonlinear interactions between the query image and IMU signal that would be lost by mapping the IMU data to a discrete activity label. Further we demonstrate our methodologys efficacy through experiments involving human activity recognition using IMU data and visual inputs. Our results show that using multiple modalities as input improves the VLMs scene understanding and enhances its overall performance in various tasks thus paving the way for more versatile and capable language models in multi-modal contexts.
