---
layout: publication
title: 'A Thousand Words Or An Image: Studying The Influence Of Persona Modality In Multimodal Llms'
authors: Julius Broomfield, Kartik Sharma, Srijan Kumar
conference: "Arxiv"
year: 2025
bibkey: broomfield2025thousand
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20504"}
  - {name: "Code", url: "https://github.com/claws-lab/persona-modality"}
tags: ['Agentic', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'Has Code']
---
Large language models (LLMs) have recently demonstrated remarkable
advancements in embodying diverse personas, enhancing their effectiveness as
conversational agents and virtual assistants. Consequently, LLMs have made
significant strides in processing and integrating multimodal information.
However, even though human personas can be expressed in both text and image,
the extent to which the modality of a persona impacts the embodiment by the LLM
remains largely unexplored. In this paper, we investigate how do different
modalities influence the expressiveness of personas in multimodal LLMs. To this
end, we create a novel modality-parallel dataset of 40 diverse personas varying
in age, gender, occupation, and location. This consists of four modalities to
equivalently represent a persona: image-only, text-only, a combination of image
and small text, and typographical images, where text is visually stylized to
convey persona-related attributes. We then create a systematic evaluation
framework with 60 questions and corresponding metrics to assess how well LLMs
embody each persona across its attributes and scenarios. Comprehensive
experiments on \\(5\\) multimodal LLMs show that personas represented by detailed
text show more linguistic habits, while typographical images often show more
consistency with the persona. Our results reveal that LLMs often overlook
persona-specific details conveyed through images, highlighting underlying
limitations and paving the way for future research to bridge this gap. We
release the data and code at https://github.com/claws-lab/persona-modality .
