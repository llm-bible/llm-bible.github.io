---
layout: publication
title: "SELF-GUIDE: Better Task-specific Instruction Following Via Self-synthetic Finetuning"
authors: Zhao Chenyang, Jia Xueying, Viswanathan Vijay, Wu Tongshuang, Neubig Graham
conference: "Arxiv"
year: 2024
bibkey: zhao2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12874"}
tags: ['Pretraining Methods', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) hold the promise of solving diverse tasks when provided with appropriate natural language prompts. However prompting often leads models to make predictions with lower accuracy compared to finetuning a model with ample training data. On the other hand while finetuning LLMs on task-specific data generally improves their performance abundant annotated datasets are not available for all tasks. Previous work has explored generating task-specific data from state-of-the-art LLMs and using this data to finetune smaller models but this approach requires access to a language model other than the one being trained which introduces cost scalability challenges and legal hurdles associated with continuously relying on more powerful LLMs. In response to these we propose SELF-GUIDE a multi-stage mechanism in which we synthesize task-specific input-output pairs from the student LLM then use these input-output pairs to finetune the student LLM itself. In our empirical evaluation of the Natural Instructions V2 benchmark we find that SELF-GUIDE improves the performance of LLM by a substantial margin. Specifically we report an absolute improvement of approximately 1537; for classification tasks and 1837; for generation tasks in the benchmarks metrics. This sheds light on the promise of self-synthesized data guiding LLMs towards becoming task-specific experts without any external learning signals.
