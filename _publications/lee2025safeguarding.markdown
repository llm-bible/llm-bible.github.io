---
layout: publication
title: 'Safeguarding Mobile GUI Agent Via Logic-based Action Verification'
authors: Jungjae Lee, Dongjae Lee, Chihun Choi, Youngmin Im, Jaeyoung Wi, Kihong Heo, Sangeun Oh, Sunjae Lee, Insik Shin
conference: "Arxiv"
year: 2025
bibkey: lee2025safeguarding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18492"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Large Foundation Models (LFMs) have unlocked new possibilities in
human-computer interaction, particularly with the rise of mobile Graphical User
Interface (GUI) Agents capable of interpreting GUIs. These agents promise to
revolutionize mobile computing by allowing users to automate complex mobile
tasks through simple natural language instructions. However, the inherent
probabilistic nature of LFMs, coupled with the ambiguity and context-dependence
of mobile tasks, makes LFM-based automation unreliable and prone to errors. To
address this critical challenge, we introduce VeriSafe Agent (VSA): a formal
verification system that serves as a logically grounded safeguard for Mobile
GUI Agents. VSA is designed to deterministically ensure that an agent's actions
strictly align with user intent before conducting an action. At its core, VSA
introduces a novel autoformalization technique that translates natural language
user instructions into a formally verifiable specification, expressed in our
domain-specific language (DSL). This enables runtime, rule-based verification,
allowing VSA to detect and prevent erroneous actions executing an action,
either by providing corrective feedback or halting unsafe behavior. To the best
of our knowledge, VSA is the first attempt to bring the rigor of formal
verification to GUI agent. effectively bridging the gap between LFM-driven
automation and formal software verification. We implement VSA using
off-the-shelf LLM services (GPT-4o) and evaluate its performance on 300 user
instructions across 18 widely used mobile apps. The results demonstrate that
VSA achieves 94.3%-98.33% accuracy in verifying agent actions, representing a
significant 20.4%-25.6% improvement over existing LLM-based verification
methods, and consequently increases the GUI agent's task completion rate by
90%-130%.
