---
layout: publication
title: 'Dynamic Intelligence Assessment: Benchmarking Llms On The Road To AGI With A Focus On Model Confidence'
authors: Norbert Tihanyi, Tamas Bisztray, Richard A. Dubniczky, Rebeka Toth, Bertalan Borsos, Bilel Cherif, Mohamed Amine Ferrag, Lajos Muzsai, Ridhi Jain, Ryan Marinelli, Lucas C. Cordeiro, Merouane Debbah, Vasileios Mavroeidis, Audun Josang
conference: "Arxiv"
year: 2024
bibkey: tihanyi2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15490"}
  - {name: "Code", url: "https://github.com/DIA-Bench"}
tags: ['Security', 'Model Architecture', 'Tools', 'GPT', 'Has Code']
---
As machine intelligence evolves, the need to test and compare the
problem-solving abilities of different AI models grows. However, current
benchmarks are often simplistic, allowing models to perform uniformly well and
making it difficult to distinguish their capabilities. Additionally, benchmarks
typically rely on static question-answer pairs that the models might memorize
or guess. To address these limitations, we introduce Dynamic Intelligence
Assessment (DIA), a novel methodology for testing AI models using dynamic
question templates and improved metrics across multiple disciplines such as
mathematics, cryptography, cybersecurity, and computer science. The
accompanying dataset, DIA-Bench, contains a diverse collection of challenge
templates with mutable parameters presented in various formats, including text,
PDFs, compiled binaries, visual puzzles, and CTF-style cybersecurity
challenges. Our framework introduces four new metrics to assess a model's
reliability and confidence across multiple attempts. These metrics revealed
that even simple questions are frequently answered incorrectly when posed in
varying forms, highlighting significant gaps in models' reliability. Notably,
API models like GPT-4o often overestimated their mathematical capabilities,
while ChatGPT-4o demonstrated better performance due to effective tool usage.
In self-assessment, OpenAI's o1-mini proved to have the best judgement on what
tasks it should attempt to solve. We evaluated 25 state-of-the-art LLMs using
DIA-Bench, showing that current models struggle with complex tasks and often
display unexpectedly low confidence, even with simpler questions. The DIA
framework sets a new standard for assessing not only problem-solving but also a
model's adaptive intelligence and ability to assess its limitations. The
dataset is publicly available on the project's page:
https://github.com/DIA-Bench.
