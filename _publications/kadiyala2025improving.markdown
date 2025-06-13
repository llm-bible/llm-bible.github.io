---
layout: publication
title: 'Improving Multilingual Capabilities With Cultural And Local Knowledge In Large Language Models While Enhancing Native Performance'
authors: Ram Mohan Rao Kadiyala, Siddartha Pullakhandam, Siddhant Gupta, Drishti Sharma, Jebish Purbey, Kanwal Mehreen, Muhammad Arham, Hamza Farooq
conference: "Arxiv"
year: 2025
bibkey: kadiyala2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09753"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques', 'Fine-Tuning']
---
Large Language Models (LLMs) have shown remarkable capabilities, but their development has primarily focused on English and other high-resource languages, leaving many languages underserved. We present our latest Hindi-English bi-lingual LLM \textbf\{Mantra-14B\} with ~3% average improvement in benchmark scores over both languages, outperforming models twice its size. Using a curated dataset composed of English and Hindi instruction data of 485K samples, we instruction tuned models such as Qwen-2.5-14B-Instruct and Phi-4 to improve performance over both English and Hindi. Our experiments encompassing seven different LLMs of varying parameter sizes and over 140 training attempts with varying English-Hindi training data ratios demonstrated that it is possible to significantly improve multilingual performance without compromising native performance. Further, our approach avoids resource-intensive techniques like vocabulary expansion or architectural modifications, thus keeping the model size small. Our results indicate that modest fine-tuning with culturally and locally informed data can bridge performance gaps without incurring significant computational overhead. We release our training code, datasets, and models under mit and apache licenses to aid further research towards under-represented and low-resource languages.
