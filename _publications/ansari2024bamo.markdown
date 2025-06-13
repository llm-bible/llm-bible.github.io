---
layout: publication
title: 'BAMO At Semeval-2024 Task 9: BRAINTEASER: A Novel Task Defying Common Sense'
authors: Baktash Ansari, Mohammadmostafa Rostamkhani, Sauleh Eetemadi
conference: "Arxiv"
year: 2024
bibkey: ansari2024bamo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04947"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'BERT', 'Prompting']
---
This paper outlines our approach to SemEval 2024 Task 9, BRAINTEASER: A Novel
Task Defying Common Sense. The task aims to evaluate the ability of language
models to think creatively. The dataset comprises multi-choice questions that
challenge models to think "outside of the box". We fine-tune 2 models, BERT and
RoBERTa Large. Next, we employ a Chain of Thought (CoT) zero-shot prompting
approach with 6 large language models, such as GPT-3.5, Mixtral, and Llama2.
Finally, we utilize ReConcile, a technique that employs a "round table
conference" approach with multiple agents for zero-shot learning, to generate
consensus answers among 3 selected language models. Our best method achieves an
overall accuracy of 85 percent on the sentence puzzles subtask.
