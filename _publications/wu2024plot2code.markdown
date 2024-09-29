---
layout: publication
title: Plot2code A Comprehensive Benchmark For Evaluating Multi-modal Large Language Models In Code Generation From Scientific Plots
authors: Wu Chengyue, Ge Yixiao, Guo Qiushan, Wang Jiahao, Liang Zhixuan, Lu Zeyu, Shan Ying, Luo Ping
conference: "Arxiv"
year: 2024
bibkey: wu2024plot2code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07990"}
  - {name: "Code", url: "https://huggingface.co/datasets/TencentARC/Plot2Code"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture']
---
The remarkable progress of Multi-modal Large Language Models (MLLMs) has attracted significant attention due to their superior performance in visual contexts. However their capabilities in turning visual figure to executable code have not been evaluated thoroughly. To address this we introduce Plot2Code a comprehensive visual coding benchmark designed for a fair and in-depth assessment of MLLMs. We carefully collect 132 manually selected high-quality matplotlib plots across six plot types from publicly available matplotlib galleries. For each plot we carefully offer its source code and an descriptive instruction summarized by GPT-4. This approach enables Plot2Code to extensively evaluate MLLMs code capabilities across various input modalities. Furthermore we propose three automatic evaluation metrics including code pass rate text-match ratio and GPT-4V overall rating for a fine-grained assessment of the output code and rendered images. Instead of simply judging pass or fail we employ GPT-4V to make an overall judgement between the generated and reference images which has been shown to be consistent with human evaluation. The evaluation results which include analyses of 14 MLLMs such as the proprietary GPT-4V Gemini-Pro and the open-sourced Mini-Gemini highlight the substantial challenges presented by Plot2Code. With Plot2Code we reveal that most existing MLLMs struggle with visual coding for text-dense plots heavily relying on textual instruction. We hope that the evaluation results from Plot2Code on visual coding will guide the future development of MLLMs. All data involved with Plot2Code are available at https://huggingface.co/datasets/TencentARC/Plot2Code.
