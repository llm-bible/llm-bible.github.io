---
layout: publication
title: 'Focusllm: Precise Understanding Of Long Context By Dynamic Condensing'
authors: Zhenyu Li, Yike Zhang, Tengyu Pan, Yutao Sun, Zhichao Duan, Junjie Fang, Rong Han, Zixuan Wang, Jianyong Wang
conference: "Arxiv"
year: 2024
bibkey: li2024precise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11745"}
  - {name: "Code", url: "https://github.com/leezythu/FocusLLM"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Language Modeling', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Empowering LLMs with the ability to precisely understand long contexts is
crucial for many downstream applications. However, handling long contexts with
conventional transformer architecture requires substantial training and
inference resources. Existing context condensing methods cannot accurately
understand the full context, as there is a considerable amount of information
loss in the condensing process. To address these issues, we present FocusLLM, a
framework designed to extend the fixed context length of any decoder-only LLM,
allowing the model to focus on relevant information from very long sequences.
FocusLLM first divides long text input into chunks based on the model's
original context length. It then employs the dynamic condensing process to
distill crucial information from each chunk. Ultimately, through the novel
parallel decoding mechanism, FocusLLM can integrate the extracted information
into its local context. FocusLLM stands out for great training efficiency and
versatility: trained with an 8K input length and with much less training cost
than previous methods, FocusLLM exhibits superior performance across downstream
tasks and maintains strong language modeling ability when handling extensive
long texts, even up to 400K tokens. Our code is available at
https://github.com/leezythu/FocusLLM.
