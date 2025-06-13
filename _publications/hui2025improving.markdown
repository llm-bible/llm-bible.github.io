---
layout: publication
title: 'Decif: Improving Instruction-following Through Meta-decomposition'
authors: Tingfeng Hui, Pengyu Zhu, Bowen Ping, Ling Tang, Yaqi Zhang, Sen Su
conference: "Arxiv"
year: 2025
bibkey: hui2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13990'}
tags: ['Tools']
---
Instruction-following has emerged as a crucial capability for large language models (LLMs). However, existing approaches often rely on pre-existing documents or external resources to synthesize instruction-following data, which limits their flexibility and generalizability. In this paper, we introduce DecIF, a fully autonomous, meta-decomposition guided framework that generates diverse and high-quality instruction-following data using only LLMs. DecIF is grounded in the principle of decomposition. For instruction generation, we guide LLMs to iteratively produce various types of meta-information, which are then combined with response constraints to form well-structured and semantically rich instructions. We further utilize LLMs to detect and resolve potential inconsistencies within the generated instructions. Regarding response generation, we decompose each instruction into atomic-level evaluation criteria, enabling rigorous validation and the elimination of inaccurate instruction-response pairs. Extensive experiments across a wide range of scenarios and settings demonstrate DecIF's superior performance on instruction-following tasks. Further analysis highlights its strong flexibility, scalability, and generalizability in automatically synthesizing high-quality instruction data.
