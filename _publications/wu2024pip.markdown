---
layout: publication
title: 'PIP-MM: Pre-integrating Prompt Information Into Visual Encoding Via Existing MLLM Structures'
authors: Tianxiang Wu, Minxin Nie, Ziqiang Cao
conference: "Arxiv"
year: 2024
bibkey: wu2024pip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23089"}
tags: ['Prompting', 'Multimodal Models', 'Tools', 'Reinforcement Learning']
---
The Multimodal Large Language Models (MLLMs) have activated the
capabilitiesof Large Language Models (LLMs) in solving visual-language tasks by
integratingvisual information. The prevailing approach in existing MLLMs
involvesemploying an image encoder to extract visual features, converting
thesefeatures into visual tokens via an adapter, and then integrating them with
theprompt into the LLM. However, because the process of image encoding
isprompt-agnostic, the extracted visual features only provide a
coarsedescription of the image, impossible to focus on the requirements of
theprompt. On one hand, it is easy for image features to lack information
aboutthe prompt-specified objects, resulting in unsatisfactory responses. On
theother hand, the visual features contain a large amount of
irrelevantinformation, which not only increases the burden on memory but also
worsens thegeneration effectiveness. To address the aforementioned issues, we
propose\textbf\{PIP-MM\}, a framework that
\textbf\{P\}re-\textbf\{I\}ntegrates\textbf\{P\}rompt information into the visual
encoding process using existingmodules of MLLMs. Specifically, We utilize the
frozen LLM in the MLLM tovectorize the input prompt, which summarizes the
requirements of the prompt.Then, we input the prompt vector into our trained
Multi-Layer Perceptron (MLP)to align with the visual input requirements, and
subsequently replace the classembedding in the image encoder. Since our model
only requires adding atrainable MLP, it can be applied to any MLLM. To validate
the effectiveness ofPIP-MM, we conducted experiments on multiple benchmarks.
Automated evaluationmetrics and manual assessments demonstrate the strong
performance of PIP-MM.Particularly noteworthy is that our model maintains
excellent generationresults even when half of the visual tokens are reduced.
