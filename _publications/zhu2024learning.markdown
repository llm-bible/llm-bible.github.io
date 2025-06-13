---
layout: publication
title: 'Learning From "silly" Questions Improves Large Language Models, But Only Slightly'
authors: Tingyuan Zhu, Shudong Liu, Yidong Wang, Derek F. Wong, Han Yu, Takahiro Shinozaki, Jindong Wang
conference: "Arxiv"
year: 2024
bibkey: zhu2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14121"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Constructing high-quality Supervised Fine-Tuning (SFT) datasets is critical
for the training of large language models (LLMs). Recent studies have shown
that using data from a specific source, Ruozhiba, a Chinese website where users
ask "silly" questions to better understand certain topics, can lead to better
fine-tuning performance. This paper aims to explore some hidden factors: the
potential interpretations of its success and a large-scale evaluation of the
performance. First, we leverage GPT-4 to analyze the successful cases of
Ruozhiba questions from the perspective of education, psychology, and cognitive
science, deriving a set of explanatory rules. Then, we construct fine-tuning
datasets by applying these rules to the MMLU training set. Surprisingly, our
results indicate that rules can significantly improve model performance in
certain tasks, while potentially diminishing performance on others. For
example, SFT data generated following the "Counterintuitive Thinking" rule can
achieve approximately a 5% improvement on the "Global Facts" task, whereas the
"Blurring the Conceptual Boundaries" rule leads to a performance drop of 6.14%
on the "Econometrics" task. In addition, for specific tasks, different rules
tend to have a consistent impact on model performance. This suggests that the
differences between the extracted rules are not as significant, and the
effectiveness of the rules is relatively consistent across tasks. Our research
highlights the importance of considering task diversity and rule applicability
when constructing SFT datasets to achieve more comprehensive performance
improvements.
