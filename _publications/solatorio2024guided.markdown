---
layout: publication
title: Gistembed: Guided In-sample Selection Of Training Negatives For Text Embedding Fine-tuning
authors: Solatorio Aivin V.
conference: "Arxiv"
year: 2024
bibkey: solatorio2024guided
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16829"}
tags: ['Applications', 'Ethics And Bias', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Embedding models are integral to AI applications like semantic search personalized recommendations and retrieval augmented generation for LLMs necessitating high-quality training data. However the limited scalability of manual data curation prompts the need for automated methods to ensure data integrity. Traditional unsupervised triplet mining automates training data generation crucial for embedding model training yet inadvertently injects biases and noise thereby degrading model performance. Addressing this we introduce GISTEmbed a novel strategy that enhances in-batch negative selection during contrastive training through a guide model. This approach departs from reliance on random sampling and equal utility assumption of batch negatives significantly reducing noise from data quality issues and improving model fine-tuning. Benchmarked against the Massive Text Embedding Benchmark (MTEB) GISTEmbed showcases consistent performance improvements across various model sizes and achieves state-of-the-art results in select categories. This framework enables significant enhancements for smaller models by leveraging the capabilities of powerful yet resource-intensive large models. GISTEmbed can potentially revolutionize the creation of highly efficient smaller models democratizing access to advanced AI technologies. Making these technologies more accessible and cost-effective especially for applications constrained by resources significantly expands the impact and accessibility of state-of-the-art AI solutions across diverse sectors.
