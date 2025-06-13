---
layout: publication
title: 'Understanding Multi-turn Toxic Behaviors In Open-domain Chatbots'
authors: Bocheng Chen, Guangjing Wang, Hanqing Guo, Yuanda Wang, Qiben Yan
conference: "Arxiv"
year: 2023
bibkey: chen2023understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.09579'}
tags: ['Security', 'Model Architecture', 'Training Techniques', 'Tools', 'Fine-Tuning', 'GPT', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advances in natural language processing and machine learning have led
to the development of chatbot models, such as ChatGPT, that can engage in
conversational dialogue with human users. However, the ability of these models
to generate toxic or harmful responses during a non-toxic multi-turn
conversation remains an open research question. Existing research focuses on
single-turn sentence testing, while we find that 82% of the individual
non-toxic sentences that elicit toxic behaviors in a conversation are
considered safe by existing tools. In this paper, we design a new attack,
\toxicbot, by fine-tuning a chatbot to engage in conversation with a target
open-domain chatbot. The chatbot is fine-tuned with a collection of crafted
conversation sequences. Particularly, each conversation begins with a sentence
from a crafted prompt sentences dataset. Our extensive evaluation shows that
open-domain chatbot models can be triggered to generate toxic responses in a
multi-turn conversation. In the best scenario, \toxicbot achieves a 67%
activation rate. The conversation sequences in the fine-tuning stage help
trigger the toxicity in a conversation, which allows the attack to bypass two
defense methods. Our findings suggest that further research is needed to
address chatbot toxicity in a dynamic interactive environment. The proposed
\toxicbot can be used by both industry and researchers to develop methods for
detecting and mitigating toxic responses in conversational dialogue and improve
the robustness of chatbots for end users.
