---
layout: publication
title: TestAug A Framework for Augmenting Capability-based NLP Tests
authors: Yang Guanqun, Haque Mirazul, Song Qiaochu, Yang Wei, Liu Xueqing
conference: "Arxiv"
year: 2022
bibkey: yang2022testaug
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.08097"}
  - {name: "Code", url: "https://guanqun-yang.github.io/testaug/)"}
  - {name: "Code", url: "https://github.com/guanqun-yang/testaug)"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Tools']
---
The recently proposed capability-based NLP testing allows model developers to test the functional capabilities of NLP models revealing functional failures that cannot be detected by the traditional heldout mechanism. However existing work on capability-based testing requires extensive manual efforts and domain expertise in creating the test cases. In this paper we investigate a low-cost approach for the test case generation by leveraging the GPT-3 engine. We further propose to use a classifier to remove the invalid outputs from GPT-3 and expand the outputs into templates to generate more test cases. Our experiments show that TestAug has three advantages over the existing work on behavioral testing (1) TestAug can find more bugs than existing work; (2) The test cases in TestAug are more diverse; and (3) TestAug largely saves the manual efforts in creating the test suites. The code and data for TestAug can be found at our project website (https://guanqun-yang.github.io/testaug/) and GitHub (https://github.com/guanqun-yang/testaug).
