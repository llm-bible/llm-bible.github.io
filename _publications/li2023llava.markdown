---
layout: publication
title: Llava45;med Training A Large Language45;and45;vision Assistant For Biomedicine In One Day
authors: Li Chunyuan, Wong Cliff, Zhang Sheng, Usuyama Naoto, Liu Haotian, Yang Jianwei, Naumann Tristan, Poon Hoifung, Gao Jianfeng
conference: "Arxiv"
year: 2023
bibkey: li2023llava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00890"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'RAG', 'Tools', 'Training Techniques']
---
Conversational generative AI has demonstrated remarkable promise for empowering biomedical practitioners but current investigations focus on unimodal text. Multimodal conversational AI has seen rapid progress by leveraging billions of image45;text pairs from the public web but such general45;domain vision45;language models still lack sophistication in understanding and conversing about biomedical images. In this paper we propose a cost45;efficient approach for training a vision45;language conversational assistant that can answer open45;ended research questions of biomedical images. The key idea is to leverage a large45;scale broad45;coverage biomedical figure45;caption dataset extracted from PubMed Central use GPT45;4 to self45;instruct open45;ended instruction45;following data from the captions and then fine45;tune a large general45;domain vision45;language model using a novel curriculum learning method. Specifically the model first learns to align biomedical vocabulary using the figure45;caption pairs as is then learns to master open45;ended conversational semantics using GPT45;4 generated instruction45;following data broadly mimicking how a layperson gradually acquires biomedical knowledge. This enables us to train a Large Language and Vision Assistant for BioMedicine (LLaVA45;Med) in less than 15 hours (with eight A100s). LLaVA45;Med exhibits excellent multimodal conversational capability and can follow open45;ended instruction to assist with inquiries about a biomedical image. On three standard biomedical visual question answering datasets LLaVA45;Med outperforms previous supervised state45;of45;the45;art on certain metrics. To facilitate biomedical multimodal research we will release our instruction45;following data and the LLaVA45;Med model.
