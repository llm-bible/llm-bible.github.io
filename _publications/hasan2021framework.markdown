---
layout: publication
title: 'Text2app: A Framework For Creating Android Apps From Text Descriptions'
authors: Masum Hasan, Kazi Sajeed Mehrab, Wasi Uddin Ahmad, Rifat Shahriyar
conference: "Arxiv"
year: 2021
bibkey: hasan2021framework
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2104.08301'}
  - {name: "Code", url: 'https://github.com/text2app/Text2App'}
tags: ['Has Code', 'Tools', 'Applications', 'GPT', 'Model Architecture', 'Survey Paper', 'Reinforcement Learning']
---
We present Text2App -- a framework that allows users to create functional
Android applications from natural language specifications. The conventional
method of source code generation tries to generate source code directly, which
is impractical for creating complex software. We overcome this limitation by
transforming natural language into an abstract intermediate formal language
representing an application with a substantially smaller number of tokens. The
intermediate formal representation is then compiled into target source codes.
This abstraction of programming details allows seq2seq networks to learn
complex application structures with less overhead. In order to train sequence
models, we introduce a data synthesis method grounded in a human survey. We
demonstrate that Text2App generalizes well to unseen combination of app
components and it is capable of handling noisy natural language instructions.
We explore the possibility of creating applications from highly abstract
instructions by coupling our system with GPT-3 -- a large pretrained language
model. We perform an extensive human evaluation and identify the capabilities
and limitations of our system. The source code, a ready-to-run demo notebook,
and a demo video are publicly available at
\url\{https://github.com/text2app/Text2App\}.
