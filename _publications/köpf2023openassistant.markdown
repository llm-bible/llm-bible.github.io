---
layout: publication
title: OpenAssistant Conversations -- Democratizing Large Language Model Alignment
authors: Köpf Andreas, Kilcher Yannic, Von Rütte Dimitri, Anagnostidis Sotiris, Tam Zhi-rui, Stevens Keith, Barhoum Abdullah, Duc Nguyen Minh, Stanley Oliver, Nagyfi Richárd, Es Shahul, Suri Sameer, Glushkov David, Dantuluri Arnav, Maguire Andrew, Schuhmann Christoph, Nguyen Huu, Mattick Alexander
conference: "Arxiv"
year: 2023
bibkey: köpf2023openassistant
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.07327"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Aligning large language models (LLMs) with human preferences has proven to drastically improve usability and has driven rapid adoption as demonstrated by ChatGPT. Alignment techniques such as supervised fine-tuning (SFT) and reinforcement learning from human feedback (RLHF) greatly reduce the required skill and domain knowledge to effectively harness the capabilities of LLMs increasing their accessibility and utility across various domains. However state-of-the-art alignment techniques like RLHF rely on high-quality human feedback data which is expensive to create and often remains proprietary. In an effort to democratize research on large-scale alignment we release OpenAssistant Conversations a human-generated human-annotated assistant-style conversation corpus consisting of 161443 messages in 35 different languages annotated with 461292 quality ratings resulting in over 10000 complete and fully annotated conversation trees. The corpus is a product of a worldwide crowd-sourcing effort involving over 13500 volunteers. Models trained on OpenAssistant Conversations show consistent improvements on standard benchmarks over respective base models. We release our code and data under a fully permissive licence.
