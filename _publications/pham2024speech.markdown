---
layout: publication
title: 'Silvar: Speech Driven Multimodal Model For Reasoning Visual Question Answering And Object Localization'
authors: Tan-hanh Pham, Hoang-nam Le, Phu-vinh Nguyen, Chris Ngo, Truong-son Hy
conference: "Arxiv"
year: 2024
bibkey: pham2024speech
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.16771'}
tags: ['Prompting', 'Multimodal Models', 'Applications']
---
Visual Language Models have demonstrated remarkable capabilities across
tasks, including visual question answering and image captioning. However, most
models rely on text-based instructions, limiting their effectiveness in
human-machine interactions. Moreover, the quality of language models depends on
reasoning and prompting techniques, such as COT, which remain underexplored
when using speech instructions. To address these challenges, we propose SilVar,
a novel end-to-end multimodal model that uses speech instructions for reasoning
in visual question answering. In addition, we investigate reasoning techniques
with levels including conversational, simple, and complex speech instruction.
SilVar is built upon CLIP, Whisper, and LLaMA 3.1-8B, enabling intuitive
interactions by allowing users to provide verbal or text instructions. To this
end, we introduce a dataset designed to challenge models with speech-based
reasoning tasks for object localization. This dataset enhances the model
ability to process and explain visual scenes from spoken input, moving beyond
object recognition to reasoning-based interactions. The experiments show that
SilVar achieves SOTA performance on the MMMU and ScienceQA benchmarks despite
the challenge of speech-based instructions. We believe SilVar will inspire
next-generation multimodal reasoning models, toward expert artificial general
intelligence. Our code and dataset are available here.
