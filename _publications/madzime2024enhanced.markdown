---
layout: publication
title: 'Enhanced Electronic Health Records Text Summarization Using Large Language Models'
authors: Ruvarashe Madzime, Clement Nyirenda
conference: "Arxiv"
year: 2024
bibkey: madzime2024enhanced
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.09628'}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
The development of Electronic Health Records summarization systems has
revolutionized patient data management. Previous research advanced this field
by adapting Large Language Models for clinical tasks, using diverse datasets to
generate general EHR summaries. However, clinicians often require specific,
focused summaries for quicker insights. This project builds on prior work by
creating a system that generates clinician-preferred, focused summaries,
improving EHR summarization for more efficient patient care. The proposed
system leverages the Google Flan-T5 model to generate tailored EHR summaries
based on clinician-specified topics. The approach involved fine-tuning the
Flan-T5 model on an EHR question-answering dataset formatted in the Stanford
Question Answering Dataset (SQuAD) style, which is a large-scale reading
comprehension dataset with questions and answers. Fine-tuning utilized the
Seq2SeqTrainer from the Hugging Face Transformers library with optimized
hyperparameters. Key evaluation metrics demonstrated promising results: the
system achieved an Exact Match (EM) score of 81.81%. ROUGE (Recall-Oriented
Understudy for Gisting Evaluation) metrics showed strong performance, with
ROUGE-1 at 96.03%, ROUGE-2 at 86.67%, and ROUGE-L at 96.10%. Additionally, the
Bilingual Evaluation Understudy (BLEU) score was 63%, reflecting the model's
coherence in generating summaries. By enhancing EHR summarization through LLMs,
this project supports digital transformation efforts in healthcare,
streamlining workflows, and enabling more personalized patient care.
