---
layout: publication
title: 'Test-time Backdoor Mitigation For Black-box Large Language Models With Defensive Demonstrations'
authors: Wenjie Mo, Jiashu Xu, Qin Liu, Jiongxiao Wang, Jun Yan, Hadi Askari, Chaowei Xiao, Muhao Chen
conference: "Arxiv"
year: 2023
bibkey: mo2023test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09763"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
Existing studies in backdoor defense have predominantly focused on the
training phase, overlooking the critical aspect of testing time defense. This
gap becomes pronounced in the context of LLMs deployed as Web Services, which
typically offer only black-box access, rendering training-time defenses
impractical. To bridge this gap, this study critically examines the use of
demonstrations as a defense mechanism against backdoor attacks in black-box
LLMs. We retrieve task-relevant demonstrations from a clean data pool and
integrate them with user queries during testing. This approach does not
necessitate modifications or tuning of the model, nor does it require insight
into the model's internal architecture. The alignment properties inherent in
in-context learning play a pivotal role in mitigating the impact of backdoor
triggers, effectively recalibrating the behavior of compromised models. Our
experimental analysis demonstrates that this method robustly defends against
both instance-level and instruction-level backdoor attacks, outperforming
existing defense baselines across most evaluation scenarios.
