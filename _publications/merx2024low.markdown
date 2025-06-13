---
layout: publication
title: 'Low-resource Machine Translation Through Retrieval-augmented LLM Prompting: A Study On The Mambai Language'
authors: Raphaël Merx, Aso Mahmudi, Katrina Langford, Leo Alberto De Araujo, Ekaterina Vylomova
conference: "Arxiv"
year: 2024
bibkey: merx2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04809"}
tags: ['Model Architecture', 'Few-Shot', 'RAG', 'GPT', 'Prompting', 'Applications']
---
This study explores the use of large language models (LLMs) for translating
English into Mambai, a low-resource Austronesian language spoken in
Timor-Leste, with approximately 200,000 native speakers. Leveraging a novel
corpus derived from a Mambai language manual and additional sentences
translated by a native speaker, we examine the efficacy of few-shot LLM
prompting for machine translation (MT) in this low-resource context. Our
methodology involves the strategic selection of parallel sentences and
dictionary entries for prompting, aiming to enhance translation accuracy, using
open-source and proprietary LLMs (LlaMa 2 70b, Mixtral 8x7B, GPT-4). We find
that including dictionary entries in prompts and a mix of sentences retrieved
through TF-IDF and semantic embeddings significantly improves translation
quality. However, our findings reveal stark disparities in translation
performance across test sets, with BLEU scores reaching as high as 21.2 on
materials from the language manual, in contrast to a maximum of 4.4 on a test
set provided by a native speaker. These results underscore the importance of
diverse and representative corpora in assessing MT for low-resource languages.
Our research provides insights into few-shot LLM prompting for low-resource MT,
and makes available an initial corpus for the Mambai language.
