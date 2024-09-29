---
layout: publication
title: Behind The Scene Revealing The Secrets Of Pre45;trained Vision45;and45;language Models
authors: Cao Jize, Gan Zhe, Cheng Yu, Yu Licheng, Chen Yen-chun, Liu Jingjing
conference: "Arxiv"
year: 2020
bibkey: cao2020behind
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.07310"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent Transformer45;based large45;scale pre45;trained models have revolutionized vision45;and45;language (V+L) research. Models such as ViLBERT LXMERT and UNITER have significantly lifted state of the art across a wide range of V+L benchmarks with joint image45;text pre45;training. However little is known about the inner mechanisms that destine their impressive success. To reveal the secrets behind the scene of these powerful models we present VALUE (Vision45;And45;Language Understanding Evaluation) a set of meticulously designed probing tasks (e.g. Visual Coreference Resolution Visual Relation Detection Linguistic Probing Tasks) generalizable to standard pre45;trained V+L models aiming to decipher the inner workings of multimodal pre45;training (e.g. the implicit knowledge garnered in individual attention heads the inherent cross45;modal alignment learned through contextualized multimodal embeddings). Through extensive analysis of each archetypal model architecture via these probing tasks our key observations are (i) Pre45;trained models exhibit a propensity for attending over text rather than images during inference. (ii) There exists a subset of attention heads that are tailored for capturing cross45;modal interactions. (iii) Learned attention matrix in pre45;trained models demonstrates patterns coherent with the latent alignment between image regions and textual words. (iv) Plotted attention patterns reveal visually45;interpretable relations among image regions. (v) Pure linguistic knowledge is also effectively encoded in the attention heads. These are valuable insights serving to guide future work towards designing better model architecture and objectives for multimodal pre45;training.
