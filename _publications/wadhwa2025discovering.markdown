---
layout: publication
title: 'Evalagent: Discovering Implicit Evaluation Criteria From The Web'
authors: Manya Wadhwa, Zayne Sprague, Chaitanya Malaviya, Philippe Laban, Junyi Jessy Li, Greg Durrett
conference: "Arxiv"
year: 2025
bibkey: wadhwa2025discovering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15219"}
tags: ['Prompting', 'Agentic', 'Tools']
---
Evaluation of language model outputs on structured writing tasks is typically
conducted with a number of desirable criteria presented to human evaluators or
large language models (LLMs). For instance, on a prompt like "Help me draft an
academic talk on coffee intake vs research productivity", a model response may
be evaluated for criteria like accuracy and coherence. However, high-quality
responses should do more than just satisfy basic task requirements. An
effective response to this query should include quintessential features of an
academic talk, such as a compelling opening, clear research questions, and a
takeaway. To help identify these implicit criteria, we introduce EvalAgent, a
novel framework designed to automatically uncover nuanced and task-specific
criteria. EvalAgent first mines expert-authored online guidance. It then uses
this evidence to propose diverse, long-tail evaluation criteria that are
grounded in reliable external sources. Our experiments demonstrate that the
grounded criteria produced by EvalAgent are often implicit (not directly stated
in the user's prompt), yet specific (high degree of lexical precision).
Further, EvalAgent criteria are often not satisfied by initial responses but
they are actionable, such that responses can be refined to satisfy them.
Finally, we show that combining LLM-generated and EvalAgent criteria uncovers
more human-valued criteria than using LLMs alone.
