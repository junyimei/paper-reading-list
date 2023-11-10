# paper-reading-list
Papers about graph sampling framework, GNN system, graph processing and GPU techniques. Inspired by [Literature on Graph Neural Networks Acceleration](https://github.com/BUAA-CI-Lab/Literatures-on-GNN-Acceleration#literature-on-graph-neural-networks-acceleration).

## Graph Sampling
### CPU Graph Sampling
* [**ASPLOS 2023**] NosWalker: A Decoupled Architecture for Out-of-Core Random Walk Processing.
  >*Shuke Wang, Mingxing Zhang, Ke Yang, et al.* [[paper]](https://dl.acm.org/doi/abs/10.1145/3582016.3582025)

* [**ATC 2023**] SOWalker: An I/O-Optimized Out-of-Core Graph Processing System for Second-Order Random Walks.
  >*Yutong Wu, Zhan Shi, et al.* [[paper]](https://www.usenix.org/conference/atc23/presentation/wu)

* [**EuroSys 2023**] TEA: A General-Purpose Temporal Graph Random Walk Engine.
  >*Chengying Huan, Shuaiwen Leon Song, et al.* [[paper]](https://dl.acm.org/doi/abs/10.1145/3552326.3567491)

* [**VLDB 2022**] An I/O-efficient disk-based graph system for scalable second-order random walk of large graphs.
  >*Hongzheng Li, Yingxia Shao, et al.* [[paper]](https://dl.acm.org/doi/10.14778/3529337.3529346)

* [**SOSP 2021**] Random Walks on Huge Graphs at Cache Efficiency.
  >*Ke Yang, Xiaosong Ma, et al.* [[paper]](https://dl.acm.org/doi/10.1145/3477132.3483575)

* [**VLDB 2021**] ThunderRW: an in-memory graph random walk engine.
  >*Shixuan Sun, Yuhang Chen, Shengliang Lu, et al.* [[paper]](https://dl.acm.org/doi/abs/10.14778/3476249.3476257)

* [**ATC 2020**] GraphWalker: An I/O-Efficient and Resource-Friendly Graph Analytic System for Fast and Scalable Random Walks.
  >*Rui Wang, Yongkun Li, et al.* [[paper]](https://www.usenix.org/conference/atc20/presentation/wang-rui)

* [**SOSP 2019**] KnightKing: a fast distributed graph random walk engine.
  >*Ke Yang, MingXing Zhang, Kang Chen, et al.* [[paper]](https://dl.acm.org/doi/10.1145/3341301.3359634)

### Graph Sampling on GPU and FPGA
* [**ICDE 2023**] LightTraffic: On Optimizing CPU-GPU Data Traffic for Efficient Large-scale Random Walks.
  >*Y. Xing, Y. Li, Z. Wang, Y. Xu and J. C. S. Lui.* [[paper]](https://ieeexplore.ieee.org/document/10184564)

* [**SIGMOD 2023**] LightRW: FPGA Accelerated Graph Dynamic Random Walks.
  >*Hongshi Tan, Xinyu Chen, Yao Chen, et al.* [[paper]](https://dl.acm.org/doi/10.1145/3588944)

* [**SOSP 2023**] gSampler: General and Efficient GPU-based Graph Sampling for Graph Learning.
  >*Ping Gong, Renjie Liu, Zunyao Mao, et al.* [[paper]](https://dl.acm.org/doi/10.1145/3600006.3613168)

* [**CIKM 2022**] Scalable Graph Sampling on GPUs with Compressed Graph.
  >*Hongbo Yin, Yingxia Shao, Xupeng Miao, et al.* [[paper]](https://dl.acm.org/doi/abs/10.1145/3511808.3557443)

* [**EuroSys 2021**] Accelerating graph sampling for graph machine learning using GPUs.
  >*Abhinav Jangda, Sandeep Polisetty, et al.* [[paper]](https://dl.acm.org/doi/abs/10.1145/3447786.3456244)

* [**PACT 2021**] Skywalker: Efficient Alias-Method-Based Graph Sampling and Random Walk on GPUs.
  >*P. Wang et al.* [[paper]](https://ieeexplore.ieee.org/document/9563020)

* [**SC 2020**] C-SAW: A Framework for Graph Sampling and Random Walk on GPUs.
  >*S. Pandey, L. Li, A. Hoisie, X. S. Li and H. Liu.* [[paper]](https://ieeexplore.ieee.org/document/9355289)


## GNN
* [**SIGMOD 2024**] HongTu: Scalable Full-Graph GNN Training on Multiple GPUs.
  >*Qiange Wang, Yao Chen, et al.* 

* [**ASPLOS 2023**] uGrapher: High-Performance Graph Operator Computation via Unified Abstraction for Graph Neural Networks.
  >*Yangjie Zhou, Jingwen Leng, Yaoxu Song, et al.* [[paper]](https://dl.acm.org/doi/10.1145/3575693.3575723)

* [**ASPLOS 2023**] Betty: Enabling Large-Scale GNN Training with Batch-Level Graph Partitioning.
  >*Yang, Shuangyan and Zhang, Minjia and Dong, Wenqian and Li, Dong.* [[paper]](https://dl.acm.org/doi/10.1145/3575693.3575725)

* [**ATC 2023**] TC-GNN: Bridging Sparse GNN Computation and Dense Tensor Cores on GPUs.
  >*Yuke Wang, Boyuan Feng, et al.* [[paper]](https://www.usenix.org/conference/atc23/presentation/wang-yuke)

* [**EuroSys 2023**] MariusGNN: Resource-Efficient Out-of-Core Training of Graph Neural Networks.
  >*Roger Waleffe, Jason Mohoney, et al.* [[paper]](https://dl.acm.org/doi/10.1145/3552326.3567501)

* [**NSDI 2023**] BGL: GPU-Efficient GNN Training by Optimizing Graph Data I/O and Preprocessing.
  >*Tianfeng Liu, Yangrui Chen, et al.* [[paper]](https://www.usenix.org/conference/nsdi23/presentation/liu-tianfeng)

* [**OSDI 2023**] MGG: Accelerating Graph Neural Networks with Fine-Grained Intra-Kernel Communication-Computation Pipelining on Multi-GPU Platforms.
  >*Yuke Wang, Boyuan Feng, Zheng Wang, et al.* [[paper]](https://www.usenix.org/conference/osdi23/presentation/wang-yuke)

* [**PPoPP 2023**] DSP: Efficient GNN Training with Multiple GPUs.
  >*Zhenkun Cai, Qihui Zhou, et al.* [[paper]](https://dl.acm.org/doi/10.1145/3572848.3577528)

* [**SOSP 2023**] UGACHE: A Unified GPU Cache for Embedding-based Deep Learning.
  >*Xiaoniu Song, Yiwen Zhang, Rong Chen, and Haibo Chen.* [[paper]](https://dl.acm.org/doi/10.1145/3600006.3613169)

* [**EuroSys 2022**] GNNLab: a factored system for sample-based GNN training over GPUs.
  >*Jianbang Yang, Dahai Tang, Xiaoniu Song, et al.* [[paper]](https://dl.acm.org/doi/10.1145/3492321.3519557)

* [**PPoPP 2022**] QGTC: accelerating quantized graph neural networks via GPU tensor core.
  >*Yuke Wang, Boyuan Feng, and Yufei Ding* [[paper]](https://dl.acm.org/doi/abs/10.1145/3503221.3508408)

* [**OSDI 2021**] Marius: Learning Massive Graph Embeddings on a Single Machine.
  >*Jason Mohoney, Roger Waleffe, et al.* [[paper]](https://www.usenix.org/conference/osdi21/presentation/mohoney)

## Graph Processing
* [**ASPLOS 2023**] Achieving Sub-second Pairwise Query over Evolving Graphs.
  >*Hongtao Chen, Mingxing Zhang, Ke Yang, et al.* [[paper]](https://dl.acm.org/doi/10.1145/3575693.3576173)

* [**VLDB 2022**] Efficient load-balanced butterfly counting on GPU.
  >*Qingyu Xu, Feng Zhang, Zhiming Yao, et al.* [[paper]](https://dl.acm.org/doi/abs/10.14778/3551793.3551806)