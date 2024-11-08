---
layout: publication
title: 'Promptdsi: Prompt-based Rehearsal-free Instance-wise Incremental Learning For Document Retrieval'
authors: Huynh Tuan-luc, Vu Thuy-trang, Wang Weiqing, Wei Yinwei, Le Trung, Gasevic Dragan, Li Yuan-fang, Do Thanh-toan
conference: "Arxiv"
year: 2024
bibkey: huynh2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12593"}
tags: ['Prompting', 'RAG', 'Training Techniques']
---
Differentiable Search Index (DSI) utilizes Pre-trained Language Models (PLMs)
for efficient document retrieval without relying on external indexes. However,
DSIs need full re-training to handle updates in dynamic corpora, causing
significant computational inefficiencies. We introduce PromptDSI, a
rehearsal-free, prompt-based approach for instance-wise incremental learning in
document retrieval. PromptDSI attaches prompts to the frozen PLM's encoder of
DSI, leveraging its powerful representation to efficiently index new corpora
while maintaining a balance between stability and plasticity. We eliminate the
initial forward pass of prompt-based continual learning methods that doubles
training and inference time. Moreover, we propose a topic-aware prompt pool
that employs neural topic embeddings as fixed keys. This strategy ensures
diverse and effective prompt usage, addressing the challenge of parameter
underutilization caused by the collapse of the query-key matching mechanism.
Our empirical evaluations demonstrate that PromptDSI matches IncDSI in managing
forgetting while significantly enhancing recall by over 4% on new corpora.
