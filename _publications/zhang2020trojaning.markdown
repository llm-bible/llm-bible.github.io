---
layout: publication
title: Trojaning Language Models For Fun And Profit
authors: Zhang Xinyang, Zhang Zheng, Ji Shouling, Wang Ting
conference: "Arxiv"
year: 2020
bibkey: zhang2020trojaning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2008.00312"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Security', 'Tools']
---
Recent years have witnessed the emergence of a new paradigm of building natural language processing (NLP) systems general45;purpose pre45;trained language models (LMs) are composed with simple downstream models and fine45;tuned for a variety of NLP tasks. This paradigm shift significantly simplifies the system development cycles. However as many LMs are provided by untrusted third parties their lack of standardization or regulation entails profound security implications which are largely unexplored. To bridge this gap this work studies the security threats posed by malicious LMs to NLP systems. Specifically we present TROJAN45;LM a new class of trojaning attacks in which maliciously crafted LMs trigger host NLP systems to malfunction in a highly predictable manner. By empirically studying three state45;of45;the45;art LMs (BERT GPT45;2 XLNet) in a range of security45;critical NLP tasks (toxic comment detection question answering text completion) as well as user studies on crowdsourcing platforms we demonstrate that TROJAN45;LM possesses the following properties (i) flexibility 45; the adversary is able to flexibly dene logical combinations (e.g. and or xor) of arbitrary words as triggers (ii) efficacy 45; the host systems misbehave as desired by the adversary with high probability when trigger45;embedded inputs are present (iii) specificity 45; the trojan LMs function indistinguishably from their benign counterparts on clean inputs and (iv) fluency 45; the trigger45;embedded inputs appear as fluent natural language and highly relevant to their surrounding contexts. We provide analytical justification for the practicality of TROJAN45;LM and further discuss potential countermeasures and their challenges which lead to several promising research directions.
