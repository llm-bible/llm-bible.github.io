---
layout: publication
title: 'Answer When Needed, Forget When Not: Language Models Pretend To Forget Via In-context Knowledge Unlearning'
authors: Shota Takashiro, Takeshi Kojima, Andrew Gambardella, Qi Cao, Yusuke Iwasawa, Yutaka Matsuo
conference: "Arxiv"
year: 2024
bibkey: takashiro2024answer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.00382"}
tags: ['Security', 'Prompting']
---
As large language models (LLMs) are applied across diverse domains, the ability to selectively unlearn specific information is becoming increasingly essential. For instance, LLMs are expected to selectively provide confidential information to authorized internal users, such as employees or trusted partners, while withholding it from external users, including the general public and unauthorized entities. Therefore, we propose a novel method termed ``in-context knowledge unlearning'', which enables the model to selectively forget information in test-time based on the query context. Our method fine-tunes pre-trained LLMs to enable prompt unlearning of target knowledge within the context, while preserving unrelated information. Experiments on TOFU, AGE and RWKU datasets using Llama2-7B/13B and Mistral-7B models demonstrate that our method achieves up to 95% forget accuracy while retaining 80% of unrelated knowledge, significantly outperforming baselines in both in-domain and out-of-domain scenarios. Further investigation of the model's internal behavior revealed that while fine-tuned LLMs generate correct predictions in the middle layers and preserve them up to the final layer. However, the decision to forget is made only at the last layer, i.e. ``LLMs pretend to forget''. Our findings offer valuable insight into the improvement of the robustness of the unlearning mechanisms in LLMs, laying a foundation for future research in the field.
