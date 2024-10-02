---
layout: publication
title: 'AST-T5: Structure-aware Pretraining For Code Generation And Understanding'
authors: Gong Linyuan, Elhoushi Mostafa, Cheung Alvin
conference: "Arxiv"
year: 2024
bibkey: gong2024ast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.03003"}
  - {name: "Code", url: "https://github.com/gonglinyuan/ast_t5"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
'Large language models (LLMs) have made significant advancements in code-related tasks, yet many LLMs treat code as simple sequences, neglecting its structured nature. We introduce AST-T5, a novel pretraining paradigm that leverages the Abstract Syntax Tree (AST) for enhanced code generation, transpilation, and understanding. Using dynamic programming, our AST-Aware Segmentation retains code structure, while our AST-Aware Span Corruption objective equips the model to reconstruct various code structures. Unlike other models, AST-T5 avoids intricate program analyses or architectural changes, so it integrates seamlessly with any encoder-decoder Transformer. Evaluations show that AST-T5 consistently outperforms similar-sized LMs across various code-related tasks. Structure-awareness makes AST-T5 particularly powerful in code-to-code tasks, surpassing CodeT5 by 2 points in exact match score for the Bugs2Fix task and by 3 points in exact match score for Java-C\# Transpilation in CodeXGLUE. Our code and model are publicly available at https://github.com/gonglinyuan/ast\_t5.'
