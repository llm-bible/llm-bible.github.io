---
layout: publication
title: PPTC-R Benchmark Towards Evaluating The Robustness Of Large Language Models For Powerpoint Task Completion
authors: Zhang Zekai, Guo Yiduo, Liang Yaobo, Zhao Dongyan, Duan Nan
conference: "Arxiv"
year: 2024
bibkey: zhang2024pptc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03788"}
  - {name: "Code", url: "https://github.com/ZekaiGalaxy/PPTCR"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Tools']
---
The growing dependence on Large Language Models (LLMs) for finishing user instructions necessitates a comprehensive understanding of their robustness to complex task completion in real-world situations. To address this critical need we propose the PowerPoint Task Completion Robustness benchmark (PPTC-R) to measure LLMs robustness to the user PPT task instruction and software version. Specifically we construct adversarial user instructions by attacking user instructions at sentence semantic and multi-language levels. To assess the robustness of Language Models to software versions we vary the number of provided APIs to simulate both the newest version and earlier version settings. Subsequently we test 3 closed-source and 4 open-source LLMs using a benchmark that incorporates these robustness settings aiming to evaluate how deviations impact LLMs API calls for task completion. We find that GPT-4 exhibits the highest performance and strong robustness in our benchmark particularly in the version update and the multilingual settings. However we find that all LLMs lose their robustness when confronted with multiple challenges (e.g. multi-turn) simultaneously leading to significant performance drops. We further analyze the robustness behavior and error reasons of LLMs in our benchmark which provide valuable insights for researchers to understand the LLMs robustness in task completion and develop more robust LLMs and agents. We release the code and data at (url)https://github.com/ZekaiGalaxy/PPTCR\}."
