---
layout: publication
title: Autocap Towards Automatic Cross45;lingual Alignment Planning For Zero45;shot Chain45;of45;thought
authors: Zhang Yongheng, Chen Qiguang, Li Min, Che Wanxiang, Qin Libo
conference: "Arxiv"
year: 2024
bibkey: zhang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13940"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting']
---
Cross45;lingual chain45;of45;thought can effectively complete reasoning tasks across languages which gains increasing attention. Recently dominant approaches in the literature improve cross45;lingual alignment capabilities by integrating reasoning knowledge from different languages. Despite achieving excellent performance current methods still have two main challenges (1) Manual language specification They still highly rely on manually selecting the languages to integrate severely affecting their generalizability; (2) Static weight allocation Current methods simply integrate all languages equally. In fact different language reasoning paths should have different weights to achieve better complementation and integration. Motivated by this we introduce an Automatic Cross45;lingual Alignment Planning (AutoCAP) for zero45;shot chain45;of45;thought to address the above challenges. The core of AutoCAP consists of two components (1) Automatic Language Selection Prompting to guide LLMs to select appropriate languages and (2) Automatic Weight Allocation Prompting to automatically allocate alignment weight scores to each reasoning path. Extensive experiments on several benchmarks reveal that AutoCAP achieves state45;of45;the45;art performance surpassing previous methods that required manual effort.
