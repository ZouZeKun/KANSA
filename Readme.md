# KAN Attention Networks for Real-Time Modeling of Water Distribution Systems (KANSA)

**Paper**： [Learning Physics and Temporal Dependencies: Real-Time Modeling of Water Distribution Systems via Kolmogorov–Arnold Attention Networks]
**Authors**： [Zekun Zou], [Zhihong Long], [Gang Xu], [Raziyeh Farmani], [Tingchao Yu], [Shipeng Chu]

## 📜 Abstract / 论文简介
> **English Version**: [Real-time modeling] is vital for the intelligent management of urban water distribution systems (WDSs), enabling proactive decision-making, rapid anomaly detection, and efficient operational control. In comparison with traditional mechanistic simulators, data-driven models offer faster computation and reduced calibration demands, making them more suitable for real-time applications. However, existing models often accumulate long-term prediction errors and fail to capture the strong temporal dependencies in measured time series. To address these challenges, this study propose the Kolmogorov–Arnold Attention Network for the real-time modeling of WDSs (KANSA), which combines Kolmogorov–Arnold Networks with attention mechanisms to extract temporal dependency features through bidirectional spatiotemporal processing. Additionally, a multi-equation soft-constraint formulation embeds mass and energy conservation laws into the loss function, mitigating cumulative errors and enhancing physical consistency. Evaluations on a benchmark network and a real-world system demonstrate that KANSA achieves high-accuracy real-time estimation and pattern fidelity while maintaining engineering-grade hydraulic balance.
> **中文版本**：[实时建模]对城市供水系统的智能化管理至关重要，其能够实现主动决策、快速异常检测与高效运行控制。相较于传统机理模拟器，数据驱动模型具有更快的计算速度和更低的校准需求，因而更适用于实时应用场景。然而，现有模型普遍存在长期预测误差累积问题，且难以捕捉实测时间序列中的强时间依赖性特征。为应对这些挑战，本研究提出基于Kolmogorov-Arnold注意网络的供水系统实时建模框架（KANSA）。该框架通过融合Kolmogorov-Arnold网络与注意力机制，构建双向时空处理架构以提取时序依赖特征；同时采用多方程软约束形式，将质量与能量守恒定律嵌入损失函数，有效抑制累积误差并增强物理一致性。在基准管网和实际系统的评估中，KANSA在保持工程级水力平衡的前提下，实现了高精度实时状态估计与模式保真度。

## 🧠 Model Architecture / 模型架构
![Model Architecture](ModelArchitecture.jpg)  
*Overall architecture of the [KANSA] model proposed in the paper* / *图：论文提出的 [KANSA] 模型整体架构图*

## 🚀 Qucik Start / 快速开始

### How to Use / 如何使用
#### **1. The code is organized in  Notebook format / 代码采用 Notebook 的格式进行整理**
#### **2. Just adjust the file read path to run the code / 只需要调整好文件读取路径即可运行代码**
#### **3. Description of the document / 文件说明**
- **dataset**   ：Simulated network dataset / 模拟管网数据集
- **KANSA**     ：Realization of the simulated network / 模拟管网实现
- **SM1_Text1** : Realization of the Supplyment Material Text 1 / 实现补充材料1
- **SM1_Text2** : Realization of the Supplyment Material Text 2 / 实现补充材料2

### Operation Environment / 运行环境
- **Python Version**： `3.12.3` 
- **CUDA Version**： `12.100` 
- **PyTorch Version**： `2.3.0+cu121` 
- **Numpy**： `1.26.4`
- **Pandas**： `2.2.2` 
###  If you have any questions, please contact us at: [*zekunzou@zju.edu.cn*]