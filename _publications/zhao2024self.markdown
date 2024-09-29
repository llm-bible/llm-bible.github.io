---
layout: publication
title: SELF45;GUIDE Better Task45;specific Instruction Following Via Self45;synthetic Finetuning
authors: Zhao Chenyang, Jia Xueying, Viswanathan Vijay, Wu Tongshuang, Neubig Graham
conference: "Arxiv"
year: 2024
bibkey: zhao2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12874"}
tags: ['Pretraining Methods', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) hold the promise of solving diverse tasks when provided with appropriate natural language prompts. However prompting often leads models to make predictions with lower accuracy compared to finetuning a model with ample training data. On the other hand while finetuning LLMs on task45;specific data generally improves their performance abundant annotated datasets are not available for all tasks. Previous work has explored generating task45;specific data from state45;of45;the45;art LLMs and using this data to finetune smaller models but this approach requires access to a language model other than the one being trained which introduces cost scalability challenges and legal hurdles associated with continuously relying on more powerful LLMs. In response to these we propose SELF45;GUIDE a multi45;stage mechanism in which we synthesize task45;specific input45;output pairs from the student LLM then use these input45;output pairs to finetune the student LLM itself. In our empirical evaluation of the Natural Instructions V2 benchmark we find that SELF45;GUIDE improves the performance of LLM by a substantial margin. Specifically we report an absolute improvement of approximately 1537; for classification tasks and 1837; for generation tasks in the benchmarks metrics. This sheds light on the promise of self45;synthesized data guiding LLMs towards becoming task45;specific experts without any external learning signals.
