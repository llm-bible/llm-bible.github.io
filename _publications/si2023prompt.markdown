---
layout: publication
title: 'Mondrian: Prompt Abstraction Attack Against Large Language Models For Cheaper API Pricing'
authors: Si Wai Man, Backes Michael, Zhang Yang
conference: "Arxiv"
year: 2023
bibkey: si2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.03558"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Security', 'Tools']
---
The Machine Learning as a Service (MLaaS) market is rapidly expanding and
becoming more mature. For example, OpenAI's ChatGPT is an advanced large
language model (LLM) that generates responses for various queries with
associated fees. Although these models can deliver satisfactory performance,
they are far from perfect. Researchers have long studied the vulnerabilities
and limitations of LLMs, such as adversarial attacks and model toxicity.
Inevitably, commercial ML models are also not exempt from such issues, which
can be problematic as MLaaS continues to grow. In this paper, we discover a new
attack strategy against LLM APIs, namely the prompt abstraction attack.
Specifically, we propose Mondrian, a simple and straightforward method that
abstracts sentences, which can lower the cost of using LLM APIs. In this
approach, the adversary first creates a pseudo API (with a lower established
price) to serve as the proxy of the target API (with a higher established
price). Next, the pseudo API leverages Mondrian to modify the user query,
obtain the abstracted response from the target API, and forward it back to the
end user. Our results show that Mondrian successfully reduces user queries'
token length ranging from 13% to 23% across various tasks, including text
classification, generation, and question answering. Meanwhile, these abstracted
queries do not significantly affect the utility of task-specific and general
language models like ChatGPT. Mondrian also reduces instruction prompts' token
length by at least 11% without compromising output quality. As a result, the
prompt abstraction attack enables the adversary to profit without bearing the
cost of API development and deployment.
