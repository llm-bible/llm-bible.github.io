---
layout: publication
title: ICL Markup Structuring In45;context Learning Using Soft45;token Tags
authors: Marc-etienne Brunet, Ashton Anderson, Richard Zemel
conference: "Arxiv"
year: 2023
bibkey: brunet2023icl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2312.07405v1"}
tags: ['Applications', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large pretrained language models (LLMs) can be rapidly adapted to a wide variety of tasks via a text45;to45;text approach where the instruction and input are fed to the model in natural language. Combined with in45;context learning (ICL) this paradigm is impressively flexible and powerful. However it also burdens users with an overwhelming number of choices many of them arbitrary. Inspired by markup languages like HTML we contribute a method of using soft45;token tags to compose prompt templates. This approach reduces arbitrary decisions and streamlines the application of ICL. Our method is a form of meta45;learning for ICL; it learns these tags in advance during a parameter45;efficient fine45;tuning warm45;up process. The tags can subsequently be used in templates for ICL on new unseen tasks without any additional fine45;tuning. Our experiments with this approach yield promising initial results improving LLM performance on important enterprise applications such as few45;shot and open45;world intent detection as well as text classification in news and legal domains.
