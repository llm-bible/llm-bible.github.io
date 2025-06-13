---
layout: publication
title: 'Can Language Models Follow Multiple Turns Of Entangled Instructions?'
authors: Chi Han
conference: "Arxiv"
year: 2025
bibkey: han2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13222'}
tags: ['Attention Mechanism', 'GPT', 'Reinforcement Learning', 'Model Architecture']
---
Despite significant achievements in improving the instruction-following
capabilities of large language models (LLMs), the ability to process multiple
potentially entangled or conflicting instructions remains a considerable
challenge. Real-world scenarios often require consistency across multiple
instructions over time, such as secret privacy, personal preferences, and
prioritization, which demand sophisticated abilities to integrate multiple
turns and carefully balance competing objectives when instructions intersect or
conflict. This work presents a systematic investigation of LLMs' capabilities
in handling multiple turns of instructions, covering three levels of
difficulty: (1) retrieving information from instructions, (2) tracking and
reasoning across turns, and (3) resolving conflicts among instructions. We
construct MultiTurnInstruct with around 1.1K high-quality multi-turn
conversations through the human-in-the-loop approach and result in nine
capability categories, including statics and dynamics, reasoning, and
multitasking. Our finding reveals an intriguing trade-off between different
capabilities. While GPT models demonstrate superior memorization, they show
reduced effectiveness in privacy-protection tasks requiring selective
information withholding. Larger models exhibit stronger reasoning capabilities
but still struggle with resolving conflicting instructions. Importantly, these
performance gaps cannot be attributed solely to information loss, as models
demonstrate strong BLEU scores on memorization tasks but their attention
mechanisms fail to integrate multiple related instructions effectively. These
findings highlight critical areas for improvement in complex real-world tasks
involving multi-turn instructions.
