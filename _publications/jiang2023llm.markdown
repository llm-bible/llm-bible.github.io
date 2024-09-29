---
layout: publication
title: Llm45;blender Ensembling Large Language Models With Pairwise Ranking And Generative Fusion
authors: Jiang Dongfu, Ren Xiang, Lin Bill Yuchen
conference: "Arxiv"
year: 2023
bibkey: jiang2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.02561"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'GPT', 'Merging', 'Model Architecture', 'RAG', 'Tools']
---
We present LLM45;Blender an ensembling framework designed to attain consistently superior performance by leveraging the diverse strengths of multiple open45;source large language models (LLMs). Our framework consists of two modules PairRanker and GenFuser addressing the observation that optimal LLMs for different examples can significantly vary. PairRanker employs a specialized pairwise comparison method to distinguish subtle differences between candidate outputs. It jointly encodes the input text and a pair of candidates using cross45;attention encoders to determine the superior one. Our results demonstrate that PairRanker exhibits the highest correlation with ChatGPT45;based ranking. Then GenFuser aims to merge the top45;ranked candidates generating an improved output by capitalizing on their strengths and mitigating their weaknesses. To facilitate large45;scale evaluation we introduce a benchmark dataset MixInstruct which is a mixture of multiple instruction datasets featuring oracle pairwise comparisons. Our LLM45;Blender significantly outperform individual LLMs and baseline methods across various metrics establishing a substantial performance gap.
