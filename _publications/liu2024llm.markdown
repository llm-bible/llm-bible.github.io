---
layout: publication
title: 'Autofeedback: An Llm-based Framework For Efficient And Accurate API Request Generation'
authors: Huanxi Liu, Jiaqi Liao, Dawei Feng, Kele Xu, Huaimin Wang
conference: "Arxiv"
year: 2024
bibkey: liu2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06943"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting']
---
Large Language Models (LLMs) leverage external tools primarily through
generating the API request to enhance task completion efficiency. The accuracy
of API request generation significantly determines the capability of LLMs to
accomplish tasks.
  Due to the inherent hallucinations within the LLM, it is difficult to
efficiently and accurately generate the correct API request.
  Current research uses prompt-based feedback to facilitate the LLM-based API
request generation. However, existing methods lack factual information and are
insufficiently detailed.
  To address these issues, we propose AutoFeedback, an LLM-based framework for
efficient and accurate API request generation, with a Static Scanning Component
(SSC) and a Dynamic Analysis Component (DAC). SSC incorporates errors detected
in the API requests as pseudo-facts into the feedback, enriching the factual
information. DAC retrieves information from API documentation, enhancing the
level of detail in feedback.
  Based on this two components, Autofeedback implementes two feedback loops
during the process of generating API requests by the LLM.
  Extensive experiments demonstrate that it significantly improves accuracy of
API request generation and reduces the interaction cost. AutoFeedback achieves
an accuracy of 100.00% on a real-world API dataset and reduces the cost of
interaction with GPT-3.5 Turbo by 23.44%, and GPT-4 Turbo by 11.85%.
