---
layout: publication
title: 'GC-KBVQA: A New Four-stage Framework For Enhancing Knowledge Based Visual Question Answering Performance'
authors: Mohammad Mahdi Moradi, Sudhir Mudur
conference: "Arxiv"
year: 2025
bibkey: moradi2025gc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19354"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Knowledge-Based Visual Question Answering (KB-VQA) methods focus on tasks that demand reasoning with information extending beyond the explicit content depicted in the image. Early methods relied on explicit knowledge bases to provide this auxiliary information. Recent approaches leverage Large Language Models (LLMs) as implicit knowledge sources. While KB-VQA methods have demonstrated promising results, their potential remains constrained as the auxiliary text provided may not be relevant to the question context, and may also include irrelevant information that could misguide the answer predictor. We introduce a novel four-stage framework called Grounding Caption-Guided Knowledge-Based Visual Question Answering (GC-KBVQA), which enables LLMs to effectively perform zero-shot VQA tasks without the need for end-to-end multimodal training. Innovations include grounding question-aware caption generation to move beyond generic descriptions and have compact, yet detailed and context-rich information. This is combined with knowledge from external sources to create highly informative prompts for the LLM. GC-KBVQA can address a variety of VQA tasks, and does not require task-specific fine-tuning, thus reducing both costs and deployment complexity by leveraging general-purpose, pre-trained LLMs. Comparison with competing KB-VQA methods shows significantly improved performance. Our code will be made public.
