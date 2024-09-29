---
layout: publication
title: Synthetic Imitation Edit Feedback For Factual Alignment In Clinical Summarization
authors: Mishra Prakamya, Yao Zonghai, Chen Shuwei, Wang Beining, Mittal Rohan, Yu Hong
conference: "Arxiv"
year: 2023
bibkey: mishra2023synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20033"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Large Language Models (LLMs) like the GPT and LLaMA families have demonstrated exceptional capabilities in capturing and condensing critical contextual information and achieving state-of-the-art performance in the summarization task. However community concerns about these models hallucination issues continue to rise. LLMs sometimes generate factually hallucinated summaries which can be extremely harmful in the clinical domain NLP tasks (e.g. clinical note summarization) where factually incorrect statements can lead to critically erroneous diagnoses. Fine-tuning LLMs using human feedback has shown the promise of aligning LLMs to be factually consistent during generation but such training procedure requires high-quality human-annotated data which can be extremely expensive to get in the clinical domain. In this work we propose a new pipeline using ChatGPT instead of human experts to generate high-quality feedback data for improving factual consistency in the clinical note summarization task. We focus specifically on edit feedback because recent work discusses the shortcomings of human alignment via preference feedback in complex situations (such as clinical NLP tasks that require extensive expert knowledge) as well as some advantages of collecting edit feedback from domain experts. In addition although GPT has reached the expert level in many clinical NLP tasks (e.g. USMLE QA) there is not much previous work discussing whether GPT can generate expert-level edit feedback for LMs in the clinical note summarization task. We hope to fill this gap. Finally our evaluations demonstrate the potential use of GPT edits in human alignment especially from a factuality perspective.
