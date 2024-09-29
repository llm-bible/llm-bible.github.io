---
layout: publication
title: '1.5-pints Technical Report: Pretraining In Days, Not Months -- Your Language Model Thrives On Quality Data'
authors: Tan Calvin, Wang Jerome
conference: "Arxiv"
year: 2024
bibkey: tan2024technical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03506"}
tags: ['Model Architecture', 'Pretraining Methods', 'Survey Paper', 'Training Techniques']
---
This paper presents a compute-efficient approach to pre-training a Language Model-the 1.5-Pints-in only 9 days while outperforming state-of-the-art models as an instruction-following assistant.Based on MT-Bench (a benchmark that emulates human judgments) 1.5-Pints outperforms Apples OpenELM and Microsofts Phi.This is achieved by a carefully curated pre-training dataset of 57 billion tokens using a mix of automated workflows and manual human review. The selection of the dataset prioritizes content that is considered expository and textbook-like to aid the model in reasoning and logical deduction culminating in its overall ability as a strong and versatile AI model. In terms of the model architecture we employed a modified Mistral tokenizer alongside a Llama-2 architecture for wider compatibility. For training we adopted the methodologies used by StableLM TinyLlama and Huggingface Zephyr. 1.5-Pints demonstrates that by focusing on data quality over quantity in LLM training we can significantly reduce training time and resources required. We believe this approach will not only make pre-training more accessible but also reduce our carbon footprint. Our findings and resources from this research are open-sourced aiming to facilitate further advancements in the field. The 1.5-Pints model is available in two versions 2K and 16K context windows.
