---
layout: publication
title: Chameleon Plug45;and45;play Compositional Reasoning With Large Language Models
authors: Pan Lu, Baolin Peng, Hao Cheng, Michel Galley, Kai-wei Chang, Ying Nian Wu, Song-chun Zhu, Jianfeng Gao
conference: "Arxiv"
year: 2023
bibkey: lu2023plug
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2304.09842v3"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
Large language models (LLMs) have achieved remarkable progress in solving various natural language processing tasks due to emergent reasoning abilities. However LLMs have inherent limitations as they are incapable of accessing up45;to45;date information (stored on the Web or in task45;specific knowledge bases) using external tools and performing precise mathematical and logical reasoning. In this paper we present Chameleon an AI system that mitigates these limitations by augmenting LLMs with plug45;and45;play modules for compositional reasoning. Chameleon synthesizes programs by composing various tools (e.g. LLMs off45;the45;shelf vision models web search engines Python functions and heuristic45;based modules) for accomplishing complex reasoning tasks. At the heart of Chameleon is an LLM45;based planner that assembles a sequence of tools to execute to generate the final response. We showcase the effectiveness of Chameleon on two multi45;modal knowledge45;intensive reasoning tasks ScienceQA and TabMWP. Chameleon powered by GPT45;4 achieves an 86.5437; overall accuracy on ScienceQA improving the best published few45;shot result by 11.3737;. On TabMWP GPT45;445;powered Chameleon improves the accuracy by 17.037; lifting the state of the art to 98.7837;. Our analysis also shows that the GPT45;445;powered planner exhibits more consistent and rational tool selection via inferring potential constraints from instructions compared to a ChatGPT45;powered planner. The project is available at https://chameleon&#45;llm.github.io.
