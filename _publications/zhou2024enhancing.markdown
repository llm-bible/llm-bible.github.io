---
layout: publication
title: Enhancing The General Agent Capabilities Of Low45;parameter Llms Through Tuning And Multi45;branch Reasoning
authors: Zhou Qinhao, Zhang Zihan, Xiang Xiang, Wang Ke, Wu Yuchuan, Li Yongbin
conference: "Arxiv"
year: 2024
bibkey: zhou2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19962"}
tags: ['Agentic', 'Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Open45;source pre45;trained Large Language Models (LLMs) exhibit strong language understanding and generation capabilities making them highly successful in a variety of tasks. However when used as agents for dealing with complex problems in the real world their performance is far inferior to large commercial models such as ChatGPT and GPT45;4. As intelligent agents LLMs need to have the capabilities of task planning long45;term memory and the ability to leverage external tools to achieve satisfactory performance. Various methods have been proposed to enhance the agent capabilities of LLMs. On the one hand methods involve constructing agent45;specific data and fine45;tuning the models. On the other hand some methods focus on designing prompts that effectively activate the reasoning abilities of the LLMs. We explore both strategies on the 7B and 13B models. We propose a comprehensive method for constructing agent45;specific data using GPT45;4. Through supervised fine45;tuning with constructed data we find that for these models with a relatively small number of parameters supervised fine45;tuning can significantly reduce hallucination outputs and formatting errors in agent tasks. Furthermore techniques such as multi45;path reasoning and task decomposition can effectively decrease problem complexity and enhance the performance of LLMs as agents. We evaluate our method on five agent tasks of AgentBench and achieve satisfactory results.
