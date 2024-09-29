---
layout: publication
title: THREAD Thinking Deeper With Recursive Spawning
authors: Schroeder Philip, Morgan Nathaniel, Luo Hongyin, Glass James
conference: "Arxiv"
year: 2024
bibkey: schroeder2024thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17402"}
tags: ['Agentic', 'Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have shown impressive capabilities across diverse settings but still struggle as the length and complexity of the context increases. To address this challenge we propose Thinking Recursively and Dynamically (ThReaD). THREAD frames model generation as a thread of execution that based on the context can run to completion or dynamically spawn new threads. By spawning threads can offload work (e.g. thinking retrieving information) to child threads which only return tokens needed for the parent thread to do its work. In effect this enables the model to adapt as needed the amount of intermediate work used to produce tokens. We apply THREAD in the settings of LLM task solving and question answering where the dynamic threading allows the model to recursively decompose the given task or question into progressively simpler sub45;problems that can be solved by separate child threads. We test THREAD implemented using a few45;shot learning approach on diverse benchmarks for agent tasks and data45;grounded question answering. THREAD achieves state45;of45;the45;art performance with GPT45;4 and GPT45;3.5 on these benchmarks including ALFWorld TextCraft and WebShop along with two new benchmarks DataCommons QA and MIMIC45;III ICU QA. In addition THREAD outperforms existing frameworks by 1037; to 5037; absolute points with smaller models including Llama45;345;8b and CodeLlama45;7b.
