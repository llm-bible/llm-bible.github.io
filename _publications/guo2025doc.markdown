---
layout: publication
title: 'Doc-guided Sent2sent++: A Sent2sent++ Agent With Doc-guided Memory For Document-level Machine Translation'
authors: Jiaxin Guo, Yuanchang Luo, Daimeng Wei, Ling Zhang, Zongyao Li, Hengchao Shang, Zhiqiang Rao, Shaojun Li, Jinlong Yang, Zhanglin Wu, Hao Yang
conference: "Arxiv"
year: 2025
bibkey: guo2025doc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.08523"}
tags: ['Agentic', 'RAG', 'Applications', 'Reinforcement Learning']
---
The field of artificial intelligence has witnessed significant advancements
in natural language processing, largely attributed to the capabilities of Large
Language Models (LLMs). These models form the backbone of Agents designed to
address long-context dependencies, particularly in Document-level Machine
Translation (DocMT). DocMT presents unique challenges, with quality,
consistency, and fluency being the key metrics for evaluation. Existing
approaches, such as Doc2Doc and Doc2Sent, either omit sentences or compromise
fluency. This paper introduces Doc-Guided Sent2Sent++, an Agent that employs an
incremental sentence-level forced decoding strategy \textbf\{to ensure every
sentence is translated while enhancing the fluency of adjacent sentences.\} Our
Agent leverages a Doc-Guided Memory, focusing solely on the summary and its
translation, which we find to be an efficient approach to maintaining
consistency. Through extensive testing across multiple languages and domains,
we demonstrate that Sent2Sent++ outperforms other methods in terms of quality,
consistency, and fluency. The results indicate that, our approach has achieved
significant improvements in metrics such as s-COMET, d-COMET, LTCR-\\(1_f\\), and
document-level perplexity (d-ppl). The contributions of this paper include a
detailed analysis of current DocMT research, the introduction of the
Sent2Sent++ decoding method, the Doc-Guided Memory mechanism, and validation of
its effectiveness across languages and domains.
