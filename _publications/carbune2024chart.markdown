---
layout: publication
title: Chart45;based Reasoning Transferring Capabilities From Llms To Vlms
authors: Carbune Victor, Mansoor Hassan, Liu Fangyu, Aralikatte Rahul, Baechler Gilles, Chen Jindong, Sharma Abhanshu
conference: "Arxiv"
year: 2024
bibkey: carbune2024chart
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12596"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Vision45;language models (VLMs) are achieving increasingly strong performance on multimodal tasks. However reasoning capabilities remain limited particularly for smaller VLMs while those of large45;language models (LLMs) have seen numerous improvements. We propose a technique to transfer capabilities from LLMs to VLMs. On the recently introduced ChartQA our method obtains state45;of45;the45;art performance when applied on the PaLI345;5B VLM by citet123;chen2023pali3125; while also enabling much better performance on PlotQA and FigureQA. We first improve the chart representation by continuing the pre45;training stage using an improved version of the chart45;to45;table translation task by citet123;liu2023deplot125;. We then propose constructing a 20x larger dataset than the original training set. To improve general reasoning capabilities and improve numerical operations we synthesize reasoning traces using the table representation of charts. Lastly our model is fine45;tuned using the multitask loss introduced by citet123;hsieh2023distilling125;. Our variant ChartPaLI45;5B outperforms even 10x larger models such as PaLIX45;55B without using an upstream OCR system while keeping inference time constant compared to the PaLI345;5B baseline. When rationales are further refined with a simple program45;of45;thought prompt cite123;chen2023program125; our model outperforms the recently introduced Gemini Ultra and GPT45;4V.
