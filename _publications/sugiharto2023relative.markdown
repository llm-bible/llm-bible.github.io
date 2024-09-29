---
layout: publication
title: "RCMHA: Relative Convolutional Multi-head Attention For Natural Language Modelling"
authors: Sugiharto Herman, Aradea, Mubarok Husni
conference: "Arxiv"
year: 2023
bibkey: sugiharto2023relative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.03429"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
The Attention module finds common usage in language modeling presenting distinct challenges within the broader scope of Natural Language Processing. Multi-Head Attention (MHA) employs an absolute positional encoding which imposes limitations on token length and entails substantial memory consumption during the processing of embedded inputs. The current remedy proposed by researchers involves the utilization of relative positional encoding similar to the approach adopted in Transformer-XL or Relative Multi-Head Attention (RMHA) albeit the employed architecture consumes considerable memory resources. To address these challenges this study endeavors to refine MHA leveraging relative positional encoding in conjunction with the Depth-Wise Convolutional Layer architecture which promises heightened accuracy coupled with minimized memory usage. The proposed RCMHA framework entails the modification of two integral components firstly the application of the Depth-Wise Convolutional Layer to the input embedding encompassing Query Key and Value parameters; secondly the incorporation of Relative Positional Encoding into the attention scoring phase harmoniously integrated with Scaled Dot-Product Attention. Empirical experiments underscore the advantages of RCMHA wherein it exhibits superior accuracy boasting a score of 0.572 in comparison to alternative attention modules such as MHA Multi-DConv-Head Attention (MDHA) and RMHA. Concerning memory utilization RMHA emerges as the most frugal demonstrating an average consumption of 2.98 GB surpassing RMHA which necessitates 3.5 GB.
