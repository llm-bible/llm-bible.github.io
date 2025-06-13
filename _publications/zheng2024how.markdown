---
layout: publication
title: 'Knowshiftqa: How Robust Are RAG Systems When Textbook Knowledge Shifts In K-12 Education?'
authors: Tianshi Zheng, Weihan Li, Jiaxin Bai, Weiqi Wang, Yangqiu Song
conference: "Arxiv"
year: 2024
bibkey: zheng2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08985"}
tags: ['Security', 'RAG', 'Applications', 'Tools']
---
Retrieval-Augmented Generation (RAG) systems show remarkable potential as question answering tools in the K-12 Education domain, where knowledge is typically queried within the restricted scope of authoritative textbooks. However, discrepancies between these textbooks and the parametric knowledge inherent in Large Language Models (LLMs) can undermine the effectiveness of RAG systems. To systematically investigate RAG system robustness against such knowledge discrepancies, we introduce KnowShiftQA. This novel question answering dataset simulates these discrepancies by applying deliberate hypothetical knowledge updates to both answers and source documents, reflecting how textbook knowledge can shift. KnowShiftQA comprises 3,005 questions across five subjects, designed with a comprehensive question typology focusing on context utilization and knowledge integration. Our extensive experiments on retrieval and question answering performance reveal that most RAG systems suffer a substantial performance drop when faced with these knowledge discrepancies. Furthermore, questions requiring the integration of contextual (textbook) knowledge with parametric (LLM) knowledge pose a significant challenge to current LLMs.
