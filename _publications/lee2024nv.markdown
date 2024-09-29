---
layout: publication
title: Nv45;embed Improved Techniques For Training Llms As Generalist Embedding Models
authors: Lee Chankyu, Roy Rajarshi, Xu Mengyao, Raiman Jonathan, Shoeybi Mohammad, Catanzaro Bryan, Ping Wei
conference: "Arxiv"
year: 2024
bibkey: lee2024nv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17428"}
  - {name: "Code", url: "https://huggingface.co/nvidia/NV&#45;Embed&#45;v1"}
tags: ['Attention Mechanism', 'BERT', 'Has Code', 'Model Architecture', 'Training Techniques']
---
Decoder45;only large language model (LLM)45;based embedding models are beginning to outperform BERT or T545;based embedding models in general45;purpose text embedding tasks including dense vector45;based retrieval. In this work we introduce the NV45;Embed model with a variety of architectural designs and training procedures to significantly enhance the performance of LLM as a versatile embedding model while maintaining its simplicity and reproducibility. For model architecture we propose a latent attention layer to obtain pooled embeddings which consistently improves retrieval and downstream task accuracy compared to mean pooling or using the last <EOS token embedding from LLMs. To enhance representation learning we remove the causal attention mask of LLMs during contrastive training. For model training we introduce a two45;stage contrastive instruction45;tuning method. It first applies contrastive training with instructions on retrieval datasets utilizing in45;batch negatives and curated hard negative examples. At stage45;2 it blends various non45;retrieval datasets into instruction tuning which not only enhances non45;retrieval task accuracy but also improves retrieval performance. Combining these techniques our NV45;Embed model using only publicly available data has achieved a record45;high score of 69.32 ranking No. 1 on the Massive Text Embedding Benchmark (MTEB) (as of May 24 2024) with 56 tasks encompassing retrieval reranking classification clustering and semantic textual similarity tasks. Notably our model also attains the highest score of 59.36 on 15 retrieval tasks in the MTEB benchmark (also known as BEIR). We will open45;source the model at https://huggingface.co/nvidia/NV&#45;Embed&#45;v1.
