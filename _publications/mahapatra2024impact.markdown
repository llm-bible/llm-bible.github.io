---
layout: publication
title: Impact Of Model Size On Fine45;tuned LLM Performance In Data45;to45;text Generation A State45;of45;the45;art Investigation
authors: Mahapatra Joy, Garain Utpal
conference: "Arxiv"
year: 2024
bibkey: mahapatra2024impact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14088"}
tags: ['Applications', 'BERT', 'Language Modeling', 'Model Architecture']
---
Data45;to45;text (D2T) generation aims to generate human45;readable text from semi45;structured data such as tables and graphs. The recent success of D2T is largely attributed to advancements in LLMs. Despite the success of LLMs no research has been conducted to illustrate the impact of model size on the performance of fine45;tuned LLMs for D2T tasks. D2T model performance is typically assessed based on three key qualities textit123;readability125; (indicates fluency and coherence) textit123;informativeness125; (measures content similarity) and textit123;faithfulness125; (assesses consistency of factual information). It is currently uncertain whether increasing the size of LLMs effectively improves performance in D2T tasks across these three qualities. The objective of this study is to investigate the performance of fine45;tuned LLMs in D2T tasks in terms of model size. Through extensive comparative analysis we aim to elucidate both the advantages and limitations of scaling model sizes across five widely used D2T datasets (E2E ViGGo WikiTableText DART and WebNLG) and twelve state45;of45;the45;art LLMs with varying sizes from five different LLM families (T5 BART OPT BLOOM and Llama 2). To comprehensively cover all the three essential qualities of D2T models we incorporate six widely recognized automatic metrics 45;45; textsc123;BLEU125; textsc123;METEOR125; textsc123;BERTScore125; textsc123;MoverScore125; textsc123;Parent125; and textsc123;BARTScore125;. We also provide an in45;depth analysis of LLM performance concerning model size in the presence of source45;reference divergence a critical aspect of D2T tasks. Our investigation reveals that increasing LLM size enhances textit123;readability125; and textit123;informativeness125; in D2T tasks but larger (in terms of size) LLMs may sacrifice textit123;faithfulness125;. Moreover small45;sized LLMs show more resilience than larger ones when source45;reference divergence is present.
