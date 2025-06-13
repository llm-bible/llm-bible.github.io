---
layout: publication
title: 'Viscoder: Fine-tuning Llms For Executable Python Visualization Code Generation'
authors: Yuansheng Ni, Ping Nie, Kai Zou, Xiang Yue, Wenhu Chen
conference: "Arxiv"
year: 2025
bibkey: ni2025fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.03930'}
tags: ['RAG', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) often struggle with visualization tasks like plotting diagrams, charts, where success depends on both code correctness and visual semantics. Existing instruction-tuning datasets lack execution-grounded supervision and offer limited support for iterative code correction, resulting in fragile and unreliable plot generation. We present VisCode-200K, a large-scale instruction tuning dataset for Python-based visualization and self-correction. It contains over 200K examples from two sources: (1) validated plotting code from open-source repositories, paired with natural language instructions and rendered plots; and (2) 45K multi-turn correction dialogues from Code-Feedback, enabling models to revise faulty code using runtime feedback. We fine-tune Qwen2.5-Coder-Instruct on VisCode-200K to create VisCoder, and evaluate it on PandasPlotBench. VisCoder significantly outperforms strong open-source baselines and approaches the performance of proprietary models like GPT-4o-mini. We further adopt a self-debug evaluation protocol to assess iterative repair, demonstrating the benefits of feedback-driven learning for executable, visually accurate code generation.
