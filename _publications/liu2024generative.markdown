---
layout: publication
title: Generative Expressive Conversational Speech Synthesis
authors: Liu Rui, Hu Yifan, Ren Yi, Yin Xiang, Li Haizhou
conference: "Arxiv"
year: 2024
bibkey: liu2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21491"}
  - {name: "Code", url: "https://github.com/AI&#45;S2&#45;Lab/GPT&#45;Talker"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'RAG']
---
Conversational Speech Synthesis (CSS) aims to express a target utterance with the proper speaking style in a user45;agent conversation setting. Existing CSS methods employ effective multi45;modal context modeling techniques to achieve empathy understanding and expression. However they often need to design complex network architectures and meticulously optimize the modules within them. In addition due to the limitations of small45;scale datasets containing scripted recording styles they often fail to simulate real natural conversational styles. To address the above issues we propose a novel generative expressive CSS system termed GPT45;Talker.We transform the multimodal information of the multi45;turn dialogue history into discrete token sequences and seamlessly integrate them to form a comprehensive user45;agent dialogue context. Leveraging the power of GPT we predict the token sequence that includes both semantic and style knowledge of response for the agent. After that the expressive conversational speech is synthesized by the conversation45;enriched VITS to deliver feedback to the user.Furthermore we propose a large45;scale Natural CSS Dataset called NCSSD that includes both naturally recorded conversational speech in improvised styles and dialogues extracted from TV shows. It encompasses both Chinese and English languages with a total duration of 236 hours.We conducted comprehensive experiments on the reliability of the NCSSD and the effectiveness of our GPT45;Talker. Both subjective and objective evaluations demonstrate that our model outperforms other state45;of45;the45;art CSS systems significantly in terms of naturalness and expressiveness. The Code Dataset and Pre45;trained Model are available at https://github.com/AI&#45;S2&#45;Lab/GPT&#45;Talker.
