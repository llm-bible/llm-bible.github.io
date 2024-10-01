---
layout: publication
title: 'Rapidly Developing High-quality Instruction Data And Evaluation Benchmark For Large Language Models With Minimal Human Effort: A Case Study On Japanese'
authors: Sun Yikun, Wan Zhen, Ueda Nobuhiro, Yahata Sakiko, Cheng Fei, Chu Chenhui, Kurohashi Sadao
conference: "Arxiv"
year: 2024
bibkey: sun2024rapidly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03690"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
"The creation of instruction data and evaluation benchmarks for serving Large language models often involves enormous human annotation. This issue becomes particularly pronounced when rapidly developing such resources for a non-English language like Japanese. Instead of following the popular practice of directly translating existing English resources into Japanese (e.g., Japanese-Alpaca), we propose an efficient self-instruct method based on GPT-4. We first translate a small amount of English instructions into Japanese and post-edit them to obtain native-level quality. GPT-4 then utilizes them as demonstrations to automatically generate Japanese instruction data. We also construct an evaluation benchmark containing 80 questions across 8 categories, using GPT-4 to automatically assess the response quality of LLMs without human references. The empirical results suggest that the models fine-tuned on our GPT-4 self-instruct data significantly outperformed the Japanese-Alpaca across all three base pre-trained models. Our GPT-4 self-instruct data allowed the LLaMA 13B model to defeat GPT-3.5 (Davinci-003) with a 54.37\&#37; win-rate. The human evaluation exhibits the consistency between GPT-4's assessments and human preference. Our high-quality instruction data and evaluation benchmark have been released here."
