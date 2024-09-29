---
layout: publication
title: Multilingual Jailbreak Challenges In Large Language Models
authors: Deng Yue, Zhang Wenxuan, Pan Sinno Jialin, Bing Lidong
conference: "Arxiv"
year: 2023
bibkey: deng2023multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06474"}
  - {name: "Code", url: "https://github.com/DAMO&#45;NLP&#45;SG/multilingual&#45;safety&#45;for&#45;LLMs&#125;"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
While large language models (LLMs) exhibit remarkable capabilities across a wide range of tasks they pose potential safety concerns such as the jailbreak problem wherein malicious instructions can manipulate LLMs to exhibit undesirable behavior. Although several preventive measures have been developed to mitigate the potential risks associated with LLMs they have primarily focused on English. In this study we reveal the presence of multilingual jailbreak challenges within LLMs and consider two potential risky scenarios unintentional and intentional. The unintentional scenario involves users querying LLMs using non45;English prompts and inadvertently bypassing the safety mechanisms while the intentional scenario concerns malicious users combining malicious instructions with multilingual prompts to deliberately attack LLMs. The experimental results reveal that in the unintentional scenario the rate of unsafe content increases as the availability of languages decreases. Specifically low45;resource languages exhibit about three times the likelihood of encountering harmful content compared to high45;resource languages with both ChatGPT and GPT45;4. In the intentional scenario multilingual prompts can exacerbate the negative impact of malicious instructions with astonishingly high rates of unsafe output 80.9237; for ChatGPT and 40.7137; for GPT45;4. To handle such a challenge in the multilingual context we propose a novel textsc123;Self45;Defense125; framework that automatically generates multilingual training data for safety fine45;tuning. Experimental results show that ChatGPT fine45;tuned with such data can achieve a substantial reduction in unsafe content generation. Data is available at url123;https://github.com/DAMO&#45;NLP&#45;SG/multilingual&#45;safety&#45;for&#45;LLMs&#125;.
