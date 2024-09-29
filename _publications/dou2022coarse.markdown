---
layout: publication
title: Coarse45;to45;fine Vision45;language Pre45;training With Fusion In The Backbone
authors: Dou Zi-yi, Kamath Aishwarya, Gan Zhe, Zhang Pengchuan, Wang Jianfeng, Li Linjie, Liu Zicheng, Liu Ce, Lecun Yann, Peng Nanyun, Gao Jianfeng, Wang Lijuan
conference: "Arxiv"
year: 2022
bibkey: dou2022coarse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.07643"}
  - {name: "Code", url: "https://github.com/microsoft/FIBER"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Vision45;language (VL) pre45;training has recently received considerable attention. However most existing end45;to45;end pre45;training approaches either only aim to tackle VL tasks such as image45;text retrieval visual question answering (VQA) and image captioning that test high45;level understanding of images or only target region45;level understanding for tasks such as phrase grounding and object detection. We present FIBER (Fusion45;In45;the45;Backbone45;based transformER) a new VL model architecture that can seamlessly handle both these types of tasks. Instead of having dedicated transformer layers for fusion after the uni45;modal backbones FIBER pushes multimodal fusion deep into the model by inserting cross45;attention into the image and text backbones bringing gains in terms of memory and performance. In addition unlike previous work that is either only pre45;trained on image45;text data or on fine45;grained data with box45;level annotations we present a two45;stage pre45;training strategy that uses both these kinds of data efficiently (i) coarse45;grained pre45;training based on image45;text data; followed by (ii) fine45;grained pre45;training based on image45;text45;box data. We conduct comprehensive experiments on a wide range of VL tasks ranging from VQA image captioning and retrieval to phrase grounding referring expression comprehension and object detection. Using deep multimodal fusion coupled with the two45;stage pre45;training FIBER provides consistent performance improvements over strong baselines across all tasks often outperforming methods using magnitudes more data. Code is available at https://github.com/microsoft/FIBER.
