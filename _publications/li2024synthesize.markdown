---
layout: publication
title: Synthesize Step45;by45;step Tools Templates And Llms As Data Generators For Reasoning45;based Chart VQA
authors: Li Zhuowan, Jasani Bhavan, Tang Peng, Ghadar Shabnam
conference: "Arxiv"
year: 2024
bibkey: li2024synthesize
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16385"}
tags: ['Applications', 'Fine Tuning', 'RAG', 'Tools', 'Training Techniques']
---
Understanding data visualizations like charts and plots requires reasoning about both visual elements and numerics. Although strong in extractive questions current chart visual question answering (chart VQA) models suffer on complex reasoning questions. In this work we address the lack of reasoning ability by data augmentation. We leverage Large Language Models (LLMs) which have shown to have strong reasoning ability as an automatic data annotator that generates question45;answer annotations for chart images. The key innovation in our method lies in the Synthesize Step45;by45;Step strategy our LLM45;based data generator learns to decompose the complex question into step45;by45;step sub45;questions (rationales) which are then used to derive the final answer using external tools i.e. Python. This step45;wise generation procedure is trained on synthetic data generated using a template45;based QA generation pipeline. Experimental results highlight the significance of the proposed step45;by45;step generation. By training with the LLM45;augmented data (LAMENDA) we significantly enhance the chart VQA models achieving the state45;of45;the45;art accuracy on the ChartQA and PlotQA datasets. In particular our approach improves the accuracy of the previous state45;of45;the45;art approach from 3837; to 5437; on the human45;written questions in the ChartQA dataset which needs strong reasoning. We hope our work underscores the potential of synthetic data and encourages further exploration of data augmentation using LLMs for reasoning45;heavy tasks.
