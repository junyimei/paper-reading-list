# paper-reading-list

Papers about graph sampling framework, GNN system, graph processing and GPU techniques. Inspired by [Literature on Graph Neural Networks Acceleration](https://github.com/BUAA-CI-Lab/Literatures-on-GNN-Acceleration#literature-on-graph-neural-networks-acceleration).

- [paper-reading-list](#paper-reading-list)
  - [Graph Sampling](#graph-sampling)
    - [CPU Graph Sampling](#cpu-graph-sampling)
    - [Graph Sampling on GPU and FPGA](#graph-sampling-on-gpu-and-fpga)
  - [GNN](#gnn)
  - [Graph Processing](#graph-processing)
  - [Graph Accelerator](#graph-accelerator)
  - [Miscellaneous](#miscellaneous)


## Graph Sampling

### CPU Graph Sampling

- [**ASPLOS 2023**] NosWalker: A Decoupled Architecture for Out-of-Core Random Walk Processing.

  > _Shuke Wang, Mingxing Zhang, Ke Yang, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3582016.3582025)

- [**ATC 2023**] SOWalker: An I/O-Optimized Out-of-Core Graph Processing System for Second-Order Random Walks.

  > _Yutong Wu, Zhan Shi, et al._ [[paper]](https://www.usenix.org/conference/atc23/presentation/wu)

- [**EuroSys 2023**] TEA: A General-Purpose Temporal Graph Random Walk Engine.

  > _Chengying Huan, Shuaiwen Leon Song, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3552326.3567491)

- [**ICDE 2023**] LightTraffic: On Optimizing CPU-GPU Data Traffic for Efficient Large-scale Random Walks.

  > _Xing Yipeng, Li Yongkun, et al._ [[paper]](https://ieeexplore.ieee.org/document/10184564)

- [**VLDB 2022**] An I/O-efficient disk-based graph system for scalable second-order random walk of large graphs.

  > _Hongzheng Li, Yingxia Shao, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3529337.3529346)

- [**SOSP 2021**] Random Walks on Huge Graphs at Cache Efficiency.

  > _Ke Yang, Xiaosong Ma, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3477132.3483575)

- [**VLDB 2021**] ThunderRW: an in-memory graph random walk engine.

  > _Shixuan Sun, Yuhang Chen, Shengliang Lu, et al._ [[paper]](https://dl.acm.org/doi/abs/10.14778/3476249.3476257)

- [**ATC 2020**] GraphWalker: An I/O-Efficient and Resource-Friendly Graph Analytic System for Fast and Scalable Random Walks.

  > _Rui Wang, Yongkun Li, et al._ [[paper]](https://www.usenix.org/conference/atc20/presentation/wang-rui)

- [**SOSP 2019**] KnightKing: a fast distributed graph random walk engine.
  > _Ke Yang, MingXing Zhang, Kang Chen, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3341301.3359634)

### Graph Sampling on GPU and FPGA

- [**ICDE 2023**] LightTraffic: On Optimizing CPU-GPU Data Traffic for Efficient Large-scale Random Walks.

  > _Y. Xing, Y. Li, Z. Wang, Y. Xu and J. C. S. Lui._ [[paper]](https://ieeexplore.ieee.org/document/10184564)

- [**SIGMOD 2023**] LightRW: FPGA Accelerated Graph Dynamic Random Walks.

  > _Hongshi Tan, Xinyu Chen, Yao Chen, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3588944)

- [**SOSP 2023**] gSampler: General and Efficient GPU-based Graph Sampling for Graph Learning.

  > _Ping Gong, Renjie Liu, Zunyao Mao, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3600006.3613168)

- [**CIKM 2022**] Scalable Graph Sampling on GPUs with Compressed Graph.

  > _Hongbo Yin, Yingxia Shao, Xupeng Miao, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3511808.3557443)

- [**EuroSys 2021**] Accelerating graph sampling for graph machine learning using GPUs.

  > _Abhinav Jangda, Sandeep Polisetty, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3447786.3456244)

- [**PACT 2021**] Skywalker: Efficient Alias-Method-Based Graph Sampling and Random Walk on GPUs.

  > _P. Wang et al._ [[paper]](https://ieeexplore.ieee.org/document/9563020)

- [**SC 2020**] C-SAW: A Framework for Graph Sampling and Random Walk on GPUs.
  > _S. Pandey, L. Li, A. Hoisie, X. S. Li and H. Liu._ [[paper]](https://ieeexplore.ieee.org/document/9355289)

## GNN

- [**SIGMOD 2024**] HongTu: Scalable Full-Graph GNN Training on Multiple GPUs.

  > _Qiange Wang, Yao Chen, et al._

- [**ASPLOS 2023**] uGrapher: High-Performance Graph Operator Computation via Unified Abstraction for Graph Neural Networks.

  > _Yangjie Zhou, Jingwen Leng, Yaoxu Song, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3575693.3575723)

- [**ASPLOS 2023**] Betty: Enabling Large-Scale GNN Training with Batch-Level Graph Partitioning.

  > _Yang, Shuangyan and Zhang, Minjia and Dong, Wenqian and Li, Dong._ [[paper]](https://dl.acm.org/doi/10.1145/3575693.3575725)

- [**ATC 2023**] TC-GNN: Bridging Sparse GNN Computation and Dense Tensor Cores on GPUs.

  > _Yuke Wang, Boyuan Feng, et al._ [[paper]](https://www.usenix.org/conference/atc23/presentation/wang-yuke)

- [**EuroSys 2023**] MariusGNN: Resource-Efficient Out-of-Core Training of Graph Neural Networks.

  > _Roger Waleffe, Jason Mohoney, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3552326.3567501)

- [**NSDI 2023**] BGL: GPU-Efficient GNN Training by Optimizing Graph Data I/O and Preprocessing.

  > _Tianfeng Liu, Yangrui Chen, et al._ [[paper]](https://www.usenix.org/conference/nsdi23/presentation/liu-tianfeng)

- [**OSDI 2023**] MGG: Accelerating Graph Neural Networks with Fine-Grained Intra-Kernel Communication-Computation Pipelining on Multi-GPU Platforms.

  > _Yuke Wang, Boyuan Feng, Zheng Wang, et al._ [[paper]](https://www.usenix.org/conference/osdi23/presentation/wang-yuke)

- [**PPoPP 2023**] DSP: Efficient GNN Training with Multiple GPUs.

  > _Zhenkun Cai, Qihui Zhou, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3572848.3577528)

- [**SOSP 2023**] UGACHE: A Unified GPU Cache for Embedding-based Deep Learning.

  > _Xiaoniu Song, Yiwen Zhang, Rong Chen, and Haibo Chen._ [[paper]](https://dl.acm.org/doi/10.1145/3600006.3613169)

- [**EuroSys 2022**] GNNLab: a factored system for sample-based GNN training over GPUs.

  > _Jianbang Yang, Dahai Tang, Xiaoniu Song, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3492321.3519557)

- [**PPoPP 2022**] QGTC: accelerating quantized graph neural networks via GPU tensor core.

  > _Yuke Wang, Boyuan Feng, and Yufei Ding_ [[paper]](https://dl.acm.org/doi/abs/10.1145/3503221.3508408)

- [**OSDI 2021**] Marius: Learning Massive Graph Embeddings on a Single Machine.

  > _Jason Mohoney, Roger Waleffe, et al._ [[paper]](https://www.usenix.org/conference/osdi21/presentation/mohoney)

- [**OSDI 2021**] GNNAdvisor: An Adaptive and Efficient Runtime System for GNN Acceleration on GPUs.

  > _Yuke Wang, Boyuan Feng, Gushu Li, et al._ [[paper]](https://www.usenix.org/conference/osdi21/presentation/wang-yuke)

- [**VLDB 2021**] Large graph convolutional network training with GPU-oriented data communication architecture.
  > _Seung Won Min, Kun Wu, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3476249.3476264)

## Graph Processing

- [**ASPLOS 2023**] Achieving Sub-second Pairwise Query over Evolving Graphs.

  > _Hongtao Chen, Mingxing Zhang, Ke Yang, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3575693.3576173)

- [**VLDB 2022**] Efficient load-balanced butterfly counting on GPU.

  > _Qingyu Xu, Feng Zhang, Zhiming Yao, et al._ [[paper]](https://dl.acm.org/doi/abs/10.14778/3551793.3551806)

- [**VLDB 2021**] EMOGI: Efficient Memory-access for Out-of-memory Graph-traversal in GPUs.

  > _Seung Won Min, Vikram Sharma Mailthody, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3425879.3425883)

- [**ICPP 2021**] Ascetic: Enhancing Cross-Iterations Data Efficiency in Out-of-Memory Graph Processing on GPUs.

  > _Ruiqi Tang, Ziyi Zhao, Kailun Wang, et al._ [[paper]](https://dl.acm.org/doi/fullHtml/10.1145/3472456.3472457)

- [**TACO 2021**] Grus: Toward Unified-memory-efficient High-performance Graph Processing on GPU.

  > _Pengyu Wang, Jing Wang, Chao Li, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3444844)

- [**EuroSys 2020**] Subway: minimizing data transfer during out-of-GPU-memory graph processing.
  > _Amir Hossein Nodehi Sabet, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3342195.3387537)

- [**PPoPP 2016**] Gunrock: a high-performance graph processing library on the GPU.
  > _Yangzihao Wang, Andrew Davidson, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3016078.2851145)

## Graph Accelerator
- [**ISCA 2023**] Shogun: A Task Scheduling Framework for Graph Mining Accelerators.
  > _Yibo Wu, Jianfeng Zhu, Wenrui Wei, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3579371.3589086)


## Miscellaneous
- [**SOSP 2023**] UGACHE: A Unified GPU Cache for Embedding-based Deep Learning.
  > _Xiaoniu Song, Yiwen Zhang, Rong Chen, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3600006.3613169)

- [**HPCA 2022**] Tacker: Tensor-CUDA Core Kernel Fusion for Improving the GPU Utilization while Ensuring QoS.
  > _Han Zhao, Weihao Cui, Quan Chen, et al._ [[paper]](https://ieeexplore.ieee.org/document/9773253)

- [**ICS 2021**] ThundeRiNG: Generating Multiple Independent Random Number Sequences on FPGAs.
  > _Hongshi Tan, Xinyu Chen, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3447818.3461664)