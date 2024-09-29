---
layout: publication
title: Code Soliloquies For Accurate Calculations In Large Language Models
authors: Sonkar Shashank, Le Myco, Chen Xinghe, Liu Naiming, Mallick Debshila Basu, Baraniuk Richard G.
conference: "Arxiv"
year: 2023
bibkey: sonkar2023code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.12161"}
  - {name: "Code", url: "https://github.com/luffycodes/Tutorbot&#45;Spock&#45;Phys"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting']
---
High45;quality conversational datasets are crucial for the successful development of Intelligent Tutoring Systems (ITS) that utilize a Large Language Model (LLM) backend. Synthetic student45;teacher dialogues generated using advanced GPT45;4 models are a common strategy for creating these datasets. However subjects like physics that entail complex calculations pose a challenge. While GPT45;4 presents impressive language processing capabilities its limitations in fundamental mathematical reasoning curtail its efficacy for such subjects. To tackle this limitation we introduce in this paper an innovative stateful prompt design. Our design orchestrates a mock conversation where both student and tutorbot roles are simulated by GPT45;4. Each student response triggers an internal monologue or code soliloquy in the GPT45;tutorbot which assesses whether its subsequent response would necessitate calculations. If a calculation is deemed necessary it scripts the relevant Python code and uses the Python output to construct a response to the student. Our approach notably enhances the quality of synthetic conversation datasets especially for subjects that are calculation45;intensive. Our preliminary Subject Matter Expert evaluations reveal that our Higgs model a fine45;tuned LLaMA model effectively uses Python for computations which significantly enhances the accuracy and computational reliability of Higgs responses. Code models and datasets is available at https://github.com/luffycodes/Tutorbot&#45;Spock&#45;Phys.
