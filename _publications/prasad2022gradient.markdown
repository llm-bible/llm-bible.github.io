---
layout: publication
title: Grips Gradient45;free Edit45;based Instruction Search For Prompting Large Language Models
authors: Prasad Archiki, Hase Peter, Zhou Xiang, Bansal Mohit
conference: "Arxiv"
year: 2022
bibkey: prasad2022gradient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.07281"}
  - {name: "Code", url: "https://github.com/archiki/GrIPS"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools']
---
Providing natural language instructions in prompts is a useful new paradigm for improving task performance of large language models in a zero45;shot setting. Recent work has aimed to improve such prompts via manual rewriting or gradient45;based tuning. However manual rewriting is time45;consuming and requires subjective interpretation while gradient45;based tuning can be extremely computationally demanding for large models and may not be feasible for API45;based models. In this work we introduce Gradient45;free Instructional Prompt Search (GrIPS) a gradient45;free edit45;based search approach for improving task instructions for large language models. GrIPS takes in instructions designed for humans and automatically returns an improved edited prompt while allowing for API45;based tuning. With InstructGPT models GrIPS improves the average task performance by up to 4.30 percentage points on eight classification tasks from the Natural Instructions dataset (with similar improvements for OPT BLOOM and FLAN45;T5). We see improvements for both instruction45;only prompts and instruction + k45;shot examples prompts. Notably GrIPS outperforms manual rewriting and purely example45;based prompts while controlling for the available compute and data budget. Further performance of GrIPS is comparable to select gradient45;based tuning approaches. Qualitatively we show our edits can simplify instructions and at times make them incoherent but nonetheless improve accuracy. Our code is available at https://github.com/archiki/GrIPS
