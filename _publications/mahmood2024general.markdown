---
layout: publication
title: 'VURF: A General-purpose Reasoning And Self-refinement Framework For Video Understanding'
authors: Mahmood Ahmad, Vayani Ashmal, Naseer Muzammal, Khan Salman, Khan Fahad Shahbaz
conference: "Arxiv"
year: 2024
bibkey: mahmood2024general
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14743"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools']
---
Recent studies have demonstrated the effectiveness of Large Language Models (LLMs) as reasoning modules that can deconstruct complex tasks into more manageable sub-tasks, particularly when applied to visual reasoning tasks for images. In contrast, this paper introduces a Video Understanding and Reasoning Framework (VURF) based on the reasoning power of LLMs. Ours is a novel approach to extend the utility of LLMs in the context of video tasks, leveraging their capacity to generalize from minimal input and output demonstrations within a contextual framework. By presenting LLMs with pairs of instructions and their corresponding high-level programs, we harness their contextual learning capabilities to generate executable visual programs for video understanding. To enhance program's accuracy and robustness, we implement two important strategies. Firstly, we employ a feedback-generation approach, powered by GPT-3.5, to rectify errors in programs utilizing unsupported functions. Secondly, taking motivation from recent works on self refinement of LLM outputs, we introduce an iterative procedure for improving the quality of the in-context examples by aligning the initial outputs to the outputs that would have been generated had the LLM not been bound by the structure of the in-context examples. Our results on several video-specific tasks, including visual QA, video anticipation, pose estimation and multi-video QA illustrate the efficacy of these enhancements in improving the performance of visual programming approaches for video tasks.
