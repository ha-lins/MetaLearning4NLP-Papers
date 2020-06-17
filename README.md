# Meta learning for NLP - Papers
A list of recent papers about Meta / few-shot learning methods applied in NLP areas.

## Call for Contributions
Contributions are welcomed, you are encouraged to:
- Open an issue and send me the paper info
- Directly pull request


## Taxonomy in Applications

### Fundamental NLP Tasks
* ### Semantic Parsing 
1. **Coupling Retrieval and Meta-Learning for Context-Dependent Semantic Parsing.** *Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, Jian Yin
.* ***ACL 2019***. [[pdf](https://arxiv.org/pdf/1906.07108.pdf)] [[code](https://github.com/microsoft/PointerSQL)]

2. **Natural Language to Structured Query Generation via Meta-Learning.** *Po-Sen Huang, Chenglong Wang, Rishabh Singh, Wen-tau Yih, Xiaodong He.* ***NAACL 2018[short]***. [[pdf](https://www.aclweb.org/anthology/N18-2115/)] [[code](https://github.com/microsoft/PointerSQL)]

3. **Neural Semantic Parsing in Low-Resource Settings with Back-Translation and Meta-Learning.** *Yibo Sun, Duyu Tang, Nan Duan, Yeyun Gong, Xiaocheng Feng, Bing Qin, Daxin Jiang.* ***AAAI 2020***. [[pdf](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-SunY.6672.pdf)]


* ### Named Entity Recognition
1. **Enhanced Meta-Learning for Cross-lingual Named Entity Recognition with Minimal Resources.** *Qianhui Wu, Zijia Lin, Guoxin Wang, Hui Chen, Börje F. Karlsson, Biqing Huang, Chin-Yew Lin.* ***AAAI 2020***. [[pdf](https://arxiv.org/pdf/1911.06161.pdf)]

### Dialog System
1. **Learning to Customize Model Structures for Few-shot Dialogue Generation Tasks.** *Yiping Song, Zequn Liu, Wei Bi, Rui Yan, Ming Zhang* ***ACL 2020***. [[pdf](https://arxiv.org/pdf/1910.14326.pdf)]

2. **Domain Adaptive Dialog Generation via Meta Learning.** *Kun Qian, Zhou Yu.* ***ACL 2019***. [[pdf](https://www.aclweb.org/anthology/P19-1253/)] [[code](https://github.com/qbetterk/DAML)]

3. **Meta-Learning for Low-resource Natural Language Generation in Task-oriented Dialogue Systems.** *Fei Mi, Minlie Huang, Jiyong Zhang, Boi Faltings.* ***IJCAI 2019***. [[pdf](https://arxiv.org/abs/1905.05644)] 

4. **Personalizing Dialogue Agents via Meta-Learning.** *Zhaojiang Lin, Andrea Madotto, Chien-Sheng Wu, Pascale Fung.* ***ACL 2019[short]***. [[pdf](https://www.aclweb.org/anthology/P19-1542.pdf)] [[code](https://github.com/HLTCHKUST/PAML)]

### Classification
1. **Dynamic Memory Induction Networks for Few-Shot Text Classification.** *Ruiying Geng, Binhua Li, Yongbin Li, Jian Sun, Xiaodan Zhu.* ***ACL 2020***. [[pdf](https://arxiv.org/pdf/2005.05727.pdf)]

2. **Few-shot Text Classification with Distributional Signatures.** *Yujia Bao, Menghua Wu, Shiyu Chang and Regina Barzilay.* ***ICLR 2020***. [[pdf](https://arxiv.org/abs/1908.06039)] [[code](https://github.com/YujiaBao/Distributional-Signatures)]

3. **Induction Networks for Few-Shot Text Classification.** *Ruiying Geng, Binhua Li, Yongbin Li, Xiaodan Zhu, Ping Jian, Jian Sun.* ***EMNLP 2019***. [[pdf](https://arxiv.org/pdf/1902.10482.pdf)] 

4. **Learning to Learn and Predict: A Meta-Learning Approach for Multi-Label Classification.** *Jiawei Wu, Wenhan Xiong, William Yang Wang.* ***EMNLP 2019***. [[pdf](https://www.aclweb.org/anthology/D19-1444.pdf)] 

5. **Model-Agnostic Meta-Learning for Relation Classification with Limited Supervision.** *Abiola Obamuyide, Andreas Vlachos.* ***ACL 2019[short]***. [[pdf](https://www.aclweb.org/anthology/P19-1589/)] 


### Knowledge Graph

1. **Meta Relational Learning for Few-Shot Link Prediction in Knowledge Graphs.** *Mingyang Chen, Wen Zhang, Wei Zhang, Qiang Chen, Huajun Chen.* ***EMNLP 2019***. [[pdf](https://www.aclweb.org/anthology/D19-1431.pdf)] [[code](https://github.com/AnselCmy/MetaR)]

2. **Meta-Learning with Dynamic-Memory-Based Prototypical Network for Few-Shot Event Detection.** *Shumin Deng, Ningyu Zhang, Jiaojian Kang, Yichi Zhang, Wei Zhang, Huajun Chen.* ***WSDM 2020***. [[pdf](https://arxiv.org/pdf/1910.11621.pdf)]

3. **Adapting Meta Knowledge Graph Information for Multi-Hop Reasoning over Few-Shot Relations.** *Xin Lv, Yuxian Gu, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu.* ***EMNLP 2019[short]***. [[pdf](https://arxiv.org/pdf/1908.11513.pdf)][[code](https://github.com/THU-KEG/MetaKGR)]

### Text Emotion Distribution Learning

1. **Text Emotion Distribution Learning from Small Sample: A Meta-Learning Approach.** *Zhenjie Zhao, Xiaojuan Ma.* ***EMNLP 2019***. [[pdf](https://www.aclweb.org/anthology/D19-1408.pdf)] [[code](https://github.com/zhaozj89/EDL-Meta)](metric-based) 

### Machine Translation
1. **Meta-Learning for Low-Resource Neural Machine Translation.** *Jiatao Gu, Yong Wang, Yun Chen, Victor O. K. Li, Kyunghyun Cho.* ***EMNLP 2018***. [[pdf](https://www.aclweb.org/anthology/D18-1398.pdf)]

### NLU
1. **Investigating Meta-Learning Algorithms for Low-Resource NLU tasks.** *Zi-Yi Dou, Keyi Yu, Antonios Anastasopoulos.* ***EMNLP 2019[short]***. [[pdf](https://www.aclweb.org/anthology/D19-1112.pdf)]
2. **Few-shot Slot Tagging with Collapsed Dependency Transfer and Label-enhanced Task-adaptive Projection Network.** *Yutai Hou, Wanxiang Che, Yongkui Lai, Zhihan Zhou, Yijia Liu, Han Liu, Ting Liu.* ***ACL 2020[long]***. [[pdf](https://arxiv.org/abs/2006.05702)][[code](https://github.com/AtmaHou/FewShotTagging)]

### Pre-training Text Representations
1. **Pre-training Text Representations as Meta Learning.** *Shangwen Lv, Yuechen Wang, Daya Guo, Duyu Tang, Nan Duan, Fuqing Zhu, Ming Gong, Linjun Shou, Ryan Ma, Daxin Jiang, Guihong Cao, Ming Zhou, Songlin Hu.* ***ACL 2020[short]***. [[pdf](https://arxiv.org/pdf/2004.05568)]

### Speech Recognition
1. **Meta-Transfer Learning for Code-Switched Speech Recognition.** *Genta Indra Winata, Samuel Cahyawijaya, Zhaojiang Lin, Zihan Liu, Peng Xu, Pascale Fung.* ***ACL 2020[Long]***. [[pdf](https://arxiv.org/pdf/2004.14228.pdf)][[code](https://github.com/audioku/meta-transfer-learning)]

