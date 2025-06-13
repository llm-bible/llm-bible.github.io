---
layout: publication
title: 'Webgen-bench: Evaluating Llms On Generating Interactive And Functional Websites From Scratch'
authors: Zimu Lu, Yunqiao Yang, Houxing Ren, Haotian Hou, Han Xiao, Ke Wang, Weikang Shi, Aojun Zhou, Mingjie Zhan, Hongsheng Li
conference: "Arxiv"
year: 2025
bibkey: lu2025webgen
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.03733'}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Applications', 'Training Techniques', 'GPT', 'Reinforcement Learning']
---
LLM-based agents have demonstrated great potential in generating and managing
code within complex codebases. In this paper, we introduce WebGen-Bench, a
novel benchmark designed to measure an LLM-based agent's ability to create
multi-file website codebases from scratch. It contains diverse instructions for
website generation, created through the combined efforts of human annotators
and GPT-4o. These instructions span three major categories and thirteen minor
categories, encompassing nearly all important types of web applications. To
assess the quality of the generated websites, we use GPT-4o to generate test
cases targeting each functionality described in the instructions, and then
manually filter, adjust, and organize them to ensure accuracy, resulting in 647
test cases. Each test case specifies an operation to be performed on the
website and the expected result after the operation. To automate testing and
improve reproducibility, we employ a powerful web-navigation agent to execute
tests on the generated websites and determine whether the observed responses
align with the expected results. We evaluate three high-performance code-agent
frameworks, Bolt.diy, OpenHands, and Aider, using multiple proprietary and
open-source LLMs as engines. The best-performing combination, Bolt.diy powered
by DeepSeek-R1, achieves only 27.8% accuracy on the test cases, highlighting
the challenging nature of our benchmark. Additionally, we construct
WebGen-Instruct, a training set consisting of 6,667 website-generation
instructions. Training Qwen2.5-Coder-32B-Instruct on Bolt.diy trajectories
generated from a subset of this training set achieves an accuracy of 38.2%,
surpassing the performance of the best proprietary model.
