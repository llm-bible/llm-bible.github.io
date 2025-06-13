---
layout: publication
title: 'Pointt2i: Llm-based Text-to-image Generation Via Keypoints'
authors: Taekyung Lee, Donggyu Lee, Myungjoo Kang
conference: "Arxiv"
year: 2025
bibkey: lee2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01370"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Text-to-image (T2I) generation model has made significant advancements, resulting in high-quality images aligned with an input prompt. However, despite T2I generation's ability to generate fine-grained images, it still faces challenges in accurately generating images when the input prompt contains complex concepts, especially human pose. In this paper, we propose PointT2I, a framework that effectively generates images that accurately correspond to the human pose described in the prompt by using a large language model (LLM). PointT2I consists of three components: Keypoint generation, Image generation, and Feedback system. The keypoint generation uses an LLM to directly generate keypoints corresponding to a human pose, solely based on the input prompt, without external references. Subsequently, the image generation produces images based on both the text prompt and the generated keypoints to accurately reflect the target pose. To refine the outputs of the preceding stages, we incorporate an LLM-based feedback system that assesses the semantic consistency between the generated contents and the given prompts. Our framework is the first approach to leveraging LLM for keypoints-guided image generation without any fine-tuning, producing accurate pose-aligned images based solely on textual prompts.
