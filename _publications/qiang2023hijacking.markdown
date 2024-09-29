---
layout: publication
title: "Hijacking Large Language Models Via Adversarial In-context Learning"
authors: Qiang Yao, Zhou Xiangyu, Zhu Dongxiao
conference: "Arxiv"
year: 2023
bibkey: qiang2023hijacking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09948"}
tags: ['Attention Mechanism', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Security']
---
In-context learning (ICL) has emerged as a powerful paradigm leveraging LLMs for specific downstream tasks by utilizing labeled examples as demonstrations (demos) in the precondition prompts. Despite its promising performance ICL suffers from instability with the choice and arrangement of examples. Additionally crafted adversarial attacks pose a notable threat to the robustness of ICL. However existing attacks are either easy to detect rely on external models or lack specificity towards ICL. This work introduces a novel transferable attack against ICL to address these issues aiming to hijack LLMs to generate the target response or jailbreak. Our hijacking attack leverages a gradient-based prompt search method to learn and append imperceptible adversarial suffixes to the in-context demos without directly contaminating the user queries. Comprehensive experimental results across different generation and jailbreaking tasks highlight the effectiveness of our hijacking attack resulting in distracted attention towards adversarial tokens and consequently leading to unwanted target outputs. We also propose a defense strategy against hijacking attacks through the use of extra clean demos which enhances the robustness of LLMs during ICL. Broadly this work reveals the significant security vulnerabilities of LLMs and emphasizes the necessity for in-depth studies on their robustness.
