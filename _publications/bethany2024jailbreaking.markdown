---
layout: publication
title: 'Jailbreaking Large Language Models With Symbolic Mathematics'
authors: Emet Bethany, Mazal Bethany, Juan Arturo Nolazco Flores, Sumit Kumar Jha, Peyman Najafirad
conference: "Arxiv"
year: 2024
bibkey: bethany2024jailbreaking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.11445'}
tags: ['RAG', 'Security', 'Training Techniques', 'Prompting', 'Responsible AI']
---
Recent advancements in AI safety have led to increased efforts in training
and red-teaming large language models (LLMs) to mitigate unsafe content
generation. However, these safety mechanisms may not be comprehensive, leaving
potential vulnerabilities unexplored. This paper introduces MathPrompt, a novel
jailbreaking technique that exploits LLMs' advanced capabilities in symbolic
mathematics to bypass their safety mechanisms. By encoding harmful natural
language prompts into mathematical problems, we demonstrate a critical
vulnerability in current AI safety measures. Our experiments across 13
state-of-the-art LLMs reveal an average attack success rate of 73.6%,
highlighting the inability of existing safety training mechanisms to generalize
to mathematically encoded inputs. Analysis of embedding vectors shows a
substantial semantic shift between original and encoded prompts, helping
explain the attack's success. This work emphasizes the importance of a holistic
approach to AI safety, calling for expanded red-teaming efforts to develop
robust safeguards across all potential input types and their associated risks.
