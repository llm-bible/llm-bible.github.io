---
layout: publication
title: 'Pause-tuning For Long-context Comprehension: A Lightweight Approach To LLM Attention Recalibration'
authors: James Begin, Namit Agrawal, Eshan Singh, Yicheng Fu, Sean O'brien, Vasu Sharma, Kevin Zhu
conference: "Arxiv"
year: 2025
bibkey: begin2025pause
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20405"}
  - {name: "Code", url: "https://anonymous.4open.science/r/LITM-PauseTokens-7357"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Attention Mechanism']
---
LLMs have demonstrated remarkable proficiency in understanding tasks but
continue to struggle with long-context comprehension, particularly with content
located in the middle of extensive inputs. This limitation, known as the
Lost-in-the-Middle (LITM) problem, hinders models from fully processing and
utilizing information across lengthy contexts. To address this issue, we
introduce pause-tuning, a technique that redistributes attention to enhance
comprehension of long-context inputs. Our approach involves fine-tuning
language models on datasets with artificially inserted pause tokens, which
serve to segment the input into smaller, more manageable parts. We evaluate
pause-tuning against alternative approaches using the Needle-in-a-Haystack
benchmark, where models must retrieve information embedded within contexts of
up to 128K tokens. Experimental results demonstrate significant performance
gains, with the LLaMA 3.2 3B Instruct model and the LLaMA 3.1 8B Instruct model
improving by 10.61% and 3.57% respectively on average, suggesting that
pause-tuning successfully enhances attention redistribution and improves
long-context retention. The code and data are available at
https://anonymous.4open.science/r/LITM-PauseTokens-7357.
