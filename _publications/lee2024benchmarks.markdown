---
layout: publication
title: 'Benchmarks Underestimate The Readiness Of Multi-lingual Dialogue Agents'
authors: Andrew H. Lee, Sina J. Semnani, Galo Castillo-lópez, Gäel De Chalendar, Monojit Choudhury, Ashna Dua, Kapil Rajesh Kavitha, Sungkyun Kim, Prashant Kodali, Ponnurangam Kumaraguru, Alexis Lombard, Mehrad Moradshahi, Gihyun Park, Nasredine Semmar, Jiwon Seo, Tianhao Shen, Manish Shrivastava, Deyi Xiong, Monica S. Lam
conference: "Arxiv"
year: 2024
bibkey: lee2024benchmarks
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17840"}
tags: ['Agentic', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Creating multilingual task-oriented dialogue (TOD) agents is challenging due
to the high cost of training data acquisition. Following the research trend of
improving training data efficiency, we show for the first time, that in-context
learning is sufficient to tackle multilingual TOD.
  To handle the challenging dialogue state tracking (DST) subtask, we break it
down to simpler steps that are more compatible with in-context learning where
only a handful of few-shot examples are used. We test our approach on the
multilingual TOD dataset X-RiSAWOZ, which has 12 domains in Chinese, English,
French, Korean, Hindi, and code-mixed Hindi-English. Our turn-by-turn DST
accuracy on the 6 languages range from 55.6% to 80.3%, seemingly worse than the
SOTA results from fine-tuned models that achieve from 60.7% to 82.8%; our BLEU
scores in the response generation (RG) subtask are also significantly lower
than SOTA.
  However, after manual evaluation of the validation set, we find that by
correcting gold label errors and improving dataset annotation schema, GPT-4
with our prompts can achieve (1) 89.6%-96.8% accuracy in DST, and (2) more than
99% correct response generation across different languages. This leads us to
conclude that current automatic metrics heavily underestimate the effectiveness
of in-context learning.
