---
layout: publication
title: ChatMusician Understanding and Generating Music Intrinsically with LLM
authors: Yuan Ruibin, Lin Hanfeng, Wang Yi, Tian Zeyue, Wu Shangda, Shen Tianhao, Zhang Ge, Wu Yuhang, Liu Cong, Zhou Ziya, Ma Ziyang, Xue Liumeng, Wang Ziyu, Liu Qin, Zheng Tianyu, Li Yizhi, Ma Yinghao, Liang Yiming, Chi Xiaowei, Liu Ruibo, Wang Zili, Li Pengfei, Wu Jingcheng, Lin Chenghua, Liu Qifeng, Jiang Tao, Huang Wenhao, Chen Wenhu, Benetos Emmanouil, Fu Jie, Xia Gus, Dannenberg Roger, Xue Wei, Kang Shiyin, Guo Yike
conference: "Arxiv"
year: 2024
bibkey: yuan2024chatmusician
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16153"}
tags: ['ARXIV', 'Applications', 'Fine Tuning', 'GPT', 'LLM']
---
While Large Language Models (LLMs) demonstrate impressive capabilities in text generation we find that their ability has yet to be generalized to music humanitys creative language. We introduce ChatMusician an open-source LLM that integrates intrinsic musical abilities. It is based on continual pre-training and finetuning LLaMA2 on a text-compatible music representation ABC notation and the music is treated as a second language. ChatMusician can understand and generate music with a pure text tokenizer without any external multi-modal neural structures or tokenizers. Interestingly endowing musical abilities does not harm language abilities even achieving a slightly higher MMLU score. Our model is capable of composing well-structured full-length music conditioned on texts chords melodies motifs musical forms etc surpassing GPT-4 baseline. On our meticulously curated college-level music understanding benchmark MusicTheoryBench ChatMusician surpasses LLaMA2 and GPT-3.5 on zero-shot setting by a noticeable margin. Our work reveals that LLMs can be an excellent compressor for music but there remains significant territory to be conquered. We release our 4B token music-language corpora MusicPile the collected MusicTheoryBench code model and demo in GitHub.
