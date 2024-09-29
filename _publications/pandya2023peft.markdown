---
layout: publication
title: Peft45;medaware Large Language Model For Medical Awareness
authors: Pandya Keivalya
conference: "Arxiv"
year: 2023
bibkey: pandya2023peft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10697"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Chat models are capable of answering a wide range of questions however the accuracy of their responses is highly uncertain. In this research we propose a specialized PEFT45;MedAware model where we utilize parameter45;efficient fine45;tuning (PEFT) to enhance the Falcon45;1b large language model on specialized MedQuAD data consisting of 16407 medical QA pairs leveraging only 0.4437; of its trainable parameters to enhance computational efficiency. The paper adopts data preprocessing and PEFT to optimize model performance complemented by a BitsAndBytesConfig for efficient transformer training. The resulting model was capable of outperforming other LLMs in medical question45;answering tasks in specific domains with greater accuracy utilizing limited computational resources making it suitable for deployment in resource45;constrained environments. We propose further improvements through expanded datasets larger models and feedback mechanisms for sustained medical relevancy. Our work highlights the efficiency gains and specialized capabilities of PEFT in medical AI outpacing standard models in precision without extensive resource demands. The proposed model and data are released for research purposes only.
