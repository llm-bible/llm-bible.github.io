---
layout: publication
title: 'Alice: Proactive Learning With Teacher''s Demonstrations For Weak-to-strong Generalization'
authors: Shujin Wu, Cheng Qian, Yi R. Fung, Paul Pu Liang, Heng Ji
conference: "Arxiv"
year: 2025
bibkey: wu2025proactive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07316"}
tags: ['RAG', 'Training Techniques', 'Tools']
---
The growing capabilities of large language models (LLMs) present a key
challenge of maintaining effective human oversight. Weak-to-strong
generalization (W2SG) offers a promising framework for supervising increasingly
capable LLMs using weaker ones. Traditional W2SG methods rely on passive
learning, where a weak teacher provides noisy demonstrations to train a strong
student. This hinders students from employing their knowledge during training
and reaching their full potential. In this work, we introduce Alice
(pro\{A\}ctive \{l\}earning w\{i\}th tea\{c\}her's D\{e\}monstrations), a framework that
leverages complementary knowledge between teacher and student to enhance the
learning process. We probe the knowledge base of the teacher model by eliciting
their uncertainty, and then use these insights together with teachers'
responses as demonstrations to guide student models in self-generating improved
responses for supervision. In addition, for situations with significant
capability gaps between teacher and student models, we introduce cascade Alice,
which employs a hierarchical training approach where weak teachers initially
supervise intermediate models, who then guide stronger models in sequence.
Experimental results demonstrate that our method significantly enhances the
W2SG performance, yielding substantial improvements in three key tasks compared
to the original W2SG: knowledge-based reasoning (+4.0%), mathematical reasoning
(+22.62%), and logical reasoning (+12.11%). This highlights the effectiveness
of our new W2SG paradigm that enables more robust knowledge transfer and
supervision outcome.
