---
layout: publication
title: Tiny Refinements Elicit Resilience Toward Efficient Prefix45;model Against LLM Red45;teaming
authors: Liu Jiaxu, Yin Xiangyu, Wu Sihao, Wang Jianhong, Fang Meng, Yi Xinping, Huang Xiaowei
conference: "Arxiv"
year: 2024
bibkey: liu2024tiny
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12604"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'GPT', 'Merging', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
With the proliferation of red45;teaming strategies for Large Language Models (LLMs) the deficiency in the literature about improving the safety and robustness of LLM defense strategies is becoming increasingly pronounced. This paper introduces the LLM45;based textbf123;sentinel125; model as a plug45;and45;play prefix module designed to reconstruct the input prompt with just a few (<30) additional tokens effectively reducing toxicity in responses from target LLMs. The sentinel model naturally overcomes the textit123;parameter inefficiency125; and textit123;limited model accessibility125; for fine45;tuning large target models. We employ an interleaved training regimen using Proximal Policy Optimization (PPO) to optimize both red team and sentinel models dynamically incorporating a value head45;sharing mechanism inspired by the multi45;agent centralized critic to manage the complex interplay between agents. Our extensive experiments across text45;to45;text and text45;to45;image demonstrate the effectiveness of our approach in mitigating toxic outputs even when dealing with larger models like texttt123;Llama45;2125; texttt123;GPT45;3.5125; and texttt123;Stable45;Diffusion125; highlighting the potential of our framework in enhancing safety and robustness in various applications.
