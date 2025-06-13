---
layout: publication
title: 'Spearbot: Leveraging Large Language Models In A Generative-critique Framework For Spear-phishing Email Generation'
authors: Qinglin Qi, Yun Luo, Yijia Xu, Wenbo Guo, Yong Fang
conference: "Arxiv"
year: 2024
bibkey: qi2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11109"}
tags: ['Tools', 'RAG', 'Reinforcement Learning', 'Security', 'Prompting']
---
Large Language Models (LLMs) are increasingly capable, aiding in tasks such
as content generation, yet they also pose risks, particularly in generating
harmful spear-phishing emails. These emails, crafted to entice clicks on
malicious URLs, threaten personal information security. This paper proposes an
adversarial framework, SpearBot, which utilizes LLMs to generate spear-phishing
emails with various phishing strategies. Through specifically crafted jailbreak
prompts, SpearBot circumvents security policies and introduces other LLM
instances as critics. When a phishing email is identified by the critic,
SpearBot refines the generated email based on the critique feedback until it
can no longer be recognized as phishing, thereby enhancing its deceptive
quality. To evaluate the effectiveness of SpearBot, we implement various
machine-based defenders and assess how well the phishing emails generated could
deceive them. Results show these emails often evade detection to a large
extent, underscoring their deceptive quality. Additionally, human evaluations
of the emails' readability and deception are conducted through questionnaires,
confirming their convincing nature and the significant potential harm of the
generated phishing emails.
