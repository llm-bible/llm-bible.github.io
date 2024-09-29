---
layout: publication
title: 'Identifying The Risks Of LM Agents With An Lm-emulated Sandbox'
authors: Ruan Yangjun, Dong Honghua, Wang Andrew, Pitis Silviu, Zhou Yongchao, Ba Jimmy, Dubois Yann, Maddison Chris J., Hashimoto Tatsunori
conference: "Arxiv"
year: 2023
bibkey: ruan2023identifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15817"}
tags: ['Agentic', 'Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Tools']
---
Recent advances in Language Model (LM) agents and tool use exemplified by applications like ChatGPT Plugins enable a rich set of capabilities but also amplify potential risks - such as leaking private data or causing financial losses. Identifying these risks is labor-intensive necessitating implementing the tools setting up the environment for each test scenario manually and finding risky cases. As tools and agents become more complex the high cost of testing these agents will make it increasingly difficult to find high-stakes long-tailed risks. To address these challenges we introduce ToolEmu a framework that uses an LM to emulate tool execution and enables the testing of LM agents against a diverse range of tools and scenarios without manual instantiation. Alongside the emulator we develop an LM-based automatic safety evaluator that examines agent failures and quantifies associated risks. We test both the tool emulator and evaluator through human evaluation and find that 68.837; of failures identified with ToolEmu would be valid real-world agent failures. Using our curated initial benchmark consisting of 36 high-stakes tools and 144 test cases we provide a quantitative risk analysis of current LM agents and identify numerous failures with potentially severe outcomes. Notably even the safest LM agent exhibits such failures 23.937; of the time according to our evaluator underscoring the need to develop safer LM agents for real-world deployment.
