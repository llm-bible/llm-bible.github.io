---
layout: publication
title: 'Dissecting Physics Reasoning In Small Language Models: A Multi-dimensional Analysis From An Educational Perspective'
authors: Nicy Scaria, Silvester John Joseph Kennedy, Diksha Seth, Deepak Subramani
conference: "Arxiv"
year: 2025
bibkey: scaria2025dissecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20707"}
tags: ['Efficiency and Optimization', 'Applications', 'Tools', 'Reinforcement Learning']
---
Small Language Models (SLMs) offer computational efficiency and accessibility, making them promising for educational applications. However, their capacity for complex reasoning, particularly in domains such as physics, remains underexplored. This study investigates the high school physics reasoning capabilities of state-of-the-art SLMs (under 4 billion parameters), including instruct versions of Llama 3.2, Phi 4 Mini, Gemma 3, and Qwen series. We developed a comprehensive physics dataset from the OpenStax High School Physics textbook, annotated according to Bloom's Taxonomy, with LaTeX and plaintext mathematical notations. A novel cultural contextualization approach was applied to a subset, creating culturally adapted problems for Asian, African, and South American/Australian contexts while preserving core physics principles. Using an LLM-as-a-judge framework with Google's Gemini 2.5 Flash, we evaluated answer and reasoning chain correctness, along with calculation accuracy. The results reveal significant differences between the SLMs. Qwen 3 1.7B achieved high `answer accuracy' (85%), but `fully correct reasoning' was substantially low (38%). The format of the mathematical notation had a negligible impact on performance. SLMs exhibited varied performance across the physics topics and showed a decline in reasoning quality with increasing cognitive and knowledge complexity. In particular, the consistency of reasoning was largely maintained in diverse cultural contexts, especially by better performing models. These findings indicate that, while SLMs can often find correct answers, their underlying reasoning is frequently flawed, suggesting an overreliance on pattern recognition. For SLMs to become reliable educational tools in physics, future development must prioritize enhancing genuine understanding and the generation of sound, verifiable reasoning chains over mere answer accuracy.
