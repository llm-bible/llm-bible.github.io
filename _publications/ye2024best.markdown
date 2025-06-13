---
layout: publication
title: 'Best Practices For Distilling Large Language Models Into BERT For Web Search Ranking'
authors: Dezhi Ye, Junwei Hu, Jiabin Fan, Bowen Tian, Jie Liu, Haijin Liang, Jin Ma
conference: "Arxiv"
year: 2024
bibkey: ye2024best
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.04539'}
tags: ['Training Techniques', 'GPT', 'BERT', 'Fine-Tuning', 'Model Architecture', 'Prompting', 'Pre-Training', 'Pretraining Methods']
---
Recent studies have highlighted the significant potential of Large Language
Models (LLMs) as zero-shot relevance rankers. These methods predominantly
utilize prompt learning to assess the relevance between queries and documents
by generating a ranked list of potential documents. Despite their promise, the
substantial costs associated with LLMs pose a significant challenge for their
direct implementation in commercial search systems. To overcome this barrier
and fully exploit the capabilities of LLMs for text ranking, we explore
techniques to transfer the ranking expertise of LLMs to a more compact model
similar to BERT, using a ranking loss to enable the deployment of less
resource-intensive models. Specifically, we enhance the training of LLMs
through Continued Pre-Training, taking the query as input and the clicked title
and summary as output. We then proceed with supervised fine-tuning of the LLM
using a rank loss, assigning the final token as a representative of the entire
sentence. Given the inherent characteristics of autoregressive language models,
only the final token </s> can encapsulate all preceding tokens. Additionally,
we introduce a hybrid point-wise and margin MSE loss to transfer the ranking
knowledge from LLMs to smaller models like BERT. This method creates a viable
solution for environments with strict resource constraints. Both offline and
online evaluations have confirmed the efficacy of our approach, and our model
has been successfully integrated into a commercial web search engine as of
February 2024.
