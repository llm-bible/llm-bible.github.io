---
layout: publication
title: Poisoning Language Models During Instruction Tuning
authors: Wan Alexander, Wallace Eric, Shen Sheng, Klein Dan
conference: "Arxiv"
year: 2023
bibkey: wan2023poisoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.00944"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'RAG']
---
Instruction45;tuned LMs such as ChatGPT FLAN and InstructGPT are finetuned on datasets that contain user45;submitted examples e.g. FLAN aggregates numerous open45;source datasets and OpenAI leverages examples submitted in the browser playground. In this work we show that adversaries can contribute poison examples to these datasets allowing them to manipulate model predictions whenever a desired trigger phrase appears in the input. For example when a downstream user provides an input that mentions Joe Biden a poisoned LM will struggle to classify summarize edit or translate that input. To construct these poison examples we optimize their inputs and outputs using a bag45;of45;words approximation to the LM. We evaluate our method on open45;source instruction45;tuned LMs. By using as few as 100 poison examples we can cause arbitrary phrases to have consistent negative polarity or induce degenerate outputs across hundreds of held45;out tasks. Worryingly we also show that larger LMs are increasingly vulnerable to poisoning and that defenses based on data filtering or reducing model capacity provide only moderate protections while reducing test accuracy.
