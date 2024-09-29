---
layout: publication
title: Question-instructed Visual Descriptions For Zero-shot Video Question Answering
authors: Romero David, Solorio Thamar
conference: "Arxiv"
year: 2024
bibkey: romero2024question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10698"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Tools']
---
We present Q-ViD a simple approach for video question answering (video QA) that unlike prior methods which are based on complex architectures computationally expensive pipelines or use closed models like GPTs Q-ViD relies on a single instruction-aware open vision-language model (InstructBLIP) to tackle videoQA using frame descriptions. Specifically we create captioning instruction prompts that rely on the target questions about the videos and leverage InstructBLIP to obtain video frame captions that are useful to the task at hand. Subsequently we form descriptions of the whole video using the question-dependent frame captions and feed that information along with a question-answering prompt to a large language model (LLM). The LLM is our reasoning module and performs the final step of multiple-choice QA. Our simple Q-ViD framework achieves competitive or even higher performances than current state of the art models on a diverse range of videoQA benchmarks including NExT-QA STAR How2QA TVQA and IntentQA.
