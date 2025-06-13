---
layout: publication
title: 'Visually Guided Decoding: Gradient-free Hard Prompt Inversion With Language Models'
authors: Donghoon Kim, Minji Bae, Kyuhong Shim, Byonghyo Shim
conference: "Arxiv"
year: 2025
bibkey: kim2025visually
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.08622"}
tags: ['Applications', 'Interpretability and Explainability', 'RAG', 'Language Modeling', 'Merging', 'Training Techniques', 'Prompting']
---
Text-to-image generative models like DALL-E and Stable Diffusion have revolutionized visual content creation across various applications, including advertising, personalized media, and design prototyping. However, crafting effective textual prompts to guide these models remains challenging, often requiring extensive trial and error. Existing prompt inversion approaches, such as soft and hard prompt techniques, are not so effective due to the limited interpretability and incoherent prompt generation. To address these issues, we propose Visually Guided Decoding (VGD), a gradient-free approach that leverages large language models (LLMs) and CLIP-based guidance to generate coherent and semantically aligned prompts. In essence, VGD utilizes the robust text generation capabilities of LLMs to produce human-readable prompts. Further, by employing CLIP scores to ensure alignment with user-specified visual concepts, VGD enhances the interpretability, generalization, and flexibility of prompt generation without the need for additional training. Our experiments demonstrate that VGD outperforms existing prompt inversion techniques in generating understandable and contextually relevant prompts, facilitating more intuitive and controllable interactions with text-to-image models.
