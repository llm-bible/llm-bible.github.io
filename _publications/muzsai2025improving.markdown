---
layout: publication
title: 'Improving LLM Agents With Reinforcement Learning On Cryptographic CTF Challenges'
authors: Lajos Muzsai, David Imolai, András Lukács
conference: "Arxiv"
year: 2025
bibkey: muzsai2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02048"}
tags: ['Agentic', 'Tools', 'Applications', 'Reinforcement Learning', 'Security', 'Prompting']
---
Large Language Models (LLMs) still struggle with the structured reasoning and tool-assisted computation needed for problem solving in cybersecurity applications. In this work, we introduce "random-crypto", a cryptographic Capture-the-Flag (CTF) challenge generator framework that we use to fine-tune a tool-augmented Llama-3.1-8B with Guided Reinforcement Prompt Optimisation (GRPO), allowing the agent to iteratively write and execute Python inside an isolated REPL. GRPO yields a +53% absolute jump in Pass@8 on unseen "random-crypto" tasks (0.35 -> 0.88) and raises Majority@8 to 0.41. The fine-tuned agent also generalizes to an external dataset. On a subset of picoCTF cryptography problems, it improves Pass@8 by +13 pp. Ablations show the gains stem from more reliable tool invocation and code synthesis, rather than superficial prompt adaptation.
