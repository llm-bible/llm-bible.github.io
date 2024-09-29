---
layout: publication
title: The Promise and Challenges of Using LLMs to Accelerate the Screening Process of Systematic Reviews
authors: Huotala Aleksi, Kuutila Miikka, Ralph Paul, Mäntylä Mika
conference: "Arxiv"
year: 2024
bibkey: huotala2024promise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15667"}
tags: ['Few Shot', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Survey Paper']
---
Systematic review (SR) is a popular research method in software engineering (SE). However conducting an SR takes an average of 67 weeks. Thus automating any step of the SR process could reduce the effort associated with SRs. Our objective is to investigate if Large Language Models (LLMs) can accelerate title-abstract screening by simplifying abstracts for human screeners and automating title-abstract screening. We performed an experiment where humans screened titles and abstracts for 20 papers with both original and simplified abstracts from a prior SR. The experiment with human screeners was reproduced with GPT-3.5 and GPT-4 LLMs to perform the same screening tasks. We also studied if different prompting techniques (Zero-shot (ZS) One-shot (OS) Few-shot (FS) and Few-shot with Chain-of-Thought (FS-CoT)) improve the screening performance of LLMs. Lastly we studied if redesigning the prompt used in the LLM reproduction of screening leads to improved performance. Text simplification did not increase the screeners screening performance but reduced the time used in screening. Screeners scientific literacy skills and researcher status predict screening performance. Some LLM and prompt combinations perform as well as human screeners in the screening tasks. Our results indicate that the GPT-4 LLM is better than its predecessor GPT-3.5. Additionally Few-shot and One-shot prompting outperforms Zero-shot prompting. Using LLMs for text simplification in the screening process does not significantly improve human performance. Using LLMs to automate title-abstract screening seems promising but current LLMs are not significantly more accurate than human screeners. To recommend the use of LLMs in the screening process of SRs more research is needed. We recommend future SR studies publish replication packages with screening data to enable more conclusive experimenting with LLM screening.
