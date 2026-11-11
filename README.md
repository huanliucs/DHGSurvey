<h2 align="center"><b>DHGSurvey: Dynamic Heterogeneous Graph Representation Learning</b></h2>

<p align="center">
  <a href="https://ijcai.org/proceedings/2026/0881.pdf"><img src="https://img.shields.io/badge/IJCAI%202026-Paper-1f6feb" alt="IJCAI 2026 Paper"></a>
  <a href="https://github.com/huanliucs/DHGSurvey"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="https://github.com/huanliucs/DHGSurvey/pulls"><img src="https://img.shields.io/badge/PRs-Welcome-green" alt="PRs Welcome"></a>
  <a href="https://github.com/huanliucs/DHGSurvey/commits"><img src="https://img.shields.io/github/last-commit/huanliucs/DHGSurvey?color=blue" alt="Last Commit"></a>
</p>

A curated paper list for **Dynamic Heterogeneous Graph Representation Learning**, based on our [IJCAI 2026 survey](https://doi.org/10.24963/ijcai.2026/881).

📑 Slides are available for our [IJCAI 2026 presentation](./Slides/DHGSurvey-Slides-IJCAI2026.pdf) and [CNCC 2026 tutorial](./Slides/CNCC2026-DHG.pdf).

⭐ If you find this paper list useful, please consider giving the repository a star to follow future updates.

## Contents

- [Embedding-based Papers](#1-embedding-based-papers)
- [GNN-based Papers](#2-gnn-based-papers)
- [Transformer-based Papers](#3-transformer-based-papers)
- [Application-oriented Papers](#4-application-oriented-papers)
- [Related Methods and Benchmarks](#5-related-methods-and-benchmarks)
- [Downstream Task Legend](#downstream-task-legend)
- [Datasets](#datasets)
- [Citation](#citation)

## Downstream Task Legend

| Badge | Downstream task | Badge | Downstream task |
|:---:|---|:---:|---|
| ![NC](https://img.shields.io/badge/NC-4C78A8) | Node Classification | ![LP](https://img.shields.io/badge/LP-E76F51) | Link Prediction |
| ![TLP](https://img.shields.io/badge/TLP-D1495B) | Temporal Link Prediction | ![RP](https://img.shields.io/badge/RP-F4A261) | Relation Prediction |
| ![NClust](https://img.shields.io/badge/NClust-8E6C8A) | Node Clustering | ![AD](https://img.shields.io/badge/AD-D45087) | Anomaly Detection |
| ![NR](https://img.shields.io/badge/NR-2A9D8F) | Node Regression | ![NP](https://img.shields.io/badge/NP-72B7B2) | Node Prediction |

Application-specific badges use their full task or domain names directly.

## Paper List

### 1. Embedding-based Papers

1. [INS 2024] **Dynamic heterogeneous attributed network embedding** [[paper]](https://doi.org/10.1016/j.ins.2024.120264) [[code]](https://github.com/cs-recommendation/online-recommendation) ![NC](https://img.shields.io/badge/NC-4C78A8)
2. [ISWC 2023] **H2TNE: Temporal Heterogeneous Information Network Embedding in Hyperbolic Spaces** [[pdf]](https://arxiv.org/pdf/2304.06970) [[code]](https://github.com/TaiLvYuanLiang/H2TNE) ![NC](https://img.shields.io/badge/NC-4C78A8) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
3. [PR 2023] **Higher-order memory guided temporal random walk for dynamic heterogeneous network embedding** [[paper]](https://doi.org/10.1016/j.patcog.2023.109766) [[code]](https://github.com/RingBDStack/HoMo-DyHNE) ![NC](https://img.shields.io/badge/NC-4C78A8) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
4. [TKDE 2023] **Temporal heterogeneous information network embedding via semantic evolution** [[paper]](https://doi.org/10.1109/TKDE.2023.3287260) [[code]](https://github.com/CGCL-codes/SemE) ![NC](https://img.shields.io/badge/NC-4C78A8) ![RP](https://img.shields.io/badge/RP-F4A261) ![TLP](https://img.shields.io/badge/TLP-D1495B)
5. [Mathematics 2022] **DHGEEP: A Dynamic Heterogeneous Graph-Embedding Method for Evolutionary Prediction** [[pdf]](https://www.mdpi.com/2227-7390/10/22/4193/pdf?version=1668002961) ![RP](https://img.shields.io/badge/RP-F4A261) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
6. [TKDE 2022] **Dynamic Heterogeneous Information Network Embedding With Meta-Path Based Proximity** [[paper]](https://doi.org/10.1109/TKDE.2020.2993870) [[code]](https://github.com/rootlu/DyHNE) ![NC](https://img.shields.io/badge/NC-4C78A8) ![RP](https://img.shields.io/badge/RP-F4A261) ![TLP](https://img.shields.io/badge/TLP-D1495B)
7. [TC 2022] **LIME: Low-Cost and Incremental Learning for Dynamic Heterogeneous Information Networks** [[pdf]](https://eprints.whiterose.ac.uk/id/eprint/170825/1/tc2021.pdf) [[code]](https://github.com/RingBDStack/LIME) ![NC](https://img.shields.io/badge/NC-4C78A8) ![NClust](https://img.shields.io/badge/NClust-8E6C8A) ![AD](https://img.shields.io/badge/AD-D45087)
8. [Comput. J. 2022] **Multi-view Dynamic Heterogeneous Information Network Embedding** [[pdf]](https://arxiv.org/pdf/2011.06346) ![NC](https://img.shields.io/badge/NC-4C78A8) ![RP](https://img.shields.io/badge/RP-F4A261)
9. [TOIS 2022] **Scalable Representation Learning for Dynamic Heterogeneous Information Networks via Metagraphs** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3485189) ![NC](https://img.shields.io/badge/NC-4C78A8) ![NP](https://img.shields.io/badge/NP-72B7B2) ![TLP](https://img.shields.io/badge/TLP-D1495B) ![AD](https://img.shields.io/badge/AD-D45087)
10. [Acta Electronica Sinica 2022] **基于元路径的动态异质网络表示学习** [[paper]](https://doi.org/10.12263/DZXB.20211288) ![NC](https://img.shields.io/badge/NC-4C78A8)
11. [PKDD 2021] **Dynamic Heterogeneous Graph Embedding via Heterogeneous Hawkes Process** [[paper]](https://doi.org/10.1007/978-3-030-86486-6_24) [[code]](https://github.com/BUPT-GAMMA/HPGE) ![NC](https://img.shields.io/badge/NC-4C78A8) ![TLP](https://img.shields.io/badge/TLP-D1495B)
12. [WSDM 2021] **Learning and Updating Node Embedding on Dynamic Heterogeneous Information Network** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3437963.3441745) ![TLP](https://img.shields.io/badge/TLP-D1495B)
13. [IJCAI 2021] **Temporal Heterogeneous Information Network Embedding** [[pdf]](https://www.ijcai.org/proceedings/2021/0203.pdf) [[code]](https://github.com/S-rz/THINE) ![NC](https://img.shields.io/badge/NC-4C78A8) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
14. [ICC 2021] **Towards a Translation-Based Method for Dynamic Heterogeneous Network Embedding** [[paper]](https://doi.org/10.1109/ICC42927.2021.9500303) ![NC](https://img.shields.io/badge/NC-4C78A8)
15. [CR&D 2021] **基于非递减时序随机游走的动态异质网络嵌入** [[paper]](https://doi.org/10.7544/issn1000-1239.2021.20210317) [[code]](https://github.com/guaw/TNDE) ![NC](https://img.shields.io/badge/NC-4C78A8) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
16. [ACCESS 2019] **DHNE: Network Representation Learning Method for Dynamic Heterogeneous Networks** [[pdf]](https://ieeexplore.ieee.org/ielx7/6287639/8600701/08843962.pdf) [[code]](https://github.com/Yvonneupup/DHNE) ![NC](https://img.shields.io/badge/NC-4C78A8)
17. [SIGIR 2019] **Network Embedding and Change Modeling in Dynamic Heterogeneous Networks** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3331184.3331273) [[code]](https://github.com/Change2vec/change2vec) ![NClust](https://img.shields.io/badge/NClust-8E6C8A)
18. [ECIR 2019] **Relationship Prediction in Dynamic Heterogeneous Information Networks** [[paper]](https://doi.org/10.1007/978-3-030-15712-8_2) [[code]](https://github.com/nyit-vancouver/LinkPrediction) ![RP](https://img.shields.io/badge/RP-F4A261) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
19. [CR&D 2015] **基于动态异构信息网络的时序关系预测** [[paper]](https://doi.org/10.7544/issn1000-1239.2015.20150183) ![NR](https://img.shields.io/badge/NR-2A9D8F)

### 2. GNN-based Papers

1. [WWW'25 Companion 2025] **Heterogeneous Temporal Graph Neural Networks for Link Prediction** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3701716.3715474) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
2. [IJCAI 2025] **Heterogeneous Temporal Hypergraph Neural Network** [[pdf]](https://www.ijcai.org/proceedings/2025/0347.pdf) [[code]](https://github.com/huanliucs/HTHGN) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
3. [WWW 2025] **ReadGraph: Relational Evolution Enhanced Anomaly Detection in Dynamic Heterogeneous Graph** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3701716.3715509) ![AD](https://img.shields.io/badge/AD-D45087)
4. [WWW 2025] **TESA: A Trajectory and Semantic-aware Dynamic Heterogeneous Graph Neural Network** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3696410.3714918) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
5. [arXiv 2024] **CTRL: Continuous-Time Representation Learning on Temporal Heterogeneous Information Network** [[pdf]](https://arxiv.org/pdf/2405.08013) [[code]](https://github.com/ycy89/CTRL) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
6. [TBD 2024] **HGN2T: A Simple but Plug-and-Play Framework Extending HGNNs on Heterogeneous Temporal Graphs** [[paper]](https://doi.org/10.1109/TBDATA.2024.3366085) [[code]](https://github.com/huanliucs/HGN2T) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
7. [TKDD 2024] **Neighbor-Enhanced Representation Learning for Link Prediction in Dynamic Heterogeneous Attributed Networks** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3676559) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
8. [ECAI 2024] **Relation Time-Aware Heterogeneous Dynamic Graph Neural Networks** [[paper]](https://doi.org/10.3233/FAIA240699) ![NC](https://img.shields.io/badge/NC-4C78A8) ![NR](https://img.shields.io/badge/NR-2A9D8F) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
9. [EAAI 2024] **TemporalHAN: Hierarchical attention-based heterogeneous temporal network embedding** [[paper]](https://doi.org/10.1016/j.engappai.2024.108376) ![NC](https://img.shields.io/badge/NC-4C78A8) ![RP](https://img.shields.io/badge/RP-F4A261)
10. [arXiv 2023] **DURENDAL: Graph deep learning framework for temporal heterogeneous networks** [[paper]](https://openreview.net/forum?id=77Tyf2SFhX) [[code]](https://anonymous.4open.science/r/durendal-5154) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
11. [INS 2023] **DyHNet: Learning dynamic heterogeneous network representations** [[pdf]](https://www.researchsquare.com/article/rs-2327811/latest.pdf) [[code]](https://github.com/hoangntc/DyHNet) ![NC](https://img.shields.io/badge/NC-4C78A8) ![TLP](https://img.shields.io/badge/TLP-D1495B)
12. [CIKM 2023] **Heterogeneous Temporal Graph Neural Network Explainer** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3583780.3614909) ![Explainability](https://img.shields.io/badge/Explainability-5E60CE)
13. [Neurocomputing 2023] **Multi-relational dynamic graph representation learning** [[paper]](https://doi.org/10.1016/j.neucom.2023.126688) ![RP](https://img.shields.io/badge/RP-F4A261) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
14. [TKDE 2023] **When Convolutional Network Meets Temporal Heterogeneous Graphs: An Effective Community Detection Method** [[paper]](https://doi.org/10.1109/TKDE.2021.3096122) ![NClust](https://img.shields.io/badge/NClust-8E6C8A)
15. [CR&D 2023] **基于对比学习的全局增强动态异质图神经网络** [[paper]](https://doi.org/10.7544/issn1000-1239.202330226) [[code]](https://github.com/huanliucs/HTGCL) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
16. [Applied Sciences 2022] **A Dynamic Heterogeneous Information Network Embedding Method Based on Meta-Path and Improved Rotate Model** [[pdf]](https://www.mdpi.com/2076-3417/12/21/10898/pdf) ![NC](https://img.shields.io/badge/NC-4C78A8)
17. [SDM 2022] **Heterogeneous Temporal Graph Neural Network** [[pdf]](https://epubs.siam.org/doi/pdf/10.1137/1.9781611977172.74) [[code]](https://github.com/YesLab-Code/HTGNN) ![NR](https://img.shields.io/badge/NR-2A9D8F) ![TLP](https://img.shields.io/badge/TLP-D1495B)
18. [ICPICS 2021] **Link Prediction in Dynamic Heterogeneous Networks via a Novel Embedding Technique** [[paper]](https://doi.org/10.1109/ICPICS52425.2021.9524174) ![LP](https://img.shields.io/badge/LP-E76F51)
19. [PKDD 2021] **Modeling Dynamic Heterogeneous Network for Link Prediction Using Hierarchical Attention with Temporal RNN** [[pdf]](https://arxiv.org/pdf/2004.01024) [[code]](https://github.com/skx300/DyHATR) ![TLP](https://img.shields.io/badge/TLP-D1495B)
20. [PR&AI 2021] **基于元路径与层次注意力的时序异质信息网络表示学习方法** [[paper]](https://doi.org/10.16451/j.cnki.issn1003-6059.202112003) ![NC](https://img.shields.io/badge/NC-4C78A8)
21. [ECIR 2020] **Dynamic heterogeneous graph embedding using hierarchical attentions** [[paper]](https://doi.org/10.1007/978-3-030-45442-5_53) ![TLP](https://img.shields.io/badge/TLP-D1495B)
22. [ICBK 2020] **Heterogeneous Dynamic Graph Attention Network** [[paper]](https://doi.org/10.1109/ICBK50248.2020.00064) ![NC](https://img.shields.io/badge/NC-4C78A8) ![NClust](https://img.shields.io/badge/NClust-8E6C8A)

### 3. Transformer-based Papers

1. [CCIS 2025] **A Unified Framework for Link Prediction on Heterogeneous Temporal Graph** [[paper]](https://doi.org/10.1007/978-981-96-0055-7_26) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
2. [SIGIR 2025] **HTGformer: Heterogeneous Temporal Graph Transformer** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3726302.3730209) ![NC](https://img.shields.io/badge/NC-4C78A8) ![NR](https://img.shields.io/badge/NR-2A9D8F) ![RP](https://img.shields.io/badge/RP-F4A261) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
3. [arXiv 2025] **Simple and Efficient Heterogeneous Temporal Graph Neural Network** [[pdf]](https://arxiv.org/pdf/2510.18467) ![NC](https://img.shields.io/badge/NC-4C78A8) ![NR](https://img.shields.io/badge/NR-2A9D8F) ![RP](https://img.shields.io/badge/RP-F4A261) ![TLP](https://img.shields.io/badge/TLP-D1495B)
4. [SIGIR 2024] **LLM-enhanced Cascaded Multi-level Learning on Temporal Heterogeneous Graphs** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3626772.3657731) [[code]](https://github.com/PasaLab/CasMLN) ![NC](https://img.shields.io/badge/NC-4C78A8) ![NR](https://img.shields.io/badge/NR-2A9D8F) ![RP](https://img.shields.io/badge/RP-F4A261) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
5. [AAAI 2023] **Dynamic Heterogeneous Graph Attention Neural Search** [[paper]](https://doi.org/10.1609/aaai.v37i9.26338) [[code]](https://github.com/wondergo2017/DHGAS) ![NC](https://img.shields.io/badge/NC-4C78A8) ![NR](https://img.shields.io/badge/NR-2A9D8F) ![RP](https://img.shields.io/badge/RP-F4A261) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
6. [Neurocomputing 2023] **Dynamic heterogeneous graph representation learning with neighborhood type modeling** [[paper]](https://doi.org/10.1016/j.neucom.2023.02.060) [[code]](https://github.com/linz2000/THGAT) ![NC](https://img.shields.io/badge/NC-4C78A8) ![NClust](https://img.shields.io/badge/NClust-8E6C8A) ![TLP](https://img.shields.io/badge/TLP-D1495B)
7. [CIKM 2023] **Simplifying Temporal Heterogeneous Network for Continuous-Time Link prediction** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3583780.3615059) [[code]](https://github.com/celi52/STHN) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
8. [IJCNN 2022] **A Link Prediction Model of Dynamic Heterogeneous Network Based on Transformer** [[paper]](https://doi.org/10.1109/IJCNN55064.2022.9892546) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
9. [WWW 2020] **Heterogeneous Graph Transformer** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3366423.3380027) [[code]](https://github.com/acbull/pyHGT) ![TLP](https://img.shields.io/badge/TLP-D1495B)

### 4. Application-oriented Papers

#### Cybersecurity

1. [Computers & Security 2025] **ATHITD: Attention-based temporal heterogeneous graph neural network for insider threat detection** [[paper]](https://doi.org/10.1016/j.cose.2025.104587) ![Threat Detection](https://img.shields.io/badge/Threat%20Detection-6C757D)
2. [IJCNN 2025] **DMT-DHIN: A Dynamic Heterogeneous Information Network Framework for Detecting Malicious Encrypted Traffic** [[paper]](https://doi.org/10.1109/IJCNN64981.2025.11227646) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
3. [JNCA 2025] **Sybil attack detection and traceability scheme based on temporal heterogeneous graph attention networks** [[paper]](https://doi.org/10.1016/j.jnca.2025.104261) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
4. [ASC 2024] **Hacker group identification based on dynamic heterogeneous graph node update** [[paper]](https://doi.org/10.1016/J.ASOC.2024.111587) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
5. [MSPN 2024] **StrucTemp-GNN: An Intrusion Detection Framework in IoT Networks Using Dynamic Heterogeneous Graph Neural Networks** [[paper]](https://doi.org/10.1007/978-3-031-52426-4_2) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
6. [DASFAA 2024] **Crowdsourcing Fraud Detection Over Heterogeneous Temporal MMMA Graph** [[pdf]](https://arxiv.org/pdf/2308.02793) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
7. [ASC 2023] **Improved Model for Hacker Group Identifification Based on Dynamic Heterogeneous Graph Node Update** [[paper]](https://doi.org/10.2139/ssrn.4412749) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
8. [CIKM 2023] **THGNN: An Embedding-based Model for Anomaly Detection in Dynamic Heterogeneous Social Networks** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3583780.3615079) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
9. [KBS 2022] **Cyber threat prediction using dynamic heterogeneous graph learning** [[paper]](https://doi.org/10.1016/j.knosys.2021.108086) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
10. [WCMC 2022] **Detecting Unknown Threat Based on Continuous-Time Dynamic Heterogeneous Graph Network** [[pdf]](https://downloads.hindawi.com/journals/wcmc/2022/7502294.pdf) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
11. [PRICAI 2022] **Multi-view Heterogeneous Temporal Graph Neural Network for "Click Farming" Detection** [[paper]](https://doi.org/10.1007/978-3-031-20862-1_11) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
12. [ICME 2022] **Hierarchical Multi-Modal Fusion on Dynamic Heterogeneous Graph for Health Insurance Fraud Detection** [[paper]](https://doi.org/10.1109/ICME52920.2022.9859871) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
13. [KDD 2021] **Heterogeneous Temporal Graph Transformer: An Intelligent System for Evolving Android Malware Detection** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467168) [[code]](https://github.com/kdd2021drdroid/KDD2021_DrDroid/tree/main) ![Malware Detection](https://img.shields.io/badge/Malware%20Detection-6C757D)
14. [IJCAI 2021] **MG-DVD: A Real-time Framework for Malware Variant Detection Based on Dynamic Heterogeneous Graph Learning** [[pdf]](https://www.ijcai.org/proceedings/2021/0209.pdf) ![Malware Detection](https://img.shields.io/badge/Malware%20Detection-6C757D)
15. [NSS 2021] **An Architecture for Processing a Dynamic Heterogeneous Information Network of Security Intelligence** [[paper]](https://doi.org/10.1007/978-3-030-92708-0_11) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)
16. [WWW 2020] **Entity Resolution in Dynamic Heterogeneous Networks** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3366424.3391264) ![Fraud Detection](https://img.shields.io/badge/Fraud%20Detection-6C757D)
17. [arXiv 2020] **Suspicious massive registration detection via dynamic heterogeneous graph neural network** [[pdf]](https://arxiv.org/pdf/2012.10831) ![Cybersecurity](https://img.shields.io/badge/Cybersecurity-B22222)

#### Traffic

1. [LNCS 2025] **Spatio-Temporal Heterogeneous Graph Neural Network With Multi-view Learning For Traffic Prediction** [[paper]](https://doi.org/10.1007/978-3-031-78183-4_3) ![Traffic](https://img.shields.io/badge/Traffic-E9C46A)
2. [CCIE2024 2024] **Dynamic Spatial-Temporal Heterogeneous Graph Convolutional Network for Traffic Prediction** [[paper]](https://doi.org/10.1007/978-981-97-6937-7_9) ![Traffic](https://img.shields.io/badge/Traffic-E9C46A)
3. [INFFUS 2024] **Towards integrated and fine-grained traffic forecasting: A Spatio-Temporal Heterogeneous Graph Transformer approach** [[paper]](https://doi.org/10.1016/j.inffus.2023.102063) ![Traffic Forecasting](https://img.shields.io/badge/Traffic%20Forecasting-6C757D)
4. [INFFUS 2023] **Improving airport arrival flow prediction considering heterogeneous and dynamic network dependencies** [[paper]](https://doi.org/10.1016/j.inffus.2023.101924) ![Traffic](https://img.shields.io/badge/Traffic-E9C46A)
5. [KDD 2020] **Dynamic Heterogeneous Graph Neural Network for Real-time Event Prediction** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403373) ![CTR Prediction](https://img.shields.io/badge/CTR%20Prediction-6C757D)
6. [KDD 2020] **HetETA: Heterogeneous Information Network Embedding for Estimating Time of Arrival** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403294) [[code]](https://github.com/didi/heteta) ![Estimated Time Arrival](https://img.shields.io/badge/Estimated%20Time%20Arrival-6C757D)

#### Recommendation

1. [ECR 2025] **Dynamic heterogeneous graph convolutional networks for click-through rate prediction in recommender systems** [[paper]](https://doi.org/10.1007/s10660-025-09978-y) ![Recommendation](https://img.shields.io/badge/Recommendation-2A9D8F)
2. [ICDM 2024] **Periodic Prompt on Dynamic Heterogeneous Graph for Next Basket Recommendation** [[paper]](https://doi.org/10.1109/ICDM59182.2024.00087) [[code]](https://github.com/AllminerLab) ![Recommendation](https://img.shields.io/badge/Recommendation-2A9D8F)
3. [ICDE 2023] **Instant Representation Learning for Recommendation over Large Dynamic Graphs** [[pdf]](https://arxiv.org/pdf/2305.18622) [[code]](https://github.com/NoMultiply/SUPA) ![Recommendation](https://img.shields.io/badge/Recommendation-2A9D8F)
4. [TKDD 2023] **Learning Shared Representations for Recommendation with Dynamic Heterogeneous Graph Convolutional Networks** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3565575) ![Recommendation](https://img.shields.io/badge/Recommendation-2A9D8F)
5. [KBS 2022] **Content-aware Recommendation via Dynamic Heterogeneous Graph Convolutional Network** [[paper]](https://doi.org/10.1016/j.knosys.2022.109185) ![Recommendation](https://img.shields.io/badge/Recommendation-2A9D8F)
6. [SDM 2021] **Sequence-aware Heterogeneous Graph Neural Collaborative Filtering** [[paper]](https://doi.org/10.1137/1.9781611976700) [[code]](https://github.com/LeeChenChen/SHCF) ![Recommendation](https://img.shields.io/badge/Recommendation-2A9D8F)
7. [ICDE 2021] **Sequential recommendation on dynamic heterogeneous information network** [[paper]](https://doi.org/10.1109/ICDE51399.2021.00208) ![Recommendation](https://img.shields.io/badge/Recommendation-2A9D8F)
8. [FGCS 2021] **Temporal sensitive heterogeneous graph neural network for news recommendation** [[pdf]](https://academica-e.unavarra.es/bitstreams/bb696c54-fd7f-4f43-8a8f-416d22c00e2d/download) ![Recommendation](https://img.shields.io/badge/Recommendation-2A9D8F)

#### Multimodal

1. [Neural Networks 2026] **Dual-level dynamic heterogeneous graph network for video question answering** [[paper]](https://doi.org/10.1016/j.neunet.2025.108094) ![Multimodal](https://img.shields.io/badge/Multimodal-7B2CBF)
2. [TPAMI 2025] **Cross-Modal 3D Shape Retrieval via Heterogeneous Dynamic Graph Representation** [[paper]](https://doi.org/10.1109/TPAMI.2024.3524440) ![Information Retrieval](https://img.shields.io/badge/Information%20Retrieval-6C757D)
3. [JIIS 2025] **Intentional tendency-based dynamic heterogeneous graph network for emotion recognition in conversations** [[paper]](https://doi.org/10.1007/s10844-025-00925-9) ![Multimodal](https://img.shields.io/badge/Multimodal-7B2CBF)
4. [TAC 2025] **Two-Stream Dynamic Heterogeneous Graph Recurrent Neural Network for Multi-Label Multi-Modal Emotion Recognition** [[paper]](https://doi.org/10.1109/TAFFC.2025.3561439) ![Emotion Recognition](https://img.shields.io/badge/Emotion%20Recognition-6C757D)
5. [NCA 2024] **Document-level multi-task learning approach based on coreference-aware dynamic heterogeneous graph network for event extraction** [[paper]](https://doi.org/10.1007/s00521-023-08977-0) ![Multimodal](https://img.shields.io/badge/Multimodal-7B2CBF)
6. [TMM 2024] **HSSHG: Heuristic Semantics-Constrained Spatio-Temporal Heterogeneous Graph for VideoQA** [[paper]](https://doi.org/10.1109/TMM.2024.3443661) ![VideoQA](https://img.shields.io/badge/VideoQA-6C757D)
7. [ACL 2023] **Dynamic Heterogeneous-Graph Reasoning with Language Models and Knowledge Representation Learning for Commonsense Question Answering** [[pdf]](https://aclanthology.org/2023.acl-long.785.pdf) ![Multimodal](https://img.shields.io/badge/Multimodal-7B2CBF)
8. [arXiv 2023] **STHG: Spatial-Temporal Heterogeneous Graph Learning for Advanced Audio-Visual Diarization** [[pdf]](https://arxiv.org/pdf/2306.10608) ![Multimodal](https://img.shields.io/badge/Multimodal-7B2CBF)
9. [arXiv 2020] **Jointly modeling aspect and sentiment with dynamic heterogeneous graph neural networks** [[pdf]](https://arxiv.org/pdf/2004.06427) ![Multimodal](https://img.shields.io/badge/Multimodal-7B2CBF)

#### Social computing

1. [IPM 2025] **DyHGTCR-Cas: Learning unified spatio-temporal features based on dynamic heterogeneous graph neural network for information cascade prediction** [[paper]](https://doi.org/10.1016/j.ipm.2024.104029) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
2. [JCDL 2025] **A dynamic heterogeneous graph attention fusion network for citation intent classification of scientific publications** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3677389.3702499) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
3. [JKSUCIS 2025] **DHGNN: A dynamic heterogeneous graph neural network for interpretable inventor collaboration prediction** [[paper]](https://doi.org/10.1007/S44443-025-00255-4) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
4. [IJOC 2025] **Social Network Prediction Problems: Using Meta-Paths and Dynamic Heterogeneous Graph Representation for Label Propagation** [[paper]](https://doi.org/10.1287/ijoc.2023.0274) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
5. [IPM 2025] **Technology convergence prediction based on temporal heterogeneous graph neural networks** [[paper]](https://doi.org/10.1016/j.ipm.2024.104034) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
6. [CIKM 2024] **DiHAN: A Novel Dynamic Hierarchical Graph Attention Network for Fake News Detection** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3627673.3679675) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
7. [TKDD 2023] **Community-Based Influence Maximization Using Network Embedding in Dynamic Heterogeneous Social Networks** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3594544) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
8. [TKDE 2023] **A Trend of AI Conference Convergence in Similarity: An Empirical Study Through Trans-Temporal Heterogeneous Graph** [[paper]](https://doi.org/10.1109/TKDE.2023.3243602) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
9. [ACM ICPS 2023] **HTGAT: A Heterogeneous Temporal Graph Attention Network for Scholars' Impact Prediction** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3644523.3644594) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
10. [CIKM 2023] **Modeling dynamic heterogeneous graph and node importance for future citation prediction** [[pdf]](https://arxiv.org/pdf/2305.17417) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
11. [DASFAA 2022] **A Dynamic Heterogeneous Graph Perception Network with Time-Based Mini-Batch for Information Diffusion Prediction** [[paper]](https://doi.org/10.1007/978-3-031-00123-9_49) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
12. [KBS 2022] **Heterogeneous dynamical academic network for learning scientific impact propagation** [[paper]](https://doi.org/10.1016/j.knosys.2021.107839) [[code]](https://github.com/xovee/si-hdgnn) ![Impact Prediction](https://img.shields.io/badge/Impact%20Prediction-6C757D)
13. [KDD 2022] **Talent Demand-Supply Joint Prediction with Dynamic Heterogeneous Graph Enhanced Meta-Learning** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539139) [[code]](https://github.com/gzn00417/DH-GEM) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
14. [NCA 2022] **Heterogeneous information network embedding for user behavior analysis on social media** [[paper]](https://doi.org/10.1007/s00521-021-06706-z) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
15. [WWW 2021] **HINTS: Citation Time Series Prediction for New Publications via Dynamic Heterogeneous Information Network Embedding** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3442381.3450107) ![Impact Prediction](https://img.shields.io/badge/Impact%20Prediction-6C757D)
16. [arXiv 2020] **A Heterogeneous Dynamical Graph Neural Networks Approach to Quantify Scientific Impact** [[pdf]](https://arxiv.org/pdf/2003.12042) [[code]](https://github.com/celi52/si-hdgnn) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
17. [PKDD 2020] **DyHGCN: A Dynamic Heterogeneous Graph Convolutional Network to Learn Users' Dynamic Preferences for Information Diffusion Prediction** [[pdf]](https://arxiv.org/pdf/2006.05169) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
18. [INS 2020] **Noise-based Synchronization of Bounded Confidence Opinion Dynamics in Heterogeneous Time-Varying Communication Networks** [[paper]](https://doi.org/10.1016/j.ins.2020.04.018) ![Social computing](https://img.shields.io/badge/Social%20computing-118AB2)
19. [TKDE 2018] **NetCycle+: A Framework for Collective Evolution Inference in Dynamic Heterogeneous Networks** [[paper]](https://doi.org/10.1109/TKDE.2018.2792020) ![Collective inference](https://img.shields.io/badge/Collective%20inference-6C757D)

#### Healthcare and Biomedicine

1. [LNCS 2026] **Knowledge-Enhanced Complementary Information Fusion with Temporal Heterogeneous Graph Learning for Disease Prediction** [[paper]](https://doi.org/10.1007/978-3-032-05162-2_41) ![Healthcare](https://img.shields.io/badge/Healthcare-2D6A4F)
2. [IJMS 2025] **DynHeter-DTA: Dynamic Heterogeneous Graph Representation for Drug-Target Binding Affinity Prediction** [[paper]](https://doi.org/10.3390/ijms26031223) ![Drug](https://img.shields.io/badge/Drug-2D6A4F)
3. [ARRAY 2025] **Multimodal data fusion for Alzheimer's disease based on dynamic heterogeneous graph convolutional neural network and generative adversarial network** [[paper]](https://doi.org/10.1016/j.array.2025.100415) ![Healthcare](https://img.shields.io/badge/Healthcare-2D6A4F)
4. [JBHI 2024] **Drug-Target Prediction Based on Dynamic Heterogeneous Graph Convolutional Network** [[paper]](https://doi.org/10.1109/JBHI.2024.3441324) ![Drug](https://img.shields.io/badge/Drug-2D6A4F)
5. [EMBC 2024] **HeteroEEG: A Dual-Branch Spatial-Spectral-Temporal Heterogeneous Graph Network for EEG Classification** [[paper]](https://doi.org/10.1109/EMBC53108.2024.10781679) ![Healthcare](https://img.shields.io/badge/Healthcare-2D6A4F)
6. [arXiv 2023] **Heterogeneous temporal representation for diabetic blood glucose prediction** [[pdf]](https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2023.1225638/pdf) ![Healthcare](https://img.shields.io/badge/Healthcare-2D6A4F)
7. [KDD 2022] **Disentangled Dynamic Heterogeneous Graph Learning for Opioid Overdose Prediction** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539279) ![Drug](https://img.shields.io/badge/Drug-2D6A4F)

#### Financial

1. [WWW 2025] **FiGraph: A Dynamic Heterogeneous Graph Dataset for Financial Anomaly Detection** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3701716.3715301) ![Financial](https://img.shields.io/badge/Financial-5B5F97)
2. [Energy Econ. 2024] **Impact of climate risk on energy market risk spillover: Evidence from dynamic heterogeneous network analysis** [[paper]](https://doi.org/10.1016/j.eneco.2024.107775) ![Financial](https://img.shields.io/badge/Financial-5B5F97)
3. [ICAIF 2023] **The Network of Mutual Funds: A Dynamic Heterogeneous Graph Neural Network for Estimating Mutual Funds Performance** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3604237.3626910) ![Financial](https://img.shields.io/badge/Financial-5B5F97)
4. [CIKM 2022] **Temporal and Heterogeneous Graph Neural Network for Financial Time Series Prediction** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3511808.3557089) [[code]](https://github.com/TongjiFinLab/THGNN) ![Time Series Prediction](https://img.shields.io/badge/Time%20Series%20Prediction-6C757D)

#### Education and Knowledge Services

1. [ICoAILO 2025] **Exploring Temporal Heterogeneous Graph Deep Learning and Machine Learning Models for Predicting Student Success** [[paper]](https://doi.org/10.1109/ICoAILO66760.2025.11155968) ![Education](https://img.shields.io/badge/Education-F4A261)
2. [arXiv 2025] **IssueCourier: Multi-Relational Heterogeneous Temporal Graph Neural Network for Open-Source Issue Assignment** [[pdf]](https://arxiv.org/pdf/2505.11205) ![Education](https://img.shields.io/badge/Education-F4A261)
3. [ASC 2024] **Dynamic heterogeneous graph contrastive networks for knowledge tracing** [[paper]](https://doi.org/10.1016/j.asoc.2024.112194) ![Education](https://img.shields.io/badge/Education-F4A261)
4. [TOIS 2024] **Heterogeneous Evolution Network Embedding with Temporal Extension for Intelligent Tutoring Systems** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3617828) ![Education](https://img.shields.io/badge/Education-F4A261)
5. [IJSAEM 2023] **Application of app intelligent voice software based on dynamic heterogeneous network in TPACK oral English teaching** [[paper]](https://doi.org/10.1007/s13198-023-02117-6) ![Education](https://img.shields.io/badge/Education-F4A261)

#### Industrial and Decision Systems

1. [COR 2026] **A novel learning model with dynamic heterogeneous graph network for uncertain multimode resource-constrained project scheduling problem** [[paper]](https://doi.org/10.1016/j.cor.2025.107319) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
2. [ESWA 2026] **Dynamic heterogeneous graph combined with reinforcement learning for solving job shop scheduling problem** [[paper]](https://doi.org/10.1016/j.eswa.2025.130249) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
3. [DBE 2026] **Intelligent diagnosis of water supply pipe leakage based on multi-modal information fusion and improved heterogeneous temporal graph neural network** [[paper]](https://doi.org/10.1016/j.dibe.2025.100825) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
4. [Applied Sciences 2025] **DHGAR: Multi-Variable-Driven Wind Power Prediction Model Based on Dynamic Heterogeneous Graph Attention Recurrent Network** [[paper]](https://doi.org/10.3390/app15041862) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
5. [Romanian Academy A 2025] **Dynamic heterogeneous graph neural networks for anomaly detection in supply chains** [[pdf]](https://acad.ro/sectii2002/proceedings/doc2025-2/PRA_2025_2_10-Zhao_Feng.pdf) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
6. [Electronics 2025] **Ultra-Short-Term Photovoltaic Cluster Power Prediction Based on Photovoltaic Cluster Dynamic Clustering and Spatiotemporal Heterogeneous Dynamic Graph Modeling** [[paper]](https://doi.org/10.3390/electronics14183641) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
7. [IEICETD 2024] **Agent Allocation-Action Learning with Dynamic Heterogeneous Graph in Multi-Task Games** [[paper]](https://doi.org/10.1587/transinf.2023EDP7180) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
8. [JSTARS 2024] **Heterogeneous dynamic graph convolutional networks for enhanced spatiotemporal flood forecasting by remote sensing** [[paper]](https://doi.org/10.1109/JSTARS.2023.3349162) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
9. [CC 2024] **Heterogeneous temporal graph powered DRL algorithm for channel allocation in Maritime IoT Systems** [[paper]](https://doi.org/10.1016/j.comcom.2023.11.005) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
10. [ROBIO 2024] **Learning Goal-oriented Bimanual Dough Rolling Using Dynamic Heterogeneous Graph Based on Human Demonstration** [[pdf]](https://arxiv.org/pdf/2410.22355) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
11. [WWWJ 2024] **Multi-temporal heterogeneous graph learning with pattern-aware attention for industrial chain risk detection** [[paper]](https://doi.org/10.1007/s11280-024-01280-5) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
12. [arXiv 2024] **Virtual Sensor for Real-Time Bearing Load Prediction Using Heterogeneous Temporal Graph Neural Networks** [[pdf]](https://arxiv.org/pdf/2404.02304) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
13. [GANDC 2023] **Spatio-temporal heterogeneous graph using multivariate earth observation time series: Application for drought forecasting** [[paper]](https://doi.org/10.1016/j.cageo.2023.105435) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
14. [HPCC 2022] **Multi-Value Chain Auto Parts Demand Prediction Based on Dynamic Heterogeneous Graph Convolution** [[paper]](https://doi.org/10.1109/HPCC-DSS-SmartCity-DependSys57074.2022.00331) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)
15. [CCOMS 2022] **Spatial-Temporal Heterogeneous Graph Modeling for Opponent's Location Prediction in War-game** [[paper]](https://doi.org/10.1109/ICCCS55155.2022.9846737) ![Industrial Systems](https://img.shields.io/badge/Industrial%20Systems-795548)

### 5. Related Methods and Benchmarks

1. [NeurIPS 2024] **TGB 2.0: A Benchmark for Learning on Temporal Knowledge Graphs and Heterogeneous Graphs** [[pdf]](https://arxiv.org/pdf/2406.09639) ![Benchmark](https://img.shields.io/badge/Benchmark-343A40)
2. [Int. J. Crowd Sci. 2022] **Link Prediction in Continuous-Time Dynamic Heterogeneous Graphs with Causality of Event Types** [[paper]](https://doi.org/10.26599/IJCS.2022.9100013) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
3. [CIKM 2022] **PyDHNet: A Python Library for Dynamic Heterogeneous Network Representation Learning and Evaluation** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3511808.3557181) [[code]](https://github.com/hoangntc/PyDHNet) ![Benchmark](https://img.shields.io/badge/Benchmark-343A40)
4. [TKDD 2019] **Continuous-Time Relationship Prediction in Dynamic Heterogeneous Information Networks** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3333028) [[code]](https://github.com/sisaman/NPGLM) ![LP](https://img.shields.io/badge/LP-E76F51) ![TLP](https://img.shields.io/badge/TLP-D1495B)
5. [MLG 2018] **Temporal Motifs in Heterogeneous Information Networks** [[pdf]](https://yu-shi-homepage.github.io/mlg18.pdf) ![Analysis](https://img.shields.io/badge/Analysis-6C757D)

## Datasets

Official release papers, original data sources, and representative repositories that provide processed data or dataset-specific preparation.

1. **DBLP** — [PVLDB 2009] **DBLP — Some Lessons Learned** [[paper]](https://dblp.org/xml/docu/dblpxml.pdf) [[source data]](https://dblp.org/) [[Change2vec]](https://github.com/Change2vec/change2vec/tree/master/Dataset) [[DHNE]](https://github.com/Yvonneupup/DHNE/tree/master/DHNE/Dblp/dblp_dataset)
2. **AMiner** — [KDD 2008] **ArnetMiner: Extraction and Mining of Academic Social Networks** [[paper]](https://doi.org/10.1145/1401890.1402008) [[source data]](https://www.aminer.cn/) [[DHNE]](https://github.com/Yvonneupup/DHNE/tree/master/DHNE/Aminer/aminer_dataset) [[HoMo-DyHNE]](https://github.com/RingBDStack/HoMo-DyHNE/tree/main/datasets/aminer2)
3. **MAG** — [QSS 2020] **Microsoft Academic Graph: When Experts Are Not Enough** [[paper]](https://www.microsoft.com/en-us/research/publication/microsoft-academic-graph-when-experts-are-not-enough/) [[source data]](https://ogb.stanford.edu/docs/nodeprop/#ogbn-mag) [[HTGNN]](https://github.com/YesLab-Code/HTGNN/tree/main/data)
4. **Twitter** — [Scientific Reports 2013] **The Anatomy of a Scientific Rumor** [[paper]](https://www.nature.com/articles/srep02980) [[source data]](https://snap.stanford.edu/data/higgs-twitter.html) [[MNE]](https://github.com/HKUST-KnowComp/MNE)
5. **COVID** — [arXiv 2020] **CovidNet: To Bring Data Transparency in the Era of COVID-19** [[paper]](https://arxiv.org/abs/2005.10948) [[source data]](https://coronavirus.1point3acres.com/) [[HTGNN]](https://github.com/YesLab-Code/HTGNN/tree/main/data) [[DHGAS]](https://github.com/wondergo2017/DHGAS/tree/main/dhgas/data)
6. **MovieLens** — [ACM TiiS 2015] **The MovieLens Datasets: History and Context** [[paper]](https://files.grouplens.org/papers/harper-tiis2015.pdf) [[source data]](https://grouplens.org/datasets/movielens/) [[NPGLM]](https://github.com/sisaman/NPGLM) [[STHN]](https://github.com/celi52/STHN/tree/main/DATA/movie)
7. **Math-Overflow** — [WSDM 2017] **Motifs in Temporal Networks** [[paper]](https://doi.org/10.1145/3018661.3018731) [[source data]](https://snap.stanford.edu/data/sx-mathoverflow.html) [[STHN]](https://github.com/celi52/STHN)
8. **TGB 2.0** — [NeurIPS 2024] **TGB 2.0: A Benchmark for Learning on Temporal Knowledge Graphs and Heterogeneous Graphs** [[paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/fda026cf2423a01fcbcf1e1e43ee9a50-Paper-Datasets_and_Benchmarks_Track.pdf) [[source data]](https://tgb.complexdatalab.com/docs/thg/) [[TGB]](https://github.com/shenyangHuang/TGB)

## Contact

New papers, code repositories, datasets, and corrections are welcome through issues or pull requests.
For any questions or feedback, feel free to contact [Huan Liu](mailto:huanliu@hdu.edu.cn).

## Citation

If you find DHGSurvey useful in your research or applications, please kindly cite:

```bibtex
@inproceedings{ijcai2026p881,
  title     = {Dynamic Heterogeneous Graph Representation Learning: A Survey},
  author    = {Liu, Huan and Jiao, Pengfei and Yin, Jie and Chen, Hongjiang and Zhao, Zhidong},
  booktitle = {Proceedings of the Thirty-Fifth International Joint Conference on Artificial Intelligence, {IJCAI-26}},
  pages     = {7940--7948},
  year      = {2026},
  doi       = {10.24963/ijcai.2026/881}
}
```

