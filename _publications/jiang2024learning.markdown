---
layout: publication
title: Learning To Edit&#58; Aligning Llms With Knowledge Editing
authors: Jiang Yuxin, Wang Yufei, Wu Chuhan, Zhong Wanjun, Zeng Xingshan, Gao Jiahui, Li Liangyou, Jiang Xin, Shang Lifeng, Tang Ruiming, Liu Qun, Wang Wei
conference: "Arxiv"
year: 2024
bibkey: jiang2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11905"}
  - {name: "Code", url: "https://github.com/YJiangcm/LTE"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'RAG', 'Security', 'Tools']
---
Knowledge editing techniques aiming to efficiently modify a minor proportion of knowledge in large language models (LLMs) without negatively impacting performance across other inputs have garnered widespread attention. However existing methods predominantly rely on memorizing the updated knowledge impeding LLMs from effectively combining the new knowledge with their inherent knowledge when answering questions. To this end we propose a Learning to Edit (LTE) framework focusing on teaching LLMs to apply updated knowledge into input questions inspired by the philosophy of Teach a man to fish. LTE features a two-phase process (i) the Alignment Phase which fine-tunes LLMs on a meticulously curated parallel dataset to make reliable in-scope edits while preserving out-of-scope information and linguistic proficiency; and (ii) the Inference Phase which employs a retrieval-based mechanism for real-time and mass knowledge editing. By comparing our approach with seven advanced baselines across four popular knowledge editing benchmarks and two LLM architectures we demonstrate LTEs superiority in knowledge editing performance robustness in both batch and sequential editing minimal interference on general tasks and rapid editing speeds. The data and code are available at https://github.com/YJiangcm/LTE."
