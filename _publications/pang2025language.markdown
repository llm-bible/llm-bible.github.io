---
layout: publication
title: 'Language Models Can See Better: Visual Contrastive Decoding For LLM Multimodal Reasoning'
authors: Yuqi Pang, Bowen Yang, Haoqin Tu, Yun Cao, Zeyu Zhang
conference: "Arxiv"
year: 2025
bibkey: pang2025language
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11751'}
  - {name: "Code", url: 'https://github.com/Pbhgit/MVCD'}
tags: ['Has Code', 'ACL', 'RAG', 'Training Techniques', 'Tools', 'Applications', 'Multimodal Models', 'TACL']
---
Although Large Language Models (LLMs) excel in reasoning and generation for
language tasks, they are not specifically designed for multimodal challenges.
Training Multimodal Large Language Models (MLLMs), however, is
resource-intensive and constrained by various training limitations. In this
paper, we propose the Modular-based Visual Contrastive Decoding (MVCD)
framework to move this obstacle. Our framework leverages LLMs' In-Context
Learning (ICL) capability and the proposed visual contrastive-example decoding
(CED), specifically tailored for this framework, without requiring any
additional training. By converting visual signals into text and focusing on
contrastive output distributions during decoding, we can highlight the new
information introduced by contextual examples, explore their connections, and
avoid over-reliance on prior encoded knowledge. MVCD enhances LLMs' visual
perception to make it see and reason over the input visuals. To demonstrate
MVCD's effectiveness, we conduct experiments with four LLMs across five
question answering datasets. Our results not only show consistent improvement
in model accuracy but well explain the effective components inside our decoding
strategy. Our code will be available at https://github.com/Pbhgit/MVCD.
