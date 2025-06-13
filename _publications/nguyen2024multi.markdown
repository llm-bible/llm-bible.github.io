---
layout: publication
title: 'Multi-objective Linguistic Control Of Large Language Models'
authors: Dang Nguyen, Jiuhai Chen, Tianyi Zhou
conference: "Arxiv"
year: 2024
bibkey: nguyen2024multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.16229'}
tags: ['GPT', 'Model Architecture']
---
Large language models (LLMs), despite their breakthroughs on many challenging
benchmark tasks, lean to generate verbose responses and lack the
controllability of output complexity, which is usually preferred by human users
in practice. In this paper, we study how to precisely control multiple
linguistic complexities of LLM output by finetuning using off-the-shelf data.
To this end, we propose multi-control tuning (MCTune), which includes multiple
linguistic complexity values of ground-truth responses as controls in the input
for instruction tuning. We finetune LLaMA2-7B on Alpaca-GPT4 and WizardLM
datasets. Evaluations on widely used benchmarks demonstrate that our method
does not only improve LLMs' multi-complexity controllability substantially but
also retains or even enhances the quality of the responses as a side benefit.
