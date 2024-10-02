---
layout: publication
title: 'Model-enhanced Llm-driven VUI Testing Of VPA Apps'
authors: Li Suwan, Bu Lei, Bai Guangdong, Xie Fuman, Chen Kai, Yue Chang
conference: "Arxiv"
year: 2024
bibkey: li2024model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02791"}
tags: ['Efficiency And Optimization', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools']
---
'The flourishing ecosystem centered around voice personal assistants (VPA), such as Amazon Alexa, has led to the booming of VPA apps. The largest app market Amazon skills store, for example, hosts over 200,000 apps. Despite their popularity, the open nature of app release and the easy accessibility of apps also raise significant concerns regarding security, privacy and quality. Consequently, various testing approaches have been proposed to systematically examine VPA app behaviors. To tackle the inherent lack of a visible user interface in the VPA app, two strategies are employed during testing, i.e., chatbot-style testing and model-based testing. The former often lacks effective guidance for expanding its search space, while the latter falls short in interpreting the semantics of conversations to construct precise and comprehensive behavior models for apps. In this work, we introduce Elevate, a model-enhanced large language model (LLM)-driven VUI testing framework. Elevate leverages LLMs'' strong capability in natural language processing to compensate for semantic information loss during model-based VUI testing. It operates by prompting LLMs to extract states from VPA apps'' outputs and generate context-related inputs. During the automatic interactions with the app, it incrementally constructs the behavior model, which facilitates the LLM in generating inputs that are highly likely to discover new states. Elevate bridges the LLM and the behavior model with innovative techniques such as encoding behavior model into prompts and selecting LLM-generated inputs based on the context relevance. Elevate is benchmarked on 4,000 real-world Alexa skills, against the state-of-the-art tester Vitas. It achieves 15&#37; higher state space coverage compared to Vitas on all types of apps, and exhibits significant advancement in efficiency.'
