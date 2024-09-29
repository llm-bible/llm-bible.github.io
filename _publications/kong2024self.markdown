---
layout: publication
title: Self45;prompt Tuning Enable Autonomous Role45;playing In Llms
authors: Kong Aobo, Zhao Shiwan, Chen Hao, Li Qicheng, Qin Yong, Sun Ruiqi, Zhou Xin, Zhou Jiaming, Sun Haoqin
conference: "Arxiv"
year: 2024
bibkey: kong2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08995"}
  - {name: "Code", url: "https://anonymous.4open.science/r/Self&#45;Prompt&#45;Tuning&#45;739E/&#125;&#123;url&#125;"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Recent advancements in LLMs have showcased their remarkable role45;playing capabilities able to accurately simulate the dialogue styles and cognitive processes of various roles based on different instructions and contexts. Studies indicate that assigning LLMs the roles of experts a strategy known as role45;play prompting can enhance their performance in the corresponding domains. However the prompt needs to be manually designed for the given problem requiring certain expertise and iterative modifications. To this end we propose self45;prompt tuning making LLMs themselves generate role45;play prompts through fine45;tuning. Leveraging the LIMA dataset as our foundational corpus we employ GPT45;4 to annotate role45;play prompts for each data points resulting in the creation of the LIMA45;Role dataset. We then fine45;tune LLMs like Llama45;245;7B and Mistral45;7B on LIMA45;Role. Consequently the self45;prompt tuned LLMs can automatically generate expert role prompts for any given question. We extensively evaluate self45;prompt tuned LLMs on widely used NLP benchmarks and open45;ended question test. Our empirical results illustrate that self45;prompt tuned LLMs outperform standard instruction tuned baselines across most datasets. This highlights the great potential of utilizing fine45;tuning to enable LLMs to self45;prompt thereby automating complex prompting strategies. We release the dataset models and code at this href123;https://anonymous.4open.science/r/Self&#45;Prompt&#45;Tuning&#45;739E/&#125;&#123;url&#125;.
