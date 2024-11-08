---
layout: publication
title: 'Perturbation-restrained Sequential Model Editing'
authors: Ma Jun-yu, Wang Hong, Xu Hao-xiang, Ling Zhen-hua, Gu Jia-chen
conference: "Arxiv"
year: 2024
bibkey: ma2024perturbation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16821"}
  - {name: "Code", url: "https://github.com/mjy1111/PRUNE"}
tags: ['Has Code', 'Merging', 'Tools', 'Training Techniques']
---
Model editing is an emerging field that focuses on updating the knowledge
embedded within large language models (LLMs) without extensive retraining.
However, current model editing methods significantly compromise the general
abilities of LLMs as the number of edits increases, and this trade-off poses a
substantial challenge to the continual learning of LLMs. In this paper, we
first theoretically analyze that the factor affecting the general abilities in
sequential model editing lies in the condition number of the edited matrix. The
condition number of a matrix represents its numerical sensitivity, and
therefore can be used to indicate the extent to which the original knowledge
associations stored in LLMs are perturbed after editing. Subsequently,
statistical findings demonstrate that the value of this factor becomes larger
as the number of edits increases, thereby exacerbating the deterioration of
general abilities. To this end, a framework termed Perturbation Restraint on
Upper bouNd for Editing (PRUNE) is proposed, which applies the condition number
restraints in sequential editing. These restraints can lower the upper bound on
perturbation to edited models, thus preserving the general abilities.
Systematically, we conduct experiments employing three popular editing methods
on three LLMs across four representative downstream tasks. Evaluation results
show that PRUNE can preserve considerable general abilities while maintaining
the editing performance effectively in sequential model editing. The code and
data are available at https://github.com/mjy1111/PRUNE.
