---
layout: publication
title: Prompt Packer Deceiving LLMs through Compositional Instruction with Hidden Attacks
authors: Jiang Shuyu, Chen Xingshu, Tang Rui
conference: "Arxiv"
year: 2023
bibkey: jiang2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10077"}
tags: ['ARXIV', 'Applications', 'Chatgpt', 'Ethics And Bias', 'GPT', 'LLM', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security']
---
Recently Large language models (LLMs) with powerful general capabilities have been increasingly integrated into various Web applications while undergoing alignment training to ensure that the generated content aligns with user intent and ethics. Unfortunately they remain the risk of generating harmful content like hate speech and criminal activities in practical applications. Current approaches primarily rely on detecting collecting and training against harmful prompts to prevent such risks. However they typically focused on the superficial harmful prompts with a solitary intent ignoring composite attack instructions with multiple intentions that can easily elicit harmful content in real-world scenarios. In this paper we introduce an innovative technique for obfuscating harmful instructions Compositional Instruction Attacks (CIA) which refers to attacking by combination and encapsulation of multiple instructions. CIA hides harmful prompts within instructions of harmless intentions making it impossible for the model to identify underlying malicious intentions. Furthermore we implement two transformation methods known as T-CIA and W-CIA to automatically disguise harmful instructions as talking or writing tasks making them appear harmless to LLMs. We evaluated CIA on GPT-4 ChatGPT and ChatGLM2 with two safety assessment datasets and two harmful prompt datasets. It achieves an attack success rate of 95+ on safety assessment datasets and 83+ for GPT-4 91+ for ChatGPT (gpt-3.5-turbo backed) and ChatGLM2-6B on harmful prompt datasets. Our approach reveals the vulnerability of LLMs to such compositional instruction attacks that harbor underlying harmful intentions contributing significantly to LLM security development. Warning this paper may contain offensive or upsetting content!
