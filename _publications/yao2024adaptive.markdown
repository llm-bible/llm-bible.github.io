---
layout: publication
title: CLAVE An Adaptive Framework For Evaluating Values Of LLM Generated Responses
authors: Yao Jing, Yi Xiaoyuan, Xie Xing
conference: "Arxiv"
year: 2024
bibkey: yao2024adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10725"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
The rapid progress in Large Language Models (LLMs) poses potential risks such as generating unethical content. Assessing LLMs values can help expose their misalignment but relies on reference45;free evaluators e.g. fine45;tuned LLMs or close45;source ones like GPT45;4 to identify values reflected in generated responses. Nevertheless these evaluators face two challenges in open45;ended value evaluation they should align with changing human value definitions with minimal annotation against their own bias (adaptability) and detect varying value expressions and scenarios robustly (generalizability). To handle these challenges we introduce CLAVE a novel framework which integrates two complementary LLMs a large one to extract high45;level value concepts from a few human labels leveraging its extensive knowledge and generalizability and a smaller one fine45;tuned on such concepts to better align with human value understanding. This dual45;model approach enables calibration with any value systems using <100 human45;labeled samples per value type. Then we present ValEval a comprehensive dataset comprising 13k+ (textvaluelabel) tuples across diverse domains covering three major value systems. We benchmark the capabilities of 12+ popular LLM evaluators and analyze their strengths and weaknesses. Our findings reveal that combining fine45;tuned small models and prompt45;based large ones serves as a superior balance in value evaluation.
