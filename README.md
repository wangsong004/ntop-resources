# nTop 隐式建模软件资料整理

最后更新：2026-05-26

> 这里的 nTop 指 nTop / nTopology 隐式建模、计算设计、增材制造建模软件，不是 ntop.org 网络流量监控软件。

自动维护目标：每天上午 10:00 新增 2 条 nTop / nTopology 隐式建模资料，优先选择带项目文件、Example File、Download file、`.ntop`、视频教程和高质量文章的资源。

标记说明：![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 表示你已经看过；![标星](https://img.shields.io/badge/%E6%A0%87%E6%98%9F-red) 表示重点收藏；![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) 表示自动任务新添加的资料。你以后告诉我哪些看过或要标星，我会把对应条目移动到前面，并使用红色标记；每天自动新增的条目会保留绿色新增标记和新增日期，方便你回看。

## 已读 / 标星置顶

1. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) ![标星](https://img.shields.io/badge/%E6%A0%87%E6%98%9F-red) **[Introduction to the Remap Field block](https://support.ntop.com/hc/en-us/articles/4408249667731-Introduction-to-the-Remap-Field-block)** · 已读：2026-05-10 · 五星。  
   适合：remap field、mirroring/arraying/orienting、image on body、shape field warping、cylindrical remap。

2. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[Automated topology optimization reconstruction and smoothening](https://www.ntop.com/resources/videos/ntop-live-automated-topology-optimization-reconstruction-smoothening-in-ntopology/)** · 已读：2026-05-06。  
   适合：拓扑优化结果重建、Smoothen Body、面向制造的 topology optimized part 输出。

3. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[How to loft between profiles](https://support.ntop.com/hc/en-us/articles/1500000929422-How-to-loft-between-profiles)** · 已读：2026-05-16；Support，更新 2026-04-02；提供 `.ntop` `Example File`。  
   适合：在多个 2D profiles 间生成平滑过渡体，练习 loft、截面轮廓、implicit body 与参数化截面建模。

4. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[How to create a surface mesh](https://support.ntop.com/hc/en-us/articles/360038828913-How-to-create-a-surface-mesh)** · 已读：2026-05-16；Support，更新 2026-04-02；提供 `Example File`。  
   适合：把 implicit body / CAD body 转成高质量 surface mesh，练习网格尺寸、tolerance、feature preservation 与制造/仿真前处理。

5. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[How to generate random patterns on the surface of a part](https://support.ntop.com/hc/en-us/articles/1500003975321-How-to-generate-random-patterns-on-the-surface-of-a-part)** · 已读：2026-05-23；SEED 2026-05-11；`.ntop` notebook：[Random Pattern on Part Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Random%20Pattern%20on%20Part%20Example.ntop)。  
   适合：随机表面图案、纹理扰动、field-driven 外观变化和工艺品表面装饰。

6. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[How to create perforations on any part](https://support.ntop.com/hc/en-us/articles/1500012943262-How-to-create-perforations-on-any-part)** · 已读：2026-05-23；SEED 2026-05-11；`.ntop` notebook：[Perforated Part Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Implicit%20Modeling/Perforated%20Part%20Example.ntop)。  
   适合：可变孔洞、穿孔外壳、轻量化表皮和由 field 控制的孔径变化。

7. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[How to generate randomized lattice thickness](https://support.ntop.com/hc/en-us/articles/360041726534-How-to-generate-randomized-lattice-thickness)** · 已读：2026-05-23；SEED 2026-05-11；`.ntop` notebook：[Variable_Voronoi_Lattice_Thicken_Simplex_Noise.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Variable_Voronoi_Lattice_Thicken_Simplex_Noise.ntop)。  
   适合：随机晶格厚度、Simplex Noise、Voronoi lattice 和 stochastic foam 质感。

8. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[How to create a Voronoi surface texture](https://support.ntop.com/hc/en-us/articles/360042365673-How-to-create-a-Voronoi-surface-texture)** · 已读：2026-05-23；SEED 2026-05-11；`.ntop` notebook：[Voronoi Surface Texture Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Voronoi%20Surface%20Texture%20Example.ntop)。  
   适合：Voronoi 表面纹理、浮雕凹纹、仿生孔洞和装饰性表面结构。

9. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[How to build a structural lattice on a CAD face](https://support.ntop.com/hc/en-us/articles/360042295414-How-to-build-a-structural-lattice-on-a-CAD-face)** · 已读：2026-05-23；SEED 2026-05-11；`.ntop` notebook：[Structural Ribbing.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Structural%20Ribbing.ntop)。  
   适合：CAD face 上的 structural ribbing、conformal lattice、表面补强和轻量化筋结构。

10. ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[How to build a custom lattice unit cell](https://support.ntop.com/hc/en-us/articles/360055403953-How-to-build-a-custom-lattice-unit-cell)** · 已读：2026-05-23；SEED 2026-05-11；`.ntop` notebook：[CustomUnitCellExamples.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/CustomUnitCellExamples.ntop)。  
   适合：自定义晶格单元、graph unit cell、unit cell domain 和混合 face-beam lattice 练习。

## 每日新增记录

> 自动任务会从这里继续追加每天新增的 2 条资料；每条都会带绿色 ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) 标记和新增日期；已有链接不会重复添加。

## 工艺品 / 外观灵感

> 这组偏向工艺品、消费品外观、鞋类、纹理、浮雕和可 3D 打印的视觉结构。优先保留有图片、视频、项目文件或 Example File 的资源。

1. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[nTop training: Shoe design](https://www.ntop.com/resources/videos/ntop-training-shoe-design-thursday-september-9-2021/)** · 新增：2026-05-14 · 视频 + Download file。  
   适合：鞋底、泡沫结构、渐变晶格、表面纹理。这个是偏“跟做训练”的资源，适合把鞋类和工艺品外观流程拆开学习。

2. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Midsoles with periodic TPMS structures for high-performance sport shoes](https://www.ntop.com/resources/videos/ntop-live-tpms-structures-for-custom-design/)** · 新增：2026-05-14 · 视频 + Download file。  
   适合：TPMS 鞋底、周期极小曲面、运动鞋中底、好看的参数化曲面结构。

3. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Designing a 3D printed shoe using nTop](https://www.ntop.com/resources/blog/designing-a-3d-printed-shoe-using-ntop-platform/)** · 新增：2026-05-14 · 图片/动画 + 文章。  
   适合：一体打印鞋、鞋面 Voronoi、鞋底纹理、工业设计探索。图片很多，灵感价值高。

4. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Parametric modeling of hyper-realistic 3D textures for industrial design](https://www.ntop.com/resources/videos/ntop-live-parametric-modeling-of-hyper-realistic-3d-textures-for-industrial-design/)** · 新增：2026-05-14 · 视频 + Download file。  
   适合：皮革、木纹、大理石、手柄、鞋底、汽车内饰件和装饰外壳表面。

5. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Generating surface textures with procedural modeling](https://support.ntop.com/hc/en-us/articles/360060809134-Generating-surface-textures-with-procedural-modeling)** · 新增：2026-05-14 · 文章 + 图片 + 多个 `.ntop` 示例文件。  
   适合：roughness、leather、wood、marble 等程序纹理，是做工艺品外壳、摆件、握把和产品表面的高价值教程。

6. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) **[How to create a Voronoi surface texture](https://support.ntop.com/hc/en-us/articles/360042365673-How-to-create-a-Voronoi-surface-texture)** · 新增：2026-05-14 · 已读：2026-05-23 · 文章 + 图片 + Example File：[Voronoi Surface Texture Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Voronoi%20Surface%20Texture%20Example.ntop)。  
   适合：Voronoi 表面纹理、花瓶、外壳、浮雕表面、仿生孔洞装饰。

7. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to map a bitmap onto a curved surface](https://support.ntop.com/hc/en-us/articles/5384098529555-How-to-map-a-bitmap-onto-a-curved-surface)** · 新增：2026-05-14 · 文章 + 图片 + Example file + Custom Block。  
   适合：把图案、Logo 或灰度图压到曲面、球面、吊坠、奖章、摆件表面。

8. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to deboss an image](https://support.ntop.com/hc/en-us/articles/4403963185683-How-to-deboss-an-image)** · 新增：2026-05-14 · 文章 + 图片 + Example file。  
   适合：凹雕/浮雕 Logo、铭牌、徽章、包装件和产品外壳装饰。

9. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to create a knurled texture](https://support.ntop.com/hc/en-us/articles/360041727774-How-to-create-a-knurled-texture)** · 新增：2026-05-14 · 文章 + 图片 + Example File。  
   适合：旋钮、笔杆、手柄、工具握把、防滑纹理和小型功能工艺件。

10. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[We gave nTop to students: Here’s what they designed](https://www.ntop.com/resources/blog/we-gave-ntop-to-students-heres-what-they-designed/)** · 新增：2026-05-14 · 图片 + 案例文章。  
    适合：学生项目灵感合集，包含柔性护具、晶格鞋垫、轻量结构等，适合找“别人用 nTop 做了什么有意思的东西”。

## Custom Blocks / 有趣形状

> 这组专门收集可复用 custom blocks、能拆开学习的参数化 notebook，以及社区里特别有形状启发的 nTop / nTopology 作品。优先保留带 `.ntop`、Example File、Downloadable Files、模型文件或视频演示的资源。

1. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Commonly Used Custom Blocks](https://learn.ntop.com/courses/230-intro-to-automation/lessons/commonly-used-custom-blocks/)** · 新增：2026-05-24 · nTop Learn；多个 `.ntop` custom block。  
   文件：[`CB - Mesh Export.ntop`](https://files.learn.ntop.com/Courses/230%20Intro%20to%20Automation/nTop%20Files/230_7_1%20CB%20-%20Mesh%20Export.ntop)、[`CB - Move Object.ntop`](https://files.learn.ntop.com/Courses/230%20Intro%20to%20Automation/nTop%20Files/230_7_2%20CB%20-%20Move%20Object.ntop)、[`CB - Point from Bounding Box.ntop`](https://files.learn.ntop.com/Courses/230%20Intro%20to%20Automation/nTop%20Files/230_7_3%20CB%20-%20Point%20from%20Bounding%20Box.ntop)、[`CB - One Sided Offset.ntop`](https://files.learn.ntop.com/Courses/230%20Intro%20to%20Automation/nTop%20Files/230_7_4%20CB%20-%20One Sided Offset.ntop)。  
   适合：建立个人 My Blocks Folder，把常用导出、移动、包围盒取点、单侧偏移等操作做成工具箱。

2. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[CB Stochastic Lattice](https://learn.ntop.com/courses/230-intro-to-automation/lessons/download-cb-stochastic-lattice/)** · 新增：2026-05-24 · nTop Learn；`.ntop` custom block + 使用示例。  
   文件：[`CB - Stochastic Lattice.ntop`](https://files.learn.ntop.com/Courses/230%20Intro%20to%20Automation/nTop%20Files/230_9_1%20CB%20-%20Stochastic%20Lattice.ntop)、[`Using a Custom Block.ntop`](https://files.learn.ntop.com/Courses/230%20Intro%20to%20Automation/nTop%20Files/230_9_2%20Using%20a%20Custom%20Block.ntop)、[`Completed Stochastic Lattice Workflow.ntop`](https://files.learn.ntop.com/Courses/230%20Intro%20to%20Automation/nTop%20Files/230_3_1%20%26%208_1%20Completed%20--%20Stochastic%20Lattice%20Workflow.ntop)。  
   适合：把 Voronoi / stochastic lattice workflow 封装成可复用模块，用在支架、鞋底、泡沫结构和轻量化内芯。

3. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Guide to Conformal Latticing](https://support.ntop.com/hc/en-us/articles/29651196870035-Guide-to-Conformal-Latticing)** · 新增：2026-05-24 · Support，更新 2026-05-18；Custom Block + Example File。  
   文件：[`CB - Conformal Lattice Skin.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/CB%20-%20Conformal%20Lattice%20Skin.ntop)、[`Conformal Lattice Skin Example File.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Conformal%20Lattice%20Skin%20Example%20File.ntop)。  
   适合：conformal lattice、表面晶格皮肤、曲面贴合 lattice、Delaunay / Voronoi / quad mesh 晶格方案对比。

4. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to measure surface roughness](https://support.ntop.com/hc/en-us/articles/7257188263699-How-to-measure-surface-roughness)** · 新增：2026-05-24 · Support，更新 2026-05-18；`Surface Analysis V1` custom block。  
   文件：[`Surface Analysis V1 - CB`](https://ntopology.box.com/s/2i62s4yz2ngixyrrh3omp50ch3hxhvf3)。  
   适合：把程序纹理从“看起来不错”推进到可量化，测 Ra、Rq、skewness、kurtosis 等表面粗糙度指标。

5. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to create equidistant planes on a curve](https://support.ntop.com/hc/en-us/articles/25440621211027-How-to-create-equidistant-planes-on-a-curve)** · 新增：2026-05-24 · Support，更新 2026-05-18；两个 custom block + Example File。  
   文件：[`Spiral Curve`](https://ntop.box.com/s/dzn1o2agomz8n2ehzexmsh471vzhq4bg)、[`Planes Following a Curve`](https://ntop.box.com/s/9rtjl54bb802kqgx55u2wu4hxwh76elp)、[`Equidistant Planes on Curve Example.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Equidistant%20Planes%20on%20Curve%20Example.ntop)。  
   适合：沿曲线阵列、螺旋纹理、knurl / perforation 的路径控制，以及需要稳定方向帧的装饰结构。

6. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to slice by tiers](https://support.ntop.com/hc/en-us/articles/4408945215251-How-to-slice-by-tiers)** · 新增：2026-05-24 · Support，更新 2026-05-18；Custom Block + Example File。  
   文件：[`CLI Slice Body by Tiers.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Additive%20Manufacturing%20Preparation/CLI%20Slice%20Body%20by%20Tiers.ntop)、[`Slice By Tiers Example.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Additive%20Manufacturing%20Preparation/Slice%20By%20Tiers%20Example.ntop)。  
   适合：大模型切片、CLI 输出、复杂模型分层导出和避免 Slice Body 一次性计算崩溃。

7. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to use Run Command block](https://support.ntop.com/hc/en-us/articles/23766024928787-How-to-use-Run-Command-block)** · 新增：2026-05-24 · Support，更新 2026-05-18；多个 `.ntop` / zip 示例。  
   文件：[`Files in Directory.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/User%20Interface/Run%20Command%201-%20Files%20in%20directory.ntop)、[`Run Command 1 Example.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/User%20Interface/Run%20Command%201-%20Example.ntop)、[`2D Plot.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/User%20Interface/Run%20Command%202-%202D%20Plot.ntop)、[`Plot.zip`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/User%20Interface/Run%20Command%202-%20Plot.zip)、[`fluent_example.zip`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/User%20Interface/Run%20Command%203-%20fluent_example.zip)。  
   适合：把 nTop workflow 接到 PowerShell、Python、Fluent、外部仿真/制造流程，做真正的自动化工具链。

8. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Parametric Aircraft Design](https://learn.ntop.com/courses/parametric-aircraft-modeling/)** · 新增：2026-05-24 · nTop Learn；课程 + 多个 downloadable `.ntop` custom blocks。  
   适合：把 wing、fuselage、ducting、empennage 拆成可复用 aircraft component blocks，学习大型参数化系统如何组织。

9. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Creating a Parametric Jet Model with nTop Blocks](https://www.ntop.com/resources/videos/creating-a-parametric-jet-model-with-ntop-blocks/)** · 新增：2026-05-24 · 视频，2025-04-04；自定义可复用 blocks 演示。  
   适合：看完整飞机如何由 fuselage、wings、ducts、tails 等 modular user-defined blocks 拼起来，是“建一个自己的 block system”的好参照。

10. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Topology Tiles - Hex](https://thangs.com/designer/DaveMakesStuff/3d-model/Topology%20Tiles%20%E2%80%93%20Hex-955066)** / **[Square](https://thangs.com/models/955067)** · 新增：2026-05-24 · 社区 3D model；TPMS / minimal surface 风格装饰砖。  
    适合：数学艺术、TPMS pattern、声学扩散板、墙面装饰、可打印模块化纹理；源码不一定公开，但形状灵感很强。

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

7. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Guide to Rib Design](https://support.ntop.com/hc/en-us/articles/35117560848275-Guide-to-Rib-Design)** · 新增：2026-05-26 · Support，更新 2026-05-25；2 个 `Example File`。  
   文件：[`mapping_examples.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Advanced%20Modeling/mapping_examples.ntop)、[`rib_design_examples.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Advanced%20Modeling/rib_design_examples.ntop)。  
   适合：rib network、curve/body/surface mapping、结构补强与参数化筋位布局，适合把加强筋做成可调规则而不是手工拉几何。

8. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Users' Guide to Topology Optimization](https://support.ntop.com/hc/en-us/articles/360060355953-Users-Guide-to-Topology-Optimization)** · 新增：2026-05-26 · Support，更新 2026-05-18；`Example File` + `zip`。  
   文件：[`Topology Optimization Examples.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Topology%20Optimization/Topology%20Optimization%20Examples.ntop)、[`Topology Optimization Examples.zip`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Topology%20Optimization/Topology%20Optimization%20Examples.zip)。  
   适合：从约束、载荷、制造区到结果解释的完整拓扑优化流程，适合系统复盘 nTop 里的 optimization setup。

9. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to use Remap Field to scale or translate an object](https://support.ntop.com/hc/en-us/articles/4407263917331-How-to-use-Remap-Field-to-scale-or-translate-an-object)** · 新增：2026-05-24 · Support，更新 2026-04-06；`Example file`：[Remap Field to Scale or Translate Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Fields/Remap%20Field%20to%20Scale%20or%20Translate%20Example.ntop)。  
   适合：把缩放和位移做成 field-driven 变化，练习 Remap Field、渐变变形、阵列过渡和更灵活的隐式建模调参。

10. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to add fillets to lattices](https://support.ntop.com/hc/en-us/articles/360053643474-How-to-add-fillets-to-lattices)** · 新增：2026-05-24 · Support，更新 2026-04-02；3 个 `Example file`。  
   文件：[`fillet_ribs.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/fillet_ribs.ntop)、[`custom_unit_cell_fillet.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/custom_unit_cell_fillet.ntop)、[`fillet_spheres.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/fillet_spheres.ntop)。  
   适合：晶格圆角、rib/joint 过渡、custom unit cell 细节修饰，以及提升 lattice 可制造性和外观完成度。

11. **[Introduction to the Remap Field block](https://support.ntop.com/hc/en-us/articles/4408249667731-Introduction-to-the-Remap-Field-block)** · Support，更新 2026-04-06；40:17 视频 + `Example File`。  
   > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) ![标星](https://img.shields.io/badge/%E6%A0%87%E6%98%9F-red) 已读：2026-05-10 · 五星  
   适合：remap field、mirroring/arraying/orienting、image on body、shape field warping、cylindrical remap。

12. **[How to generate random patterns on the surface of a part](https://support.ntop.com/hc/en-us/articles/1500003975321-How-to-generate-random-patterns-on-the-surface-of-a-part)** · Support；提供 `.ntop` notebook：[Random Pattern on Part Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Random Pattern on Part Example.ntop)。  
   > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
   适合：随机表面图案、纹理扰动、field-driven 外观变化和工艺品表面装饰。

13. **[How to create perforations on any part](https://support.ntop.com/hc/en-us/articles/1500012943262-How-to-create-perforations-on-any-part)** · Support；提供 `.ntop` notebook：[Perforated Part Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Implicit%20Modeling/Perforated%20Part%20Example.ntop)。  
   > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
   适合：可变孔洞、穿孔外壳、轻量化表皮和由 field 控制的孔径变化。

14. **[How to generate randomized lattice thickness](https://support.ntop.com/hc/en-us/articles/360041726534-How-to-generate-randomized-lattice-thickness)** · Support，2026-04-02；提供 `.ntop` notebook：[Variable_Voronoi_Lattice_Thicken_Simplex_Noise.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Variable_Voronoi_Lattice_Thicken_Simplex_Noise.ntop)。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
    适合：Simplex Noise、Ramp 控制 beam thickness、Voronoi Volume Lattice、随机泡沫结构。

15. **[How to create a Voronoi surface texture](https://support.ntop.com/hc/en-us/articles/360042365673-How-to-create-a-Voronoi-surface-texture)** · Support，2026-03-02；提供 `.ntop` notebook：[Voronoi Surface Texture Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Voronoi%20Surface%20Texture%20Example.ntop)。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
    适合：Random Points on Mesh、Voronoi Surface Lattice、Boolean Subtract、仿皮革/浮雕/凹纹。

16. **[How to build a structural lattice on a CAD face](https://support.ntop.com/hc/en-us/articles/360042295414-How-to-build-a-structural-lattice-on-a-CAD-face)** · Support，2026-04-02；提供 `.ntop` notebook：[Structural Ribbing.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Structural%20Ribbing.ntop)。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
    适合：CAD face 上生成 honeycomb / conformal lattice，学习 `Cell Map from CAD Face`。

17. **[How to build a custom lattice unit cell](https://support.ntop.com/hc/en-us/articles/360055403953-How-to-build-a-custom-lattice-unit-cell)** · Support，2026-04-02；提供 `.ntop` notebook：[CustomUnitCellExamples.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/CustomUnitCellExamples.ntop)。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
    适合：custom unit cell、implicit/graph overload、unit cell domain、face-based / CAD sketch / hybrid face-beam lattice。

18. **[How to warp a lattice with sine wave spacing](https://support.ntop.com/hc/en-us/articles/1500002409602-How-to-warp-a-lattice-with-sine-wave-spacing)** · Support，2025-12-19；提供 `Example file` + `Normalize Field` custom block。  
    适合：sine wave field、Remap Field、Normalize Field、空间周期结构变形。

19. **[How to create an FE Mesh for a complex shell lattice](https://support.ntop.com/hc/en-us/articles/360058488094-How-to-create-an-FE-Mesh-for-a-complex-shell-lattice)** · Support，2026-01-13；提供 `Example file`。  
    适合：trimmed shell lattice、faces as mesh、FE Surface Mesh、复杂晶格仿真前处理。

20. **[How to warp the cell size of a Cell Map](https://support.ntop.com/hc/en-us/articles/360060023794-How-to-warp-the-cell-size-of-a-Cell-Map)** · Support，2026-04-02；提供 `Example File`。  
    适合：Warp Cell Map、U/V/W scale fields、linear/radial warp、graded lattice。

21. **[Generating surface textures with procedural modeling](https://support.ntop.com/hc/en-us/articles/360060809134-Generating-surface-textures-with-procedural-modeling)** · Support，2026-03-02；多个 `.ntop` 示例 + 附件。  
    适合：Roughness / Leather / Wood / Marble，噪声场 + Offset + Ramp / Remap Field 做程序纹理。

22. **[Download: Completed Box and Lattice nTop Automate Files](https://learn.ntop.com/courses/330-ntop-automate/lessons/download-completed-box-and-lattice-ntop-automate-files/)** · nTop Learn，Published: 2.1 years ago；提供 `BoxExample.zip`、`LatticeExample.zip`。  
    适合：Intro to nTop Automate 完成版文件、JSON I/O、批处理变体、脚本化调用 nTopCL。

23. **[Download: Completed Lattice Simulation nTop Files](https://learn.ntop.com/lessons/download-completed-lattice-simulation-ntop-files-2/)** · nTop Learn，Published: 2.1 years ago；3 个 `.ntop`，last updated in `nTop 5.14.2`。  
    适合：solid elements / beam elements / homogenization 三种 lattice FEA 方法对比。

24. **[Download: Completed Field Driven Bracket](https://learn.ntop.com/courses/220-intro-to-field-driven-design/lessons/download-completed-field-driven-bracket/)** · nTop Learn；提供 `Completed — Field Driven Bracket.ntop`，last updated in `nTop 5.15.2`。  
    适合：Intro to Field-Driven Design 完整小项目，用 distance / ramp / remap 驱动几何。

25. **[How to use nTop Automate in ModeFrontier DOE workflows](https://support.ntop.com/hc/en-us/articles/360052078394-How-to-use-nTop-Automate-in-ModeFrontier-DOE-workflows)** · Support，2026-03-16；视频 + `Mode Frontier Example.zip`。  
    适合：ModeFrontier DOE/MDO，JSON 输入输出，nTop Automate 接外部设计探索平台。

26. **[nTop Learn 课程总览：nTop Automate（Course 330）](https://learn.ntop.com/courses/330-ntop-automate/)** · nTop Learn 课程页，含多个 follow-along / completed files。  
    适合：系统学习 CLI、`ntopcl`、批处理、参数探索；再按章节下载对应 `.ntop` / zip。

27. **[nTop Learn 课程总览：Intro to Field-Driven Design（Course 220）](https://learn.ntop.com/courses/220-intro-to-field-driven-design/)** · nTop Learn 课程页，含多个 follow-along / completed files。  
    适合：field 概念、常用 block、组合套路和完整 bracket 小项目复盘。

28. **[How to loft between profiles](https://support.ntop.com/hc/en-us/articles/1500000929422-How-to-loft-between-profiles)** · Support，更新 2026-04-02；提供 `.ntop` `Example File`（`loft_profiles.ntop`）。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-16  
    适合：在多个 2D profiles 间生成平滑过渡体，练习 loft、截面轮廓、implicit body 与参数化截面建模。

29. **[How to create a surface mesh](https://support.ntop.com/hc/en-us/articles/360038828913-How-to-create-a-surface-mesh)** · Support，更新 2026-04-02；提供 `Example File`。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-16  
    适合：把 implicit body / CAD body 转成高质量 surface mesh，练习网格尺寸、tolerance、feature preservation 与制造/仿真前处理。

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
| 刚入门 | Dashboard examples、nTop Learn、Loft between profiles、What is implicit modeling |
| 工艺品 / 外观灵感 | Shoe design、TPMS midsole、3D printed shoe、random pattern、procedural textures、bitmap/deboss/knurl |
| 隐式建模理论 | Whitepaper、Implicit modeling for engineering design、B-rep vs implicit |
| Field-driven design | How to use fields、Two-body field、Remap Field block、Remap Field scale/translate |
| Custom Blocks / 有趣形状 | Commonly Used Custom Blocks、CB Stochastic Lattice、Conformal Lattice Skin、Parametric Aircraft / Jet Blocks、Topology Tiles |
| 晶格结构 | Custom lattice unit cell、Structural lattice on CAD face、Randomized lattice thickness、Fillets to lattices |
| 表面纹理 | Random pattern、Voronoi surface texture、Perforations、Hyper-realistic 3D textures、Procedural textures |
| 拓扑优化 | Intro to Topology Optimization、Users' Guide to Topology Optimization、Topology reconstruction video、Custom Field Optimization Component |
| 自动化 | nTop Automate course、Preparing Notebook for Automate、Python scripts、ModeFrontier DOE |
| 换热器 / 热管理 | End-to-End Heat Exchanger、Thermal management、nTop Fluids |
| 仿真 / 网格 | Surface mesh、FE Mesh for complex shell lattice、Robust meshing、Lattice Simulation files |
| 航空参数化 | Parametric Aircraft Design、Accelerated Aircraft Modeling Webinar |
