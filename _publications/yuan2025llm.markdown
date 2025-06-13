---
layout: publication
title: 'LLM In The Loop: Creating The PARADEHATE Dataset For Hate Speech Detoxification'
authors: Shuzhou Yuan, Ercong Nie, Lukas Kouba, Ashish Yashwanth Kangen, Helmut Schmid, Hinrich Schutze, Michael Farber
conference: "Arxiv"
year: 2025
bibkey: yuan2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01484"}
tags: ['RAG', 'Model Architecture', 'GPT']
---
Detoxification, the task of rewriting harmful language into non-toxic text, has become increasingly important amid the growing prevalence of toxic content online. However, high-quality parallel datasets for detoxification, especially for hate speech, remain scarce due to the cost and sensitivity of human annotation. In this paper, we propose a novel LLM-in-the-loop pipeline leveraging GPT-4o-mini for automated detoxification. We first replicate the ParaDetox pipeline by replacing human annotators with an LLM and show that the LLM performs comparably to human annotation. Building on this, we construct PARADEHATE, a large-scale parallel dataset specifically for hatespeech detoxification. We release PARADEHATE as a benchmark of over 8K hate/non-hate text pairs and evaluate a wide range of baseline methods. Experimental results show that models such as BART, fine-tuned on PARADEHATE, achieve better performance in style accuracy, content preservation, and fluency, demonstrating the effectiveness of LLM-generated detoxification text as a scalable alternative to human annotation.
