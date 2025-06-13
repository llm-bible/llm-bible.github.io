---
layout: publication
title: 'QUILL: Quotation Generation Enhancement Of Large Language Models'
authors: Jin Xiao, Bowei Zhang, Qianyu He, Jiaqing Liang, Feng Wei, Jinglei Chen, Zujie Liang, Deqing Yang, Yanghua Xiao
conference: "Arxiv"
year: 2024
bibkey: xiao2024quotation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.03675"}
  - {name: "Code", url: "https://github.com/GraceXiaoo/QUILL"}
tags: ['Has Code', 'Uncategorized']
---
While Large language models (LLMs) have become excellent writing assistants,
they still struggle with quotation generation. This is because they either
hallucinate when providing factual quotations or fail to provide quotes that
exceed human expectations. To bridge the gap, we systematically study how to
evaluate and improve LLMs' performance in quotation generation tasks. We first
establish a holistic and automatic evaluation system for quotation generation
task, which consists of five criteria each with corresponding automatic metric.
To improve the LLMs' quotation generation abilities, we construct a bilingual
knowledge base that is broad in scope and rich in dimensions, containing up to
32,022 quotes. Moreover, guided by our critiria, we further design a
quotation-specific metric to rerank the retrieved quotations from the knowledge
base. Extensive experiments show that our metrics strongly correlate with human
preferences. Existing LLMs struggle to generate desired quotes, but our
quotation knowledge base and reranking metric help narrow this gap. Our dataset
and code are publicly available at https://github.com/GraceXiaoo/QUILL.
