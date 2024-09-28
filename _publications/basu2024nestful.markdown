---
layout: publication
title: NESTFUL A Benchmark for Evaluating LLMs on Nested Sequences of API Calls
authors: Basu Kinjal, Abdelaziz Ibrahim, Bradford Kelsey, Crouse Maxwell, Kate Kiran, Kumaravel Sadhana, Goyal Saurabh, Munawar Asim, Rizk Yara, Wang Xin, Lastras Luis, Kapanipathi Pavan
conference: "Arxiv"
year: 2024
bibkey: basu2024nestful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03797"}
tags: ['Arxiv', 'Applications', 'LLM', 'A']
---
Autonomous agent applications powered by large language models (LLMs) have recently risen to prominence as effective tools for addressing complex real-world tasks. At their core agentic workflows rely on LLMs to plan and execute the use of tools and external Application Programming Interfaces (APIs) in sequence to arrive at the answer to a users request. Various benchmarks and leaderboards have emerged to evaluate an LLMs capabilities for tool and API use; however most of these evaluations only track single or multiple isolated API calling capabilities. In this paper we present NESTFUL a benchmark to evaluate LLMs on nested sequences of API calls i.e. sequences where the output of one API call is passed as input to a subsequent call. NESTFUL has a total of 300 human annotated samples divided into two types - executable and non-executable. The executable samples are curated manually by crawling Rapid-APIs whereas the non-executable samples are hand picked by human annotators from data synthetically generated using an LLM. We evaluate state-of-the-art LLMs with function calling abilities on NESTFUL. Our results show that most models do not perform well on nested APIs in NESTFUL as compared to their performance on the simpler problem settings available in existing benchmarks.
