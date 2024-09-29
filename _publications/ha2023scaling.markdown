---
layout: publication
title: Scaling Up And Distilling Down Language45;guided Robot Skill Acquisition
authors: Ha Huy, Florence Pete, Song Shuran
conference: "Arxiv"
year: 2023
bibkey: ha2023scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.14535"}
  - {name: "Code", url: "https://www.cs.columbia.edu/~huy/scalingup/"}
tags: ['Has Code', 'Merging', 'Pretraining Methods', 'RAG', 'Tools']
---
We present a framework for robot skill acquisition which 1) efficiently scale up data generation of language45;labelled robot data and 2) effectively distills this data down into a robust multi45;task language45;conditioned visuo45;motor policy. For (1) we use a large language model (LLM) to guide high45;level planning and sampling45;based robot planners (e.g. motion or grasp samplers) for generating diverse and rich manipulation trajectories. To robustify this data45;collection process the LLM also infers a code45;snippet for the success condition of each task simultaneously enabling the data45;collection process to detect failure and retry as well as the automatic labeling of trajectories with success/failure. For (2) we extend the diffusion policy single45;task behavior45;cloning approach to multi45;task settings with language conditioning. Finally we propose a new multi45;task benchmark with 18 tasks across five domains to test long45;horizon behavior common45;sense reasoning tool45;use and intuitive physics. We find that our distilled policy successfully learned the robust retrying behavior in its data collection procedure while improving absolute success rates by 33.237; on average across five domains. Code data and additional qualitative results are available on https://www.cs.columbia.edu/~huy/scalingup/.
