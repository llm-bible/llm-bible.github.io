---
layout: publication
title: 'Interactive Prompt Debugging With Sequence Salience'
authors: Ian Tenney, Ryan Mullins, Bin Du, Shree Pandya, Minsuk Kahng, Lucas Dixon
conference: "Arxiv"
year: 2024
bibkey: tenney2024interactive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.07498'}
  - {name: "Code", url: 'http://goo.gle/sequence-salience'}
tags: ['Has Code', 'Interpretability and Explainability', 'Few-Shot', 'RAG', 'Tools', 'Prompting', 'Reinforcement Learning']
---
We present Sequence Salience, a visual tool for interactive prompt debugging
with input salience methods. Sequence Salience builds on widely used salience
methods for text classification and single-token prediction, and extends this
to a system tailored for debugging complex LLM prompts. Our system is
well-suited for long texts, and expands on previous work by 1) providing
controllable aggregation of token-level salience to the word, sentence, or
paragraph level, making salience over long inputs tractable; and 2) supporting
rapid iteration where practitioners can act on salience results, refine
prompts, and run salience on the new output. We include case studies showing
how Sequence Salience can help practitioners work with several complex
prompting strategies, including few-shot, chain-of-thought, and constitutional
principles. Sequence Salience is built on the Learning Interpretability Tool,
an open-source platform for ML model visualizations, and code, notebooks, and
tutorials are available at http://goo.gle/sequence-salience.
