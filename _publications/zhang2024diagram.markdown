---
layout: publication
title: 'Diagram-driven Course Questions Generation'
authors: Xinyu Zhang, Lingling Zhang, Yanrui Wu, Muye Huang, Wenjun Wu, Bo Li, Shaowei Wang, Basura Fernando, Jun Liu
conference: "Arxiv"
year: 2024
bibkey: zhang2024diagram
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17771"}
tags: ['RAG', 'Tools', 'Multimodal Models']
---
Visual Question Generation (VQG) research focuses predominantly on natural images while neglecting the diagram, which is a critical component in educational materials. To meet the needs of pedagogical assessment, we propose the Diagram-Driven Course Questions Generation (DDCQG) task and construct DiagramQG, a comprehensive dataset with 15,720 diagrams and 25,798 questions across 37 subjects and 371 courses. Our approach employs course and input text constraints to generate course-relevant questions about specific diagram elements. We reveal three challenges of DDCQG: domain-specific knowledge requirements across courses, long-tail distribution in course coverage, and high information density in diagrams. To address these, we propose the Hierarchical Knowledge Integration framework (HKI-DDCQG), which utilizes trainable CLIP for identifying relevant diagram patches, leverages frozen vision-language models for knowledge extraction, and generates questions with trainable T5. Experiments demonstrate that HKI-DDCQG outperforms existing models on DiagramQG while maintaining strong generalizability across natural image datasets, establishing a strong baseline for DDCQG.
