---
layout: publication
title: Enhancing Large Language Models In Coding Through Multi45;perspective Self45;consistency
authors: Huang Baizhou, Lu Shuai, Chen Weizhu, Wan Xiaojun, Duan Nan
conference: "Arxiv"
year: 2023
bibkey: huang2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.17272"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Tools']
---
Large language models (LLMs) have exhibited remarkable ability in code generation. However generating the correct solution in a single attempt still remains a challenge. Prior works utilize verification properties in software engineering to verify and re45;rank solutions in a majority voting manner. But the assumption behind them that generated verification properties have better qualities than solutions may not always hold. In this paper we treat them equally as different perspectives of LLMs reasoning processes. We propose the Multi45;Perspective Self45;Consistency (MPSC) framework incorporating both inter45; and intra45;consistency across outputs from multiple perspectives. Specifically we prompt LLMs to generate diverse outputs from three perspectives Solution Specification and Test case constructing a 345;partite graph. With two measure functions of consistency we embed both inter45; and intra45;consistency information into the graph. The optimal choice of solutions is then determined based on analysis in the graph. MPSC significantly boosts performance of foundation models (ChatGPT in this paper) on various benchmarks including HumanEval (+15.9137;) MBPP (+6.4337;) and CodeContests (+9.3737;) even surpassing GPT45;4.
