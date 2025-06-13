---
layout: publication
title: 'Biasjailbreak:analyzing Ethical Biases And Jailbreak Vulnerabilities In Large Language Models'
authors: Isack Lee, Haebin Seong
conference: "Arxiv"
year: 2024
bibkey: lee2024ethical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13334"}
tags: ['Responsible AI', 'Tools', 'GPT', 'Ethics and Bias', 'Model Architecture', 'Security', 'Prompting']
---
Although large language models (LLMs) demonstrate impressive proficiency in
various tasks, they present potential safety risks, such as `jailbreaks', where
malicious inputs can coerce LLMs into generating harmful content bypassing
safety alignments. In this paper, we delve into the ethical biases in LLMs and
examine how those biases could be exploited for jailbreaks. Notably, these
biases result in a jailbreaking success rate in GPT-4o models that differs by
20% between non-binary and cisgender keywords and by 16% between white and
black keywords, even when the other parts of the prompts are identical. We
introduce the concept of BiasJailbreak, highlighting the inherent risks posed
by these safety-induced biases. BiasJailbreak generates biased keywords
automatically by asking the target LLM itself, and utilizes the keywords to
generate harmful output. Additionally, we propose an efficient defense method
BiasDefense, which prevents jailbreak attempts by injecting defense prompts
prior to generation. BiasDefense stands as an appealing alternative to Guard
Models, such as Llama-Guard, that require additional inference cost after text
generation. Our findings emphasize that ethical biases in LLMs can actually
lead to generating unsafe output, and suggest a method to make the LLMs more
secure and unbiased. To enable further research and improvements, we
open-source our code and artifacts of BiasJailbreak, providing the community
with tools to better understand and mitigate safety-induced biases in LLMs.
