---
layout: publication
title: 'Feature-aware Malicious Output Detection And Mitigation'
authors: Weilong Dong, Peiguang Li, Yu Tian, Xinyi Zeng, Fengdi Li, Sirui Wang
conference: "Arxiv"
year: 2025
bibkey: dong2025feature
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09191"}
tags: ['Responsible AI', 'Agentic', 'Tools', 'Reinforcement Learning', 'Security']
---
The rapid advancement of large language models (LLMs) has brought significant
benefits to various domains while introducing substantial risks. Despite being
fine-tuned through reinforcement learning, LLMs lack the capability to discern
malicious content, limiting their defense against jailbreak. To address these
safety concerns, we propose a feature-aware method for harmful response
rejection (FMM), which detects the presence of malicious features within the
model's feature space and adaptively adjusts the model's rejection mechanism.
By employing a simple discriminator, we detect potential malicious traits
during the decoding phase. Upon detecting features indicative of toxic tokens,
FMM regenerates the current token. By employing activation patching, an
additional rejection vector is incorporated during the subsequent token
generation, steering the model towards a refusal response. Experimental results
demonstrate the effectiveness of our approach across multiple language models
and diverse attack techniques, while crucially maintaining the models' standard
generation capabilities.
