---
layout: publication
title: 'Text2scenario: Text-driven Scenario Generation For Autonomous Driving Test'
authors: Xuan Cai, Xuesong Bai, Zhiyong Cui, Danmu Xie, Daocheng Fu, Haiyang Yu, Yilong Ren
conference: "Arxiv"
year: 2025
bibkey: cai2025text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.02911'}
  - {name: "Code", url: 'https://caixxuan.github.io/Text2Scenario.GitHub.io'}
tags: ['RAG', 'Has Code', 'Prompting', 'Tools']
---
Autonomous driving (AD) testing constitutes a critical methodology for
assessing performance benchmarks prior to product deployment. The creation of
segmented scenarios within a simulated environment is acknowledged as a robust
and effective strategy; however, the process of tailoring these scenarios often
necessitates laborious and time-consuming manual efforts, thereby hindering the
development and implementation of AD technologies. In response to this
challenge, we introduce Text2Scenario, a framework that leverages a Large
Language Model (LLM) to autonomously generate simulation test scenarios that
closely align with user specifications, derived from their natural language
inputs. Specifically, an LLM, equipped with a meticulously engineered input
prompt scheme functions as a text parser for test scenario descriptions,
extracting from a hierarchically organized scenario repository the components
that most accurately reflect the user's preferences. Subsequently, by
exploiting the precedence of scenario components, the process involves
sequentially matching and linking scenario representations within a Domain
Specific Language corpus, ultimately fabricating executable test scenarios. The
experimental results demonstrate that such prompt engineering can meticulously
extract the nuanced details of scenario elements embedded within various
descriptive formats, with the majority of generated scenarios aligning closely
with the user's initial expectations, allowing for the efficient and precise
evaluation of diverse AD stacks void of the labor-intensive need for manual
scenario configuration. Project page:
https://caixxuan.github.io/Text2Scenario.GitHub.io.
