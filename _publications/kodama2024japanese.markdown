---
layout: publication
title: "Recmind: Japanese Movie Recommendation Dialogue With Seeker's Internal State"
authors: Kodama Takashi, Kiyomaru Hirokazu, Huang Yin Jou, Kurohashi Sadao
conference: "Arxiv"
year: 2024
bibkey: kodama2024japanese
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13522"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Humans pay careful attention to the interlocutors internal state in dialogues. For example in recommendation dialogues we make recommendations while estimating the seekers internal state such as his/her level of knowledge and interest. Since there are no existing annotated resources for the analysis we constructed RecMind a Japanese movie recommendation dialogue dataset with annotations of the seekers internal state at the entity level. Each entity has a subjective label annotated by the seeker and an objective label annotated by the recommender. RecMind also features engaging dialogues with long seekers utterances enabling a detailed analysis of the seekers internal state. Our analysis based on RecMind reveals that entities that the seeker has no knowledge about but has an interest in contribute to recommendation success. We also propose a response generation framework that explicitly considers the seekers internal state utilizing the chain-of-thought prompting. The human evaluation results show that our proposed method outperforms the baseline method in both consistency and the success of recommendations.
