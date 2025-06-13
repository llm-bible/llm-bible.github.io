---
layout: publication
title: 'Annotation Alignment: Comparing LLM And Human Annotations Of Conversational Safety'
authors: Rajiv Movva, Pang Wei Koh, Emma Pierson
conference: "Arxiv"
year: 2024
bibkey: movva2024annotation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06369"}
tags: ['Responsible AI', 'RAG', 'Model Architecture', 'GPT']
---
Do LLMs align with human perceptions of safety? We study this question via
annotation alignment, the extent to which LLMs and humans agree when annotating
the safety of user-chatbot conversations. We leverage the recent DICES dataset
(Aroyo et al., 2023), in which 350 conversations are each rated for safety by
112 annotators spanning 10 race-gender groups. GPT-4 achieves a Pearson
correlation of \\(r = 0.59\\) with the average annotator rating, \textit\{higher\}
than the median annotator's correlation with the average (\\(r=0.51\\)). We show
that larger datasets are needed to resolve whether LLMs exhibit disparities in
how well they correlate with different demographic groups. Also, there is
substantial idiosyncratic variation in correlation within groups, suggesting
that race & gender do not fully capture differences in alignment. Finally, we
find that GPT-4 cannot predict when one demographic group finds a conversation
more unsafe than another.
