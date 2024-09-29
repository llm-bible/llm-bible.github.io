---
layout: publication
title: Benchmarks Underestimate the Readiness of Multi-lingual Dialogue Agents
authors: Lee Andrew H., Semnani Sina J., Castillo-lópez Galo, De Chalendar Gäel, Choudhury Monojit, Dua Ashna, Kavitha Kapil Rajesh, Kim Sungkyun, Kodali Prashant, Kumaraguru Ponnurangam, Lombard Alexis, Moradshahi Mehrad, Park Gihyun, Semmar Nasredine, Seo Jiwon, Shen Tianhao, Shrivastava Manish, Xiong Deyi, Lam Monica S.
conference: "Arxiv"
year: 2024
bibkey: lee2024benchmarks
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17840"}
tags: ['Agentic', 'Efficiency And Optimization', 'Few Shot', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Creating multilingual task-oriented dialogue (TOD) agents is challenging due to the high cost of training data acquisition. Following the research trend of improving training data efficiency we show for the first time that in-context learning is sufficient to tackle multilingual TOD. To handle the challenging dialogue state tracking (DST) subtask we break it down to simpler steps that are more compatible with in-context learning where only a handful of few-shot examples are used. We test our approach on the multilingual TOD dataset X-RiSAWOZ which has 12 domains in Chinese English French Korean Hindi and code-mixed Hindi-English. Our turn-by-turn DST accuracy on the 6 languages range from 55.6 to 80.3 seemingly worse than the SOTA results from fine-tuned models that achieve from 60.7 to 82.8; our BLEU scores in the response generation (RG) subtask are also significantly lower than SOTA. However after manual evaluation of the validation set we find that by correcting gold label errors and improving dataset annotation schema GPT-4 with our prompts can achieve (1) 89.6-96.8 accuracy in DST and (2) more than 99 correct response generation across different languages. This leads us to conclude that current automatic metrics heavily underestimate the effectiveness of in-context learning.
