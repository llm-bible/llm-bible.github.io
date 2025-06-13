---
layout: publication
title: 'Ghostprompt: Jailbreaking Text-to-image Generative Models Based On Dynamic Optimization'
authors: Zixuan Chen, Hao Lin, Ke Xu, Xinghao Jiang, Tanfeng Sun
conference: "Arxiv"
year: 2025
bibkey: chen2025jailbreaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18979"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting']
---
Text-to-image (T2I) generation models can inadvertently produce not-safe-for-work (NSFW) content, prompting the integration of text and image safety filters. Recent advances employ large language models (LLMs) for semantic-level detection, rendering traditional token-level perturbation attacks largely ineffective. However, our evaluation shows that existing jailbreak methods are ineffective against these modern filters. We introduce GhostPrompt, the first automated jailbreak framework that combines dynamic prompt optimization with multimodal feedback. It consists of two key components: (i) Dynamic Optimization, an iterative process that guides a large language model (LLM) using feedback from text safety filters and CLIP similarity scores to generate semantically aligned adversarial prompts; and (ii) Adaptive Safety Indicator Injection, which formulates the injection of benign visual cues as a reinforcement learning problem to bypass image-level filters. GhostPrompt achieves state-of-the-art performance, increasing the ShieldLM-7B bypass rate from 12.5% (Sneakyprompt) to 99.0%, improving CLIP score from 0.2637 to 0.2762, and reducing the time cost by \\(4.2 \times\\). Moreover, it generalizes to unseen filters including GPT-4.1 and successfully jailbreaks DALLE 3 to generate NSFW images in our evaluation, revealing systemic vulnerabilities in current multimodal defenses. To support further research on AI safety and red-teaming, we will release code and adversarial prompts under a controlled-access protocol.
