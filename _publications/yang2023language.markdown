---
layout: publication
title: LACMA Language45;aligning Contrastive Learning With Meta45;actions For Embodied Instruction Following
authors: Yang Cheng-fu, Chen Yen-chun, Yang Jianwei, Dai Xiyang, Yuan Lu, Wang Yu-chiang Frank, Chang Kai-wei
conference: "Arxiv"
year: 2023
bibkey: yang2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12344"}
  - {name: "Code", url: "https://github.com/joeyy5588/LACMA"}
tags: ['Agentic', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'TACL', 'Training Techniques', 'Transformer']
---
End45;to45;end Transformers have demonstrated an impressive success rate for Embodied Instruction Following when the environment has been seen in training. However they tend to struggle when deployed in an unseen environment. This lack of generalizability is due to the agents insensitivity to subtle changes in natural language instructions. To mitigate this issue we propose explicitly aligning the agents hidden states with the instructions via contrastive learning. Nevertheless the semantic gap between high45;level language instructions and the agents low45;level action space remains an obstacle. Therefore we further introduce a novel concept of meta45;actions to bridge the gap. Meta45;actions are ubiquitous action patterns that can be parsed from the original action sequence. These patterns represent higher45;level semantics that are intuitively aligned closer to the instructions. When meta45;actions are applied as additional training signals the agent generalizes better to unseen environments. Compared to a strong multi45;modal Transformer baseline we achieve a significant 4.537; absolute gain in success rate in unseen environments of ALFRED Embodied Instruction Following. Additional analysis shows that the contrastive objective and meta45;actions are complementary in achieving the best results and the resulting agent better aligns its states with corresponding instructions making it more suitable for real45;world embodied agents. The code is available at https://github.com/joeyy5588/LACMA.
