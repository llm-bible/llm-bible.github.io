---
layout: publication
title: 'Generative AI To Generate Test Data Generators'
authors: Benoit Baudry, Khashayar Etemadi, Sen Fang, Yogya Gamage, Yi Liu, Yuxin Liu, Martin Monperrus, Javier Ron, André Silva, Deepika Tiwari
conference: "IEEE Software 2024"
year: 2024
bibkey: baudry2024generative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.17626'}
tags: ['Prompting']
---
Generating fake data is an essential dimension of modern software testing, as
demonstrated by the number and significance of data faking libraries. Yet,
developers of faking libraries cannot keep up with the wide range of data to be
generated for different natural languages and domains. In this paper, we assess
the ability of generative AI for generating test data in different domains. We
design three types of prompts for Large Language Models (LLMs), which perform
test data generation tasks at different levels of integrability: 1) raw test
data generation, 2) synthesizing programs in a specific language that generate
useful test data, and 3) producing programs that use state-of-the-art faker
libraries. We evaluate our approach by prompting LLMs to generate test data for
11 domains. The results show that LLMs can successfully generate realistic test
data generators in a wide range of domains at all three levels of
integrability.
