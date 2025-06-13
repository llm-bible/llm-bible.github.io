---
layout: publication
title: 'Sphinx: Sample Efficient Multilingual Instruction Fine-tuning Through N-shot Guided Prompting'
authors: Sanchit Ahuja, Kumar Tanmay, Hardik Hansrajbhai Chauhan, Barun Patra, Kriti Aggarwal, Luciano Del Corro, Arindam Mitra, Tejas Indulal Dhamecha, Ahmed Awadallah, Monojit Choudhary, Vishrav Chaudhary, Sunayana Sitaram
conference: "Arxiv"
year: 2024
bibkey: ahuja2024sample
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09879"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Despite the remarkable success of LLMs in English, there is a significant gap
in performance in non-English languages. In order to address this, we introduce
a novel recipe for creating a multilingual synthetic instruction tuning
dataset, sPhinX, which is created by selectively translating instruction
response pairs from English into 50 languages. We test the effectiveness of
sPhinx by using it to fine-tune two state-of-the-art models, Mistral-7B and
Phi-Small and then evaluating them across a comprehensive suite of multilingual
benchmarks that test reasoning, question answering, reading comprehension and
machine translation. Our results show that Mistral-7B and Phi-Small fine-tuned
with sPhinX perform better on an average by 5%pt for both the models when
compared to the base variants of these models. We also devise a strategy to
incorporate N-shot examples in each fine-tuning sample which further boosts the
performance of these models by 9%pt and 4%pt respectively respectively compared
to vanilla fine-tuning. To show efficacy of our data curation approach, we also
directly translate our original dataset to the target languages, and observe an
increase of 7%pt and 4%pt on both the models respectively. sPhinX outperforms
other multilingual instruction tuning datasets in both efficiency and
diversity, reducing dataset creation costs. It also maintains strong
performance on standard English LLM benchmarks, with minimal regression.
