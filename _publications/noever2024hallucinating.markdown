---
layout: publication
title: 'Hallucinating AI Hijacking Attack: Large Language Models And Malicious Code Recommenders'
authors: David Noever, Forrest Mckee
conference: "Arxiv"
year: 2024
bibkey: noever2024hallucinating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06462"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Prompting']
---
The research builds and evaluates the adversarial potential to introduce
copied code or hallucinated AI recommendations for malicious code in popular
code repositories. While foundational large language models (LLMs) from OpenAI,
Google, and Anthropic guard against both harmful behaviors and toxic strings,
previous work on math solutions that embed harmful prompts demonstrate that the
guardrails may differ between expert contexts. These loopholes would appear in
mixture of expert's models when the context of the question changes and may
offer fewer malicious training examples to filter toxic comments or recommended
offensive actions. The present work demonstrates that foundational models may
refuse to propose destructive actions correctly when prompted overtly but may
unfortunately drop their guard when presented with a sudden change of context,
like solving a computer programming challenge. We show empirical examples with
trojan-hosting repositories like GitHub, NPM, NuGet, and popular content
delivery networks (CDN) like jsDelivr which amplify the attack surface. In the
LLM's directives to be helpful, example recommendations propose application
programming interface (API) endpoints which a determined domain-squatter could
acquire and setup attack mobile infrastructure that triggers from the naively
copied code. We compare this attack to previous work on context-shifting and
contrast the attack surface as a novel version of "living off the land" attacks
in the malware literature. In the latter case, foundational language models can
hijack otherwise innocent user prompts to recommend actions that violate their
owners' safety policies when posed directly without the accompanying coding
support request.
