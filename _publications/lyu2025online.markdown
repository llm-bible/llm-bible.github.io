---
layout: publication
title: 'Docia: An Online Document-level Context Incorporation Agent For Speech Translation'
authors: Xinglin Lyu, Wei Tang, Yuang Li, Xiaofeng Zhao, Ming Zhu, Junhui Li, Yunfei Lu, Min Zhang, Daimeng Wei, Hao Yang, Min Zhang
conference: "Arxiv"
year: 2025
bibkey: lyu2025online
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05122"}
tags: ['Agentic', 'Tools', 'RAG', 'Applications', 'INTERSPEECH']
---
Document-level context is crucial for handling discourse challenges in
text-to-text document-level machine translation (MT). Despite the increased
discourse challenges introduced by noise from automatic speech recognition
(ASR), the integration of document-level context in speech translation (ST)
remains insufficiently explored. In this paper, we develop DoCIA, an online
framework that enhances ST performance by incorporating document-level context.
DoCIA decomposes the ST pipeline into four stages. Document-level context is
integrated into the ASR refinement, MT, and MT refinement stages through
auxiliary LLM (large language model)-based modules. Furthermore, DoCIA
leverages document-level information in a multi-level manner while minimizing
computational overhead. Additionally, a simple yet effective determination
mechanism is introduced to prevent hallucinations from excessive refinement,
ensuring the reliability of the final results. Experimental results show that
DoCIA significantly outperforms traditional ST baselines in both sentence and
discourse metrics across four LLMs, demonstrating its effectiveness in
improving ST performance.
