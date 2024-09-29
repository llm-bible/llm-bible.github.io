---
layout: publication
title: "Unirag: Universal Retrieval Augmentation For Multi-modal Large Language Models"
authors: Sharifymoghaddam Sahel, Upadhyay Shivani, Chen Wenhu, Lin Jimmy
conference: "Arxiv"
year: 2024
bibkey: sharifymoghaddam2024universal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10311"}
tags: ['Applications', 'Few Shot', 'GPT', 'Model Architecture', 'Prompting', 'RAG']
---
Recently Multi-Modal(MM) Large Language Models(LLMs) have unlocked many complex use-cases that require MM understanding (e.g. image captioning or visual question answering) and MM generation (e.g. text-guided image generation or editing) capabilities. To further improve the output fidelity of MM-LLMs we introduce the model-agnostic UniRAG technique that adds relevant retrieved information to prompts as few-shot examples during inference. Unlike the common belief that Retrieval Augmentation (RA) mainly improves generation or understanding of uncommon entities our evaluation results on the MSCOCO dataset with common entities show that both proprietary models like GPT4 and Gemini-Pro and smaller open-source models like Llava LaVIT and Emu2 significantly enhance their generation quality when their input prompts are augmented with relevant information retrieved by MM retrievers like UniIR models.
