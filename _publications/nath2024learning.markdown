---
layout: publication
title: Learning Goal45;conditioned Representations For Language Reward Models
authors: Nath Vaskar, Slack Dylan, Da Jeff, Ma Yuntao, Zhang Hugh, Whitehead Spencer, Hendryx Sean
conference: "Arxiv"
year: 2024
bibkey: nath2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13887"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Techniques that learn improved representations via offline data or self45;supervised objectives have shown impressive results in traditional reinforcement learning (RL). Nevertheless it is unclear how improved representation learning can benefit reinforcement learning from human feedback (RLHF) on language models (LMs). In this work we propose training reward models (RMs) in a contrastive textit123;goal45;conditioned125; fashion by increasing the representation similarity of future states along sampled preferred trajectories and decreasing the similarity along randomly sampled dispreferred trajectories. This objective significantly improves RM performance by up to 0.09 AUROC across challenging benchmarks such as MATH and GSM8k. These findings extend to general alignment as well 45;45; on the Helpful45;Harmless dataset we observe 2.337; increase in accuracy. Beyond improving reward model performance we show this way of training RM representations enables improved textit123;steerability125; because it allows us to evaluate the likelihood of an action achieving a particular goal45;state (e.g. whether a solution is correct or helpful). Leveraging this insight we find that we can filter up to 5537; of generated tokens during majority voting by discarding trajectories likely to end up in an incorrect state which leads to significant cost savings. We additionally find that these representations can perform fine45;grained control by conditioning on desired future goal45;states. For example we show that steering a Llama 3 model towards helpful generations with our approach improves helpfulness by 9.637; over a supervised45;fine45;tuning trained baseline. Similarly steering the model towards complex generations improves complexity by 21.637; over the baseline. Overall we find that training RMs in this contrastive goal45;conditioned fashion significantly improves performance and enables model steerability.
