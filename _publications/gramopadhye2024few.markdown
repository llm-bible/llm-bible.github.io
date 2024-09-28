---
layout: publication
title: Few shot chain-of-thought driven reasoning to prompt LLMs for open ended medical question answering
authors: Gramopadhye Ojas, Nachane Saeel Sandeep, Chanda Prateek, Ramakrishnan Ganesh, Jadhav Kshitij Sharad, Nandwani Yatin, Raghu Dinesh, Joshi Sachindra
conference: "Arxiv"
year: 2024
bibkey: gramopadhye2024few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04890"}
tags: ['ARXIV', 'Applications', 'LLM', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language models (LLMs) have demonstrated significant potential in transforming healthcare by automating tasks such as clinical documentation information retrieval and decision support. In this aspect carefully engineered prompts have emerged as a powerful tool for using LLMs for medical scenarios e.g. patient clinical scenarios. In this paper we propose a modified version of the MedQA-USMLE dataset which is subjective to mimic real-life clinical scenarios. We explore the Chain of Thought (CoT) reasoning based on subjective response generation for the modified MedQA-USMLE dataset with appropriate LM-driven forward reasoning for correct responses to the medical questions. Keeping in mind the importance of response verification in the medical setting we utilize a reward training mechanism whereby the language model also provides an appropriate verified response for a particular response to a clinical question. In this regard we also include human-in-the-loop for different evaluation aspects. We develop better in-contrast learning strategies by modifying the 5-shot-codex-CoT-prompt from arXiv2207.08143 for the subjective MedQA dataset and developing our incremental-reasoning prompt. Our evaluations show that the incremental reasoning prompt performs better than the modified codex prompt in certain scenarios. We also show that greedy decoding with the incremental reasoning method performs better than other strategies such as prompt chaining and eliminative reasoning.
