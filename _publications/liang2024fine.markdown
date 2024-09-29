---
layout: publication
title: Fennec Fine45;grained Language Model Evaluation And Correction Extended Through Branching And Bridging
authors: Liang Xiaobo, Zhang Haoke, Hu Helan, Li Juntao, Xu Jun, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: liang2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12163"}
  - {name: "Code", url: "https://github.com/dropreg/Fennec&#125;&#125;"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The rapid advancement of large language models has given rise to a plethora of applications across a myriad of real45;world tasks mainly centered on aligning with human intent. However the complexities inherent in human intent necessitate a dependence on labor45;intensive and time45;consuming human evaluation. To alleviate this constraint we delve into the paradigm of employing open45;source large language models as evaluators aligning with the prevailing trend of utilizing GPT45;4. Particularly we present a step45;by45;step evaluation framework textbf123;Fennec125; capable of textbf123;F125;ine45;grained textbf123;E125;valuatiotextbf123;N125; and correctiotextbf123;N125; textbf123;E125;xtended through brantextbf123;C125;hing and bridging. Specifically the branching operation dissects the evaluation task into various dimensions and granularities thereby alleviating the challenges associated with evaluation. Concurrently the bridging operation amalgamates diverse training datasets augmenting the variety of evaluation tasks. In experimental trials our 7B model consistently outperforms open45;source larger45;scale evaluation models across various widely adopted benchmarks in terms of both textit123;Agreement125; and textit123;Consistency125; closely approaching the capabilities of GPT45;4. We employ the fine45;grained correction capabilities induced by the evaluation model to refine multiple model responses and the results show that the refinement elevates the quality of responses leading to an improvement of 145;2 points on the MT45;Bench. Our code is available at Githubfootnote123;url123;https://github.com/dropreg/Fennec&#125;&#125;.
