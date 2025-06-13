---
layout: publication
title: 'Evaluating Large Language Models For Automatic Analysis Of Teacher Simulations'
authors: David De-fitero-dominguez, Mariano Albaladejo-gonzález, Antonio Garcia-cabot, Eva Garcia-lopez, Antonio Moreno-cediel, Erin Barno, Justin Reich
conference: "Arxiv"
year: 2024
bibkey: defiterodominguez2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20360"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Few-Shot', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Prompting']
---
Digital Simulations (DS) provide safe environments where users interact with
an agent through conversational prompts, providing engaging learning
experiences that can be used to train teacher candidates in realistic classroom
scenarios. These simulations usually include open-ended questions, allowing
teacher candidates to express their thoughts but complicating an automatic
response analysis. To address this issue, we have evaluated Large Language
Models (LLMs) to identify characteristics (user behaviors) in the responses of
DS for teacher education. We evaluated the performance of DeBERTaV3 and Llama
3, combined with zero-shot, few-shot, and fine-tuning. Our experiments
discovered a significant variation in the LLMs' performance depending on the
characteristic to identify. Additionally, we noted that DeBERTaV3 significantly
reduced its performance when it had to identify new characteristics. In
contrast, Llama 3 performed better than DeBERTaV3 in detecting new
characteristics and showing more stable performance. Therefore, in DS where
teacher educators need to introduce new characteristics because they change
depending on the simulation or the educational objectives, it is more
recommended to use Llama 3. These results can guide other researchers in
introducing LLMs to provide the highly demanded automatic evaluations in DS.
