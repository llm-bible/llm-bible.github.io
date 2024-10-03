---
layout: publication
title: 'Bridging Cross-lingual Gaps During Leveraging The Multilingual Sequence-to-sequence Pretraining For Text Generation And Understanding'
authors: Zan Changtong, Ding Liang, Shen Li, Cao Yu, Liu Weifeng, Tao Dacheng
conference: "Arxiv"
year: 2022
bibkey: zan2022bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.07834"}
  - {name: "Code", url: "https://github.com/zanchangtong/CSR4mBART"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
For multilingual sequence-to-sequence pretrained language models (multilingual Seq2Seq PLMs), e.g. mBART, the self-supervised pretraining task is trained on a wide range of monolingual languages, e.g. 25 languages from CommonCrawl, while the downstream cross-lingual tasks generally progress on a bilingual language subset, e.g. English-German, making there exists the data discrepancy, namely domain discrepancy, and cross-lingual learning objective discrepancy, namely task discrepancy, between the pretraining and finetuning stages. To bridge the above cross-lingual domain and task gaps, we extend the vanilla pretrain-finetune pipeline with extra code-switching restore task. Specifically, the first stage employs the self-supervised code-switching restore task as a pretext task, allowing the multilingual Seq2Seq PLMs to acquire some in-domain alignment information. And for the second stage, we fine-tune the model on downstream data normally. Experiments on both NLG evaluation (12 bilingual translation tasks, 30 zero-shot translation tasks, and 2 cross-lingual summarization tasks) and NLU evaluation (7 cross-lingual natural language inference tasks) show our model outperforms the strong baseline mBART with standard finetuning strategy, consistently. Analyses indicate our approach could narrow the Euclidean distance of cross-lingual sentence representations, and improve the model generalization with trivial computational cost. We release the code at: https://github.com/zanchangtong/CSR4mBART.
