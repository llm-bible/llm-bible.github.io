---
layout: publication
title: Probing The Safety Response Boundary Of Large Language Models Via Unsafe Decoding Path Generation
authors: Wang Haoyu, Wu Bingzhe, Bian Yatao, Chang Yongzhe, Wang Xueqian, Zhao Peilin
conference: "Arxiv"
year: 2024
bibkey: wang2024probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10668"}
tags: ['Applications', 'Efficiency And Optimization', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security']
---
Large Language Models (LLMs) are implicit troublemakers. While they provide valuable insights and assist in problem-solving they can also potentially serve as a resource for malicious activities. Implementing safety alignment could mitigate the risk of LLMs generating harmful responses. We argue that even when an LLM appears to successfully block harmful queries there may still be hidden vulnerabilities that could act as ticking time bombs. To identify these underlying weaknesses we propose to use a cost value model as both a detector and an attacker. Trained on external or self-generated harmful datasets the cost value model could successfully influence the original safe LLM to output toxic content in decoding process. For instance LLaMA-2-chat 7B outputs 39.1837; concrete toxic content along with only 22.1637; refusals without any harmful suffixes. These potential weaknesses can then be exploited via prompt optimization such as soft prompts on images. We name this decoding strategy Jailbreak Value Decoding (JVD) emphasizing that seemingly secure LLMs may not be as safe as we initially believe. They could be used to gather harmful data or launch covert attacks.
