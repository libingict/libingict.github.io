## 存内计算进展（Processing-in Memory On Going）

### 近存计算 Processing Near Memory (PNM)

#### ISCA 2024
- UM-PIM: DRAM-based PIM with Uniform & Shared Memory Space 
  - Yilong Zhao, Mingyu Gao , Fangxin Liu , Yiwei Hu , Zongwu Wang , Han Lin , Ji Li, He Xian , Hanlin Dong , Tao Yang, Naifeng Jing , Xiaoyao Liang, Li Jiang
  * Upmem, 系统内存与PIM数据交换问题，支持PIM 间通信。 上交大、上海启智、清华、华为合作
- NDPBridge: Enabling Cross-Bank Coordination in Near-DRAM-Bank Processing Architectures
  - Boyu Tian, Yiwei Li , Li Jiang, Shuangyu Cai, Mingyu Gao 
  * 要点: HBM, 支持存储块bank间通信。清华、上交大、华为合作
- pSyncPIM: Partially Synchronous Execution of Sparse Matrix Operations for All-Bank PIM Architectures
  - Daehyeon Baek , Soojin Hwang, Jaehyuk Huh
  - HBM-PIM的拓展, 稀疏矩阵乘加速。三星、韩国大学、KAIST合作
- NDSEARCH: Accelerating Graph-Traversal-Based Approximate Nearest Neighbor Search through Near Data Processing 
  - Yitu Wang , Shiyu Li, Qilin Zheng, Linghao Song, Zongwang Li , Andrew Chang, Hai Li , Yiran Chen
  - Approximate nearest neighbor search (ANNS)的算法加速，考虑near SSD. 杜克大学、加州洛杉矶大学、三星美国合作
- Flagger: Cooperative Acceleration for Large-Scale Cross-Silo Federated Learning Aggregation 
  - Xiurui Pan, Yuda An , Shengwen Liang , Bo Mao, Mingzhe Zhang, Qiao Li, Myoungsoo Jung, Jie Zhang
  - 同态加密，近内存与近SSD. 北京大学、中科院计算所、厦门大学、中科院信工所、韩国KAIST合作

#### ASPLOS 2024
- AttAcc! Unleashing the Power of PIM for Batched Transformer-based Generative Model Inference
  - Jaehyun Park, Jaewan Choi, Kwanhee Kyung, Michael Jaemin Kim, and Yongsuk Kwon ; Nam Sung Kim ; Jung Ho Ahn 
  - 大模型算子加速，软硬件结合。首尔国立大学、UIUC合作
- SpecPIM: Accelerating Speculative Inference on PIM-Enabled System via Architecture-Dataflow Co-Exploration
  - Cong Li, Zhe Zhou, Size Zheng, Jiaxi Zhang, Yun Liang, and Guangyu Sun (Peking University)
  - 大模型中Speculative Inference加速。北京大学
- PIM-DL: Expanding the Applicability of Commodity DRAM-PIMs for Deep Learning via Algorithm-System Co-Optimization 
  - Cong Li and Zhe Zhou ; Yang Wang; Fan Yang ; Ting Cao and Mao Yang ; Yun Liang and Guangyu Sun
  - 提出基于LUT的GEMV操作. 北京大学，微软亚研院，南开大学合作
- NeuPIMs: NPU-PIM Heterogeneous Acceleration for Batched LLM Inferencing
  - Guseul Heo, Sangyeop Lee, Jaehong Cho, Hyunmin Choi, and Sanghyeon Lee (KAIST); Hyungkyu Ham and Gwangsun Kim (POSTECH); Divya Mahajan (Georgia Tech); Jongse Park (KAIST)
  - 大模型推理优化. KAIST, POSTECH浦项科技大学，乔治亚理工合作
- IANUS: Integrated Accelerator based on NPU-PIM Unified Memory System
  - Minseok Seo and Xuan Truong Nguyen (Seoul National University and Inter-university Semiconductor Research Center); Seok Joong Hwang (SAPEON); Yongkee Kwon, Guhyun Kim, Chanwook Park, Ilkon Kim, Jaehan Park, Jeongbin Kim, Woojae Shin, Jongsoon Won, Haerang Choi, Kyuyoung Kim, Daehan Kwon, and Chunseok Jeong (SK hynix);Sangheon Lee, Yongseok Choi, Wooseok Byun, and Seungcheol Baek (SAPEON);Hyuk-Jae Lee (Seoul National University and Inter-university Semiconductor Research Center);John Kim (KAIST)
  - 基于近存的大模型专用加速架构
- PIM-STM: Software Transactional Memory for Processing-In-Memory Systems
  - André Lopes, Daniel Castro, and Paolo Romano (IST/INESC-ID)
  - PIM事务型内存的支持. 葡萄牙系统与计算工程研究所
- BVAP: Energy and Memory Efficient Automata Processing for Regular Expressions with Bounded Repetitions
  - Ziyuan Wen, Lingkun Kong, Alexis Le Glaunec, Konstantinos Mamouras, and Kaiyuan Yang (Rice University)
  - 正则模式匹配算法加速，存内位向量自动机. Rice大学

### 存内计算 Computing-in Memory (CIM)
#### ISCA 2024
- On Error Correction for Nonvolatile Processing-In-Memory
  - Husrev Cilasun, Salonik Resch, Zamshed I. Chowdhury, Masoud Zabihi , Yang Lv , Brandon Zink, Jian-Ping Wang , Sachin S. Sapatnekar , Ulya R. Karpuzcu
  - 新型存储器，按位逻辑计算(logic computing)，ECC 容错. 明尼苏达双城分校

#### ASPLOS 2024
- CIM-MLC: A Multi-level Compilation Stack for Computing-In-Memory Accelerators
  - Songyun Qu and Shixin Zhao (Chinese Academy of Sciences); Bing Li (Capital Normal University); Yintao He, Xuyi Cai, Lei Zhang, and Ying Wang (Chinese Academy of Sciences)
  - 不同存内计算架构，跨层级优化，已开源(Opensourced)，[代码库](https://cimmlc.github.io/) . 中科院计算所、首都师范大学合作
### 产业界 
#### 传统企业 
- 三星 Samsung: HMB-PIM
- 海力士 Hynix: AiM (Accelerator in Memory, GDDR6) 
#### 产业公司 Startup
- Mythic (Flash)
- Witmem (知存科技)
- 