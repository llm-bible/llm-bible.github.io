---
layout: publication
title: "A Comprehensive Study Of The Capabilities Of Large Language Models For Vulnerability Detection"
authors: Steenhoek Benjamin, Rahman Md Mahbubur, Roy Monoshi Kumar, Alam Mirza Sanjida, Barr Earl T., Le Wei
conference: "Arxiv"
year: 2024
bibkey: steenhoek2024comprehensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17218"}
  - {name: "Code", url: "https://figshare.com/s/78fe02e56e09ec49300b"}
tags: ['Applications', 'Has Code', 'In Context Learning', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Survey Paper']
---
Large Language Models (LLMs) have demonstrated great potential for code generation and other software engineering tasks. Vulnerability detection is of crucial importance to maintaining the security integrity and trustworthiness of software systems. Precise vulnerability detection requires reasoning about the code making it a good case study for exploring the limits of LLMs reasoning capabilities. Although recent work has applied LLMs to vulnerability detection using generic prompting techniques their full capabilities for this task and the types of errors they make when explaining identified vulnerabilities remain unclear. In this paper we surveyed eleven LLMs that are state-of-the-art in code generation and commonly used as coding assistants and evaluated their capabilities for vulnerability detection. We systematically searched for the best-performing prompts incorporating techniques such as in-context learning and chain-of-thought and proposed three of our own prompting methods. Our results show that while our prompting methods improved the models performance LLMs generally struggled with vulnerability detection. They reported 0.5-0.63 Balanced Accuracy and failed to distinguish between buggy and fixed versions of programs in 7637; of cases on average. By comprehensively analyzing and categorizing 287 instances of model reasoning we found that 5737; of LLM responses contained errors and the models frequently predicted incorrect locations of buggy code and misidentified bug types. LLMs only correctly localized 6 out of 27 bugs in DbgBench and these 6 bugs were predicted correctly by 70-10037; of human participants. These findings suggest that despite their potential for other tasks LLMs may fail to properly comprehend critical code structures and security-related concepts. Our data and code are available at https://figshare.com/s/78fe02e56e09ec49300b."
