---
layout: publication
title: 'Nv-embed: Improved Techniques For Training Llms As Generalist Embedding Models'
authors: Lee Chankyu, Roy Rajarshi, Xu Mengyao, Raiman Jonathan, Shoeybi Mohammad, Catanzaro Bryan, Ping Wei
conference: "Arxiv"
year: 2024
bibkey: lee2024nv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17428"}
  - {name: "Code", url: "https://huggingface.co/nvidia/NV-Embed-v1"}
tags: ['Attention Mechanism', 'BERT', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Training Techniques']
---
'Decoder-only large language model (LLM)-based embedding models are beginning to outperform BERT or T5-based embedding models in general-purpose text embedding tasks, including dense vector-based retrieval. In this work, we introduce the NV-Embed model with a variety of architectural designs and training procedures to significantly enhance the performance of LLM as a versatile embedding model, while maintaining its simplicity and reproducibility. For model architecture, we propose a latent attention layer to obtain pooled embeddings, which consistently improves retrieval and downstream task accuracy compared to mean pooling or using the last <EOS> token embedding from LLMs. To enhance representation learning, we remove the causal attention mask of LLMs during contrastive training. For model training, we introduce a two-stage contrastive instruction-tuning method. It first applies contrastive training with instructions on retrieval datasets, utilizing in-batch negatives and curated hard negative examples. At stage-2, it blends various non-retrieval datasets into instruction tuning, which not only enhances non-retrieval task accuracy but also improves retrieval performance. Combining these techniques, our NV-Embed model, using only publicly available data, has achieved a record-high score of 69.32, ranking No. 1 on the Massive Text Embedding Benchmark (MTEB) (as of May 24, 2024), with 56 tasks, encompassing retrieval, reranking, classification, clustering, and semantic textual similarity tasks. Notably, our model also attains the highest score of 59.36 on 15 retrieval tasks in the MTEB benchmark (also known as BEIR). We will open-source the model at: https://huggingface.co/nvidia/NV-Embed-v1.'
