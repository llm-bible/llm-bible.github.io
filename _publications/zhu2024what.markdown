---
layout: publication
title: 'What You See Is Not Always What You Get: An Empirical Study Of Code Comprehension By Large Language Models'
authors: Bangshuo Zhu, Jiawen Wen, Huaming Chen
conference: "Arxiv"
year: 2024
bibkey: zhu2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08098"}
tags: ['Prompting', 'Security', 'Applications']
---
Recent studies have demonstrated outstanding capabilities of large language
models (LLMs) in software engineering tasks, including code generation and
comprehension. While LLMs have shown significant potential in assisting with
coding, it is perceived that LLMs are vulnerable to adversarial attacks. In
this paper, we investigate the vulnerability of LLMs to imperceptible attacks,
where hidden character manipulation in source code misleads LLMs' behaviour
while remaining undetectable to human reviewers. We devise these attacks into
four distinct categories and analyse their impacts on code analysis and
comprehension tasks. These four types of imperceptible coding character attacks
include coding reordering, invisible coding characters, code deletions, and
code homoglyphs. To comprehensively benchmark the robustness of current LLMs
solutions against the attacks, we present a systematic experimental evaluation
on multiple state-of-the-art LLMs. Our experimental design introduces two key
performance metrics, namely model confidence using log probabilities of
response, and the response correctness. A set of controlled experiments are
conducted using a large-scale perturbed and unperturbed code snippets as the
primary prompt input. Our findings confirm the susceptibility of LLMs to
imperceptible coding character attacks, while different LLMs present different
negative correlations between perturbation magnitude and performance. These
results highlight the urgent need for robust LLMs capable of manoeuvring
behaviours under imperceptible adversarial conditions. We anticipate this work
provides valuable insights for enhancing the security and trustworthiness of
LLMs in software engineering applications.
