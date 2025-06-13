---
layout: publication
title: 'Emojiprompt: Generative Prompt Obfuscation For Privacy-preserving Communication With Cloud-based Llms'
authors: Sam Lin, Wenyue Hua, Zhenting Wang, Mingyu Jin, Lizhou Fan, Yongfeng Zhang
conference: "Arxiv"
year: 2024
bibkey: lin2024generative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.05868'}
  - {name: "Code", url: 'https://github.com/agiresearch/EmojiCrypt'}
tags: ['Has Code', 'Security', 'GPT', 'Model Architecture', 'Prompting']
---
Cloud-based Large Language Models (LLMs) such as ChatGPT have become
increasingly integral to daily operations. Nevertheless, they also introduce
privacy concerns: firstly, numerous studies underscore the risks to user
privacy posed by jailbreaking cloud-based LLMs; secondly, the LLM service
providers have access to all user data, which deters individuals from
confidently utilizing such services. To address such concerns, we propose a
simple yet effective paradigm, EmojiPrompt, to protect user privacy. At its
core, EmojiPrompt performs generative transformation, obfuscating private data
within prompts with linguistic and non-linguistic elements before submitting
them to cloud-based LLMs. We evaluate EmojiPrompt's performance across 8
datasets from various domains. We also propose simulated inference attacks to
assess EmojiPrompt's ability to preserve user privacy. The results demonstrate
that EmojiPrompt effectively obfuscates user private data, while largely
maintaining, or even enhancing, performances compared to the unobfuscated
version. Furthermore, EmojiPrompt's atomic-level obfuscation allows it to
function exclusively with cloud-based LLMs. For source code, please refer to:
https://github.com/agiresearch/EmojiCrypt.
