---
layout: publication
title: Chatbug\: A Common Vulnerability Of Aligned Llms Induced By Chat Templates
authors: Jiang Fengqing, Xu Zhangchen, Niu Luyao, Lin Bill Yuchen, Poovendran Radha
conference: "Arxiv"
year: 2024
bibkey: jiang2024common
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12935"}
tags: ['Ethics And Bias', 'Prompting', 'RAG', 'Responsible AI', 'Security', 'Training Techniques']
---
Large language models (LLMs) are expected to follow instructions from users and engage in conversations. Techniques to enhance LLMs instruction-following capabilities typically fine-tune them using data structured according to a predefined chat template. Although chat templates are shown to be effective in optimizing LLM performance their impact on safety alignment of LLMs has been less understood which is crucial for deploying LLMs safely at scale. In this paper we investigate how chat templates affect safety alignment of LLMs. We identify a common vulnerability named ChatBug that is introduced by chat templates. Our key insight to identify ChatBug is that the chat templates provide a rigid format that need to be followed by LLMs but not by users. Hence a malicious user may not necessarily follow the chat template when prompting LLMs. Instead malicious users could leverage their knowledge of the chat template and accordingly craft their prompts to bypass safety alignments of LLMs. We develop two attacks to exploit the ChatBug vulnerability. We demonstrate that a malicious user can exploit the ChatBug vulnerability of eight state-of-the-art (SOTA) LLMs and effectively elicit unintended responses from these models. Moreover we show that ChatBug can be exploited by existing jailbreak attacks to enhance their attack success rates. We investigate potential countermeasures to ChatBug. Our results show that while adversarial training effectively mitigates the ChatBug vulnerability the victim model incurs significant performance degradation. These results highlight the trade-off between safety alignment and helpfulness. Developing new methods for instruction tuning to balance this trade-off is an open and critical direction for future research
