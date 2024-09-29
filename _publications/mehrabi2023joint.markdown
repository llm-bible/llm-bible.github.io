---
layout: publication
title: "JAB: Joint Adversarial Prompting And Belief Augmentation"
authors: Mehrabi Ninareh, Goyal Palash, Ramakrishna Anil, Dhamala Jwala, Ghosh Shalini, Zemel Richard, Chang Kai-wei, Galstyan Aram, Gupta Rahul
conference: "Arxiv"
year: 2023
bibkey: mehrabi2023joint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09473"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'RAG', 'Responsible AI', 'Security', 'Tools']
---
With the recent surge of language models in different applications attention to safety and robustness of these models has gained significant importance. Here we introduce a joint framework in which we simultaneously probe and improve the robustness of a black-box target model via adversarial prompting and belief augmentation using iterative feedback loops. This framework utilizes an automated red teaming approach to probe the target model along with a belief augmenter to generate instructions for the target model to improve its robustness to those adversarial probes. Importantly the adversarial model and the belief generator leverage the feedback from past interactions to improve the effectiveness of the adversarial prompts and beliefs respectively. In our experiments we demonstrate that such a framework can reduce toxic content generation both in dynamic cases where an adversary directly interacts with a target model and static cases where we use a static benchmark dataset to evaluate our model.
