---
layout: publication
title: PROXYQA: An Alternative Framework For Evaluating Long-form Text Generation With Large Language Models
authors: Tan Haochen, Guo Zhijiang, Shi Zhan, Xu Lu, Liu Zhili, Feng Yunlong, Li Xiaoguang, Wang Yasheng, Shang Lifeng, Liu Qun, Song Linqi
conference: "Arxiv"
year: 2024
bibkey: tan2024alternative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.15042"}
  - {name: "Code", url: "https://proxy-qa.com"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Language Modeling', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have succeeded remarkably in understanding long-form contents. However exploring their capability for generating long-form contents such as reports and articles has been relatively unexplored and inadequately assessed by existing benchmarks. The prevalent evaluation methods which predominantly rely on crowdsourcing are recognized for their labor-intensive nature and lack of efficiency whereas automated metrics such as the ROUGE score demonstrate discordance with human judgment criteria. In this paper we propose ProxyQA an innovative framework dedicated to assessing long-text generation. ProxyQA comprises in-depth human-curated meta-questions spanning various domains each accompanied by specific proxy-questions with pre-annotated answers. LLMs are tasked to generate extensive content in response to these meta-questions by engaging an evaluator and incorporating the generated texts as contextual background ProxyQA assesses the generated contents quality through the evaluators accuracy in addressing the proxy-questions. We examine multiple LLMs emphasizing ProxyQAs demanding nature as a high-quality assessment tool. Human evaluation demonstrates that the proxy-question method is notably self-consistent and aligns closely with human evaluative standards. The dataset and leaderboard is available at (url)https://proxy-qa.com\}."
