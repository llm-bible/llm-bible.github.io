---
layout: publication
title: Surgicalgpt End45;to45;end Language45;vision GPT For Visual Question Answering In Surgery
authors: Seenivasan Lalithkumar, Islam Mobarakol, Kannan Gokul, Ren Hongliang
conference: "Arxiv"
year: 2023
bibkey: seenivasan2023end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.09974"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG']
---
Advances in GPT45;based large language models (LLMs) are revolutionizing natural language processing exponentially increasing its use across various domains. Incorporating uni45;directional attention these autoregressive LLMs can generate long and coherent paragraphs. However for visual question answering (VQA) tasks that require both vision and language processing models with bi45;directional attention or models employing fusion techniques are often employed to capture the context of multiple modalities all at once. As GPT does not natively process vision tokens to exploit the advancements in GPT models for VQA in robotic surgery we design an end45;to45;end trainable Language45;Vision GPT (LV45;GPT) model that expands the GPT2 model to include vision input (image). The proposed LV45;GPT incorporates a feature extractor (vision tokenizer) and vision token embedding (token type and pose). Given the limitations of unidirectional attention in GPT models and their ability to generate coherent long paragraphs we carefully sequence the word tokens before vision tokens mimicking the human thought process of understanding the question to infer an answer from an image. Quantitatively we prove that the LV45;GPT model outperforms other state45;of45;the45;art VQA models on two publically available surgical45;VQA datasets (based on endoscopic vision challenge robotic scene segmentation 2018 and CholecTriplet2021) and on our newly annotated dataset (based on the holistic surgical scene dataset). We further annotate all three datasets to include question45;type annotations to allow sub45;type analysis. Furthermore we extensively study and present the effects of token sequencing token type and pose embedding for vision tokens in the LV45;GPT model.
