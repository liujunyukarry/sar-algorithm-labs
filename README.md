# SAR Algorithm Labs

合成孔径雷达（Synthetic Aperture Radar，SAR）的 MATLAB 学习算法集合。每个原仓库完整保留，数据文件不去重、不互相覆盖。大型 `liujunyukarry/sar` 继续独立维护。

## 项目索引与运行

| 分类 | 完整原仓库目录 | 入口及说明 |
| --- | --- | --- |
| 雷达基础仿真 | [Radar-SAR-simu](radar-basics/Radar-SAR-simu/) | `lfmPulseCompression.m` 脉冲压缩，`radarImaging_withDotsTarget.m` 点目标，`realDataProsessing.m` 真实数据处理 |
| 成像算法 | [SAR-imaging](imaging-algorithms/SAR-imaging/) | `CSA_Img`、`RDA2_Img`、`RDA3_Img`、`wKA_Img`；先读各目录 readme.txt |
| 点目标仿真 | [Simulation-of-SAR-Imaging-Algorithm](point-targets/Simulation-of-SAR-Imaging-Algorithm/) | `RDA_imaging.m`、`CSA_imaging.m`、`target_analysis.m`、`zhibiao_2.m`，见原 readme.txt |

基础仿真示例：在 MATLAB 中将当前目录切到 `radar-basics/Radar-SAR-simu`，检查脚本参数后运行 `lfmPulseCompression` 或 `radarImaging_withDotsTarget`；后者保持与辅助函数 `rect.m` 同目录。

成像算法在 MATLAB 中分别进入各算法目录，按各自 readme.txt 指定的步骤运行。部分真实数据需要将 `DAT_01.001` 放入算法目录的 `scene01/` 并检查 `specify_parameters.m`。原始代码、已提交的 `.mat` 数据和图片均保留；外部下载数据不属于此次 Git 文件迁移范围，其历史链接仍在原 README 中，尚未验证可下载。

点目标实验需先核对初始化参数、脚本顺序和工具箱依赖，再运行对应算法。当前没有宣称 MATLAB 运行、数值正确性或成像质量已验证。

## 来源与许可

| 原仓库 | 原上游 | 原始许可 |
| --- | --- | --- |
| liujunyukarry/Radar-SAR-simu | lwh521jll/Radar-SAR-simu | [原 LICENSE](radar-basics/Radar-SAR-simu/LICENSE) |
| liujunyukarry/SAR-imaging | joeyos/SAR-imaging | [原 LICENSE](imaging-algorithms/SAR-imaging/LICENSE) |
| liujunyukarry/Simulation-of-SAR-Imaging-Algorithm | denkywu/Simulation-of-SAR-Imaging-Algorithm | 未发现独立 LICENSE；不额外授予许可 |

本仓库没有用统一许可证覆盖原项目，原作者署名和原始许可文本保持原样。新综合仓库并不继承三个 fork 的 GitHub fork 关系；原 fork 仓库保留该关系。

见 [迁移说明与验证方法](docs/MIGRATION.md) 和 [验证结果](docs/VALIDATION.md)。
