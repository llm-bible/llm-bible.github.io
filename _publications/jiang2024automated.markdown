---
layout: publication
title: 'Automated Progressive Red Teaming'
authors: Bojian Jiang, Yi Jing, Tianhao Shen, Tong Wu, Qing Yang, Deyi Xiong
conference: "Arxiv"
year: 2024
bibkey: jiang2024automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03876"}
tags: ['Responsible AI', 'Tools', 'GPT', 'RAG', 'Model Architecture', 'Security', 'Prompting']
---
Ensuring the safety of large language models (LLMs) is paramount, yet
identifying potential vulnerabilities is challenging. While manual red teaming
is effective, it is time-consuming, costly and lacks scalability. Automated red
teaming (ART) offers a more cost-effective alternative, automatically
generating adversarial prompts to expose LLM vulnerabilities. However, in
current ART efforts, a robust framework is absent, which explicitly frames red
teaming as an effectively learnable task. To address this gap, we propose
Automated Progressive Red Teaming (APRT) as an effectively learnable framework.
APRT leverages three core modules: an Intention Expanding LLM that generates
diverse initial attack samples, an Intention Hiding LLM that crafts deceptive
prompts, and an Evil Maker to manage prompt diversity and filter ineffective
samples. The three modules collectively and progressively explore and exploit
LLM vulnerabilities through multi-round interactions. In addition to the
framework, we further propose a novel indicator, Attack Effectiveness Rate
(AER) to mitigate the limitations of existing evaluation metrics. By measuring
the likelihood of eliciting unsafe but seemingly helpful responses, AER aligns
closely with human evaluations. Extensive experiments with both automatic and
human evaluations, demonstrate the effectiveness of ARPT across both open- and
closed-source LLMs. Specifically, APRT effectively elicits 54% unsafe yet
useful responses from Meta's Llama-3-8B-Instruct, 50% from GPT-4o (API access),
and 39% from Claude-3.5 (API access), showcasing its robust attack capability
and transferability across LLMs (especially from open-source LLMs to
closed-source LLMs).
