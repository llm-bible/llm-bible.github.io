---
layout: publication
title: 'VL-ICL Bench: The Devil In The Details Of Multimodal In-context Learning'
authors: Yongshuo Zong, Ondrej Bohdal, Timothy Hospedales
conference: "Arxiv"
year: 2024
bibkey: zong2024vl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13164"}
  - {name: "Code", url: "https://github.com/ys-zong/VL-ICL"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Has Code', 'Few-Shot', 'Multimodal Models', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) famously exhibit emergent in-context learning
(ICL) -- the ability to rapidly adapt to new tasks using few-shot examples
provided as a prompt, without updating the model's weights. Built on top of
LLMs, vision large language models (VLLMs) have advanced significantly in areas
such as recognition, reasoning, and grounding. However, investigations into
*multimodal ICL* have predominantly focused on few-shot visual question
answering (VQA), and image captioning, which we will show neither exploit the
strengths of ICL, nor test its limitations. The broader capabilities and
limitations of multimodal ICL remain under-explored. In this study, we
introduce a comprehensive benchmark VL-ICL Bench for multimodal in-context
learning, encompassing a broad spectrum of tasks that involve both images and
text as inputs and outputs, and different types of challenges, from \{perception
to reasoning and long context length\}. We evaluate the abilities of
state-of-the-art VLLMs against this benchmark suite, revealing their diverse
strengths and weaknesses, and showing that even the most advanced models, such
as GPT-4, find the tasks challenging. By highlighting a range of new ICL tasks,
and the associated strengths and limitations of existing models, we hope that
our dataset will inspire future work on enhancing the in-context learning
capabilities of VLLMs, as well as inspire new applications that leverage VLLM
ICL. The code and dataset are available at https://github.com/ys-zong/VL-ICL.
