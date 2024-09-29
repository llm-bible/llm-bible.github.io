---
layout: publication
title: SOS! Soft Prompt Attack Against Open-source Large Language Models
authors: Yang Ziqing, Backes Michael, Zhang Yang, Salem Ahmed
conference: "Arxiv"
year: 2024
bibkey: yang2024sos
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03160"}
tags: ['Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Open-source large language models (LLMs) have become increasingly popular among both the general public and industry as they can be customized fine-tuned and freely used. However some open-source LLMs require approval before usage which has led to third parties publishing their own easily accessible versions. Similarly third parties have been publishing fine-tuned or quantized variants of these LLMs. These versions are particularly appealing to users because of their ease of access and reduced computational resource demands. This trend has increased the risk of training time attacks compromising the integrity and security of LLMs. In this work we present a new training time attack SOS which is designed to be low in computational demand and does not require clean data or modification of the model weights thereby maintaining the models utility intact. The attack addresses security issues in various scenarios including the backdoor attack jailbreak attack and prompt stealing attack. Our experimental findings demonstrate that the proposed attack is effective across all evaluated targets. Furthermore we present the other side of our SOS technique namely the copyright token -- a novel technique that enables users to mark their copyrighted content and prevent models from using it.
