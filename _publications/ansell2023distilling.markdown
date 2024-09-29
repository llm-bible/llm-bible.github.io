---
layout: publication
title: Distilling Efficient Language45;specific Models For Cross45;lingual Transfer
authors: Ansell Alan, Ponti Edoardo Maria, Korhonen Anna, Vulić Ivan
conference: "Arxiv"
year: 2023
bibkey: ansell2023distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.01709"}
  - {name: "Code", url: "https://github.com/AlanAnsell/bistil"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Massively multilingual Transformers (MMTs) such as mBERT and XLM45;R are widely used for cross45;lingual transfer learning. While these are pretrained to represent hundreds of languages end users of NLP systems are often interested only in individual languages. For such purposes the MMTs language coverage makes them unnecessarily expensive to deploy in terms of model size inference time energy and hardware cost. We thus propose to extract compressed language45;specific models from MMTs which retain the capacity of the original MMTs for cross45;lingual transfer. This is achieved by distilling the MMT bilingually i.e. using data from only the source and target language of interest. Specifically we use a two45;phase distillation approach termed BiStil (i) the first phase distils a general bilingual model from the MMT while (ii) the second task45;specific phase sparsely fine45;tunes the bilingual student model using a task45;tuned variant of the original MMT as its teacher. We evaluate this distillation technique in zero45;shot cross45;lingual transfer across a number of standard cross45;lingual benchmarks. The key results indicate that the distilled models exhibit minimal degradation in target language performance relative to the base MMT despite being significantly smaller and faster. Furthermore we find that they outperform multilingually distilled models such as DistilmBERT and MiniLMv2 while having a very modest training budget in comparison even on a per45;language basis. We also show that bilingual models distilled from MMTs greatly outperform bilingual models trained from scratch. Our code and models are available at https://github.com/AlanAnsell/bistil.
