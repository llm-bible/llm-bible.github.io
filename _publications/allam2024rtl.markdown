---
layout: publication
title: 'Rtl-repo: A Benchmark For Evaluating Llms On Large-scale RTL Design Projects'
authors: Ahmed Allam, Mohamed Shalan
conference: "Arxiv"
year: 2024
bibkey: allam2024rtl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17378"}
tags: ['Model Architecture', 'GPT', 'Applications', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated potential in assisting with
Register Transfer Level (RTL) design tasks. Nevertheless, there remains to be a
significant gap in benchmarks that accurately reflect the complexity of
real-world RTL projects. To address this, this paper presents RTL-Repo, a
benchmark specifically designed to evaluate LLMs on large-scale RTL design
projects. RTL-Repo includes a comprehensive dataset of more than 4000 Verilog
code samples extracted from public GitHub repositories, with each sample
providing the full context of the corresponding repository. We evaluate several
state-of-the-art models on the RTL-Repo benchmark, including GPT-4, GPT-3.5,
Starcoder2, alongside Verilog-specific models like VeriGen and RTLCoder, and
compare their performance in generating Verilog code for complex projects. The
RTL-Repo benchmark provides a valuable resource for the hardware design
community to assess and compare LLMs' performance in real-world RTL design
scenarios and train LLMs specifically for Verilog code generation in complex,
multi-file RTL projects. RTL-Repo is open-source and publicly available on
Github.
