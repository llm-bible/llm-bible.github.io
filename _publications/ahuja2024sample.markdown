---
layout: publication
title: Sphinx Sample Efficient Multilingual Instruction Fine45;tuning Through N45;shot Guided Prompting
authors: Ahuja Sanchit, Tanmay Kumar, Chauhan Hardik Hansrajbhai, Patra Barun, Aggarwal Kriti, Del Corro Luciano, Mitra Arindam, Dhamecha Tejas Indulal, Awadallah Ahmed, Choudhary Monojit, Chaudhary Vishrav, Sitaram Sunayana
conference: "Arxiv"
year: 2024
bibkey: ahuja2024sample
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09879"}
tags: ['Applications', 'Prompting', 'RAG']
---
Despite the remarkable success of LLMs in English there is a significant gap in performance in non45;English languages. In order to address this we introduce a novel recipe for creating a multilingual synthetic instruction tuning dataset sPhinX which is created by selectively translating instruction response pairs from English into 50 languages. We test the effectiveness of sPhinX by using it to fine45;tune two state45;of45;the45;art models Phi45;345;small and Mistral45;7B and then evaluating them across a comprehensive suite of multilingual benchmarks that test reasoning question answering and reading comprehension. Our results show that Phi45;345;small and Mistral45;7B fine45;tuned with sPhinX perform better on an average by 4.237;pt and 537;pt respectively as compared to the baselines. We also devise a strategy to incorporate N45;shot examples in each fine45;tuning sample which further boosts the performance of these models by 337;pt and 1037;pt respectively. Additionally sPhinX also outperforms other multilingual instruction tuning datasets on the same benchmarks along with being sample efficient and diverse thereby reducing dataset creation costs. Additionally instruction tuning with sPhinX does not lead to regression on most standard LLM benchmarks.
