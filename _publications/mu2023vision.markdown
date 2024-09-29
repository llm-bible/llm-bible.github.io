---
layout: publication
title: Embodiedgpt Vision45;language Pre45;training Via Embodied Chain Of Thought
authors: Yao Mu, Qinglong Zhang, Mengkang Hu, Wenhai Wang, Mingyu Ding, Jun Jin, Bin Wang, Jifeng Dai, Yu Qiao, Ping Luo
conference: "Arxiv"
year: 2023
bibkey: mu2023vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2305.15021v2"}
tags: ['Agentic', 'Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Embodied AI is a crucial frontier in robotics capable of planning and executing action sequences for robots to accomplish long45;horizon tasks in physical environments. In this work we introduce EmbodiedGPT an end45;to45;end multi45;modal foundation model for embodied AI empowering embodied agents with multi45;modal understanding and execution capabilities. To achieve this we have made the following efforts (i) We craft a large45;scale embodied planning dataset termed EgoCOT. The dataset consists of carefully selected videos from the Ego4D dataset along with corresponding high45;quality language instructions. Specifically we generate a sequence of sub45;goals with the Chain of Thoughts mode for effective embodied planning. (ii) We introduce an efficient training approach to EmbodiedGPT for high45;quality plan generation by adapting a 7B large language model (LLM) to the EgoCOT dataset via prefix tuning. (iii) We introduce a paradigm for extracting task45;related features from LLM45;generated planning queries to form a closed loop between high45;level planning and low45;level control. Extensive experiments show the effectiveness of EmbodiedGPT on embodied tasks including embodied planning embodied control visual captioning and visual question answering. Notably EmbodiedGPT significantly enhances the success rate of the embodied control task by extracting more effective features. It has achieved a remarkable 1.6 times increase in success rate on the Franka Kitchen benchmark and a 1.3 times increase on the Meta45;World benchmark compared to the BLIP45;2 baseline fine45;tuned with the Ego4D dataset.
