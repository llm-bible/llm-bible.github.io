---
layout: publication
title: LXMERT Learning Cross45;modality Encoder Representations From Transformers
authors: Tan Hao, Bansal Mohit
conference: "Arxiv"
year: 2019
bibkey: tan2019learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1908.07490"}
  - {name: "Code", url: "https://github.com/airsplay/lxmert"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Has Code', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Vision45;and45;language reasoning requires an understanding of visual concepts language semantics and most importantly the alignment and relationships between these two modalities. We thus propose the LXMERT (Learning Cross45;Modality Encoder Representations from Transformers) framework to learn these vision45;and45;language connections. In LXMERT we build a large45;scale Transformer model that consists of three encoders an object relationship encoder a language encoder and a cross45;modality encoder. Next to endow our model with the capability of connecting vision and language semantics we pre45;train the model with large amounts of image45;and45;sentence pairs via five diverse representative pre45;training tasks masked language modeling masked object prediction (feature regression and label classification) cross45;modality matching and image question answering. These tasks help in learning both intra45;modality and cross45;modality relationships. After fine45;tuning from our pre45;trained parameters our model achieves the state45;of45;the45;art results on two visual question answering datasets (i.e. VQA and GQA). We also show the generalizability of our pre45;trained cross45;modality model by adapting it to a challenging visual45;reasoning task NLVR2 and improve the previous best result by 2237; absolute (5437; to 7637;). Lastly we demonstrate detailed ablation studies to prove that both our novel model components and pre45;training strategies significantly contribute to our strong results; and also present several attention visualizations for the different encoders. Code and pre45;trained models publicly available at https://github.com/airsplay/lxmert
