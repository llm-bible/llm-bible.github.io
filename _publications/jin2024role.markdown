---
layout: publication
title: GUARD Role45;playing To Generate Natural45;language Jailbreakings To Test Guideline Adherence Of Large Language Models
authors: Jin Haibo, Chen Ruoxi, Zhou Andy, Zhang Yang, Wang Haohan
conference: "Arxiv"
year: 2024
bibkey: jin2024role
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03299"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Responsible AI']
---
The discovery of jailbreaks to bypass safety filters of Large Language Models (LLMs) and harmful responses have encouraged the community to implement safety measures. One major safety measure is to proactively test the LLMs with jailbreaks prior to the release. Therefore such testing will require a method that can generate jailbreaks massively and efficiently. In this paper we follow a novel yet intuitive strategy to generate jailbreaks in the style of the human generation. We propose a role45;playing system that assigns four different roles to the user LLMs to collaborate on new jailbreaks. Furthermore we collect existing jailbreaks and split them into different independent characteristics using clustering frequency and semantic patterns sentence by sentence. We organize these characteristics into a knowledge graph making them more accessible and easier to retrieve. Our system of different roles will leverage this knowledge graph to generate new jailbreaks which have proved effective in inducing LLMs to generate unethical or guideline45;violating responses. In addition we also pioneer a setting in our system that will automatically follow the government45;issued guidelines to generate jailbreaks to test whether LLMs follow the guidelines accordingly. We refer to our system as GUARD (Guideline Upholding through Adaptive Role45;play Diagnostics). We have empirically validated the effectiveness of GUARD on three cutting45;edge open45;sourced LLMs (Vicuna45;13B LongChat45;7B and Llama45;245;7B) as well as a widely45;utilized commercial LLM (ChatGPT). Moreover our work extends to the realm of vision language models (MiniGPT45;v2 and Gemini Vision Pro) showcasing GUARDs versatility and contributing valuable insights for the development of safer more reliable LLM45;based applications across diverse modalities.
