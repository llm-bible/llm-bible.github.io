---
layout: publication
title: 'Unveiling The Landscape Of LLM Deployment In The Wild: An Empirical Study'
authors: Xinyi Hou, Jiahao Han, Yanjie Zhao, Haoyu Wang
conference: "Arxiv"
year: 2025
bibkey: hou2025unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.02502"}
tags: ['Security', 'Applications', 'Tools', 'Reinforcement Learning']
---
Background: Large language models (LLMs) are increasingly deployed via
open-source and commercial frameworks, enabling individuals and organizations
to self-host advanced AI capabilities. However, insecure defaults and
misconfigurations often expose LLM services to the public Internet, posing
significant security and system engineering risks. Aims: This study aims to
unveil the current landscape of public-facing LLM deployments in the wild
through a large-scale empirical study, focusing on service prevalence, exposure
characteristics, systemic vulnerabilities, and associated risks. Method: We
conducted an Internet-wide measurement to identify public-facing LLM
deployments across 15 frameworks, discovering 320,102 services. We extracted
158 unique API endpoints, grouped into 12 functional categories based on
capabilities and security risks. We further analyzed configurations,
authentication practices, and geographic distributions, revealing deployment
trends and systemic issues in real-world LLM system engineering. Results: Our
study shows that public LLM deployments are rapidly growing but often insecure.
Among all endpoints, we observe widespread use of insecure protocols, poor TLS
configurations, and unauthenticated access to critical operations. Security
risks, including model disclosure, system leakage, and unauthorized access, are
pervasive, highlighting the need for secure-by-default frameworks and stronger
deployment practices. Conclusions: Public-facing LLM deployments suffer from
widespread security and configuration flaws, exposing services to misuse, model
theft, resource hijacking, and remote exploitation. Strengthening default
security, deployment practices, and operational standards is critical for the
growing self-hosted LLM ecosystem.
