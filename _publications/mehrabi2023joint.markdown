---
layout: publication
title: 'JAB: Joint Adversarial Prompting And Belief Augmentation'
authors: Ninareh Mehrabi, Palash Goyal, Anil Ramakrishna, Jwala Dhamala, Shalini Ghosh, Richard Zemel, Kai-wei Chang, Aram Galstyan, Rahul Gupta
conference: "Arxiv"
year: 2023
bibkey: mehrabi2023joint
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.09473'}
tags: ['Attention Mechanism', 'RAG', 'Security', 'Model Architecture', 'Applications', 'Tools', 'Prompting', 'Responsible AI']
---
With the recent surge of language models in different applications, attention
to safety and robustness of these models has gained significant importance.
Here we introduce a joint framework in which we simultaneously probe and
improve the robustness of a black-box target model via adversarial prompting
and belief augmentation using iterative feedback loops. This framework utilizes
an automated red teaming approach to probe the target model, along with a
belief augmenter to generate instructions for the target model to improve its
robustness to those adversarial probes. Importantly, the adversarial model and
the belief generator leverage the feedback from past interactions to improve
the effectiveness of the adversarial prompts and beliefs, respectively. In our
experiments, we demonstrate that such a framework can reduce toxic content
generation both in dynamic cases where an adversary directly interacts with a
target model and static cases where we use a static benchmark dataset to
evaluate our model.
