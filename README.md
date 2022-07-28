[TOC]

# 事件抽取与事件关系抽取论文整理

## 事件关系抽取

### 事件因果关系抽取
| 年份 | 来源 | 名称 | 源码 | 数据集 |
| :-----: | :-----:| :-----:| :-----: | :-----: |
| 2020 | COLING |[KnowDis: Knowledge Enhanced Data Augmentation for Event Causality Detection via Distant Supervision](https://www.aclweb.org/anthology/2020.coling-main.135)||[COPA](https://people.ict.usc.edu/~gordon/copa.html)|
| 2020 | IJCAI | [Knowledge Enhanced Event Causality Identification with Mention Masking Generalizations](https://www.ijcai.org/proceedings/2020/499) | [Code](https://github.com/jianliu-ml/EventCausalityIdentification) ||
### 事件共指关系抽取
| 年份 | 来源 | 名称 | 源码 | 数据集 |
| :-----: | :-----:| :-----:| :-----: | :-----: |
| 2021 | AAAI | [Span-Based Event Coreference Resolution](https://www.aaai.org/AAAI21Papers/AAAI-9086.LJ.pdf) |||
| 2021 | EACL | [Automatic Data Acquisition for Event Coreference Resolution](https://aclanthology.org/2021.eacl-main.101/) | [Code](https://github.com/prafulla77/Event-Coref-EACL-2021) | [Data](https://drive.google.com/drive/folders/1NNBKiO4eYkGBjkdXGUieKg2fCWfbUBuf) |
| 2021 | NAACL | [A Context-Dependent Gated Module for Incorporating Symbolic Semantics into Event Coreference Resolution](http://arxiv.org/abs/2104.01697) | [Code](https://github.com/laituan245/eventcoref) | ACE 2005&KBP 2016 |
### 事件时序关系抽取
| 年份 | 来源 | 名称 | 源码 | 数据集 |
| :-----: | :-----:| :-----:| :-----: | :-----: |
| 2021 | IJCNLP | [TIMERS: Document-level Temporal Relation Extraction](https://aclanthology.org/2021.acl-short.67.pdf) |  |  |
| 2021 | [计算机研究与发展](https://crad.ict.ac.cn/) | [融合上下文信息的篇章级事件时序关系抽取方法](https://crad.ict.ac.cn/CN/abstract/abstract4529.shtml) |  |  |
| 2019 | ACL | [Fine-Grained Temporal Relation Extraction](https://aclanthology.org/P19-1280.pdf) | [decomp](http://decomp.io/projects/time/) | [decomp](http://decomp.io/projects/time/) |

### 事件父子关系抽取
| 年份 | 来源 | 名称 | 源码 | 数据集 |
| :-----: | :-----:| :-----:| :-----: | :-----: |
| 2022 | TACL | [Decomposing and Recomposing Event Structure](https://aclanthology.org/2022.tacl-1.2.pdf) | [decomp](http://decomp.io/projects/event-structure/) | [decomp](http://decomp.io/projects/event-structure/) |
| 2021 | EMNLP | [Learning Constraints and Descriptive Segmentation for Subevent Detection](https://cogcomp.seas.upenn.edu/page/publication_view/950) | [CogComp/Subevent_EventSeg](https://github.com/CogComp/Subevent_EventSeg) | [HiEve](https://github.com/CogComp/Subevent_EventSeg/tree/main/hievents_v2) and [IC](https://github.com/CogComp/Subevent_EventSeg/tree/main/IC) |
| 2021 | EMNLP | [Weakly Supervised Subevent Knowledge Acquisition](https://aclanthology.org/2020.emnlp-main.430.pdf) | [SubeventAcquisition](https://github.com/wenlinyao/EMNLP20-SubeventAcquisition) | [RED, ESC, HiEve, Timebank](https://github.com/wenlinyao/EMNLP20-SubeventAcquisition/tree/master/datasets) and [RED](https://catalog.ldc.upenn.edu/LDC2016T23) |
| 2020 | EMNLP | [Joint Constrained Learning for Event-Event Relation Extraction](https://cogcomp.seas.upenn.edu/page/publication_view/914) | [CogComp/JointConstrainedLearning](https://github.com/CogComp/JointConstrainedLearning) | [MATRES](https://github.com/why2011btv/JointConstrainedLearning/tree/master/MATRES) and [HiEve](https://github.com/why2011btv/JointConstrainedLearning/tree/master/hievents_v2) |
## 事件抽取

### 中文（句子）事件抽取

| 年份 | 来源 |                             名称                             |                            源码                             |                            数据集                            |
| :--: | :--: | :----------------------------------------------------------: | :---------------------------------------------------------: | :----------------------------------------------------------: |
| 2020 | CCL  | [A Novel Joint Framework for Multiple Chinese Events Extraction](https://aclanthology.org/2020.ccl-1.88/) | [Code](https://github.com/prafulla77/Event-Coref-EACL-2021) | [Data](https://drive.google.com/drive/folders/1NNBKiO4eYkGBjkdXGUieKg2fCWfbUBuf) |
| 2021 | ACL  | [CasEE: A Joint Learning Framework with Cascade Decoding for Overlapping Event Extraction](https://aclanthology.org/2021.findings-acl.14/) |        [Code](https://github.com/JiaweiSheng/CasEE)         | [FewFC (中国金融事件提取数据集)](https://github.com/TimeBurningFish/FewFC) |

### 篇章级事件抽取

| 年份 |     来源      |                             名称                             |                             源码                             |                            数据集                            |
| :--: | :-----------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2018 |      ACL      | [DCFEE: A Document-level Chinese Financial Event Extraction System based on Automatically Labeled Training Data](https://aclanthology.org/P18-4009/) |         [Code](https://github.com/yanghang111/DCFEE)         |         [Data](https://github.com/yanghang111/DCFEE)         |
| 2019 |     EMNLP     | [Doc2EDAG: An End-to-End Document-level Framework for Chinese Financial Event Extraction](https://aclanthology.org/D19-1032/) |        [Code](https://github.com/dolphin-zs/Doc2EDAG)        | [ChFinAnn(2008年至2018年中国上市公司的财务公告)](https://github.com/dolphin-zs/Doc2EDAG/blob/master/Data.zip) |
| 2021 |      ACL      | （GIT）[Document-level Event Extraction via Heterogeneous Graph-based Interaction Model with a Tracker](https://aclanthology.org/2021.acl-long.274/) |           [Code](https://github.com/RunxinXu/GIT)            | [ChFinAnn](https://github.com/dolphin-zs/Doc2EDAG/blob/master/Data.zip) |
| 2021 |      ACL      | (DE-PPN)[Document-level Event Extraction via Parallel Prediction Networks](https://aclanthology.org/2021.acl-long.492/) | [官方](https://github.com/HangYang-NLP/DE-PPN)、[非官方](https://github.com/Spico197/DE-PPN) | [ChFinAnn](https://github.com/dolphin-zs/Doc2EDAG/blob/master/Data.zip) |
| 2021 | arxiv(待发表) | (PTPCG)[Efficient Document-level Event Extraction via Pseudo-Trigger-aware Pruned Complete Graph](https://arxiv.org/abs/2112.06013) |          [Code](https://github.com/Spico197/DocEE)           | [ChFinAnn](https://github.com/dolphin-zs/Doc2EDAG/blob/master/Data.zip) |

### 开放域事件抽取

| 年份 | 来源 |                             名称                             |                        源码                         |                            数据集                            |
| :--: | :--: | :----------------------------------------------------------: | :-------------------------------------------------: | :----------------------------------------------------------: |
| 2019 | ACL  | [Open Domain Event Extraction Using Neural Latent Variable Models](https://aclanthology.org/P19-1276/) | [Code](https://github.com/lx865712528/ACL2019-ODEE) | [Data](https://drive.google.com/file/d/1KjL3mAxj9nmzqC75s2rNaT6x6CJBZZTj/view) |
| 2022 | TOIS | [A Multi-Channel Hierarchical Graph Attention Network for Open Event Extraction](https://dl.acm.org/doi/10.1145/3528668) |     [Code](https://github.com/hawisdom/DL-OEE)      |                     CoNLL-2009 & ACE2005                     |

## 扩展阅读

| 年份 | 来源 | 名称 | 源码 | 数据集 |
| :-----: | :-----:| :-----:| :-----: | :-----: |
| 2021 | IEEE Access | [A Survey on Event Extraction for Natural Language Understanding: Riding the Biomedical Literature Wave](https://ieeexplore.ieee.org/document/9627684) |  |  |
| 2021 | IEEE DSC | [Survey on social event detection](https://ieeexplore.ieee.org/document/9750511) |  |  |
| 2021 | [LNNS](https://link.springer.com/bookseries/15179) | [Deep Learning Approaches to Detect Real Time Events Recognition in Smart Manufacturing Systems – A Short Survey](https://link.springer.com/chapter/10.1007/978-3-030-84910-8_20) |  |  |
| 2021 |  TKDE 2022 | [**What is Event Knowledge Graph: A Survey**](https://arxiv.org/abs/2112.15280) |  |  |
| 2020 | AI Open | [Extracting Events and Their Relations from Texts: A Survey on Recent Research Progress and Challenges](https://www.sciencedirect.com/science/article/pii/S266665102100005X?via%3Dihub) |  |  |
| 2020 | [Knowledge-Based Systems](https://www.sciencedirect.com/journal/knowledge-based-systems) | [A survey on multi-modal social event detection](https://www.sciencedirect.com/science/article/pii/S0950705120301271?via%3Dihub) |  |  |
| 2020 | CCKS | [A Survey on Event Relation Identification](https://link.springer.com/chapter/10.1007/978-981-16-1964-9_14) |  |  |
| 2019 | IEEE Access | [A Survey of Event Extraction From Text](https://ieeexplore.ieee.org/document/8918013) |  |  |
| 2019 | 计算机科学 | [元事件抽取研究综述](https://www.jsjkx.com/CN/10.11896/j.issn.1002-137X.2019.08.002) |  |  |
| 2019 | ACM Trans | [How Deep Features Have Improved Event Recognition in Multimedia: A Survey](https://dl.acm.org/doi/10.1145/3306240) |  |  |
| 2018 | IJCAI | [Event Coreference Resolution: A Survey of Two Decades of Research](https://www.ijcai.org/proceedings/2018/773) |  |  |
|  |  | [Reviews on Event Knowledge Graph Construction Techniques and Application-ReadPaper](https://readpaper.com/paper/623485299804831744) | | |
| 2021 |  | [Event Relation Reasoning Based on Event Knowledge Graph-ReadPaper](https://readpaper.com/paper/3197259738) | | |
| 2020 |  | [Introduction: What Is a Knowledge Graph?-ReadPaper](https://readpaper.com/paper/3004035003) | | |
| 2021 |  | [OEKG - The Open Event Knowledge Graph-ReadPaper](https://readpaper.com/paper/3159675306) | | |

## 搜索工具

- [dblp: computer science bibliography](https://dblp.org/)

- [arXiv.org e-Print archive](https://arxiv.org/)
- [Sci-Hub](https://sci-hub.se/)