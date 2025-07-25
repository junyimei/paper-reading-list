# paper-reading-list

Jot down the awesome papers I've read. Mainly about graph sampling framework, GNN system, graph processing and GPU techniques. Inspired by [Literature on Graph Neural Networks Acceleration](https://github.com/BUAA-CI-Lab/Literatures-on-GNN-Acceleration#literature-on-graph-neural-networks-acceleration).

- [paper-reading-list](#paper-reading-list)
  - [Graph Sampling](#graph-sampling)
    - [CPU Graph Sampling](#cpu-graph-sampling)
    - [Graph Sampling on GPU and FPGA](#graph-sampling-on-gpu-and-fpga)
  - [GNN | Graph Embedding](#gnn--graph-embedding)
  - [Graph Processing](#graph-processing)
  - [Other Topics of Interest](#other-topics-of-interest)
    - [Sparse Matrix](#sparse-matrix)
    - [Vector Search](#vector-search)
    - [GPU-related Techniques](#gpu-related-techniques)
    - [Compiler](#compiler)
    - [Architecture](#architecture)


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

- [**VLDB 2023**] Distributed Graph Embedding with Information-Oriented Random Walks.
  > _Peng Fang, Arijit Khan, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3587136.3587140)

- [**IPDPS 2022**] FlashWalker: An In-Storage Accelerator for Graph Random Walks.

  > _Fuping Niu, Jianhui Yue, et al._ [[paper]](https://ieeexplore.ieee.org/document/9820661)

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

- [**RecSys 2013**] DrunkardMob: billions of random walks on just a PC.
  > _Aapo Kyrola._ [[paper]](https://dl.acm.org/doi/10.1145/2507157.2507173)

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

## GNN | Graph Embedding
- [**ASPLOS 2024**] FastGL: A GPU-Efficient Framework for Accelerating Sampling-Based GNN Training at Large Scale.

  > _Zeyu Zhu, et al._ [[paper]](https://arxiv.org/abs/2409.14939)

- [**EuroSys 2024**] WiseGraph: Optimizing GNN with Joint Workload Partition of Graph and Operations.

  > _Kezhao Huang, Jidong Zhai, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3627703.3650063)

- [**SIGMOD 2024**] HongTu: Scalable Full-Graph GNN Training on Multiple GPUs.

  > _Qiange Wang, Yao Chen, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3626733)

- [**VLDB 2024**] Accelerating Sampling and Aggregation Operations in GNN Frameworks with GPU Initiated Direct Storage Accesses.

  > _Jeongmin Brian Park, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3648160.3648166)

- [**VLDB 2024**] DAHA: Accelerating GNN Training with Data and Hardware Aware Execution Planning.

  > _Zhiyuan Li, Xun Jian, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3648160.3648176)

- [**VLDB 2024**] Comprehensive Evaluation of GNN Training Systems: A Data Management Perspective.

  > _Hao Yuan, Yajiong Liu, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3648160.3648167)

- [**VLDB 2024**] NeutronOrch: Rethinking Sample-Based GNN Training under CPU-GPU Heterogeneous Environments.

  > _Xin Ai, Qiange Wang, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3659437.3659453)

- [**ASPLOS 2023**] uGrapher: High-Performance Graph Operator Computation via Unified Abstraction for Graph Neural Networks.

  > _Yangjie Zhou, Jingwen Leng, Yaoxu Song, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3575693.3575723)

- [**ASPLOS 2023**] Betty: Enabling Large-Scale GNN Training with Batch-Level Graph Partitioning.

  > _Yang, Shuangyan and Zhang, Minjia and Dong, Wenqian and Li, Dong._ [[paper]](https://dl.acm.org/doi/10.1145/3575693.3575725)

- [**ATC 2023**] TC-GNN: Bridging Sparse GNN Computation and Dense Tensor Cores on GPUs.

  > _Yuke Wang, Boyuan Feng, et al._ [[paper]](https://www.usenix.org/conference/atc23/presentation/wang-yuke)

- [**CF 2023**] AdaptGear: Accelerating GNN Training via Adaptive Subgraph-Level Kernels on GPUs.

  > _Yangjie Zhou, Yaoxu Song, Jingwen Leng, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3587135.3592199)

- [**EuroSys 2023**] MariusGNN: Resource-Efficient Out-of-Core Training of Graph Neural Networks.

  > _Roger Waleffe, Jason Mohoney, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3552326.3567501)

- [**NSDI 2023**] BGL: GPU-Efficient GNN Training by Optimizing Graph Data I/O and Preprocessing.

  > _Tianfeng Liu, Yangrui Chen, et al._ [[paper]](https://www.usenix.org/conference/nsdi23/presentation/liu-tianfeng)

- [**OSDI 2023**] MGG: Accelerating Graph Neural Networks with Fine-Grained Intra-Kernel Communication-Computation Pipelining on Multi-GPU Platforms.

  > _Yuke Wang, Boyuan Feng, Zheng Wang, et al._ [[paper]](https://www.usenix.org/conference/osdi23/presentation/wang-yuke)

- [**PPoPP 2023**] DSP: Efficient GNN Training with Multiple GPUs.

  > _Zhenkun Cai, Qihui Zhou, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3572848.3577528)

- [**SOSP 2023**] UGACHE: A Unified GPU Cache for Embedding-based Deep Learning.
  > _Xiaoniu Song, Yiwen Zhang, Rong Chen, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3600006.3613169)

- [**EuroSys 2022**] GNNLab: a factored system for sample-based GNN training over GPUs.

  > _Jianbang Yang, Dahai Tang, Xiaoniu Song, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3492321.3519557)

- [**MLSys 2022**] Graphiler: Optimizing graph neural networks with message passing data flow graph.
  > _Zhiqiang Xie, et al._ [[paper]](https://assets.amazon.science/80/8f/d2f0d72a45ffb02fae21cc74631e/graphiler-optimizing-graph-neural-networks-with-message-passing-data-flow-graph.pdf)

- [**MLSys 2022**] Understanding gnn computational graph: A coordinated computation, io, and memory perspective.
  > _Hengrui Zhang, et al._ [[paper]](https://proceedings.mlsys.org/paper_files/paper/2022/file/b559156047e50cf316207249d0b5a6c5-Paper.pdf)

- [**PACT 2022**] T-GCN: A Sampling Based Streaming Graph Neural Network System with Hybrid Architecture.

  > _Chengying Huan, Shuaiwen Leon Song, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3559009.3569648)

- [**PPoPP 2022**] QGTC: accelerating quantized graph neural networks via GPU tensor core.

  > _Yuke Wang, Boyuan Feng, and Yufei Ding_ [[paper]](https://dl.acm.org/doi/abs/10.1145/3503221.3508408)

- [**SC 2022**] WholeGraph: A Fast Graph Neural Network Training Framework with Multi-GPU Distributed Shared Memory Architecture.
  > _Dongxu Yang, Junhong Liu, er al._ [[paper]](https://ieeexplore.ieee.org/document/10046129)

- [**EuroSys 2021**] Seastar: Vertex-Centric Programming for Graph Neural Networks.
  > _Yidi Wu, Kaihao Ma, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3447786.3456247)

- [**OSDI 2021**] Marius: Learning Massive Graph Embeddings on a Single Machine.

  > _Jason Mohoney, Roger Waleffe, et al._ [[paper]](https://www.usenix.org/conference/osdi21/presentation/mohoney)

- [**OSDI 2021**] GNNAdvisor: An Adaptive and Efficient Runtime System for GNN Acceleration on GPUs.

  > _Yuke Wang, Boyuan Feng, Gushu Li, et al._ [[paper]](https://www.usenix.org/conference/osdi21/presentation/wang-yuke)

- [**PPoPP 2021**] Understanding and bridging the gaps in current GNN performance optimizations.

  > _Kezhao Huang, Jidong Zhai, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3437801.3441585)

- [**VLDB 2021**] Large graph convolutional network training with GPU-oriented data communication architecture.
  > _Seung Won Min, Kun Wu, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3476249.3476264)

- [**ICCAD 2020**] fuseGNN: accelerating graph convolutional neural network training on GPGPU.
  > _Zhaodong Chen, Mingyu Yan, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3400302.3415610)

- [**SC 2020**] FeatGraph: a flexible and efficient backend for graph neural network systems.
  > _Yuwei Hu, Zihao Ye, Minjie Wang, et al._ [[paper]](https://dl.acm.org/doi/abs/10.5555/3433701.3433795)


- [**SIGKDD 2020**] Redundancy-Free Computation for Graph Neural Networks.
  > _Zhihao Jia, Sina Lin, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3394486.3403142)

## Graph Processing

- [**ATC 2024**] Efficient Large Graph Processing with Chunk-Based Graph Representation Model.

  > _Rui Wang, et al._ [[paper]](https://www.usenix.org/conference/atc24/presentation/wang-rui)

- [**VLDB 2024**] BYO: A Unified Framework for Benchmarking Large-Scale Graph Containers.

  > _Brian Wheatman, Xiaojun Dong, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3665844.3665859)

- [**VLDB 2024**] CGgraph: An Ultra-fast Graph Processing System on Modern Commodity CPU-GPU Co-processor.

  > _Pengjie Cui, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3648160.3648179)

- [**ASPLOS 2023**] Achieving Sub-second Pairwise Query over Evolving Graphs.

  > _Hongtao Chen, Mingxing Zhang, Ke Yang, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3575693.3576173)


- [**SC 2023**] Choosing the Best Parallelization and Implementation Styles for Graph Analytics Codes: Lessons Learned from 1106 Programs.

  > _Yiqian Liu, Noushin Azami, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3581784.3607038)


- [**OSDI 2022**] Efficient and Scalable Graph Pattern Mining on GPUs.

  > _Xuhao Chen and Arvind._ [[paper]](https://www.usenix.org/system/files/osdi22-chen.pdf)

- [**VLDB 2022**] Efficient load-balanced butterfly counting on GPU.

  > _Qingyu Xu, Feng Zhang, Zhiming Yao, et al._ [[paper]](https://dl.acm.org/doi/abs/10.14778/3551793.3551806)

- [**ICPP 2021**] Ascetic: Enhancing Cross-Iterations Data Efficiency in Out-of-Memory Graph Processing on GPUs.

  > _Ruiqi Tang, Ziyi Zhao, Kailun Wang, et al._ [[paper]](https://dl.acm.org/doi/fullHtml/10.1145/3472456.3472457)

- [**TACO 2021**] Grus: Toward Unified-memory-efficient High-performance Graph Processing on GPU.

  > _Pengyu Wang, Jing Wang, Chao Li, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3444844)

- [**VLDB 2021**] EMOGI: Efficient Memory-access for Out-of-memory Graph-traversal in GPUs.

  > _Seung Won Min, Vikram Sharma Mailthody, et al._ [[paper]](https://dl.acm.org/doi/10.14778/3425879.3425883)

- [**EuroSys 2020**] Subway: minimizing data transfer during out-of-GPU-memory graph processing.
  > _Amir Hossein Nodehi Sabet, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3342195.3387537)

- [**FCS 2020**] WolfGraph: The edge-centric graph processing on GPU.
  > _Huanzhou Zhu, Ligang He, et al._ [[paper]](https://www.sciencedirect.com/science/article/pii/S0167739X18325251)

- [**BigData 2017**] Making caches work for graph analytics.
  > _Yunming Zhang, Vladimir Kiriansk, et al._ [[paper]](https://ieeexplore.ieee.org/document/8257937)

- [**FAST 2017**] Graphene: Fine-Grained IO Management for Graph Computing.
  > _Hang Liu and H. Howie Huang._ [[paper]](https://www.usenix.org/conference/fast17/technical-sessions/presentation/liu)

- [**VLDB 2017**] A Distributed Multi-GPU System for Fast Graph Processing.
  > _Zhihao Jia, et al._ [[paper]](https://www.vldb.org/pvldb/vol11/p297-jia.pdf)

- [**PPoPP 2016**] Gunrock: a high-performance graph processing library on the GPU.
  > _Yangzihao Wang, Andrew Davidson, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3016078.2851145)

- [**IPDPS 2014**] Work-Efficient Parallel GPU Methods for Single-Source Shortest Paths.
  > _Andrew Davidson, Sean Baxter, et al._ [[paper]](https://ieeexplore.ieee.org/document/6877269)

## Other Topics of Interest
### Sparse Matrix
- [**ISCA 2025**] RTSpMSpM: Harnessing Ray Tracing for Efficient Sparse Matrix Computations.
  > _Hongrui Zhang, Yunan Zhang, and Hung-Wei Tseng._ [[paper]](https://dl.acm.org/doi/10.1145/3695053.3731072)

- [**ASPLOS 2023**] SparseTIR: Composable Abstractions for Sparse Compilation in Deep Learning.
  > _Zihao Ye, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3582016.3582047)

- [**DAC 2022**] Heuristic adaptability to input dynamics for SpMM on GPUs.
  > _Guohao Dai, Guyue Huang, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3489517.3530508)

- and [**arxiv 2021**] Efficient Sparse Matrix Kernels based on Adaptive Workload-Balancing and Parallel-Reduction.
  > _Guyue Huang, Guohao Dai, et al._ [[paper]](https://arxiv.org/pdf/2106.16064)
  
- [**SC 2020**] GE-SpMM: General-Purpose Sparse Matrix-Matrix Multiplication on GPUs for Graph Neural Networks.
  > _Guyue Huang, Guohao Dai, et al._ [[paper]](https://ieeexplore.ieee.org/document/9355302)

- [**EuroPar 2018**] Design Principles for Sparse Matrix Multiplication on the GPU.
  > _Carl Yang, et al._ [[paper]](https://dl.acm.org/doi/10.1007/978-3-319-96983-1_48)

- [**SC 2016**] Merge-Based Parallel Sparse Matrix-Vector Multiplication.
  > _D. Merrill and M. Garland._ [[paper]](https://ieeexplore.ieee.org/document/7877136)

- [**IPDPS 2015**] Optimizing Sparse Matrix Operations on GPUs Using Merge Path.
  > _Steven Dalton, Sean Baxter, et al._ [[paper]](https://ieeexplore.ieee.org/document/7161529)

- [**SC 2014**] Efficient Sparse Matrix-Vector Multiplication on GPUs using the CSR Storage Format.
  > _Joseph L. Greathouse and Mayank Daga._ [[paper]](https://ieeexplore.ieee.org/document/7013050)

- [**SC 2009**] Implementing Sparse Matrix-Vector Multiplication
on Throughput-Oriented Processors.
  > _Nathan Bell, Michael Garland._ [[paper]](https://www.nvidia.com/docs/io/77944/sc09-spmv-throughput.pdf)

### Vector Search 
- [**ASPLOS 2024**] JUNO: Optimizing High-Dimensional Approximate Nearest Neighbour Search with Sparsity-Aware Algorithm and Ray-Tracing Core Mapping.
  > _Zihan Liu, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3620665.3640360)

- [**PPoPP 2023**] WISE: Predicting the Performance of Sparse Matrix Vector Multiplication with Machine Learning.
  > _Serif Yesil, Azin Heidarshenas, Adam Morrison, and Josep Torrellas._ [[paper]](https://dl.acm.org/doi/10.1145/3572848.3577506)

- [**SC 2023**] Parallel Top-K Algorithms on GPU: A Comprehensive Study and New Methods.
  > _Jingrong Zhang, Akira Naruse, Xipeng Li, and Yong Wang._ [[paper]](https://dl.acm.org/doi/10.1145/3581784.3607062)

- [**HPCA 2022**] Tacker: Tensor-CUDA Core Kernel Fusion for Improving the GPU Utilization while Ensuring QoS.
  > _Han Zhao, Weihao Cui, Quan Chen, et al._ [[paper]](https://ieeexplore.ieee.org/document/9773253)

- [**ICDE 2022**] GPU-accelerated Proximity Graph Approximate Nearest Neighbor Search and Construction.
  > _Yuanhang Yu, Dong Wen, et al._ [[paper]](https://ieeexplore.ieee.org/document/9835618)

- [**PPoPP 2022**] RTNN: accelerating neighbor search using hardware ray tracing.
  > _Yuhao Zhu._ [[paper]](https://dl.acm.org/doi/10.1145/3503221.3508409)

- [**SIGMOD 2021**] Milvus: A Purpose-Built Vector Data Management System.
  > _Jianguo Wang, Xiaomeng Yi, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3448016.3457550)

- [**TOBD 2021**] Billion-Scale Similarity Search with GPUs.
  > _Jeff Johnson, et al._ [[paper]](https://www.computer.org/csdl/journal/bd/2021/03/08733051/1aFvgKKpjoc)


### GPU-related Techniques
- [**ASPLOS 2024**] GMLake: Efficient and Transparent GPU Memory Defragmentation for Large-scale DNN Training with Virtual Memory Stitching.
  > _Cong Guo, Rui Zhang, Jiale Xu, Jingwen Leng, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3620665.3640423)

- [**ASPLOS 2024**] ngAP: Non-blocking Large-scale Automata Processing on GPUs.
  > _Tianao Ge, Tong Zhang, and Hongyuan Liu._ [[paper]](https://dl.acm.org/doi/10.1145/3617232.3624848)

- [**ATC 2024**] Metis: Fast Automatic Distributed Training on Heterogeneous GPUs.
  > _Taegeon Um, et al._ [[paper]](https://www.usenix.org/conference/atc24/presentation/um)

- [**EuroSys 2024**] Orion: Interference-aware, Fine-grained GPU Sharing for ML Applications.
  > _Foteini Strati, Xianzhe Ma, and Ana Klimovic._ [[paper]](https://dl.acm.org/doi/10.1145/3627703.3629578)

- [**PPoPP 2024**] Gallatin: A General-Purpose GPU Memory Manager.
  > _Hunter Mccoy, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3627535.3638499)

- [**PPoPP 2023**] A Programming Model for GPU Load Balancing.
  > _Muhammad Osama, Serban D. Porumbescu, and John D. Owens._ [[paper]](https://dl.acm.org/doi/10.1145/3572848.3577434)

- [**VLDB 2022**] Query Processing on Tensor Computation Runtimes.
  > _Dong He, et al._ [[paper]](https://www.vldb.org/pvldb/vol15/p2811-he.pdf)

- [**MICRO 2017**] Versapipe: a versatile programming framework for pipelined computing on GPU.
  > _Zhen Zheng, Chanyoung Oh, Jidong Zhai, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3123939.3123978)

### Compiler
- [**GCO 2024**] oneDNN Graph Compiler: A Hybrid Approach for High-Performance Deep Learning Compilation.
  > _Jianhui Li, et al._ [[paper]](https://www.computer.org/csdl/proceedings-article/cgo/2024/10444871/1UUdPicbmOA)

- [**GCO 2024**] Seer: Predictive Runtime Kernel Selection for Irregular Problems.
  > _Ryan Swann, Muhammad Osama, et al._ [[paper]](https://dl.acm.org/doi/10.1109/CGO57630.2024.10444812)

- [**PPoPP 2024**] ConvStencil: Transform Stencil Computation to Matrix Multiplication on Tensor Cores.
  > _Yuetao Chen, Kun Li, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3627535.3638476)

- [**HPCA 2023**] Chimera: An Analytical Optimizing Framework for Effective Compute-intensive Operators Fusion.
  > _S. Zheng, et al._ [[paper]](https://ieeexplore.ieee.org/document/10071018)


- [**MLSys 2022**] Understanding gnn computational graph: A coordinated computation, io, and memory perspective.
  > _Hengrui Zhang, et al._ [[paper]](https://proceedings.mlsys.org/paper_files/paper/2022/file/b559156047e50cf316207249d0b5a6c5-Paper.pdf)

- [**PACT 2022**] Decoupling Schedule, Topology Layout, and Algorithm to Easily Enlarge the Tuning Space of GPU Graph Processing.
  > _Shinnung Jeong, Yongwoo Lee, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3559009.3569686)

- [**GCO 2021**] Compiling Graph Applications for GPU s with GraphIt.
  > _Ajay Brahmakshatriya, Yunming Zhang, et al._ [[paper]](https://ieeexplore.ieee.org/document/9370321)

- [**ASPLOS 2020**] FlexTensor: An Automatic Schedule Exploration and Optimization Framework for Tensor Computation on Heterogeneous System.
  > _Size Zheng, Yun Liang, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3373376.3378508)

- [**arxiv 2019**] Glow: Graph Lowering Compiler Techniques for Neural Networks.
  > _Nadav Rotem, Jordan Fix, et al._ [[paper]](https://arxiv.org/abs/1805.00907)

- [**PPoPP 2019**] A pattern based algorithmic autotuner for graph processing on GPUs.
  > _Ke Meng, Jiajia Li, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3293883.3295716)

- [**OOPSLA 2018**] GraphIt: a high-performance graph DSL.
  > _Zhang Yunming, Yang Mengjiao, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3276491)

- [**OSDI 2018**] TVM: an automated end-to-end optimizing compiler for deep learning.
  > _Tianqi Chen, Thierry Moreau, et al._ [[paper]](https://dl.acm.org/doi/abs/10.5555/3291168.3291211)

- [**OOPSLA 2016**] A compiler for throughput optimization of graph algorithms on GPUs.
  > _Sreepathi Pai and Keshav Pingali._ [[paper]](https://dl.acm.org/doi/10.1145/2983990.2984015)

- [**PACT 2014**] OpenTuner: An extensible framework for program autotuning.
  > _Jason Ansel, et al._ [[paper]](https://ieeexplore.ieee.org/document/7855909)

### Architecture
- [**ISCA 2023**] Shogun: A Task Scheduling Framework for Graph Mining Accelerators.
  > _Yibo Wu, Jianfeng Zhu, Wenrui Wei, et al._ [[paper]](https://dl.acm.org/doi/abs/10.1145/3579371.3589086)

- [**ICS 2021**] ThundeRiNG: Generating Multiple Independent Random Number Sequences on FPGAs.
  > _Hongshi Tan, Xinyu Chen, et al._ [[paper]](https://dl.acm.org/doi/10.1145/3447818.3461664)




