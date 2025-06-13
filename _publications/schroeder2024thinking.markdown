---
layout: publication
title: 'THREAD: Thinking Deeper With Recursive Spawning'
authors: Philip Schroeder, Nathaniel Morgan, Hongyin Luo, James Glass
conference: "Arxiv"
year: 2024
bibkey: schroeder2024thinking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.17402'}
tags: ['Agentic', 'Few-Shot', 'GPT', 'Tools', 'Model Architecture', 'Applications', 'Reinforcement Learning']
---
Large language models (LLMs) have shown impressive capabilities across
diverse settings, but still struggle as the length and complexity of the
context increases. To address this challenge, we propose Thinking Recursively
and Dynamically (ThReaD). THREAD frames model generation as a thread of
execution that, based on the context, can run to completion or dynamically
spawn new threads. By spawning, threads can offload work (e.g., thinking,
retrieving information) to child threads, which only return tokens needed for
the parent thread to do its work. In effect, this enables the model to adapt,
as needed, the amount of intermediate work used to produce tokens. We apply
THREAD in the settings of LLM task solving and question answering, where the
dynamic threading allows the model to recursively decompose the given task or
question into progressively simpler sub-problems that can be solved by separate
child threads. We test THREAD, implemented using a few-shot learning approach,
on diverse benchmarks for agent tasks and data-grounded question answering.
THREAD achieves state-of-the-art performance with GPT-4 and GPT-3.5 on these
benchmarks, including ALFWorld, TextCraft, and WebShop, along with two new
benchmarks, DataCommons QA and MIMIC-III ICU QA. In addition, THREAD
outperforms existing frameworks by 10% to 50% absolute points with smaller
models, including Llama-3-8b and CodeLlama-7b.
