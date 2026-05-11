# nTop 隐式建模软件资料整理

最后更新：2026-05-11

> 这里的 nTop 指 nTop / nTopology 隐式建模、计算设计、增材制造建模软件，不是 ntop.org 网络流量监控软件。

自动维护目标：每天上午 10:00 新增 2 条 nTop / nTopology 隐式建模资料，优先选择带项目文件、Example File、Download file、`.ntop`、视频教程和高质量文章的资源。

标记说明：![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 表示你已经看过；![标星](https://img.shields.io/badge/%E6%A0%87%E6%98%9F-red) 表示重点收藏。你以后告诉我哪些看过或要标星，我会把对应条目移动到前面，并使用红色标记。

## 已读 / 标星置顶

1. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) ![标星](https://img.shields.io/badge/%E6%A0%87%E6%98%9F-red) **[Introduction to the Remap Field block](https://support.ntop.com/hc/en-us/articles/4408249667731-Introduction-to-the-Remap-Field-block)** · 已读：2026-05-10 · 五星。  
   适合：remap field、mirroring/arraying/orienting、image on body、shape field warping、cylindrical remap。

2. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[Automated topology optimization reconstruction and smoothening](https://www.ntop.com/resources/videos/ntop-live-automated-topology-optimization-reconstruction-smoothening-in-ntopology/)** · 已读：2026-05-06。  
   适合：拓扑优化结果重建、Smoothen Body、面向制造的 topology optimized part 输出。

## 每日新增记录

> 自动任务会从这里继续追加每天新增的 2 条资料；已有链接不会重复添加。

## 学习路线

1. 先登录 [`app.ntop.com`](https://app.ntop.com)，下载软件、examples 和 learning resources。
2. 再用 [`nTop Learn`](https://learn.ntop.com/) 学 `nTop Foundations`、`Intro to Modeling`、`Intro to Field-Driven Design`、`Intro to Lattices`。
3. 优先做带 `.ntop`、Example File、Follow Along Files、Download file 的资料。
4. 最后补 Blog / Whitepaper，理解 implicit modeling、field-driven design、design automation 背后的思想。

## 项目文件 / 示例文件优先

1. **[nTop Dashboard 示例文件入口](https://support.ntop.com/hc/en-us/articles/360048775554-nTop-Account-Guide)** · 官方入口，需 nTop 账号；可下载软件、examples、learning resources。  
   适合：安装软件、找官方 examples、配合 Learn 课程练习。

2. **[nTop Learn 课程库](https://learn.ntop.com/)** · 官方免费课程，很多章节带 follow-along / download lesson。  
   适合：从零系统学习 `nTop Foundations`、Modeling、Field、Lattices、Topology Optimization、Automate、Heat Exchanger 等课程。

3. **[End-to-End High-Efficiency Heat Exchanger Design with Integrated CFD](https://www.ntop.com/resources/webinars/end-to-end-high-efficiency-heat-exchanger-design-with-integrated-cfd/)** · Webinar，2026-03-25；提供 `nTop Heat Exchanger` 文件。  
   适合：TPMS lattice heat exchanger、热管理、GPU CFD、CHT、flow field 驱动优化。

4. **[Custom Field Optimization Component with a Custom Graph Unit Cell](https://support.ntop.com/hc/en-us/articles/16505180871315-How-to-create-Custom-Field-Optimization-Component-with-a-Custom-Graph-Unit-Cell)** · Support，2026-03-02；提供 `Follow Along Files`。  
   适合：custom graph unit cell、nTop Automate、拓扑优化、field optimization、homogenization、Python 批处理。

5. **[Preparing an nTop Notebook for nTop Automate](https://support.ntop.com/hc/en-us/articles/360052833053-Preparing-an-nTop-Notebook-for-nTop-Automate)** · Support，2026-03-16；提供 `Example File`。  
   适合：声明 inputs/outputs，用 `ntopcl -j input.json -o output.json SampleFile.ntop` 批处理 notebook。

6. **[Running nTop Automate in Python scripts](https://support.ntop.com/hc/en-us/articles/360052703693-Running-nTop-Automate-in-Python-scripts)** · Support，2026-04-02；提供 `Sample File` + `Script_JSON.py`。  
   适合：Python 生成 JSON、调用 `nTopCL.exe`、DoE、批量生成变体、外部优化/仿真联动。

7. **[Introduction to the Remap Field block](https://support.ntop.com/hc/en-us/articles/4408249667731-Introduction-to-the-Remap-Field-block)** · Support，更新 2026-04-06；40:17 视频 + `Example File`。  
   > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) ![标星](https://img.shields.io/badge/%E6%A0%87%E6%98%9F-red) 已读：2026-05-10 · 五星  
   适合：remap field、mirroring/arraying/orienting、image on body、shape field warping、cylindrical remap。

8. **[How to build a custom lattice unit cell](https://support.ntop.com/hc/en-us/articles/360055403953-How-to-build-a-custom-lattice-unit-cell)** · Support，2026-04-02；提供 `Example File`。  
   适合：custom unit cell、implicit/graph overload、unit cell domain、face-based / CAD sketch / hybrid face-beam lattice。

9. **[How to build a structural lattice on a CAD face](https://support.ntop.com/hc/en-us/articles/360042295414-How-to-build-a-structural-lattice-on-a-CAD-face)** · Support，2026-04-02；提供 `Example File`。  
   适合：CAD face 上生成 honeycomb / conformal lattice，学习 `Cell Map from CAD Face`。

10. **[How to generate randomized lattice thickness](https://support.ntop.com/hc/en-us/articles/360041726534-How-to-generate-randomized-lattice-thickness)** · Support，2026-04-02；提供 `Example File`。  
    适合：Simplex Noise、Ramp 控制 beam thickness、Voronoi Volume Lattice、随机泡沫结构。

11. **[How to create a Voronoi surface texture](https://support.ntop.com/hc/en-us/articles/360042365673-How-to-create-a-Voronoi-surface-texture)** · Support，2026-03-02；提供 `Example File`。  
    适合：Random Points on Mesh、Voronoi Surface Lattice、Boolean Subtract、仿皮革/浮雕/凹纹。

12. **[How to warp a lattice with sine wave spacing](https://support.ntop.com/hc/en-us/articles/1500002409602-How-to-warp-a-lattice-with-sine-wave-spacing)** · Support，2025-12-19；提供 `Example file` + `Normalize Field` custom block。  
    适合：sine wave field、Remap Field、Normalize Field、空间周期结构变形。

13. **[How to create an FE Mesh for a complex shell lattice](https://support.ntop.com/hc/en-us/articles/360058488094-How-to-create-an-FE-Mesh-for-a-complex-shell-lattice)** · Support，2026-01-13；提供 `Example file`。  
    适合：trimmed shell lattice、faces as mesh、FE Surface Mesh、复杂晶格仿真前处理。

14. **[How to warp the cell size of a Cell Map](https://support.ntop.com/hc/en-us/articles/360060023794-How-to-warp-the-cell-size-of-a-Cell-Map)** · Support，2026-04-02；提供 `Example File`。  
    适合：Warp Cell Map、U/V/W scale fields、linear/radial warp、graded lattice。

15. **[Generating surface textures with procedural modeling](https://support.ntop.com/hc/en-us/articles/360060809134-Generating-surface-textures-with-procedural-modeling)** · Support，2026-03-02；多个 `.ntop` 示例 + 附件。  
    适合：Roughness / Leather / Wood / Marble，噪声场 + Offset + Ramp / Remap Field 做程序纹理。

16. **[Download: Completed Box and Lattice nTop Automate Files](https://learn.ntop.com/courses/330-ntop-automate/lessons/download-completed-box-and-lattice-ntop-automate-files/)** · nTop Learn，Published: 2.1 years ago；提供 `BoxExample.zip`、`LatticeExample.zip`。  
    适合：Intro to nTop Automate 完成版文件、JSON I/O、批处理变体、脚本化调用 nTopCL。

17. **[Download: Completed Lattice Simulation nTop Files](https://learn.ntop.com/lessons/download-completed-lattice-simulation-ntop-files-2/)** · nTop Learn，Published: 2.1 years ago；3 个 `.ntop`，last updated in `nTop 5.14.2`。  
    适合：solid elements / beam elements / homogenization 三种 lattice FEA 方法对比。

18. **[Download: Completed Field Driven Bracket](https://learn.ntop.com/courses/220-intro-to-field-driven-design/lessons/download-completed-field-driven-bracket/)** · nTop Learn；提供 `Completed — Field Driven Bracket.ntop`，last updated in `nTop 5.15.2`。  
    适合：Intro to Field-Driven Design 完整小项目，用 distance / ramp / remap 驱动几何。

19. **[How to use nTop Automate in ModeFrontier DOE workflows](https://support.ntop.com/hc/en-us/articles/360052078394-How-to-use-nTop-Automate-in-ModeFrontier-DOE-workflows)** · Support，2026-03-16；视频 + `Mode Frontier Example.zip`。  
    适合：ModeFrontier DOE/MDO，JSON 输入输出，nTop Automate 接外部设计探索平台。

20. **[nTop Learn 课程总览：nTop Automate（Course 330）](https://learn.ntop.com/courses/330-ntop-automate/)** · nTop Learn 课程页，含多个 follow-along / completed files。  
    适合：系统学习 CLI、`ntopcl`、批处理、参数探索；再按章节下载对应 `.ntop` / zip。

21. **[nTop Learn 课程总览：Intro to Field-Driven Design（Course 220）](https://learn.ntop.com/courses/220-intro-to-field-driven-design/)** · nTop Learn 课程页，含多个 follow-along / completed files。  
    适合：field 概念、常用 block、组合套路和完整 bracket 小项目复盘。

## 视频资料

1. **[What is implicit modeling in nTop?](https://www.ntop.com/videos/video/ntop-live-what-is-implicit-modeling-in-ntopology/)** · 视频，2021-08-30；提供 `Download the files`。  
   适合：implicit modeling 入门、为什么不显式计算 edges / vertices、复杂几何生成。

2. **[How to use fields in nTop](https://www.ntop.com/resources/videos/how-to-use-fields-in-ntopology/)** · 视频，2021-08-18；提供 `Download the files`。  
   适合：distance field、field viewer、ramp block、仿真数据驱动几何。

3. **[Field-driven design techniques: Two-body field](https://www.ntop.com/resources/videos/ntop-live-workflow-and-modeling-techniques-in-ntop-platform/)** · nTop Live，2020-04-13；提供 `Download file`。  
   适合：Blake Courter masterclass、two-body field、流体喷嘴/ribs/flow guides 设计。

4. **[Robust meshing of complex geometries for manufacturing](https://www.ntop.com/resources/videos/ntop-live-robust-meshing-of-complex-geometries-for-manufacturing/)** · nTop Live，2021-03-15；提供 `Download the files`。  
   适合：implicit body 到 mesh、lattice mesh、mesh simplification、制造前处理。

5. **[How to shell any 3D body without errors in nTop](https://www.ntop.com/resources/videos/how-to-shell-any-3d-body-without-errors-in-ntopology/)** · 视频，2021-10-13；提供 `Download the files`。  
   适合：CAD 转 implicit、shell、lattice infill、批量 shell + infill workflow。

6. **[Parametric modeling of hyper-realistic 3D textures](https://www.ntop.com/resources/videos/ntop-live-parametric-modeling-of-hyper-realistic-3d-textures-for-industrial-design/)** · nTop Live，2020-08-10；提供 `Download file`。  
   适合：leather / wood / marble texture，复杂曲面 wrap，field 控制 texture 参数。

7. **[Automated topology optimization reconstruction and smoothening](https://www.ntop.com/resources/videos/ntop-live-automated-topology-optimization-reconstruction-smoothening-in-ntopology/)** · 视频，2021-10-21；提供 `Download the files`。  
   > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-06  
   适合：拓扑优化结果重建、Smoothen Body、面向制造的 topology optimized part 输出。

8. **[Lightweighting an impeller for additive manufacturing](https://www.ntop.com/resources/videos/lightweighting-an-impeller-for-additive-manufacturing/)** · 视频，2024-03-01。  
   适合：impeller lightweighting、topology optimization、variable shelling、latticing、仿真数据驱动厚度。

9. **[How nTop Enables Computational Design](https://www.ntop.com/resources/videos/how-ntop-enables-computational-design/)** · 视频，2025-09-19。  
   适合：理解 nTop 如何支撑 computational design、迭代分析和优化闭环。

10. **[Implicits: The Future of CAD](https://www.ntop.com/resources/videos/implicits-the-future-of-cad/)** · 视频，2025-09-19。  
    适合：理解 implicit modeling 在鲁棒性、速度、复杂度上相对传统 CAD 的优势。

11. **[From Months to Minutes: Accelerated Aircraft Modeling](https://www.ntop.com/resources/webinars/from-months-to-minutes-accelerated-aircraft-modeling-webinar/)** · Webinar，2026-01-26。  
    适合：航空参数化建模、modeling as code、aircraft design toolkit、simulation-ready geometry / mesh。

12. **[The block anatomy in nTop](https://www.ntop.com/resources/videos/ntop-live-the-block-anatomy-in-ntopology/)** · nTop Live，2021-07-26；提供 `Download file`。  
    适合：block 输出类型、overload、属性、信息面板、comments、自定义 block / 自动化 workflow 基础。

13. **[nTop training: Thermal management](https://www.ntop.com/resources/videos/ntop-training-thermal-management/)** · Training，2022-05-31；提供 `Download the files`。  
    适合：Thermal FEA、仿真结果转 field、simulation-driven design、custom blocks 训练。

## Blog / Whitepaper / 理论资料

1. **[Implicit Modeling Technology Whitepaper](https://www.ntop.com/resources/whitepaper-implicit-modeling-technology)** · 官方白皮书。  
   适合：系统理解 implicit modeling、signed distance function / implicit body、复杂几何与 AM 友好性。

2. **[Implicit modeling for engineering design](https://www.ntop.com/blog/implicit-modeling-for-mechanical-design/)** · Blog，2019-01-22。  
   适合：why implicit modeling、unbreakable modeling operations、automation、field-driven design。

3. **[B-rep vs. implicit modeling: Understanding the basics](https://www.ntop.com/blog/understanding-the-basics-of-b-reps-and-implicits/)** · Blog，2019-03-12。  
   适合：区分 B-rep、mesh、distance fields、implicits。

4. **[Interpolating with implicit modeling](https://www.ntop.com/blog/interpolating-with-implicit-modeling/)** · Blog，2019-04-12。  
   适合：implicit blending、loft-like interpolation、variable offset。

5. **[Lightweighting with implicit models](https://www.ntop.com/blog/lightweighting-with-implicit-models/)** · Blog，2019-05-08。  
   适合：lattice、metamaterial、mesoscale structure、轻量化基础思路。

6. **[Design at scale with nTop Automate](https://www.ntop.com/resources/blog/design-at-scale-with-ntop-automate/)** · Blog，2023-06-28。  
   适合：nTop Automate / CLI、batch processing、design exploration、mass customization。

7. **[Introducing nTop Fluids](https://www.ntop.com/resources/blog/introducing-ntop-fluids/)** · Blog，2025-05-27。  
   适合：nTop Fluids、GPU-native CFD、implicit modeling 与快速流体仿真结合。

8. **[nTop Modeling Capability Page](https://www.ntop.com/software/capabilities/modeling/)** · 官方能力页。  
   适合：快速了解 parametric implicit design、SDF、stable geometry、simulation-ready workflows、DfAM。

## 最新版本 / What's New

入口：[nTop Support 首页](https://support.ntop.com/hc/en-us) · [What's New 分类](https://support.ntop.com/hc/en-us/categories/360005712353-What-s-New) · [nTop 5.45](https://support.ntop.com/hc/en-us/articles/50924590694163-nTop-5-45-What-s-New) · [nTop 5.44](https://support.ntop.com/hc/en-us/articles/50584612932755-nTop-5-44-What-s-New) · [nTop 5.43](https://support.ntop.com/hc/en-us/articles/50080923413907-nTop-5-43-What-s-New) · [nTop 5.0 Kernel](https://support.ntop.com/hc/en-us/articles/26062971882131-nTop-5-0-New-Implicit-Modeling-Kernel)

2026-05-05 查询时，Support 首页显示最近版本包含：`nTop 5.46` curve generation blocks、`5.45` Fluids solver improvements、`5.44` physics improvements、`5.43` ONNX / surrogate modeling / Remap Field overload / Track to Block。

## 按方向快速选择

| 方向 | 优先资料 |
| --- | --- |
| 刚入门 | Dashboard examples、nTop Learn、What is implicit modeling |
| 隐式建模理论 | Whitepaper、Implicit modeling for engineering design、B-rep vs implicit |
| Field-driven design | How to use fields、Two-body field、Remap Field block |
| 晶格结构 | Custom lattice unit cell、Structural lattice on CAD face、Randomized lattice thickness |
| 表面纹理 | Voronoi surface texture、Hyper-realistic 3D textures、Procedural textures |
| 拓扑优化 | Intro to Topology Optimization、Topology reconstruction video、Custom Field Optimization Component |
| 自动化 | nTop Automate course、Preparing Notebook for Automate、Python scripts、ModeFrontier DOE |
| 换热器 / 热管理 | End-to-End Heat Exchanger、Thermal management、nTop Fluids |
| 仿真 / 网格 | FE Mesh for complex shell lattice、Robust meshing、Lattice Simulation files |
| 航空参数化 | Parametric Aircraft Design、Accelerated Aircraft Modeling Webinar |
