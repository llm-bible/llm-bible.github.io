---
layout: publication
title: Can Large Language Models Reason About Medical Questions
authors: Liévin Valentin, Hother Christoffer Egeberg, Motzfeldt Andreas Geert, Winther Ole
conference: "Arxiv"
year: 2022
bibkey: liévin2022can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.08143"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Although large language models (LLMs) often produce impressive outputs it remains unclear how they perform in real45;world scenarios requiring strong reasoning skills and expert domain knowledge. We set out to investigate whether close45; and open45;source models (GPT45;3.5 LLama45;2 etc.) can be applied to answer and reason about difficult real45;world45;based questions. We focus on three popular medical benchmarks (MedQA45;USMLE MedMCQA and PubMedQA) and multiple prompting scenarios Chain45;of45;Thought (CoT think step45;by45;step) few45;shot and retrieval augmentation. Based on an expert annotation of the generated CoTs we found that InstructGPT can often read reason and recall expert knowledge. Last by leveraging advances in prompt engineering (few45;shot and ensemble methods) we demonstrated that GPT45;3.5 not only yields calibrated predictive distributions but also reaches the passing score on three datasets MedQA45;USMLE 60.237; MedMCQA 62.737; and PubMedQA 78.237;. Open45;source models are closing the gap Llama45;2 70B also passed the MedQA45;USMLE with 62.537; accuracy.
