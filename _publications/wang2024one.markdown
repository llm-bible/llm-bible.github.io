---
layout: publication
title: One Prompt Is Not Enough Automated Construction Of A Mixture45;of45;expert Prompts
authors: Wang Ruochen, An Sohyun, Cheng Minhao, Zhou Tianyi, Hwang Sung Ju, Hsieh Cho-jui
conference: "Proceedings of the"
year: 2024
bibkey: wang2024one
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00256"}
tags: ['Prompting', 'RAG']
---
Large Language Models (LLMs) exhibit strong generalization capabilities to novel tasks when prompted with language instructions and in45;context demos. Since this ability sensitively depends on the quality of prompts various methods have been explored to automate the instruction design. While these methods demonstrated promising results they also restricted the searched prompt to one instruction. Such simplification significantly limits their capacity as a single demo45;free instruction might not be able to cover the entire complex problem space of the targeted task. To alleviate this issue we adopt the Mixture45;of45;Expert paradigm and divide the problem space into a set of sub45;regions; Each sub45;region is governed by a specialized expert equipped with both an instruction and a set of demos. A two45;phase process is developed to construct the specialized expert for each region (1) demo assignment Inspired by the theoretical connection between in45;context learning and kernel regression we group demos into experts based on their semantic similarity; (2) instruction assignment A region45;based joint search of an instruction per expert complements the demos assigned to it yielding a synergistic effect. The resulting method codenamed Mixture45;of45;Prompts (MoP) achieves an average win rate of 8137; against prior arts across several major benchmarks.
