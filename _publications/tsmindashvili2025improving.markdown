---
layout: publication
title: 'Improving LLM Outputs Against Jailbreak Attacks With Expert Model Integration'
authors: Tatia Tsmindashvili, Ana Kolkhidashvili, Dachi Kurtskhalia, Nino Maghlakelidze, Elene Mekvabishvili, Guram Dentoshvili, Orkhan Shamilov, Zaal Gachechiladze, Steven Saporta, David Dachi Choladze
conference: "Arxiv"
year: 2025
bibkey: tsmindashvili2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17066"}
tags: ['Fine-Tuning', 'Tools', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Using LLMs in a production environment presents security challenges that include vulnerabilities to jailbreaks and prompt injections, which can result in harmful outputs for humans or the enterprise. The challenge is amplified when working within a specific domain, as topics generally accepted for LLMs to address may be irrelevant to that field. These problems can be mitigated, for example, by fine-tuning large language models with domain-specific and security-focused data. However, these alone are insufficient, as jailbreak techniques evolve. Additionally, API-accessed models do not offer the flexibility needed to tailor behavior to industry-specific objectives, and in-context learning is not always sufficient or reliable. In response to these challenges, we introduce Archias, an expert model adept at distinguishing between in-domain and out-of-domain communications. Archias classifies user inquiries into several categories: in-domain (specifically for the automotive industry), malicious questions, price injections, prompt injections, and out-of-domain examples. Our methodology integrates outputs from the expert model (Archias) into prompts, which are then processed by the LLM to generate responses. This method increases the model's ability to understand the user's intention and give appropriate answers. Archias can be adjusted, fine-tuned, and used for many different purposes due to its small size. Therefore, it can be easily customized to the needs of any industry. To validate our approach, we created a benchmark dataset for the automotive industry. Furthermore, in the interest of advancing research and development, we release our benchmark dataset to the community.
