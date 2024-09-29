---
layout: publication
title: "Response-act Guided Reinforced Dialogue Generation For Mental Health Counseling"
authors: Srivastava Aseem, Pandey Ishan, Akhtar Md. Shad, Chakraborty Tanmoy
conference: "Arxiv"
year: 2023
bibkey: srivastava2023response
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.12729"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Virtual Mental Health Assistants (VMHAs) have become a prevalent method for receiving mental health counseling in the digital healthcare space. An assistive counseling conversation commences with natural open-ended topics to familiarize the client with the environment and later converges into more fine-grained domain-specific topics. Unlike other conversational systems which are categorized as open-domain or task-oriented systems VMHAs possess a hybrid conversational flow. These counseling bots need to comprehend various aspects of the conversation such as dialogue-acts intents etc. to engage the client in an effective conversation. Although the surge in digital health research highlights applications of many general-purpose response generation systems they are barely suitable in the mental health domain -- the prime reason is the lack of understanding in mental health counseling. Moreover in general dialogue-act guided response generators are either limited to a template-based paradigm or lack appropriate semantics. To this end we propose READER -- a REsponse-Act guided reinforced Dialogue genERation model for the mental health counseling conversations. READER is built on transformer to jointly predict a potential dialogue-act d(t+1) for the next utterance (aka response-act) and to generate an appropriate response u(t+1). Through the transformer-reinforcement-learning (TRL) with Proximal Policy Optimization (PPO) we guide the response generator to abide by d(t+1) and ensure the semantic richness of the responses via BERTScore in our reward computation. We evaluate READER on HOPE a benchmark counseling conversation dataset and observe that it outperforms several baselines across several evaluation metrics -- METEOR ROUGE and BERTScore. We also furnish extensive qualitative and quantitative analyses on results including error analysis human evaluation etc.
