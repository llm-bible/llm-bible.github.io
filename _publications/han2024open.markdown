---
layout: publication
title: Wildguard Open One45;stop Moderation Tools For Safety Risks Jailbreaks And Refusals Of Llms
authors: Han Seungju, Rao Kavel, Ettinger Allyson, Jiang Liwei, Lin Bill Yuchen, Lambert Nathan, Choi Yejin, Dziri Nouha
conference: "Arxiv"
year: 2024
bibkey: han2024open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18495"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
We introduce WildGuard 45;45; an open light45;weight moderation tool for LLM safety that achieves three goals (1) identifying malicious intent in user prompts (2) detecting safety risks of model responses and (3) determining model refusal rate. Together WildGuard serves the increasing needs for automatic safety moderation and evaluation of LLM interactions providing a one45;stop tool with enhanced accuracy and broad coverage across 13 risk categories. While existing open moderation tools such as Llama45;Guard2 score reasonably well in classifying straightforward model interactions they lag far behind a prompted GPT45;4 especially in identifying adversarial jailbreaks and in evaluating models refusals a key measure for evaluating safety behaviors in model responses. To address these challenges we construct WildGuardMix a large45;scale and carefully balanced multi45;task safety moderation dataset with 92K labeled examples that cover vanilla (direct) prompts and adversarial jailbreaks paired with various refusal and compliance responses. WildGuardMix is a combination of WildGuardTrain the training data of WildGuard and WildGuardTest a high45;quality human45;annotated moderation test set with 5K labeled items covering broad risk scenarios. Through extensive evaluations on WildGuardTest and ten existing public benchmarks we show that WildGuard establishes state45;of45;the45;art performance in open45;source safety moderation across all the three tasks compared to ten strong existing open45;source moderation models (e.g. up to 26.437; improvement on refusal detection). Importantly WildGuard matches and sometimes exceeds GPT45;4 performance (e.g. up to 3.937; improvement on prompt harmfulness identification). WildGuard serves as a highly effective safety moderator in an LLM interface reducing the success rate of jailbreak attacks from 79.837; to 2.437;.
