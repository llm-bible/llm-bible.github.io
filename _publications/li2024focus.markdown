---
layout: publication
title: Focus On Your Question! Interpreting And Mitigating Toxic Cot Problems In Commonsense Reasoning
authors: Li Jiachun, Cao Pengfei, Wang Chenhao, Jin Zhuoran, Chen Yubo, Zeng Daojian, Liu Kang, Zhao Jun
conference: "Arxiv"
year: 2024
bibkey: li2024focus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18344"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture']
---
Large language models exhibit high45;level commonsense reasoning abilities especially with enhancement methods like Chain45;of45;Thought (CoT). However we find these CoT45;like methods lead to a considerable number of originally correct answers turning wrong which we define as the Toxic CoT problem. To interpret and mitigate this problem we first utilize attribution tracing and causal tracing methods to probe the internal working mechanism of the LLM during CoT reasoning. Through comparisons we prove that the model exhibits information loss from the question over the shallow attention layers when generating rationales or answers. Based on the probing findings we design a novel method called RIDERS (Residual decodIng and sERial45;position Swap) which compensates for the information deficit in the model from both decoding and serial45;position perspectives. Through extensive experiments on multiple commonsense reasoning benchmarks we validate that this method not only significantly eliminates Toxic CoT problems (decreased by 23.637;) but also effectively improves the models overall commonsense reasoning performance (increased by 5.537;).
