---
layout: publication
title: 'CSRT: Evaluation And Analysis Of Llms Using Code-switching Red-teaming Dataset'
authors: Yoo Haneul, Yang Yongjin, Lee Hwaran
conference: "Arxiv"
year: 2024
bibkey: yoo2024evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15481"}
tags: ['Efficiency And Optimization', 'Language Modeling', 'Large Scale Training', 'Model Architecture', 'Prompting', 'Responsible AI', 'Scaling Laws', 'Security']
---
Recent studies in large language models (LLMs) shed light on their multilingual ability and safety, beyond conventional tasks in language modeling. Still, current benchmarks reveal their inability to comprehensively evaluate them and are excessively dependent on manual annotations. In this paper, we introduce code-switching red-teaming (CSRT), a simple yet effective red-teaming technique that simultaneously tests multilingual understanding and safety of LLMs. We release the CSRT dataset, which comprises 315 code-switching queries combining up to 10 languages and eliciting a wide range of undesirable behaviors. Through extensive experiments with ten state-of-the-art LLMs, we demonstrate that CSRT significantly outperforms existing multilingual red-teaming techniques, achieving 46.7&#37; more attacks than existing methods in English. We analyze the harmful responses toward the CSRT dataset concerning various aspects under ablation studies with 16K samples, including but not limited to scaling laws, unsafe behavior categories, and input conditions for optimal data generation. Additionally, we validate the extensibility of CSRT, by generating code-switching attack prompts with monolingual data.
