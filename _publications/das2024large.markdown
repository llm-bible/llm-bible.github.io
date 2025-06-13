---
layout: publication
title: 'Speechverse: A Large-scale Generalizable Audio Language Model'
authors: Nilaksh Das, Saket Dingliwal, Srikanth Ronanki, Rohit Paturi, Zhaocheng Huang, Prashant Mathur, Jie Yuan, Dhanush Bekal, Xing Niu, Sai Muralidhar Jayanthi, Xilai Li, Karel Mundnich, Monica Sunkara, Sravan Bodapati, Sundararajan Srinivasan, Kyu J Han, Katrin Kirchhoff
conference: "Arxiv"
year: 2024
bibkey: das2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.08295"}
tags: ['INTERSPEECH', 'Tools', 'Training Techniques', 'Multimodal Models', 'Prompting']
---
Large language models (LLMs) have shown incredible proficiency in performing
tasks that require semantic understanding of natural language instructions.
Recently, many works have further expanded this capability to perceive
multimodal audio and text inputs, but their capabilities are often limited to
specific fine-tuned tasks such as automatic speech recognition and translation.
We therefore develop SpeechVerse, a robust multi-task training and curriculum
learning framework that combines pre-trained speech and text foundation models
via a small set of learnable parameters, while keeping the pre-trained models
frozen during training. The models are instruction finetuned using continuous
latent representations extracted from the speech foundation model to achieve
optimal zero-shot performance on a diverse range of speech processing tasks
using natural language instructions. We perform extensive benchmarking that
includes comparing our model performance against traditional baselines across
several datasets and tasks. Furthermore, we evaluate the model's capability for
generalized instruction following by testing on out-of-domain datasets, novel
prompts, and unseen tasks. Our empirical experiments reveal that our multi-task
SpeechVerse model is even superior to conventional task-specific baselines on 9
out of the 11 tasks.
