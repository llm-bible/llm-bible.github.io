---
layout: publication
title: Leveraging Vision45;language Models For Improving Domain Generalization In Image Classification
authors: Addepalli Sravanti, Asokan Ashish Ramayee, Sharma Lakshay, Babu R. Venkatesh
conference: "Arxiv"
year: 2023
bibkey: addepalli2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08255"}
tags: ['Distillation', 'Efficiency And Optimization', 'RAG', 'Training Techniques']
---
Vision45;Language Models (VLMs) such as CLIP are trained on large amounts of image45;text pairs resulting in remarkable generalization across several data distributions. However in several cases their expensive training and data collection/curation costs do not justify the end application. This motivates a vendor45;client paradigm where a vendor trains a large45;scale VLM and grants only input45;output access to clients on a pay45;per45;query basis in a black45;box setting. The client aims to minimize inference cost by distilling the VLM to a student model using the limited available task45;specific data and further deploying this student model in the downstream application. While naive distillation largely improves the In45;Domain (ID) accuracy of the student it fails to transfer the superior out45;of45;distribution (OOD) generalization of the VLM teacher using the limited available labeled images. To mitigate this we propose Vision45;Language to Vision 45; Align Distill Predict (VL2V45;ADiP) which first aligns the vision and language modalities of the teacher model with the vision modality of a pre45;trained student model and further distills the aligned VLM representations to the student. This maximally retains the pre45;trained features of the student while also incorporating the rich representations of the VLM image encoder and the superior generalization of the text embeddings. The proposed approach achieves state45;of45;the45;art results on the standard Domain Generalization benchmarks in a black45;box teacher setting as well as a white45;box setting where the weights of the VLM are accessible.
