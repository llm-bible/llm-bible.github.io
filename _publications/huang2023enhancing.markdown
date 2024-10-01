---
layout: publication
title: 'Enhancing Large Language Models In Coding Through Multi-perspective Self-consistency'
authors: Huang Baizhou, Lu Shuai, Chen Weizhu, Wan Xiaojun, Duan Nan
conference: "Arxiv"
year: 2023
bibkey: huang2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.17272"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Tools']
---
"Large language models (LLMs) have exhibited remarkable ability in code generation. However, generating the correct solution in a single attempt still remains a challenge. Prior works utilize verification properties in software engineering to verify and re-rank solutions in a majority voting manner. But the assumption behind them that generated verification properties have better qualities than solutions may not always hold. In this paper, we treat them equally as different perspectives of LLMs' reasoning processes. We propose the Multi-Perspective Self-Consistency (MPSC) framework incorporating both inter- and intra-consistency across outputs from multiple perspectives. Specifically, we prompt LLMs to generate diverse outputs from three perspectives, Solution, Specification and Test case, constructing a 3-partite graph. With two measure functions of consistency, we embed both inter- and intra-consistency information into the graph. The optimal choice of solutions is then determined based on analysis in the graph. MPSC significantly boosts performance of foundation models (ChatGPT in this paper) on various benchmarks, including HumanEval (+15.91&#37;), MBPP (+6.43&#37;) and CodeContests (+9.37&#37;), even surpassing GPT-4."
