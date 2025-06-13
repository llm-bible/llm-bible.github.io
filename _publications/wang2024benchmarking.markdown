---
layout: publication
title: 'Officebench: Benchmarking Language Agents Across Multiple Applications For Office Automation'
authors: Zilong Wang, Yuedong Cui, Li Zhong, Zimin Zhang, Da Yin, Bill Yuchen Lin, Jingbo Shang
conference: "Arxiv"
year: 2024
bibkey: wang2024benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.19056'}
tags: ['Agentic', 'GPT', 'Tools', 'Applications', 'Model Architecture', 'Reinforcement Learning']
---
Office automation significantly enhances human productivity by automatically
finishing routine tasks in the workflow. Beyond the basic information
extraction studied in much of the prior document AI literature, the office
automation research should be extended to more realistic office tasks which
require to integrate various information sources in the office system and
produce outputs through a series of decision-making processes. We introduce
OfficeBench, one of the first office automation benchmarks for evaluating
current LLM agents' capability to address office tasks in realistic office
workflows. OfficeBench requires LLM agents to perform feasible long-horizon
planning, proficiently switch between applications in a timely manner, and
accurately ground their actions within a large combined action space, based on
the contextual demands of the workflow. Applying our customized evaluation
methods on each task, we find that GPT-4 Omni achieves the highest pass rate of
47.00%, demonstrating a decent performance in handling office tasks. However,
this is still far below the human performance and accuracy standards required
by real-world office workflows. We further observe that most issues are related
to operation redundancy and hallucinations, as well as limitations in switching
between multiple applications, which may provide valuable insights for
developing effective agent frameworks for office automation.
