# SAR 成像算法仿真（MATLAB）

本仓库是用于点目标（point targets）的合成孔径雷达（SAR）成像算法 MATLAB 实验，原有 [readme.txt](readme.txt) 说明为研究生阶段的算法模拟工作。

## 文件导航

| 文件 | 说明 |
| --- | --- |
| `RDA_imaging.m` | 距离多普勒算法（Range Doppler Algorithm，RDA）仿真 |
| `CSA_imaging.m` | 线性调频变标算法（Chirp Scaling Algorithm，CSA）仿真 |
| `target_analysis.m` | 目标分析代码 |
| `zhibiao_2.m` | 指标/辅助计算脚本（具体逻辑以源码为准） |

## 运行前检查

1. 使用 MATLAB 打开整个目录。
2. 按源码核实参数初始化、脚本执行顺序及工具箱依赖。
3. 运行相应算法并保存必要的参数、图像与实验结果说明。

本次未执行 MATLAB 代码；算法实现与结果正确性尚未重新验证。

## 整理原则

保留原始 `.m` 文件名和 `readme.txt` 以兼容旧引用。今后新增实验可在 `docs/` 记录方法、参数及可复现结果，避免把大体积中间数据无说明地混入源码。
