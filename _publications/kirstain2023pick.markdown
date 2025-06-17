---
layout: publication
title: 'Pick-a-pic: An Open Dataset Of User Preferences For Text-to-image Generation'
authors: Yuval Kirstain et al.
conference: Arxiv
year: 2023
citations: 28
bibkey: kirstain2023pick
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.01569'}]
tags: [RAG, Prompting]
---
The ability to collect a large dataset of human preferences from
text-to-image users is usually limited to companies, making such datasets
inaccessible to the public. To address this issue, we create a web app that
enables text-to-image users to generate images and specify their preferences.
Using this web app we build Pick-a-Pic, a large, open dataset of text-to-image
prompts and real users' preferences over generated images. We leverage this
dataset to train a CLIP-based scoring function, PickScore, which exhibits
superhuman performance on the task of predicting human preferences. Then, we
test PickScore's ability to perform model evaluation and observe that it
correlates better with human rankings than other automatic evaluation metrics.
Therefore, we recommend using PickScore for evaluating future text-to-image
generation models, and using Pick-a-Pic prompts as a more relevant dataset than
MS-COCO. Finally, we demonstrate how PickScore can enhance existing
text-to-image models via ranking.