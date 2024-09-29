---
layout: publication
title: Bridging Cross45;lingual Gaps During Leveraging The Multilingual Sequence45;to45;sequence Pretraining For Text Generation And Understanding
authors: Zan Changtong, Ding Liang, Shen Li, Cao Yu, Liu Weifeng, Tao Dacheng
conference: "Arxiv"
year: 2022
bibkey: zan2022bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.07834"}
  - {name: "Code", url: "https://github.com/zanchangtong/CSR4mBART"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
For multilingual sequence45;to45;sequence pretrained language models (multilingual Seq2Seq PLMs) e.g. mBART the self45;supervised pretraining task is trained on a wide range of monolingual languages e.g. 25 languages from CommonCrawl while the downstream cross45;lingual tasks generally progress on a bilingual language subset e.g. English45;German making there exists the data discrepancy namely domain discrepancy and cross45;lingual learning objective discrepancy namely task discrepancy between the pretraining and finetuning stages. To bridge the above cross45;lingual domain and task gaps we extend the vanilla pretrain45;finetune pipeline with extra code45;switching restore task. Specifically the first stage employs the self45;supervised code45;switching restore task as a pretext task allowing the multilingual Seq2Seq PLMs to acquire some in45;domain alignment information. And for the second stage we fine45;tune the model on downstream data normally. Experiments on both NLG evaluation (12 bilingual translation tasks 30 zero45;shot translation tasks and 2 cross45;lingual summarization tasks) and NLU evaluation (7 cross45;lingual natural language inference tasks) show our model outperforms the strong baseline mBART with standard finetuning strategy consistently. Analyses indicate our approach could narrow the Euclidean distance of cross45;lingual sentence representations and improve the model generalization with trivial computational cost. We release the code at https://github.com/zanchangtong/CSR4mBART.
