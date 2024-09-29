---
layout: publication
title: Layout and Task Aware Instruction Prompt for Zero-shot Document Image Question Answering
authors: Wang Wenjin, Li Yunhao, Ou Yixin, Zhang Yin
conference: "Arxiv"
year: 2023
bibkey: wang2023layout
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00526"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Layout-aware pre-trained models has achieved significant progress on document image question answering. They introduce extra learnable modules into existing language models to capture layout information within document images from text bounding box coordinates obtained by OCR tools. However extra modules necessitate pre-training on extensive document images. This prevents these methods from directly utilizing off-the-shelf instruction-tuning language foundation models which have recently shown promising potential in zero-shot learning. Instead in this paper we find that instruction-tuning language models like Claude and ChatGPT can understand layout by spaces and line breaks. Based on this observation we propose the LAyout and Task aware Instruction Prompt (LATIN-Prompt) which consists of layout-aware document content and task-aware instruction. Specifically the former uses appropriate spaces and line breaks to recover the layout information among text segments obtained by OCR tools and the latter ensures that generated answers adhere to formatting requirements. Moreover we propose the LAyout and Task aware Instruction Tuning (LATIN-Tuning) to improve the performance of small instruction-tuning models like Alpaca. Experimental results show that LATIN-Prompt enables zero-shot performance of Claude and ChatGPT to be comparable to the fine-tuning performance of SOTAs on document image question answering and LATIN-Tuning enhances the zero-shot performance of Alpaca significantly. For example LATIN-Prompt improves the performance of Claude and ChatGPT on DocVQA by 263 and 20 respectively. LATIN-Tuning improves the performance of Alpaca on DocVQA by 87.7. Quantitative and qualitative analyses demonstrate the effectiveness of LATIN-Prompt and LATIN-Tuning. We provide the code in supplementary and will release it to facilitate future research.
