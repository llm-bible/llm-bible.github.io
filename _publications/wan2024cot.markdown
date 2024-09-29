---
layout: publication
title: Cot Rerailer&#58; Enhancing The Reliability Of Large Language Models In Complex Reasoning Tasks Through Error Detection And Correction
authors: Wan Guangya, Wu Yuqi, Chen Jie, Li Sheng
conference: "Arxiv"
year: 2024
bibkey: wan2024cot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13940"}
tags: ['Agentic', 'Applications', 'Prompting']
---
Chain-of-Thought (CoT) prompting enhances Large Language Models (LLMs) complex reasoning abilities by generating intermediate steps. However these steps can introduce hallucinations and accumulate errors. We propose the CoT Rerailer to address these challenges employing self-consistency and multi-agent debate systems to identify and rectify errors in the reasoning process. The CoT Rerailer first selects the most logically correct Reasoning Path (RP) using consistency checks and critical evaluation by automated agents. It then engages a multi-agent debate system to propose and validate corrections to ensure the generation of an error-free intermediate logical path. The corrected steps are then used to generate a revised reasoning chain to further reduce hallucinations and enhance answer quality. We demonstrate the effectiveness of our approach across diverse question-answering datasets in various knowledge domains. The CoT Rerailer enhances the reliability of LLM-generated reasoning contributing to more trustworthy AI driven decision-making processes.
