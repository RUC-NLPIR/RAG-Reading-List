# RAG-Reading-List

This repository is used to collect recent studies on RAG methods, benchmarks, and toolkits. Welcome any updates through pull requests.

## 📄 Method

### Text only

1. **In-Context Retrieval-Augmented Language Models**
   - arXiv, 2023-08-01, https://arxiv.org/abs/2302.00083
   - Ori Ram, Yoav Levine, Itay Dalmedigos, Dor Muhlgay, Amnon Shashua, Kevin Leyton-Brown, Yoav Shoham
   - Using retrieved results can effectively imrpove LLMs' performance. Retrieve after every $k$ tokens, and the performance can be improved when $k$ is small (more frequent retrieval). Reranking is also helpful.
2. **PlanXRAG: Planning-guided Retrieval Augmented Generation**
   - arXiv, 2024-10-28, https://arxiv.org/abs/2410.20753
   - Prakhar Verma, Sukruta Prakash Midigeshi, Gaurav Sinha, Arno Solin, Nagarajan Natarajan, Amit Sharma
3. **RQ-RAG: Learning to Refine Queries for Retrieval Augmented Generation**
   - arXiv, 2024-03-31 , https://arxiv.org/abs/2404.00610
   - Chi-Min Chan, Chunpu Xu, Ruibin Yuan, Hongyin Luo, Wei Xue, Yike Guo, Jie Fu

### Multimodal
1. **Murag: Multimodal retrieval-augmented generator for open question answering over images and text.**
   - EMNLP, 2022-12-7 https://aclanthology.org/2022.emnlp-main.375.pdf
   - Wenhu Chen, Hexiang Hu, Xi Chen, Pat Verga, William W. Cohen
2. **MLLM IS A STRONG RERANKER: ADVANCING MULTIMODAL RETRIEVAL-AUGMENTED GENERATION VIA KNOWLEDGE-ENHANCED RERANKING AND NOISEINJECTED TRAINING**
   - arXiv, 2024-9-25, https://arxiv.org/pdf/2407.21439 
   - Zhanpeng Chen, Chengjin Xu, Yiyan Qi, Jian Guo
3. **Retrieval-Augmented Multimodal Language Modeling**
   - ICML, 2023-7-23, https://dl.acm.org/doi/10.5555/3618408.3620067 
   - Michihiro Yasunaga, Armen Aghajanyan, Weijia Shi, Rich James, Jure Leskovec, Percy Liang, Mike Lewis, Luke Zettlemoyer, Wen-tau Yih
4. **Enhancing Multi-modal Multi-hop Question Answering via Structured Knowledge and Unified Retrieval-Generation**
   - MM, 2023-10-29, https://dl.acm.org/doi/pdf/10.1145/3581783.3611964
   - Qian Yang, Qian Chen, Wen Wang, Baotian Hu, Min Zhang
5. **An Interactive Multi-modal Query Answering System with Retrieval-Augmented Large Language Models**
   - VLDB, 2024-11-8, https://dl.acm.org/doi/10.14778/3685800.3685868 
   - Mengzhao Wang, Haotian Wu, Xiangyu Ke, Yunjun Gao, Xiaoliang Xu, Lu Chen
6. **VisRAG: Vision-based Retrieval-augmented Generation on Multi-modality Documents**
   - arXiv 2024-10-14, https://arxiv.org/abs/2410.10594
   - Shi Yu, Chaoyue Tang, Bokai Xu, Junbo Cui, Junhao Ran, Yukun Yan, Zhenghao Liu, Shuo Wang, Xu Han, Zhiyuan Liu, Maosong Sun
   - TL;DR: Authors directly view web pages as images instead of spliting text or image information blocks. They use multi-modal retriever and Visiual-understanding LLMs to build VisRAG framework and evaluate models on various visual QA tasks.
7. **iRAG: Advancing RAG for Videos with an Incremental Approach**
   - CIKM, 2024-10-21, https://dl.acm.org/doi/10.1145/3627673.3680088
   - Md Adnan Arefeen, Biplob Debnath, Md Yusuf Sarwar Uddin, Srimat Chakradhar
8. **Video Enriched Retrieval Augmented Generation Using Aligned Video Captions**
   - arXiv, 2024-5-27, https://arxiv.org/abs/2405.17706
   - Kevin Dela Rosa
9. **Towards Retrieval Augmented Generation over Large Video Libraries**
   - arXiv, 2024-6-21, https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10613524
   - Yannis Tevissen, Khalil Guetari, Frédéric Petitpont


## 📊 Benchmark

## 🛠️ Toolkit
1. **RETA-LLM: A Retrieval-Augmented Large Language Model Toolkit**
   - arXiv, 2023-6-8, https://arxiv.org/abs/2306.05212
   - Jiongnan Liu, Jiajie Jin, Zihan Wang, Jiehan Cheng, Zhicheng Dou, Ji-Rong Wen

