---
layout: publication
title: Jatmo&#58; Prompt Injection Defense By Task-specific Finetuning
authors: Piet Julien, Alrashed Maha, Sitawarin Chawin, Chen Sizhe, Wei Zeming, Sun Elizabeth, Alomair Basel, Wagner David
conference: "Arxiv"
year: 2023
bibkey: piet2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17673"}
  - {name: "Code", url: "https://github.com/wagner-group/prompt-injection-defense"}
tags: ['Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Security']
---
Large Language Models (LLMs) are attracting significant research attention due to their instruction-following abilities allowing users and developers to leverage LLMs for a variety of tasks. However LLMs are vulnerable to prompt-injection attacks a class of attacks that hijack the models instruction-following abilities changing responses to prompts to undesired possibly malicious ones. In this work we introduce Jatmo a method for generating task-specific models resilient to prompt-injection attacks. Jatmo leverages the fact that LLMs can only follow instructions once they have undergone instruction tuning. It harnesses a teacher instruction-tuned model to generate a task-specific dataset which is then used to fine-tune a base model (i.e. a non-instruction-tuned model). Jatmo only needs a task prompt and a dataset of inputs for the task it uses the teacher model to generate outputs. For situations with no pre-existing datasets Jatmo can use a single example or in some cases none at all to produce a fully synthetic dataset. Our experiments on seven tasks show that Jatmo models provide similar quality of outputs on their specific task as standard LLMs while being resilient to prompt injections. The best attacks succeeded in less than 0.537; of cases against our models versus 8737; success rate against GPT-3.5-Turbo. We release Jatmo at https://github.com/wagner-group/prompt-injection-defense."
