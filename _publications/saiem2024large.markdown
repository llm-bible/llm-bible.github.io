---
layout: publication
title: 'Sequentialbreak: Large Language Models Can Be Fooled By Embedding Jailbreak Prompts Into Sequential Prompt Chains'
authors: Bijoy Ahmed Saiem, Md Sadik Hossain Shanto, Rakib Ahsan, Md Rafi Ur Rashid
conference: "Arxiv"
year: 2024
bibkey: saiem2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06426"}
  - {name: "Code", url: "https://anonymous.4open.science/r/JailBreakAttack-4F3B/"}
tags: ['Efficiency and Optimization', 'Applications', 'Security', 'Has Code', 'Prompting']
---
As the integration of the Large Language Models (LLMs) into various applications increases, so does their susceptibility to misuse, raising significant security concerns. Numerous jailbreak attacks have been proposed to assess the security defense of LLMs. Current jailbreak attacks mainly rely on scenario camouflage, prompt obfuscation, prompt optimization, and prompt iterative optimization to conceal malicious prompts. In particular, sequential prompt chains in a single query can lead LLMs to focus on certain prompts while ignoring others, facilitating context manipulation. This paper introduces SequentialBreak, a novel jailbreak attack that exploits this vulnerability. We discuss several scenarios, not limited to examples like Question Bank, Dialog Completion, and Game Environment, where the harmful prompt is embedded within benign ones that can fool LLMs into generating harmful responses. The distinct narrative structures of these scenarios show that SequentialBreak is flexible enough to adapt to various prompt formats beyond those discussed. Extensive experiments demonstrate that SequentialBreak uses only a single query to achieve a substantial gain of attack success rate over existing baselines against both open-source and closed-source models. Through our research, we highlight the urgent need for more robust and resilient safeguards to enhance LLM security and prevent potential misuse. All the result files and website associated with this research are available in this GitHub repository: https://anonymous.4open.science/r/JailBreakAttack-4F3B/.
