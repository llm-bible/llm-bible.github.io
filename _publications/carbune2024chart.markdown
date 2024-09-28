---
layout: publication
title: Chart-based Reasoning Transferring Capabilities from LLMs to VLMs
authors: Carbune Victor, Mansoor Hassan, Liu Fangyu, Aralikatte Rahul, Baechler Gilles, Chen Jindong, Sharma Abhanshu
conference: "Arxiv"
year: 2024
bibkey: carbune2024chart
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12596"}
tags: ['ARXIV', 'GPT', 'Multimodal Models', 'Prompt', 'Tools', 'Vision Language']
---
Vision-language models (VLMs) are achieving increasingly strong performance on multimodal tasks. However reasoning capabilities remain limited particularly for smaller VLMs while those of large-language models (LLMs) have seen numerous improvements. We propose a technique to transfer capabilities from LLMs to VLMs. On the recently introduced ChartQA our method obtains state-of-the-art performance when applied on the PaLI3-5B VLM by while also enabling much better performance on PlotQA and FigureQA. We first improve the chart representation by continuing the pre-training stage using an improved version of the chart-to-table translation task by . We then propose constructing a 20x larger dataset than the original training set. To improve general reasoning capabilities and improve numerical operations we synthesize reasoning traces using the table representation of charts. Lastly our model is fine-tuned using the multitask loss introduced by . Our variant ChartPaLI-5B outperforms even 10x larger models such as PaLIX-55B without using an upstream OCR system while keeping inference time constant compared to the PaLI3-5B baseline. When rationales are further refined with a simple program-of-thought prompt our model outperforms the recently introduced Gemini Ultra and GPT-4V.
