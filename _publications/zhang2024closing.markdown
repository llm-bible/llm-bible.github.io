---
layout: publication
title: Closing The Gap Between Open45;source And Commercial Large Language Models For Medical Evidence Summarization
authors: Zhang Gongbo, Jin Qiao, Zhou Yiliang, Wang Song, Idnay Betina R., Luo Yiming, Park Elizabeth, Nestor Jordan G., Spotnitz Matthew E., Soroush Ali, Campion Thomas, Lu Zhiyong, Weng Chunhua, Peng Yifan
conference: "Arxiv"
year: 2024
bibkey: zhang2024closing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.00588"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Model Architecture']
---
Large language models (LLMs) hold great promise in summarizing medical evidence. Most recent studies focus on the application of proprietary LLMs. Using proprietary LLMs introduces multiple risk factors including a lack of transparency and vendor dependency. While open45;source LLMs allow better transparency and customization their performance falls short compared to proprietary ones. In this study we investigated to what extent fine45;tuning open45;source LLMs can further improve their performance in summarizing medical evidence. Utilizing a benchmark dataset MedReview consisting of 8161 pairs of systematic reviews and summaries we fine45;tuned three broadly45;used open45;sourced LLMs namely PRIMERA LongT5 and Llama45;2. Overall the fine45;tuned LLMs obtained an increase of 9.89 in ROUGE45;L (9537; confidence interval 8.9445;10.81) 13.21 in METEOR score (9537; confidence interval 12.0545;14.37) and 15.82 in CHRF score (9537; confidence interval 13.8945;16.44). The performance of fine45;tuned LongT5 is close to GPT45;3.5 with zero45;shot settings. Furthermore smaller fine45;tuned models sometimes even demonstrated superior performance compared to larger zero45;shot models. The above trends of improvement were also manifested in both human and GPT445;simulated evaluations. Our results can be applied to guide model selection for tasks demanding particular domain knowledge such as medical evidence summarization.
