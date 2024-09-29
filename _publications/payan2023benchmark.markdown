---
layout: publication
title: Instructexcel A Benchmark For Natural Language Instruction In Excel
authors: Payan Justin, Mishra Swaroop, Singh Mukul, Negreanu Carina, Poelitz Christian, Baral Chitta, Roy Subhro, Chakravarthy Rasika, Van Durme Benjamin, Nouri Elnaz
conference: "Arxiv"
year: 2023
bibkey: payan2023benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14495"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools']
---
With the evolution of Large Language Models (LLMs) we can solve increasingly more complex NLP tasks across various domains including spreadsheets. This work investigates whether LLMs can generate code (Excel OfficeScripts a TypeScript API for executing many tasks in Excel) that solves Excel specific tasks provided via natural language user instructions. To do so we introduce a new large45;scale benchmark InstructExcel created by leveraging the Automate feature in Excel to automatically generate OfficeScripts from users actions. Our benchmark includes over 10k samples covering 170+ Excel operations across 2000 publicly available Excel spreadsheets. Experiments across various zero45;shot and few45;shot settings show that InstructExcel is a hard benchmark for state of the art models like GPT45;4. We observe that (1) using GPT45;4 over GPT45;3.5 (2) providing more in45;context examples and (3) dynamic prompting can help improve performance on this benchmark.
