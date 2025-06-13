---
layout: publication
title: 'Every FLOP Counts: Scaling A 300B Mixture-of-experts LING LLM Without Premium Gpus'
authors: Ling Team, Binwei Zeng, Chao Huang, Chao Zhang, Changxin Tian, Cong Chen, Dingnan Jin, Feng Yu, Feng Zhu, Feng Yuan, Fakang Wang, Gangshan Wang, Guangyao Zhai, Haitao Zhang, Huizhong Li, Jun Zhou, Jia Liu, Junpeng Fang, Junjie Ou, Jun Hu, Ji Luo, Ji Zhang, Jian Liu, Jian Sha, Jianxue Qian, Jiewei Wu, Junping Zhao, Jianguo Li, Jubao Feng, Jingchao Di, Junming Xu, Jinghua Yao, Kuan Xu, Kewei Du, Longfei Li, Lei Liang, Lu Yu, Li Tang, Lin Ju, Peng Xu, Qing Cui, Song Liu, Shicheng Li, Shun Song, Song Yan, Tengwei Cai, Tianyi Chen, Ting Guo, Ting Huang, Tao Feng, Tao Wu, Wei Wu, Xiaolu Zhang, Xueming Yang, Xin Zhao, Xiaobo Hu, Xin Lin, Yao Zhao, Yilong Wang, Yongzhen Guo, Yuanyuan Wang, Yue Yang, Yang Cao, Yuhao Fu, Yi Xiong, Yanzhe Li, Zhe Li, Zhiqiang Zhang, Ziqi Liu, Zhaoxin Huan, Zujie Wen, Zhenhang Sun, Zhuoxuan Du, Zhengyu He
conference: "Arxiv"
year: 2025
bibkey: lingteam2025every
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05139'}
  - {name: "Code", url: 'https://huggingface.co/inclusionAI'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Model Architecture', 'Pre-Training']
---
In this technical report, we tackle the challenges of training large-scale
Mixture of Experts (MoE) models, focusing on overcoming cost inefficiency and
resource limitations prevalent in such systems. To address these issues, we
present two differently sized MoE large language models (LLMs), namely
Ling-Lite and Ling-Plus (referred to as "Bailing" in Chinese, spelled
B\v\{a\}il\'ing in Pinyin). Ling-Lite contains 16.8 billion parameters with 2.75
billion activated parameters, while Ling-Plus boasts 290 billion parameters
with 28.8 billion activated parameters. Both models exhibit comparable
performance to leading industry benchmarks. This report offers actionable
insights to improve the efficiency and accessibility of AI development in
resource-constrained settings, promoting more scalable and sustainable
technologies. Specifically, to reduce training costs for large-scale MoE
models, we propose innovative methods for (1) optimization of model
architecture and training processes, (2) refinement of training anomaly
handling, and (3) enhancement of model evaluation efficiency. Additionally,
leveraging high-quality data generated from knowledge graphs, our models
demonstrate superior capabilities in tool use compared to other models.
Ultimately, our experimental findings demonstrate that a 300B MoE LLM can be
effectively trained on lower-performance devices while achieving comparable
performance to models of a similar scale, including dense and MoE models.
Compared to high-performance devices, utilizing a lower-specification hardware
system during the pre-training phase demonstrates significant cost savings,
reducing computing costs by approximately 20%. The models can be accessed at
https://huggingface.co/inclusionAI.
