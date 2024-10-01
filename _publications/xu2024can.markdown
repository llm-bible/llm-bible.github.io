---
layout: publication
title: 'Can Llms Solve Longer Math Word Problems Better?'
authors: Xu Xin, Xiao Tong, Chao Zitong, Huang Zhenya, Yang Can, Wang Yang
conference: "Arxiv"
year: 2024
bibkey: xu2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14804"}
tags: ['Applications', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Math Word Problems (MWPs) are crucial for evaluating the capability of Large Language Models (LLMs), with current research primarily focusing on questions with concise contexts. However, as real-world math problems often involve complex circumstances, LLMs' ability to solve long MWPs is vital for their applications in these scenarios, yet remains under-explored. This study pioneers the exploration of Context Length Generalizability (CoLeG), the ability of LLMs to solve long MWPs. We introduce Extended Grade-School Math (E-GSM), a collection of MWPs with lengthy narratives. Two novel metrics are proposed to assess the efficacy and resilience of LLMs in solving these problems. Our examination of existing zero-shot prompting techniques and both proprietary and open-source LLMs reveals a general deficiency in CoLeG. To alleviate these challenges, we propose distinct approaches for different categories of LLMs. For proprietary LLMs, a new instructional prompt is proposed to mitigate the influence of long context. For open-source LLMs, a new data augmentation task is developed to improve CoLeG. Our comprehensive results demonstrate the effectiveness of our proposed methods, showing not only improved performance on E-GSM but also generalizability across several other MWP benchmarks. Our findings pave the way for future research in employing LLMs for complex, real-world applications, offering practical solutions to current limitations and opening avenues for further exploration of model generalizability and training methodologies.
