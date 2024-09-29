---
layout: publication
title: "Rational Decision-making Agent With Internalized Utility Judgment"
authors: Ye Yining, Cong Xin, Tian Shizuo, Qin Yujia, Liu Chong, Lin Yankai, Liu Zhiyuan, Sun Maosong
conference: "Arxiv"
year: 2023
bibkey: ye2023rational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12519"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have demonstrated remarkable advancements and have attracted significant efforts to develop LLMs into agents capable of executing intricate multi-step decision-making tasks beyond traditional NLP applications. Existing approaches to LLM-based decision-making predominantly build upon the manually-designed external performance metrics to guide the decision-making process. However reliance on the external performance metrics as prior is problematic in real-world scenarios where such prior may be unavailable flawed or even erroneous. For genuine autonomous decision making it is imperative for the agent to develop its rationality from its posterior experiences to judge decisions independently. Central to the development of rationality is the construction of an internalized utility judgment capable of assigning numerical utilities to each decision. This paper proposes RadAgent (Rational Decision-Making Agent) which fosters the development of its rationality through an iterative framework involving Experience Exploration and Utility Learning. Within this framework Elo-based Utility Construction is devised to assign Elo scores to individual decision steps to judge their utilities via pairwise comparisons. Consequently these Elo scores guide the decision-making process to derive optimal outcomes. Experimental results on the ToolBench dataset demonstrate RadAgents superiority over baselines achieving over 1037; improvement in Pass Rate on diverse tasks. It offers higher-quality solutions and reduces costs (ChatGPT API calls) highlighting its effectiveness and efficiency.
