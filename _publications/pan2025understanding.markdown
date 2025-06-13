---
layout: publication
title: 'Understanding And Mitigating Overrefusal In Llms From An Unveiling Perspective Of Safety Decision Boundary'
authors: Licheng Pan, Yongqi Tong, Xin Zhang, Xiaolu Zhang, Jun Zhou, Zhixuan Chu
conference: "Arxiv"
year: 2025
bibkey: pan2025understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18325'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/RASS-80D3'}
tags: ['Has Code', 'RAG', 'Tools', 'Prompting', 'Responsible AI']
---
Large language models (LLMs) have demonstrated remarkable capabilities across a wide range of tasks, yet they often refuse to answer legitimate queries-a phenomenon known as overrefusal. Overrefusal typically stems from over-conservative safety alignment, causing models to treat many reasonable prompts as potentially risky. To systematically understand this issue, we probe and leverage the models'safety decision boundaries to analyze and mitigate overrefusal. Our findings reveal that overrefusal is closely tied to misalignment at these boundary regions, where models struggle to distinguish subtle differences between benign and harmful content. Building on these insights, we present RASS, an automated framework for prompt generation and selection that strategically targets overrefusal prompts near the safety boundary. By harnessing steering vectors in the representation space, RASS efficiently identifies and curates boundary-aligned prompts, enabling more effective and targeted mitigation of overrefusal. This approach not only provides a more precise and interpretable view of model safety decisions but also seamlessly extends to multilingual scenarios.We have explored the safety decision boundaries of various LLMs and construct the MORBench evaluation set to facilitate robust assessment of model safety and helpfulness across multiple languages. Code and datasets will be released at https://anonymous.4open.science/r/RASS-80D3.
