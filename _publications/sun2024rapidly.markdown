---
layout: publication
title: Rapidly Developing High45;quality Instruction Data And Evaluation Benchmark For Large Language Models With Minimal Human Effort A Case Study On Japanese
authors: Sun Yikun, Wan Zhen, Ueda Nobuhiro, Yahata Sakiko, Cheng Fei, Chu Chenhui, Kurohashi Sadao
conference: "Arxiv"
year: 2024
bibkey: sun2024rapidly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03690"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
The creation of instruction data and evaluation benchmarks for serving Large language models often involves enormous human annotation. This issue becomes particularly pronounced when rapidly developing such resources for a non45;English language like Japanese. Instead of following the popular practice of directly translating existing English resources into Japanese (e.g. Japanese45;Alpaca) we propose an efficient self45;instruct method based on GPT45;4. We first translate a small amount of English instructions into Japanese and post45;edit them to obtain native45;level quality. GPT45;4 then utilizes them as demonstrations to automatically generate Japanese instruction data. We also construct an evaluation benchmark containing 80 questions across 8 categories using GPT45;4 to automatically assess the response quality of LLMs without human references. The empirical results suggest that the models fine45;tuned on our GPT45;4 self45;instruct data significantly outperformed the Japanese45;Alpaca across all three base pre45;trained models. Our GPT45;4 self45;instruct data allowed the LLaMA 13B model to defeat GPT45;3.5 (Davinci45;003) with a 54.3737; win45;rate. The human evaluation exhibits the consistency between GPT45;4s assessments and human preference. Our high45;quality instruction data and evaluation benchmark have been released here.
