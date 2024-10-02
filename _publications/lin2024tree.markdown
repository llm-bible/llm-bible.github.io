---
layout: publication
title: 'Tree-based Hard Attention With Self-motivation For Large Language Models'
authors: Lin Chenxi, Ren Jiayu, He Guoxiu, Jiang Zhuoren, Yu Haiyan, Zhu Xiaomin
conference: "Arxiv"
year: 2024
bibkey: lin2024tree
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08874"}
tags: ['Attention Mechanism', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Transformer']
---
While large language models (LLMs) excel at understanding and generating plain text, they are not specifically tailored to handle hierarchical text structures. Extracting the task-desired property from their natural language responses typically necessitates additional processing steps. In fact, selectively comprehending the hierarchical structure of large-scale text is pivotal to understanding its substance. Aligning LLMs more closely with the classification or regression values of specific task through prompting also remains challenging. To this end, we propose a novel framework called Tree-Based Hard Attention with Self-Motivation for Large Language Models (TEAROOM). TEAROOM incorporates a tree-based hard attention mechanism for LLMs to process hierarchically structured text inputs. By leveraging prompting, it enables a frozen LLM to selectively focus on relevant leaves in relation to the root, generating a tailored symbolic representation of their relationship. Moreover, TEAROOM comprises a self-motivation strategy for another LLM equipped with a trainable adapter and a linear layer. The selected symbolic outcomes are integrated into another prompt, along with the predictive value of the task. We iteratively feed output values back into the prompt, enabling the trainable LLM to progressively approximate the golden truth. TEAROOM outperforms existing state-of-the-art methods in experimental evaluations across three benchmark datasets, showing its effectiveness in estimating task-specific properties. Through comprehensive experiments and analysis, we have validated the ability of TEAROOM to gradually approach the underlying golden truth through multiple inferences.
