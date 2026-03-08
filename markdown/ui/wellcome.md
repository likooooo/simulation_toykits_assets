# Simulation-toykits

基于 [MIT 协议](https://opensource.org/licenses/MIT) 的开源光学仿真工具（玩具??）集，以 Web 应用形式提供多层膜、高斯光束与偏微分方程等计算与可视化。

---

## 功能概览

- **Fresnel 计算器**：反射率 / 透射率、Fresnel 系数、膜系结构图；支持 [refractiveindex.info](https://refractiveindex.info/) 材料库与自定义 n/k。
- **高斯光束**：Hermite-Gaussian、Laguerre-Gaussian、Flat-top 等。  
Laguerre-Gaussian 仿真示例：[下载 MP4 视频](https://github.com/likooooo/simulation_toykits_assets/raw/main/ipynb/resources/laguerre_gaussain_beam.mp4)  
- **偏微分方程**: 基于 sturm liouville 理论的偏微分方程求解器（开发中）。  
Wave-equation-1d 仿真示例：[下载 MP4 视频](https://github.com/likooooo/simulation_toykits_assets/raw/main/ipynb/resources/wave_equation_1d.mp4)  
Wave-equation-2d 仿真示例：[下载 MP4 视频](https://github.com/likooooo/simulation_toykits_assets/raw/main/ipynb/resources/wave_equation_2d.mp4)  



详细使用说明见应用内「Fresnel 计算器」页的 **📖 使用说明** 及 [docs/fresnel_calculator_usage.md](https://github.com/likooooo/simulation_toykits/blob/main/docs/fresnel_calculator_usage.md)。

---

## 材料数据

材料光学数据来源于 [refractiveindex.info](https://refractiveindex.info/)。该数据库采用 [CC0 1.0 公共领域贡献](https://creativecommons.org/publicdomain/zero/1.0/) 协议，可自由使用、修改与分发，包括商业用途，无需额外许可。

---

## 许可证

本项目采用 MIT 许可证。材料数据遵循 refractiveindex.info 的 CC0 1.0 协议。