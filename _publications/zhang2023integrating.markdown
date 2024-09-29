---
layout: publication
title: Collm Integrating Collaborative Embeddings Into Large Language Models For Recommendation
authors: Zhang Yang, Feng Fuli, Zhang Jizhi, Bao Keqin, Wang Qifan, He Xiangnan
conference: "Arxiv"
year: 2023
bibkey: zhang2023integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19488"}
  - {name: "Code", url: "https://github.com/zyang1580/CoLLM"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG']
---
Leveraging Large Language Models as Recommenders (LLMRec) has gained significant attention and introduced fresh perspectives in user preference modeling. Existing LLMRec approaches prioritize text semantics usually neglecting the valuable collaborative information from user-item interactions in recommendations. While these text-emphasizing approaches excel in cold-start scenarios they may yield sub-optimal performance in warm-start situations. In pursuit of superior recommendations for both cold and warm start scenarios we introduce CoLLM an innovative LLMRec methodology that seamlessly incorporates collaborative information into LLMs for recommendation. CoLLM captures collaborative information through an external traditional model and maps it to the input token embedding space of LLM forming collaborative embeddings for LLM usage. Through this external integration of collaborative information CoLLM ensures effective modeling of collaborative information without modifying the LLM itself providing the flexibility to employ various collaborative information modeling techniques. Extensive experiments validate that CoLLM adeptly integrates collaborative information into LLMs resulting in enhanced recommendation performance. We release the code and data at https://github.com/zyang1580/CoLLM."
