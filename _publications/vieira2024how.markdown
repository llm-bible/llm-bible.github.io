---
layout: publication
title: How Much Data Is Enough Data? Fine-tuning Large Language Models For In-house Translation&#58; Performance Evaluation Across Multiple Dataset Sizes
authors: Vieira Inacio, Allred Will, Lankford Séamus, Castilho Sheila, Way Andy
conference: "Arxiv"
year: 2024
bibkey: vieira2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03454"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Decoder-only LLMs have shown impressive performance in MT due to their ability to learn from extensive datasets and generate high-quality translations. However LLMs often struggle with the nuances and style required for organisation-specific translation. In this study we explore the effectiveness of fine-tuning Large Language Models (LLMs) particularly Llama 3 8B Instruct leveraging translation memories (TMs) as a valuable resource to enhance accuracy and efficiency. We investigate the impact of fine-tuning the Llama 3 model using TMs from a specific organisation in the software sector. Our experiments cover five translation directions across languages of varying resource levels (English to Brazilian Portuguese Czech German Finnish and Korean). We analyse diverse sizes of training datasets (1k to 207k segments) to evaluate their influence on translation quality. We fine-tune separate models for each training set and evaluate their performance based on automatic metrics BLEU chrF++ TER and COMET. Our findings reveal improvement in translation performance with larger datasets across all metrics. On average BLEU and COMET scores increase by 13 and 25 points respectively on the largest training set against the baseline model. Notably there is a performance deterioration in comparison with the baseline model when fine-tuning on only 1k and 2k examples; however we observe a substantial improvement as the training dataset size increases. The study highlights the potential of integrating TMs with LLMs to create bespoke translation models tailored to the specific needs of businesses thus enhancing translation quality and reducing turn-around times. This approach offers a valuable insight for organisations seeking to leverage TMs and LLMs for optimal translation outcomes especially in narrower domains.
