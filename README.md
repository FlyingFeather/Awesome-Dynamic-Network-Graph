# Awesome-Dynamic-Network-Graph
该库收集了大量与动态/时间网络(图)研究相关的论文。不断完善更新中。
This repository collects a lot of papers related to research of dynamic/temporal network(graph). It's a work in progress

Structure: 图的结构类型
Description: 快照还是连续时间、有无监督

Paper  | Method&Code| Structure |  Description | Core model | Task | Introduces |
|:--------------------:|:----------:|:------------:|:---------------:|:-----------:|:-----------:|:-----------:|
| | | 
|2021-WWW-Motif-Preserving Dynamic Attributed Network Embedding| [MTSN-[tensorflow]](https://github.com/ZhijunLiu95/MTSN) | Attributed | 快照| 时间卷积 | | |
|2021-sigmod-APAN: Asynchronous Propagation Attention Network for Real-time Temporal Graph Embedding | [APAN-[pytorch]](https://github.com/WangXuhongCN/APAN) |  |  |Mailbox mechanism| | |
|2021-IJCAI-Temporal Heterogeneous Information Network Embedding|[THINE-[pytorch]](https://github.com/S-rz/THINE) | Heterogeneous | 连续时间 |Hawkes过程 | embedding | [notes](https://mp.weixin.qq.com/s/MrZPxaIZ37Yj5Jt1W3MR9g)|
| 2020-AAAI-Dynamic Embedding on Textual Networks via a Gaussian Process | [DetGP-[tensorflow]](https://github.com/Linear95/DetGP) | | | 高斯过程| 文本网络的动态嵌入 | |
| [2020-ICLR TGAT: Inductive representation learning on temporal graphs](https://openreview.net/pdf?id=rJeW1yHYwH)           | [TGAT-[pytorch]](https://drive.google.com/drive/folders/1GaH8vusCXJj4ucayfO-PyHpnNsJRkB78) | - |
| [2020-WSDM DySAT: Deep Neural Representation Learning on Dynamic Graphs via Self-Attention Networks](http://asankar3.web.engr.illinois.edu/files/DySAT-WSDM2020.pdf)| [DySAT-[tensorflow & data]](https://github.com/aravindsankar28/DySAT)                            | Attributed         |
| [EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs](https://arxiv.org/abs/1902.10191)| [EvolveGCN-[pytorch & data]](https://github.com/IBM/EvolveGCN)                            | Attributed          |
| [2019-ICLR DyREP: Learning Representations over Dynamic Graphs](https://openreview.net/forum?id=HyePrhR5KX) | DyREP           | \- | \-          |
| [2019-CIKM MMDNE: Temporal Network Embedding with Micro- and Macro-dynamics](https://arxiv.org/pdf/1909.04246.pdf)   | [[MMDNE-pytorch & data]](https://github.com/rootlu/MMDNE) |   Homogeneous   | 连续时间| skip-gram| embedding   | [notes](https://mp.weixin.qq.com/s/PIbMaV2hWe6NwVj-dlupWQ)|
| [2019-KDD JODIE: Predicting Dynamic Embedding Trajectory in Temporal Interaction Networks](https://www-cs.stanford.edu/~srijan/pubs/jodie-kdd2019.pdf)   | [[JODIE-python & data]](https://github.com/srijankr/jodie/) | Heterogeneous|
| [2019-ECML PKDD node2bits: Compact Time- and Attribute-aware Node Representations for User Stitching](http://web.eecs.umich.edu/~dkoutra/papers/19-PKDD-Node2bits.pdf)   | [[node2bits-python & data]](https://github.com/GemsLab/node2bits) | Attributed & Heterogeneous          |
| [2019-IJCAI tNodeEmbed: Node Embedding over Temporal Graphs](https://www.ijcai.org/proceedings/2019/0640.pdf)         | [[tNodeEmbed-keras]](https://github.com/urielsinger/tNodeEmbed)                            | \-          | 快照|Skip-gram|embedding | |
|2018-KDD-Embedding Temporal Network via Neighborhood Formation| HTNE | Homogeneous|连续时间 | skip-gram | embedding| [notes](https://mp.weixin.qq.com/s/Y9OQZel5r3UktR9Hu_W36g) |
| [2018-AAAI DynamicTriad: Dynamic Network Embedding by Modeling Triadic Closure Process](http://yangy.org/works/dynamictriad/dynamic_triad.pdf)        | [[DynamicTriad-python27 & data]](https://github.com/luckiezhou/DynamicTriad)                 |  -     | 快照| 三元组| task | |
| [2018-TKDE DNPS: Modeling Large-Scale Dynamic Social Networks via Node Embeddings](https://sci-hub.tw/https://ieeexplore.ieee.org/document/8476241/)| DNPS | \-          |
|2018-WWW-Continuous-time dynamic network embeddings| [CTDNE](https://github.com/Shubhranshu-Shekhar/ctdne) | Homogeneous |连续时间 | Skip-gram | embedding | [notes](https://mp.weixin.qq.com/s/_fTM4wmc1Oz2D3XPE6crxQ) |
| [2017-IJCAI-workshop DynGEM: Deep Embedding Method for Dynamic Graphs](https://arxiv.org/abs/1805.11273)|[DynGEM-tensorflow](https://github.com/paulpjoby/DynGEM)         | \-          |
|2017-CIKM-Attributed network embedding for learning in a dynamic | DANE | Attributed | 基于快照 | 基于矩阵分解 | | |
| [2016-TKDE TNE: Scalable Temporal Latent Space Inference for Link Prediction in Dynamic Social Networks](https://arxiv.org/pdf/1411.3675.pdf) | [[TNE-c/c++ & data]](https://github.com/linhongseba/Temporal-Network-Embedding) | \-          |



感谢 https://github.com/seven-echo/dynamic-graph-embedding-method 库查到的部分方法