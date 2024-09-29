---
layout: publication
title: "PLUG: Leveraging Pivot Language In Cross-lingual Instruction Tuning"
authors: Zhang Zhihan, Lee Dong-ho, Fang Yuwei, Yu Wenhao, Jia Mengzhao, Jiang Meng, Barbieri Francesco
conference: "Arxiv"
year: 2023
bibkey: zhang2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08711"}
  - {name: "Code", url: "https://github.com/ytyz1307zzh/PLUG"}
tags: ['Has Code', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Instruction tuning has remarkably advanced large language models (LLMs) in understanding and responding to diverse human instructions. Despite the success in high-resource languages its application in lower-resource ones faces challenges due to the imbalanced foundational abilities of LLMs across different languages stemming from the uneven language distribution in their pre-training data. To tackle this issue we propose pivot language guided generation (PLUG) an approach that utilizes a high-resource language primarily English as the pivot to enhance instruction tuning in lower-resource languages. It trains the model to first process instructions in the pivot language and then produce responses in the target language. To evaluate our approach we introduce a benchmark X-AlpacaEval of instructions in 4 languages (Chinese Korean Italian and Spanish) each annotated by professional translators. Our approach demonstrates a significant improvement in the instruction-following abilities of LLMs by 2937; on average compared to directly responding in the target language alone. Further experiments validate the versatility of our approach by employing alternative pivot languages beyond English to assist languages where LLMs exhibit lower proficiency. Our code and data are available at https://github.com/ytyz1307zzh/PLUG."
