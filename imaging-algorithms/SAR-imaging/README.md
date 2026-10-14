# SAR Imaging · 合成孔径雷达成像算法

该仓库存放若干传统合成孔径雷达（SAR）成像算法的 MATLAB 示例及示例数据。

## 算法目录

| 目录 | 算法或版本 | 使用方法 |
| --- | --- | --- |
| `CSA_Img/` | Chirp Scaling Algorithm（CSA，线性调频变标算法） | 先读目录内 `readme.txt` |
| `RDA2_Img/` | 距离多普勒算法（RDA）变体 | 先读目录内 `readme.txt` |
| `RDA3_Img/` | 距离多普勒算法（RDA）另一变体 | 先读目录内 `readme.txt` |
| `wKA_Img/` | wavenumber-domain / ω-k 算法 | 先读目录内 `readme.txt` |

不同目录下即使数据文件名相同，也**不要未经验证就合并或替换**，可能存在格式与实验条件差异。

## 准备数据与运行

原始说明要求将数据 `DAT_01.001` 放入相应算法目录的 `scene01/` 下，并在 `specify_parameters.m` 中指定成像区域参数。各算法有不同的运行步骤，请以各目录说明和源代码为准。

原始数据下载链接（保留历史资源，不保证当前可用）：

- 百度网盘：<https://pan.baidu.com/s/198PaXLU8v8BFwQ-tG4sLHw>
- 原说明提供的提取码：`8ia7`

![原有 SAR CSA 成像示例](SAR_CSA.jpg)

## 维护约定

- 保留各算法目录、实验样本、原始许可证 [LICENSE](LICENSE) 与图片引用。
- 提交新结果时注明数据来源、MATLAB/工具箱版本、参数、运行步骤与结果指标。
- 不把算法例程未经验证地描述为生产可用。本次仅完善仓库导航，未重新运行算法。
