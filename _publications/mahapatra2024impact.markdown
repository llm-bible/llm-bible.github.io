---
layout: publication
title: Impact Of Model Size On Fine-tuned LLM Performance In Data-to-text Generation&#58; A State-of-the-art Investigation
authors: Mahapatra Joy, Garain Utpal
conference: "Arxiv"
year: 2024
bibkey: mahapatra2024impact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14088"}
tags: ['Applications', 'BERT', 'Language Modeling', 'Model Architecture']
---
Data-to-text (D2T) generation aims to generate human-readable text from semi-structured data such as tables and graphs. The recent success of D2T is largely attributed to advancements in LLMs. Despite the success of LLMs no research has been conducted to illustrate the impact of model size on the performance of fine-tuned LLMs for D2T tasks. D2T model performance is typically assessed based on three key qualities (textitreadability) (indicates fluency and coherence) (textitinformativeness) (measures content similarity) and (textitfaithfulness) (assesses consistency of factual information). It is currently uncertain whether increasing the size of LLMs effectively improves performance in D2T tasks across these three qualities. The objective of this study is to investigate the performance of fine-tuned LLMs in D2T tasks in terms of model size. Through extensive comparative analysis we aim to elucidate both the advantages and limitations of scaling model sizes across five widely used D2T datasets (E2E ViGGo WikiTableText DART and WebNLG) and twelve state-of-the-art LLMs with varying sizes from five different LLM families (T5 BART OPT BLOOM and Llama 2). To comprehensively cover all the three essential qualities of D2T models we incorporate six widely recognized automatic metrics -- (textscBLEU) (textscMETEOR) (textscBERTScore) (textscMoverScore) (textscParent) and (textscBARTScore). We also provide an in-depth analysis of LLM performance concerning model size in the presence of source-reference divergence a critical aspect of D2T tasks. Our investigation reveals that increasing LLM size enhances (textitreadability) and (textitinformativeness) in D2T tasks but larger (in terms of size) LLMs may sacrifice (textitfaithfulness). Moreover small-sized LLMs show more resilience than larger ones when source-reference divergence is present.
