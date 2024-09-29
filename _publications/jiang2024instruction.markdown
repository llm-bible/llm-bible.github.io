---
layout: publication
title: Instruction45;tuned Language Models Are Better Knowledge Learners
authors: Jiang Zhengbao, Sun Zhiqing, Shi Weijia, Rodriguez Pedro, Zhou Chunting, Neubig Graham, Lin Xi Victoria, Yih Wen-tau, Iyer Srinivasan
conference: "Arxiv"
year: 2024
bibkey: jiang2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12847"}
tags: ['Reinforcement Learning', 'Training Techniques']
---
In order for large language model (LLM)45;based assistants to effectively adapt to evolving information needs it must be possible to update their factual knowledge through continued training on new data. The standard recipe for doing so involves continued pre45;training on new documents followed by instruction45;tuning on question45;answer (QA) pairs. However we find that LLMs trained with this recipe struggle to answer questions even though the perplexity of documents is minimized. We found that QA pairs are generally straightforward while documents are more complex weaving many factual statements together in an intricate manner. Therefore we hypothesize that it is beneficial to expose LLMs to QA pairs before continued pre45;training on documents so that the process of encoding knowledge from complex documents takes into account how this knowledge is accessed through questions. Based on this we propose pre45;instruction45;tuning (PIT) a method that instruction45;tunes on questions prior to training on documents. This contrasts with standard instruction45;tuning which learns how to extract knowledge after training on documents. Extensive experiments and ablation studies demonstrate that pre45;instruction45;tuning significantly enhances the ability of LLMs to absorb knowledge from new documents outperforming standard instruction45;tuning by 17.837;.
