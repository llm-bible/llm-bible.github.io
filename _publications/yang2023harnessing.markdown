---
layout: publication
title: Harnessing The Power Of Large Language Models For Natural Language To First45;order Logic Translation
authors: Yang Yuan, Xiong Siheng, Payani Ali, Shareghi Ehsan, Fekri Faramarz
conference: "Arxiv"
year: 2023
bibkey: yang2023harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15541"}
  - {name: "Code", url: "https://github.com/gblackout/LogicLLaMA&#125;&#123;&#123;"}
  - {name: "Code", url: "https://github.com/gblackout/LogicLLaMA&#125;&#125;&#125;"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Translating natural language sentences to first45;order logic (NL45;FOL translation) is a longstanding challenge in the NLP and formal logic literature. This paper introduces LogicLLaMA a LLaMA45;7B model fine45;tuned for NL45;FOL translation using LoRA on a single GPU. LogicLLaMA is capable of directly translating natural language into FOL rules which outperforms GPT45;3.5. LogicLLaMA is also equipped to correct FOL rules predicted by GPT45;3.5 and can achieve similar performance as GPT45;4 with a fraction of the cost. This correction ability was achieved by a novel supervised fine45;tuning (SFT) + reinforcement learning with human feedback (RLHF) framework which initially trains on synthetically perturbed NL45;FOL pairs to encourage chain45;of45;thought reasoning and then fine45;tunes with RLHF on GPT45;3.5 outputs using a FOL verifier as the reward model. To train LogicLLaMA we present MALLS (large language textbf123;M125;odel genertextbf123;A125;ted Ntextbf123;L125;45;FOtextbf123;L125; pairtextbf123;S125;) a dataset of 34K high45;quality and diverse sentence45;level NL45;FOL pairs collected from GPT45;4. The dataset was created by implementing a pipeline that prompts GPT45;4 for pairs and dynamically adjusts the prompts to ensure the collection of pairs with rich and diverse contexts at different levels of complexity and verifies the validity of the generated FOL rules. Codes weights and data are available at href123;https://github.com/gblackout/LogicLLaMA&#125;&#123;&#123;\small text123;https://github.com/gblackout/LogicLLaMA&#125;&#125;&#125;$.
