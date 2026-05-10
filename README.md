# nTop 隐式建模软件资料整理

整理日期：2026-05-10

> 这里的 nTop 指的是 nTop / nTopology 隐式建模、计算设计、增材制造建模软件，不是 ntop.org 网络流量监控软件。

## 先看结论

如果你想系统学习 nTop，我建议按这个顺序：

1. 先登录 [`app.ntop.com`](https://app.ntop.com)，从 Dashboard 下载软件、示例文件和学习资源。
2. 用 [`nTop Learn`](https://learn.ntop.com/) 学基础课程，尤其是 `nTop Foundations`、`Intro to Modeling`、`Intro to Field-Driven Design`、`Intro to Lattices`。
3. 直接做带示例文件的 Support 教程，优先做 lattice、field、remap、texture、automate 这些。
4. 看 nTop Live / Webinar 中带 `Download file` 的案例，边看边复现。
5. 最后补 Blog 和 Whitepaper，理解 implicit modeling、field-driven design、design automation 背后的思想。

## 项目文件 / 示例文件优先

这些页面明确提供 `.ntop`、示例文件、脚本或可下载 follow-along files，优先级最高。

### 1. nTop Dashboard 示例文件入口

链接：[nTop Account Guide](https://support.ntop.com/hc/en-us/articles/360048775554-nTop-Account-Guide)

官方说明：登录 nTop User Dashboard 后，可以从 Home 页面下载 nTop、examples 和 learning resources。这里通常是最直接的官方示例文件入口，但需要 nTop 账号。

适合：刚开始安装软件、找官方 examples、跟着 Learn 课程做练习。

### 2. nTop Learn 课程库

链接：[https://learn.ntop.com/](https://learn.ntop.com/)

官方免费课程入口，很多课程内部有 follow-along 文件或 download lesson。推荐重点看：

- `nTop Foundations`
- `Intro to Modeling`
- `Intro to Field-Driven Design`
- `Intro to Lattices`
- `Intro to Topology Optimization`
- `Intro to nTop Automate`
- `Heat Exchanger Design 1/2/3`
- `Parametric Aircraft Design`
- `Parametric Turbomachinery Design`

适合：从零到能自己搭 notebook workflow。

### 3. End-to-End High-Efficiency Heat Exchanger Design with Integrated CFD

链接：[Webinar 页面](https://www.ntop.com/resources/webinars/end-to-end-high-efficiency-heat-exchanger-design-with-integrated-cfd/)

时间：2026-03-25

页面提供：`Download the nTop file used in this webinar: nTop Heat Exchanger`

这是比较新的高价值项目文件，内容包括：

- TPMS lattice heat exchanger
- 参数化换热器建模
- integrated GPU-based CFD
- CHT coupled thermal-fluid analysis
- 用 flow field data 反馈几何优化

适合：热管理、换热器、流体仿真、TPMS lattice。

### 4. Custom Field Optimization Component with a Custom Graph Unit Cell

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/16505180871315-How-to-create-Custom-Field-Optimization-Component-with-a-Custom-Graph-Unit-Cell)

时间：2026-03-02

页面提供：`Follow Along Files`

高级项目文件，涉及：

- custom graph unit cell
- nTop Automate
- topology optimization
- field optimization
- homogenization data
- Python 脚本批量运行
- parametric lattice component

适合：想研究晶格参数化、均匀化、场优化、自定义组件的人。

### 5. Preparing an nTop Notebook for nTop Automate

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/360052833053-Preparing-an-nTop-Notebook-for-nTop-Automate)

时间：2026-03-16

页面提供：`Example File`

核心内容：

- 如何声明 notebook input variables
- 如何声明 output
- 如何用 `ntopcl -j input.json -o output.json SampleFile.ntop` 跑 notebook

适合：把 nTop workflow 做成可重复、可批处理的自动化流程。

### 6. Running nTop Automate in Python scripts

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/360052703693-Running-nTop-Automate-in-Python-scripts)

时间：2026-04-02

页面提供：

- `Sample File`
- `Script_JSON.py`

核心内容：

- 用 Python 生成 JSON 输入
- 用 `subprocess` 调用 `nTopCL.exe`
- 批量运行 nTop notebook

适合：设计自动化、DoE、批量生成变体、和外部仿真/优化工具联动。

### 7. Introduction to the Remap Field block

> **【已读】2026-05-10**
>
> **【五星】★★★★★**

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/4408249667731-Introduction-to-the-Remap-Field-block)

更新时间：2026-04-06

页面提供：

- 40:17 视频
- `Example File`

核心内容：

- remap field 基础
- mirroring / arraying / orienting
- image on body
- spatially-varying shifting and stretching
- warping by shape fields
- cylindrical remap

适合：理解 nTop 里最关键的 field 操作之一。

### 8. How to build a custom lattice unit cell

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/360055403953-How-to-build-a-custom-lattice-unit-cell)

时间：2026-04-02

页面提供：`Example File`

核心内容：

- custom unit cell
- implicit body overload
- graph overload
- bounding box / unit cell domain
- face-based unit cell
- CAD sketch to unit cell
- hybrid face-beam lattice

适合：晶格结构设计的基础项目。

### 9. How to build a structural lattice on a CAD face

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/360042295414-How-to-build-a-structural-lattice-on-a-CAD-face)

时间：2026-04-02

页面提供：`Example File`

核心内容：

- CAD face 上生成 honeycomb lattice
- Cell Map from CAD Face
- conformal lattice / structural lattice

适合：把晶格贴合到 CAD 面上的实战。

### 10. How to generate randomized lattice thickness

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/360041726534-How-to-generate-randomized-lattice-thickness)

时间：2026-04-02

页面提供：`Example File`

核心内容：

- Simplex Noise 3D
- Ramp 控制 beam thickness
- Voronoi Volume Lattice
- stochastic foam 效果

适合：随机泡沫、随机晶格、自然纹理、可控复杂结构。

### 11. How to create a Voronoi surface texture

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/360042365673-How-to-create-a-Voronoi-surface-texture)

时间：2026-03-02

页面提供：`Example File`

核心内容：

- Random Points on Mesh
- Voronoi Surface Lattice
- Boolean Subtract 生成表面纹理

适合：表面纹理、仿皮革/浮雕/凹纹、工业设计外观。

### 12. How to warp a lattice with sine wave spacing

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/1500002409602-How-to-warp-a-lattice-with-sine-wave-spacing)

时间：2025-12-19

页面提供：

- `Example file`
- `Normalize Field` custom block 下载

核心内容：

- 用 sine wave field 扭曲晶格
- Remap Field
- Normalize Field
- trim / thicken lattice

适合：field-driven lattice、空间变形、周期结构变形。

### 13. How to create an FE Mesh for a complex shell lattice

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/360058488094-How-to-create-an-FE-Mesh-for-a-complex-shell-lattice)

时间：2026-01-13

页面提供：`Example file`

核心内容：

- trimmed shell lattice
- faces as mesh
- FE Surface Mesh
- complex lattice simulation mesh

适合：复杂晶格结构分析、FE mesh、仿真前处理。

### 14. How to warp the cell size of a Cell Map

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/360060023794-How-to-warp-the-cell-size-of-a-Cell-Map)

时间：2026-04-02

页面提供：`Example File`

核心内容：

- Warp Cell Map block（U/V/W scale fields）
- 用 Ramp / field 做 graded cell size（空间渐变晶格尺寸）
- 示例包含 linear warp / radial warp

适合：周期晶格、Cell Map 基础、graded lattice、用 fields 让晶格“随位置变化”。

### 15. Generating surface textures with procedural modeling

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/360060809134-Generating-surface-textures-with-procedural-modeling)

时间：2026-03-02

页面提供：

- 多个 `.ntop` 示例文件（Roughness / Leather / Wood / Marble）
- `Procedural texturing with nTop` 附件

核心内容：

- 用噪声场（Simplex / Cellular）+ Offset 生成表面粗糙度/纹理
- 用 Ramp / Remap Field 控制纹理强度与频率（随位置渐变）
- 将 workflow 抽象成可复用的“一键上纹理”模板

适合：表面纹理（外观/触感/功能纹理）、field-driven texturing、复杂曲面贴纹理。

### 16. Download: Completed Box and Lattice nTop Automate Files

链接：[nTop Learn 下载页](https://learn.ntop.com/courses/330-ntop-automate/lessons/download-completed-box-and-lattice-ntop-automate-files/)

发布时间：nTop Learn 页面显示 Published: 2.1 years ago

页面提供：

- `330_10_1 BoxExample.zip`
- `330_10_2 LatticeExample.zip`

核心内容：

- `Intro to nTop Automate` 课程的 follow-along 完成版文件，用于对照/复现 nTop Automate（CLI）流程
- 适合作为“可运行的起点”去练：JSON 输入输出、批处理生成变体、脚本化调用 nTopCL

适合：nTop Automate / CLI 入门、设计自动化、批量生成变体（DoE/参数扫描）。

### 17. Download: Completed Lattice Simulation nTop Files

链接：[nTop Learn 下载页](https://learn.ntop.com/lessons/download-completed-lattice-simulation-ntop-files-2/)

发布时间：nTop Learn 页面显示 Published: 2.1 years ago

页面提供（均注明 last updated in `nTop 5.14.2`）：

- `342_9_Complete — Lattice FEA Using Solid Elements.ntop`
- `342_9_Complete — Lattice FEA Using Beam Elements.ntop`
- `342_9_Complete — Lattice FEA Homogenization.ntop`

核心内容：

- 三种晶格结构分析路径的“完成版”对照文件：solid elements / beam elements / homogenization
- 文件内带注释（workflow 每一步的说明），适合拿来逐块拆解学习与对比优缺点

适合：晶格仿真入门、不同 lattice FEA 方法对比、仿真前处理与 workflow 复用。

### 18. Download: Completed Field Driven Bracket

链接：[nTop Learn 下载页](https://learn.ntop.com/courses/220-intro-to-field-driven-design/lessons/download-completed-field-driven-bracket/)

页面提供：

- `220_12_1 Completed — Field Driven Bracket.ntop`（注明 last updated in `nTop 5.15.2`）

核心内容：

- `Intro to Field-Driven Design` 课程的 follow-along 完成版文件（带描述/注释），适合对照复现完整建模思路
- 重点练 field-driven design：用 distance / ramp / remap 等 field 操作驱动几何变化，并把“参数 → 形态”的映射关系做稳定

适合：fields 入门后想做一个完整小项目的人；把 field 操作串成可复用 workflow。

### 19. How to use nTop Automate in ModeFrontier DOE workflows

链接：[Support 教程](https://support.ntop.com/hc/en-us/articles/360052078394-How-to-use-nTop-Automate-in-ModeFrontier-DOE-workflows)

时间：2026-03-16

页面提供：

- 教程内嵌视频
- `Example File`（`Mode Frontier Example.zip`）

核心内容：

- 用 ModeFrontier 做 DOE，把设计变量传给 nTop Notebook（通过 nTop Automate / `ntopcl`）
- 用 JSON 输入/输出把 nTop workflow 接入外部 MDO 平台，跑批量设计探索（mass criteria 等目标/约束）

适合：nTop Automate / CLI 进阶；需要把 nTop 接入 ModeFrontier/DOE/MDO 流程的人。

### 20. nTop Learn 课程总览：nTop Automate（Course 330）

链接：[nTop Learn 课程页](https://learn.ntop.com/courses/330-ntop-automate/)

类型：nTop Learn 课程（含多个可下载 follow-along / completed files）

更新时间：课程页未标注（以页面实际为准）

适合方向：自动化 / CLI（`ntopcl`）/ 批处理 / 参数探索

说明：和已收录的「Download: Completed Box and Lattice nTop Automate Files」「Download: Completed Lattice Simulation nTop Files」同属一个课程；建议先按课程结构系统学习，再按章节下载对应 `.ntop` / zip 复现。

### 21. nTop Learn 课程总览：Intro to Field-Driven Design（Course 220）

链接：[nTop Learn 课程页](https://learn.ntop.com/courses/220-intro-to-field-driven-design/)

类型：nTop Learn 课程（含多个可下载 follow-along / completed files）

更新时间：课程页未标注（以页面实际为准）

适合方向：Field-driven design（distance / ramp / remap 等）/ 参数化建模方法论

说明：和已收录的「Download: Completed Field Driven Bracket」同属一个课程；适合把 field 的概念、常用 block、组合套路和完整小项目串起来复盘。

## 视频资料

这些更适合边看边做。带 `Download file` 的视频优先。

### 1. What is implicit modeling in nTop?

链接：[视频页面](https://www.ntop.com/videos/video/ntop-live-what-is-implicit-modeling-in-ntopology/)

时间：2021-08-30

页面提供：`Download the files`

经典入门视频，讲：

- implicit modeling 是什么
- 为什么不显式计算 edges / vertices
- 如何快速生成传统 CAD 很难处理的复杂几何

### 2. How to use fields in nTop

链接：[视频页面](https://www.ntop.com/resources/videos/how-to-use-fields-in-ntopology/)

时间：2021-08-18

页面提供：`Download the files`

经典 field-driven design 入门，讲：

- distance field
- field viewer
- ramp block
- 用仿真数据驱动几何

### 3. Field-driven design techniques: Two-body field

链接：[视频页面](https://www.ntop.com/resources/videos/ntop-live-workflow-and-modeling-techniques-in-ntop-platform/)

时间：2020-04-13

页面提供：`Download file`

Blake Courter 的经典 masterclass，讲：

- two-body field
- distance field 的数学操作
- 用 field 设计流体喷嘴、结构 ribs、flow guides

### 4. Robust meshing of complex geometries for manufacturing

链接：[视频页面](https://www.ntop.com/resources/videos/ntop-live-robust-meshing-of-complex-geometries-for-manufacturing/)

时间：2021-03-15

页面提供：`Download the files`

适合学习：

- implicit body 到 mesh
- lattice structure mesh
- mesh simplification
- 制造前处理

### 5. How to shell any 3D body without errors in nTop

链接：[视频页面](https://www.ntop.com/resources/videos/how-to-shell-any-3d-body-without-errors-in-ntopology/)

时间：2021-10-13

页面提供：`Download the files`

适合学习：

- CAD part 转 implicit body
- shell 操作
- lattice infill
- 批量 shell + infill workflow

### 6. Parametric modeling of hyper-realistic 3D textures

链接：[视频页面](https://www.ntop.com/resources/videos/ntop-live-parametric-modeling-of-hyper-realistic-3d-textures-for-industrial-design/)

时间：2020-08-10

页面提供：`Download file`

适合学习：

- 从零创建 3D textures
- leather / wood / marble texture
- 将 texture wrap 到复杂曲面
- 用 field 空间控制 texture 参数

### 7. Automated topology optimization reconstruction and smoothening

> **【已读】2026-05-06**

链接：[视频页面](https://www.ntop.com/resources/videos/ntop-live-automated-topology-optimization-reconstruction-smoothening-in-ntopology/)

时间：2021-10-21

页面提供：`Download the files`

适合学习：

- 拓扑优化结果重建
- Smoothen Body
- 面向制造的 topology optimized part 输出

### 8. Lightweighting an impeller for additive manufacturing

链接：[视频页面](https://www.ntop.com/resources/videos/lightweighting-an-impeller-for-additive-manufacturing/)

时间：2024-03-01

比较新的实战视频，讲：

- impeller lightweighting
- topology optimization
- variable shelling
- latticing
- simulation data 驱动 shell/lattice thickness

### 9. How nTop Enables Computational Design

链接：[视频页面](https://www.ntop.com/resources/videos/how-ntop-enables-computational-design/)

时间：2025-09-19

较新，适合理解 nTop 如何支撑 computational design、迭代分析和优化闭环。

### 10. Implicits: The Future of CAD

链接：[视频页面](https://www.ntop.com/resources/videos/implicits-the-future-of-cad/)

时间：2025-09-19

较新，偏理念和技术方向，适合理解为什么 implicit modeling 在鲁棒性、速度、复杂度上优于传统 CAD。

### 11. From Months to Minutes: Accelerated Aircraft Modeling

链接：[Webinar 页面](https://www.ntop.com/resources/webinars/from-months-to-minutes-accelerated-aircraft-modeling-webinar/)

时间：2026-01-26

较新，适合航空参数化建模方向。内容包括：

- unbreakable parametric geometry
- modeling as code
- aircraft design toolkit
- simulation-ready geometry / mesh

### 12. The block anatomy in nTop

链接：[视频页面](https://www.ntop.com/resources/videos/ntop-live-the-block-anatomy-in-ntopology/)

时间：2021-07-26

类型：nTop Live 视频（含下载文件）

页面提供：`Download file`（下载：[Box 链接](https://ntopology.box.com/s/5flqgx0xfjxo9f5rdh37yqwhcf94zbxv/)）

经典基础课，适合学习：

- nTop blocks 的输出类型、overload、属性等“积木语法”
- block 信息面板 / comments / 最佳实践
- 为后续做自定义 block、自动化 workflow 打基础

### 13. nTop training: Thermal management

链接：[视频页面](https://www.ntop.com/resources/videos/ntop-training-thermal-management/)

时间：2022-05-31

类型：Training 视频（含下载文件）

页面提供：`Download the files`（下载：[Box 链接](https://ntopology.app.box.com/s/e6wd4hmbh0a8nw27kzi36u07xclilj7m)）

适合学习方向：Thermal FEA / Simulation-driven design。内容覆盖：

- thermal FEA 入门与演示（含结果理解与应用）
- 将仿真结果转为可驱动几何/结构的 field（思路与操作）
- 从基础建模到可复用 workflow / custom blocks 的训练式串联

## Blog / Whitepaper / 理论资料

这些资料适合帮助你建立底层认知。

### 1. Implicit Modeling Technology Whitepaper

链接：[Whitepaper](https://www.ntop.com/resources/whitepaper-implicit-modeling-technology)

官方 implicit modeling 白皮书，适合认真理解：

- implicit modeling 和传统 CAD 的区别
- signed distance function / implicit body 的优势
- 为什么 nTop 对复杂几何、自动化和 AM 友好

### 2. Implicit modeling for engineering design

链接：[Blog](https://www.ntop.com/blog/implicit-modeling-for-mechanical-design/)

时间：2019-01-22

经典文章，讲：

- why implicit modeling
- unbreakable modeling operations
- automation and geometric complexity
- field-driven design

### 3. B-rep vs. implicit modeling: Understanding the basics

链接：[Blog](https://www.ntop.com/blog/understanding-the-basics-of-b-reps-and-implicits/)

时间：2019-03-12

经典基础文章，适合把 B-rep、mesh、distance fields、implicits 的差异搞清楚。

### 4. Interpolating with implicit modeling

链接：[Blog](https://www.ntop.com/blog/interpolating-with-implicit-modeling/)

时间：2019-04-12

适合理解 implicit blending、loft-like interpolation、variable offset。

### 5. Lightweighting with implicit models

链接：[Blog](https://www.ntop.com/blog/lightweighting-with-implicit-models/)

时间：2019-05-08

经典轻量化文章，适合学习 lattice、metamaterial、mesoscale structure 的基础思路。

### 6. Design at scale with nTop Automate

链接：[Blog](https://www.ntop.com/resources/blog/design-at-scale-with-ntop-automate/)

时间：2023-06-28

适合学习：

- nTop Automate / CLI
- batch processing
- design exploration
- mass customization

### 7. Introducing nTop Fluids

链接：[Blog](https://www.ntop.com/resources/blog/introducing-ntop-fluids/)

时间：2025-05-27

较新，讲 nTop Fluids、GPU-native CFD、implicit modeling 与快速流体仿真的结合。

### 8. nTop Modeling Capability Page

链接：[Modeling 页面](https://www.ntop.com/software/capabilities/modeling/)

较新的官方能力介绍，适合快速了解 nTop 当前产品定位：

- parametric implicit design
- signed distance functions
- stable geometry
- simulation-ready workflows
- DfAM / lattice / complex geometry

## 最新版本 / What's New

官方 Support 首页会列出最近版本。2026-05-05 查询时，Support 首页显示最近版本包含：

- `nTop 5.46`：three new blocks for curve generation
- `nTop 5.45`：Fluids solver improvements
- `nTop 5.44`：physics improvements, Knudsen-limited non-equilibrium damping
- `nTop 5.43`：ONNX neural network import / surrogate modeling、Remap Field 新 overload、Track to Block

入口：

- [nTop Support 首页](https://support.ntop.com/hc/en-us)
- [What's New 分类](https://support.ntop.com/hc/en-us/categories/360005712353-What-s-New)
- [nTop 5.45 - What's New](https://support.ntop.com/hc/en-us/articles/50924590694163-nTop-5-45-What-s-New)
- [nTop 5.44 - What's New](https://support.ntop.com/hc/en-us/articles/50584612932755-nTop-5-44-What-s-New)
- [nTop 5.43 - What's New](https://support.ntop.com/hc/en-us/articles/50080923413907-nTop-5-43-What-s-New)
- [nTop 5.0 - New Implicit Modeling Kernel](https://support.ntop.com/hc/en-us/articles/26062971882131-nTop-5-0-New-Implicit-Modeling-Kernel)

## 按方向快速选择

| 方向 | 优先资料 |
| --- | --- |
| 刚入门 | nTop Dashboard examples、nTop Learn、What is implicit modeling |
| 隐式建模理论 | Whitepaper、Implicit modeling for engineering design、B-rep vs implicit |
| Field-driven design | How to use fields、Two-body field、Remap Field block |
| 晶格结构 | Custom lattice unit cell、Structural lattice on CAD face、Randomized lattice thickness |
| 表面纹理 | Voronoi surface texture、Parametric hyper-realistic 3D textures |
| 拓扑优化 | Intro to Topology Optimization、Topology reconstruction video、Custom Field Optimization Component |
| 自动化 | nTop Automate course、Preparing Notebook for Automate、Python scripts |
| 换热器 / 热管理 | End-to-End Heat Exchanger Webinar、Heat Exchanger Design Learn courses、nTop Fluids |
| 仿真 / 网格 | FE Mesh for complex shell lattice、Robust meshing video、nTop Fluids |
| 航空参数化 | Parametric Aircraft Design、Accelerated Aircraft Modeling Webinar |
