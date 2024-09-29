---
layout: publication
title: Exploring Parameter45;efficient Fine45;tuning Techniques For Code Generation With Large Language Models
authors: Weyssow Martin, Zhou Xin, Kim Kisub, Lo David, Sahraoui Houari
conference: "Arxiv"
year: 2023
bibkey: weyssow2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.10462"}
  - {name: "Code", url: "https://github.com/martin&#45;wey/peft&#45;llm&#45;code/"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Prompting', 'Quantization', 'Reinforcement Learning', 'Survey Paper']
---
Large Language Models (LLMs) demonstrate impressive capabilities to generate accurate code snippets given natural language intents in zero45;shot i.e. without the need for specific fine45;tuning. While prior studies have highlighted the advantages of fine45;tuning LLMs this process incurs high computational costs making it impractical in resource45;scarce environments particularly for models with billions of parameters. To address these challenges previous research explored In45;Context Learning (ICL) as a strategy to guide the LLM generative process with task45;specific prompt examples. However ICL introduces inconveniences such as the need for designing contextually relevant prompts and the absence of learning task45;specific parameters thereby limiting downstream task performance. In this context we foresee Parameter45;Efficient Fine45;Tuning (PEFT) techniques as a promising approach to efficiently specialize LLMs to task45;specific data while maintaining reasonable resource consumption. In this paper we deliver a comprehensive study of PEFT techniques for LLMs under the automated code generation scenario. Our comprehensive investigation of PEFT techniques for LLMs reveals their superiority and potential over ICL across a diverse set of LLMs. Additionally we demonstrate the extended capabilities of PEFT showcasing its ability to learn from two distinct datasets jointly without compromising performance. Furthermore our study highlights the potential for tuning larger LLMs and significant reductions in memory usage by combining PEFT with quantization. Therefore this study opens opportunities for broader applications of PEFT in software engineering scenarios. Our code is available at https://github.com/martin&#45;wey/peft&#45;llm&#45;code/.
