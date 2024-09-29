---
layout: publication
title: Active Prompting With Chain45;of45;thought For Large Language Models
authors: Shizhe Diao, Pengcheng Wang, Yong Lin, Rui Pan, Xiang Liu, Tong Zhang
conference: "Arxiv"
year: 2023
bibkey: diao2023active
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2302.12246v5"}
  - {name: "Code", url: "https://github.com/shizhediao/active&#45;prompt"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting']
---
The increasing scale of large language models (LLMs) brings emergent abilities to various complex tasks requiring reasoning such as arithmetic and commonsense reasoning. It is known that the effective design of task45;specific prompts is critical for LLMs ability to produce high45;quality answers. In particular an effective approach for complex question45;and45;answer tasks is example45;based prompting with chain45;of45;thought (CoT) reasoning which significantly improves the performance of LLMs. However current CoT methods rely on a fixed set of human45;annotated exemplars which are not necessarily the most effective examples for different tasks. This paper proposes a new method Active45;Prompt to adapt LLMs to different tasks with task45;specific example prompts (annotated with human45;designed CoT reasoning). For this purpose we propose a solution to the key problem of determining which questions are the most important and helpful ones to annotate from a pool of task45;specific queries. By borrowing ideas from the related problem of uncertainty45;based active learning we introduce several metrics to characterize the uncertainty so as to select the most uncertain questions for annotation. Experimental results demonstrate the superiority of our proposed method achieving state45;of45;the45;art on eight complex reasoning tasks. Further analyses of different uncertainty metrics pool sizes zero45;shot learning and accuracy45;uncertainty relationship demonstrate the effectiveness of our method. Our code will be available at https://github.com/shizhediao/active&#45;prompt.
