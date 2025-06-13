---
layout: publication
title: 'Enhancing Knowledge Distillation For Llms With Response-priming Prompting'
authors: Vijay Goyal, Mustafa Khan, Aprameya Tirupati, Harveer Saini, Michael Lam, Kevin Zhu
conference: "Arxiv"
year: 2024
bibkey: goyal2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.17846"}
  - {name: "Code", url: "https://github.com/alonso130r/knowledge-distillation"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Attention Mechanism', 'Has Code', 'Prompting', 'Distillation']
---
Large language models (LLMs) have demonstrated remarkable performance across
a wide range of natural language processing (NLP) tasks. However, these models
are often difficult to deploy due to significant computational requirements and
resource constraints. Knowledge distillation (KD) is an effective technique for
transferring the performance of larger LLMs to smaller models. Traditional KD
methods primarily focus on the direct output of the teacher model, with little
emphasis on the role of prompting during knowledge transfer. In this paper, we
propose a set of novel response-priming prompting strategies applied in the
knowledge distillation pipeline to enhance the performance of student models.
Our approach fine-tunes a smaller Llama 3.1 8B Instruct model by distilling
knowledge from a quantized Llama 3.1 405B Instruct teacher model. We apply LoRA
optimization and evaluate on the GSM8K benchmark. Experimental results
demonstrate that integrating reasoning-eliciting prompting into the proposed KD
pipeline significantly improves student model performance, offering an
efficient way to deploy powerful models in resource-constrained environments.
We find that Ground Truth prompting results in a 55% performance increase on
GSM8K for a distilled Llama 3.1 8B Instruct compared to the same model
distilled without prompting. A thorough investigation into the self-attention
layers of the student models indicates that the more successful prompted models
tend to exhibit certain positive behaviors inside their attention heads which
can be tied to their increased accuracy. Our implementation can be found at
https://github.com/alonso130r/knowledge-distillation.
