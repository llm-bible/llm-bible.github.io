---
layout: publication
title: 'Plagbench: Exploring The Duality Of Large Language Models In Plagiarism Generation And Detection'
authors: Lee Jooyoung, Agrawal Toshini, Uchendu Adaku, Le Thai, Chen Jinghui, Lee Dongwon
conference: "Arxiv"
year: 2024
bibkey: lee2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16288"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques', 'Uncategorized']
---
Recent literature has highlighted potential risks to academic integrity associated with large language models (LLMs), as they can memorize parts of training instances and reproduce them in the generated texts without proper attribution. In addition, given their capabilities in generating high-quality texts, plagiarists can exploit LLMs to generate realistic paraphrases or summaries indistinguishable from original work. In response to possible malicious use of LLMs in plagiarism, we introduce PlagBench, a comprehensive dataset consisting of 46.5K synthetic plagiarism cases generated using three instruction-tuned LLMs across three writing domains. The quality of PlagBench is ensured through fine-grained automatic evaluation for each type of plagiarism, complemented by human annotation. We then leverage our proposed dataset to evaluate the plagiarism detection performance of five modern LLMs and three specialized plagiarism checkers. Our findings reveal that GPT-3.5 tends to generates paraphrases and summaries of higher quality compared to Llama2 and GPT-4. Despite LLMs' weak performance in summary plagiarism identification, they can surpass current commercial plagiarism detectors. Overall, our results highlight the potential of LLMs to serve as robust plagiarism detection tools.
