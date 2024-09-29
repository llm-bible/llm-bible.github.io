---
layout: publication
title: Litcab Lightweight Language Model Calibration Over Short45; And Long45;form Responses
authors: Liu Xin, Khalifa Muhammad, Wang Lu
conference: "Arxiv"
year: 2023
bibkey: liu2023lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19208"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Language Modeling', 'Model Architecture', 'RAG', 'Training Techniques']
---
A model is considered well45;calibrated when its probability estimate aligns with the actual likelihood of the output being correct. Calibrating language models (LMs) is crucial as it plays a vital role in detecting and mitigating hallucinations of LMs as well as building more trustworthy models. However standard calibration techniques may not be suited for LM calibration. For instance post45;processing methods such as temperature scaling do not reorder the candidate generations. On the other hand training45;based methods require fine45;tuning the entire model which is impractical for LMs of large scale. We present LitCab a lightweight calibration mechanism consisting of a single linear layer that takes the input text representation and predicts a bias term which is then added to the LM output logits. LitCab improves model calibration by only adding < 237; of the original model parameters. For evaluation we construct CaT a benchmark consisting of eight text generation tasks covering responses ranging from short phrases to paragraphs. We test LitCab with Llama245;7B where it improves calibration across all tasks reducing the average ECE score by as large as 3037;. We further conduct a comprehensive evaluation with multiple popular open45;sourced LMs from GPT and LLaMA families yielding the following key findings (i) Larger models within the same family exhibit better calibration on tasks with short generation tasks but not necessarily for longer ones. (ii) GPT45;family models show superior calibration compared to LLaMA Llama2 and Vicuna models despite having much fewer parameters. (iii) Fine45;tuning pretrained model (e.g. LLaMA) with samples of limited purpose (e.g. conversations) may lead to worse calibration highlighting the importance of fine45;tuning setups for calibrating LMs.
