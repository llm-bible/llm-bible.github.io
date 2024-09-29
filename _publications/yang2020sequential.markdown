---
layout: publication
title: Seqdialn Sequential Visual Dialog Networks In Joint Visual45;linguistic Representation Space
authors: Yang Liu
conference: "Arxiv"
year: 2020
bibkey: yang2020sequential
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2008.00397"}
  - {name: "Code", url: "https://github.com/xiaoxiaoheimei/SeqDialN"}
tags: ['Attention Mechanism', 'Has Code', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Transformer']
---
In this work we formulate a visual dialog as an information flow in which each piece of information is encoded with the joint visual45;linguistic representation of a single dialog round. Based on this formulation we consider the visual dialog task as a sequence problem consisting of ordered visual45;linguistic vectors. For featurization we use a Dense Symmetric Co45;Attention network as a lightweight vison45;language joint representation generator to fuse multimodal features (i.e. image and text) yielding better computation and data efficiencies. For inference we propose two Sequential Dialog Networks (SeqDialN) the first uses LSTM for information propagation (IP) and the second uses a modified Transformer for multi45;step reasoning (MR). Our architecture separates the complexity of multimodal feature fusion from that of inference which allows simpler design of the inference engine. IP based SeqDialN is our baseline with a simple 245;layer LSTM design that achieves decent performance. MR based SeqDialN on the other hand recurrently refines the semantic question/history representations through the self45;attention stack of Transformer and produces promising results on the visual dialog task. On VisDial v1.0 test45;std dataset our best single generative SeqDialN achieves 62.5437; NDCG and 48.6337; MRR; our ensemble generative SeqDialN achieves 63.7837; NDCG and 49.9837; MRR which set a new state45;of45;the45;art generative visual dialog model. We fine45;tune discriminative SeqDialN with dense annotations and boost the performance up to 72.4137; NDCG and 55.1137; MRR. In this work we discuss the extensive experiments we have conducted to demonstrate the effectiveness of our model components. We also provide visualization for the reasoning process from the relevant conversation rounds and discuss our fine45;tuning methods. Our code is available at https://github.com/xiaoxiaoheimei/SeqDialN
