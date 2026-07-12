# nTop 隐式建模软件资料整理

最后更新：2026-07-12

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

11. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to generate surface roughness with varying amplitude or frequency](https://support.ntop.com/hc/en-us/articles/1500002498241-How-to-generate-surface-roughness-with-varying-amplitude-or-frequency)** · 新增：2026-06-07 · Support，更新 2026-05-18；`Example File` + custom block。  
    文件：[`Roughness Example with Varying Frequency or Amplitude.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Roughness%20Example%20with%20Varying%20Frequency%20or%20Amplitude.ntop)、[`Scale Roughness Field Example.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Scale%20Roughness%20Field%20Example.ntop)、[`Scale Roughness Field Example.zip`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Scale%20Roughness%20Field%20Example.zip)。  
    适合：想把 roughness 做成可控渐变的人，适合练习频率/振幅场驱动纹理、表面细节层级和更有制造感的外观处理。

12. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Adding an Image](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/follow-along-adding-an-image/)** · 新增：2026-06-08 · nTop Learn；`.ntop` starter file + custom blocks + PNG + follow-along PDF，课程页标注 last updated in `nTop 5.13.2`。  
    文件：[`311_22_Starter -- Adding an Image.ntop`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_22_Starter%20--%20Adding%20an%20Image.ntop)、[`311_22_CB Implicit Body from Logo.ntop`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_22_CB%20Implicit%20Body%20from%20Logo.ntop)、[`311_22_pattern.png`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/Images/311_22_pattern.png)、[`311_22_Follow Along - Adding an Image.pdf`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/PDFs/311_22_Follow%20Along%20-%20Adding%20an%20Image.pdf)。  
    适合：想把位图、Logo 或灰度图真正做成可打印表面纹理的人，顺手练习 image field、trim box、logo 转 implicit body 和消费品外观表达。

13. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Adding Roughness](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/follow-along-adding-roughness/)** · 新增：2026-06-16 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + 讲义 PDF，课程页标注 last updated in `nTop 5.13.2`。  
    文件：[`311_8_Starter -- Adding Roughness.ntop`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_8_Starter%20--%20Adding%20Roughness.ntop)、[`311_8_Follow Along - Adding Roughness.pdf`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/PDFs/311_8_Follow%20Along%20-%20Adding%20Roughness.pdf)。  
    适合：想把表面粗糙度做成可控视觉语言的人，适合练习 noise field、roughness 幅值控制和偏工艺品外观的细节塑形。

14. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Periodic Fields](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/periodic-fields/)** · 新增：2026-07-05 · nTop Learn；课程 lesson，位于 `Field Based Texturing` 章节，聚焦周期场如何驱动重复纹理与节奏变化。  
    适合：想把 ribs、roughness 或程序纹理做出更强重复节奏和参数控制的人，适合先补 periodic field 概念，再回头看 procedural texturing、surface pattern 和外观语言搭建。

15. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Procedural Texturing](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/download-procedural-texturing/)** · 新增：2026-06-16 · nTop Learn；下载课件，提供 `.ntop` 完整文件，课程页标注 last updated in `nTop 5.13.2`。  
    文件：[`311_12_Complete -- Procedural Texturing.ntop`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_12_Complete%20--%20Procedural%20Texturing.ntop)。  
    适合：想直接拆完整程序纹理工程的人，适合对照学习噪声场、纹理映射和消费品表面纹理的完整搭建方式。

16. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Creating Ribs](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/follow-along-creating-ribs/)** · 新增：2026-06-16 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + 讲义 PDF，课程页标注 last updated in `nTop 5.13.2`。  
    文件：[`311_3_Starter -- Creating Ribs.ntop`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_3_Starter%20--%20Creating%20Ribs.ntop)、[`311_3_Follow Along - Creating Ribs.pdf`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/PDFs/311_3_Follow%20Along%20-%20Creating%20Ribs.pdf)。  
    适合：想把加强筋做成贴合曲面的结构语言的人，适合练习 periodic lattice、cell map from CAD face / quad mesh，以及兼顾功能与外观的 conformal ribbing。

16. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Creating Ribs](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/download-creating-ribs/)** · 新增：2026-06-28 · nTop Learn；下载课件，提供 `.ntop` 完整文件，课程页标注 last updated in `nTop 5.13.2`。  
    文件：[`311_4_Complete -- Creating Ribs.ntop`](https://storage.googleapis.com/files-learn/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_4_Complete%20--%20Creating%20Ribs.ntop)。  
    适合：想直接拆完整 conformal ribbing 成品工程的人，适合对照学习加强筋在曲面上的铺设、参数组织，以及兼顾结构补强与外观语言的 notebook 搭建方式。

17. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Procedural Texturing](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/follow-along-procedural-texturing/)** · 新增：2026-06-17 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + 讲义 PDF，课程页标注 last updated in `nTop 5.13.2`。
    文件：[`311_11_Starter -- Procedural Texturing.ntop`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_11_Starter%20--%20Procedural%20Texturing.ntop)、[`311_11_Follow Along - Procedural Texturing.pdf`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/PDFs/311_11_Follow%20Along%20-%20Procedural%20Texturing.pdf)。
    适合：想从 starter file 一步步搭出程序纹理的人，适合练习 noise field、surface wrap、纹理层级控制和消费品外观细化。

18. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Orienting Bodies on a Surface](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/follow-along-orienting-bodies-on-a-surface/)** · 新增：2026-06-17 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + 讲义 PDF，课程页标注 last updated in `nTop 5.13.2`。
    文件：[`311_17_Starter -- Orienting Bodies onto a Surface.ntop`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_17_Starter%20--%20Orienting%20Bodies%20onto%20a%20Surface.ntop)、[`311_17_Follow Along - Orienting Bodies on a Surface.pdf`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/PDFs/311_17_Follow%20Along%20-%20Orienting%20Bodies%20on%20a%20Surface.pdf)。
    适合：想把小体素、纹样或装饰单元稳定铺到复杂曲面上的人，适合练习 `Orient Object`、曲面法向控制和表面贴附外观表达。

19. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Adding Roughness](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/download-adding-roughness/)** · 新增：2026-06-18 · nTop Learn；下载课件，提供 `.ntop` 完整文件，课程页标注 last updated in `nTop 5.13.2`。
    文件：[`311_9_Complete -- Adding Roughness.ntop`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_9_Complete%20--%20Adding%20Roughness.ntop)。
    适合：想直接拆完整粗糙度纹理工程的人，适合对照学习 noise field、roughness 幅值控制和消费品外观细节塑形的完整搭建方式。

20. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Adding an Image](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/download-adding-an-image/)** · 新增：2026-06-18 · nTop Learn；下载课件，提供 `.ntop` 完整文件，课程页标注 last updated in `nTop 4.14.2`。
    文件：[`311_23_Complete -- Adding an Image.ntop`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_23_Complete%20--%20Adding%20an%20Image.ntop)。
    适合：想直接复盘 bitmap/logo 转可打印表面纹理完整工程的人，适合对照学习 image field、implicit body 转换和装饰性外观表达。

21. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Orienting Bodies on a Surface](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/download-orienting-bodies-on-a-surface/)** · 新增：2026-06-16 · nTop Learn；下载课件，提供 `.ntop` 完整文件，课程页标注 last updated in `nTop 5.13.2`。
    文件：[`311_18_Complete -- Orienting Bodies onto a Surface.ntop`](https://files.learn.ntop.com/Courses/311%20Ribbing%20and%20Texturing/nTop%20Files/311_18_Complete%20--%20Orienting%20Bodies%20onto%20a%20Surface.ntop)。
    适合：想把小体素/纹样稳定铺到复杂曲面上的人，适合直接拆完整 notebook 学习 `Orient Object`、表面贴附纹理和消费品外壳细节表达。

22. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Noise Fields](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/noise-fields/)** · 新增：2026-07-07 · nTop Learn；课程 lesson，位于 `Field Based Texturing` 章节，讲解用 noise field 驱动粗糙度、程序纹理和表面细节节奏。  
    适合：想先把程序纹理底层逻辑补扎实的人，适合理解 noise field、尺度变化和后续 roughness / procedural texturing 的共用思路。

23. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Working with Bitmaps](https://learn.ntop.com/courses/311-ribbing-and-texturing/lessons/working-with-bitmaps/)** · 新增：2026-07-07 · nTop Learn；课程 lesson，位于 bitmap texturing 章节，是 `Follow Along: Adding an Image` 之前的前置概念课。  
    适合：想把 Logo、灰度图或图案更稳地映射到曲面上的人，适合理清 bitmap 输入、图像驱动纹理和后续 image-based 表面建模流程。

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

9. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Creating a Parametric Jet Model with nTop Blocks](https://www.ntop.com/resources/videos/creating-a-parametric-jet-model-with-ntop-blocks/)** · 新增：2026-05-24 · Webinar；参数化飞机/喷气机建模案例。  
   适合：看大型组件化建模怎么拆 blocks、组织参数和保留设计空间。

10. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Topology Tiles - Hex](https://thangs.com/designer/DaveMakesStuff/3d-model/Topology%20Tiles%20%E2%80%93%20Hex-955066)** / **[Square](https://thangs.com/models/955067)** · 新增：2026-05-24 · 社区 3D model；TPMS / minimal surface 风格装饰砖。  
   适合：数学艺术、TPMS pattern、声学扩散板、墙面装饰、可打印模块化纹理；源码不一定公开，但形状灵感很强。

11. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to label parts](https://support.ntop.com/hc/en-us/articles/18683788336531-How-to-label-parts)** · 新增：2026-06-07 · Support，更新 2026-05-18；`.zip` 示例包。  
    文件：[`Part Labeling.zip`](https://support.ntop.com/hc/en-us/article_attachments/18683852956947)。  
    适合：给零件、格栅或装配件批量做 embossed / debossed 标识，顺手学习文本到几何、路径放置和可复用 labeling block 的组织方式。

## Mix block / Field blending

> 这组把之前丢掉的 Mix / field blending 思路补回来。重点看 nTop 如何用 Mix、Ramp、distance field 和插值公式在两个隐式体、TPMS、profile 或晶格之间做平滑过渡。

1. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Two kinds of field blending](https://support.ntop.com/hc/en-us/articles/25455468121619-Two-kinds-of-field-blending)** · 新增：2026-05-27 · Support，更新 2026-05-18；文章 + 多个 `Example File`。  
   文件：[`Field-Driven Design for Adjusting Wall Thickness Example.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Fields/Field-Driven%20Design%20for%20Adjusting%20Wall%20Thickness%20Example.ntop)、[`Interpolate Between Profiles Example File.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Implicit%20Modeling/Interpolate%20Between%20Profiles%20Example%20File.ntop)、[`Interpolate Between Two Bodies Example File.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Implicit%20Modeling/Interpolate%20Between%20Two%20Bodies%20Example%20File.ntop)。  
   适合：厘清 `field blend` 和 `body blend` 两条路线，顺手拿现成 `.ntop` 拆 profile morphing、wall thickness gradient 和 two-body interpolation。

2. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Methods for blending TPMS and lattices without the mix block](https://support.ntop.com/hc/en-us/articles/4412634253715-Methods-for-blending-TPMS-and-lattices-without-the-mix-block)** · 新增：2026-05-27 · Support，更新 2026-05-18；多个 `.ntop` 示例 + custom block。  
   文件：[`Blend Lattice with Sine.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Blend%20Lattice%20with%20Sine.ntop)、[`Inverse Distance Weighting Example.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Inverse%20Distance%20Weighting%20Example.ntop)、[`Gyroid to Split P.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Gyroid%20to%20Split%20P.ntop)、[`Shepard.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Shepard.ntop)。  
   适合：理解 Mix block 背后的插值思想，学习 sine transition、inverse distance weighting、equation-based TPMS 过渡和自定义权重场。

3. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to loft between profiles](https://support.ntop.com/hc/en-us/articles/1500000929422-How-to-loft-between-profiles)** · 新增：2026-05-27 · Support，更新 2026-05-18；`Example File`：[loft_profiles.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Implicit%20Modeling/loft_profiles.ntop)。  
   适合：Profile 概念、Mix method for lofting profiles、解决 loft 过渡不光顺的问题；这是你之前 README 里“Mix loft 思路”的明确恢复版。

4. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Interpolating with implicit modeling](https://www.ntop.com/blog/interpolating-with-implicit-modeling/)** · 新增：2026-05-27 · Blog，2019-04-12；理论文章。  
   适合：理解 `mix(R, W, t) = (1-t) * R + t * W` 这种隐式场插值本质，覆盖 loft-like blending、morphing、midsurface 和 interference removal。

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

9. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to run a topology optimization](https://support.ntop.com/hc/en-us/articles/360044051214-How-to-run-a-topology-optimization)** · 新增：2026-06-05 · Support；`Example File`：[How_to_run_a_topology_optimization.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Topology%20Optimization/How_to_run_a_topology_optimization.ntop)。  
   适合：第一次完整走通拓扑优化 setup，串起 design space、载荷/约束、目标函数与结果解释，适合拿来直接跟做。

10. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How do I use the Remap Constraint for Topology Optimization?](https://support.ntop.com/hc/en-us/articles/1500005927541-How-do-I-use-the-Remap-Constraint-for-Topology-Optimization)** · 新增：2026-06-05 · Support；`Example File`：[RemapConstraintforTopologyOptimization.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Topology%20Optimization/RemapConstraintforTopologyOptimization.ntop)。  
   适合：想把 field / Remap Constraint 引入拓扑优化的人，尤其适合做局部制造偏好、形态引导和更有“设计味”的 optimization。

11. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Periodic Lattice](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/follow-along-periodic-lattice/)** · 新增：2026-06-28 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + 讲义 PDF，课程页标注 last updated in `nTop 5.4.2`。  
   文件：[`210_9_1 Starter--Periodic Lattice.ntop`](https://files.learn.ntop.com/Courses/210%20Intro%20to%20Lattices/nTop%20Files/210_9_1%20Starter--Periodic%20Lattice.ntop)、[`210_9_1 Follow Along - Periodic Lattices.pdf`](https://files.learn.ntop.com/Courses/210%20Intro%20to%20Lattices/PDFs/210_9_1%20Follow%20Along%20-%20Periodic%20Lattices.pdf)。  
   适合：想从 starter file 跑一遍最基础 periodic lattice 工作流的人，适合练习 graph unit cell、TPMS unit cell、rectangular / cylindrical cell map 和晶格修剪并集的完整入门流程。

12. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Completed Periodic Lattice](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/download-completed-periodic-lattice/)** · 新增：2026-06-28 · nTop Learn；下载课件，提供 `.ntop` 完整文件，课程页标注 last updated in `nTop 4.2.3`。  
   文件：[`210_10_1 Completed--Periodic Lattice.ntop`](https://files.learn.ntop.com/Courses/210%20Intro%20to%20Lattices/nTop%20Files/210_10_1%20Completed--Periodic%20Lattice.ntop)。  
   适合：想直接拆最基础 periodic lattice 成品 notebook 的人，适合对照学习 lattice to body 的完整搭建顺序、单元选择和早期晶格工作流的参数组织方式。

13. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Completed Periodic Lattice on Faces](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/download-completed-periodic-lattice-on-faces/)** · 新增：2026-06-28 · nTop Learn；下载课件，提供 `.ntop` 完整文件，课程页标注 last updated in `5.12.2`。  
   文件：[`210_14_1 Completed--Periodic Lattice on Faces.ntop`](https://files.learn.ntop.com/Courses/210%20Intro%20to%20Lattices/nTop%20Files/210_14_1%20Completed--Periodic%20Lattice%20on%20Faces.ntop)。  
   适合：想直接拆解 face-mapped periodic lattice 成品工程的人，适合对照学习 CAD face / mesh cell map 贴附后的 notebook 组织方式，以及表面晶格轻量化成品该如何收尾。

14. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Non-Periodic Lattices](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/follow-along-non-periodic-lattices/)** · 新增：2026-06-29 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + custom block + 讲义 PDF，课程页标注 last updated in `nTop 3.38.4` / `nTop 5.12.2`。  
   文件：[`210_21_1 Starter--Non-Periodic Lattices.ntop`](https://files.learn.ntop.com/Courses/210%20Intro%20to%20Lattices/nTop%20Files/210_21_1%20Starter--Non-Periodic%20Lattices.ntop)、[`210_21_2 CB Add Noise to Beam Lattice Vertices.ntop`](https://files.learn.ntop.com/Courses/210%20Intro%20to%20Lattices/nTop%20Files/210_21_2%20CB%20Add%20Noise%20to%20Beam%20Lattice%20Vertices.ntop)、[`210_21_1 Follow Along - Non Periodic Lattices.pdf`](https://files.learn.ntop.com/Courses/210%20Intro%20to%20Lattices/PDFs/210_21_1%20Follow%20Along%20-%20Non%20Periodic%20Lattices.pdf)。  
   适合：想从 starter file 跑一遍 Voronoi / Delaunay 非周期晶格工作流的人，适合练习随机点生成、beam lattice 顶点扰动，以及更偏仿生泡沫感的晶格造型。

15. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Completed Non-Periodic Lattices](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/download-completed-non-periodic-lattices/)** · 新增：2026-06-29 · nTop Learn；下载课件，提供 `.ntop` 完整文件，课程页标注 last updated in `nTop 5.12.2`。  
   文件：[`210_22_1 Completed--Non-Periodic Lattices.ntop`](https://files.learn.ntop.com/Courses/210%20Intro%20to%20Lattices/nTop%20Files/210_22_1%20Completed--Non-Periodic%20Lattices.ntop)。  
   适合：想直接拆完整 non-periodic lattice 成品工程的人，适合对照学习 Voronoi / Delaunay 晶格的成品参数组织、后处理收尾和更自由形态的晶格表达。

16. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Periodic Lattice on Faces](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/follow-along-periodic-lattice-on-faces/)** · 新增：2026-07-02 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + follow-along PDF，课程页标注 last updated in `3.37.3`。  
   文件：[`210_13_1 Starter--Periodic Lattice on Faces.ntop`](https://files.learn.ntop.com/Courses/210%20Intro%20to%20Lattices/nTop%20Files/210_13_1%20Starter--Periodic%20Lattice%20on%20Faces.ntop)、[`210_13_1 Follow Along - Periodic Lattice on Faces.pdf`](https://files.learn.ntop.com/Courses/210%20Intro%20to%20Lattices/PDFs/210_13_1%20Follow%20Along%20-%20Periodic%20Lattice%20on%20Faces.pdf)。  
   适合：想从 starter file 练习把周期晶格稳定贴到 CAD face / mesh 表面的人，适合补齐 cell map 贴附、表面纹理化轻量结构和 face-based periodic lattice 的完整跟做流程。

17. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Cell Maps Using CAD Faces](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/cell-maps-using-cad-faces/)** · 新增：2026-07-02 · nTop Learn；课程 lesson，含动态图讲解 `Cell Map From CAD Face` 与 `Cell Map between CAD Faces`。  
   适合：想先把 CAD face 上的 U/V/W 参数化、局部方向和贴附逻辑真正看明白的人，适合给后面的 face texture、surface lattice 和 conformal 晶格建模打基础。

18. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Cell Maps Using Meshes](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/cell-maps-using-meshes/)** · 新增：2026-07-05 · nTop Learn；课程 lesson，聚焦 `Cell Map From Quad Mesh` 与多面连续贴图思路。  
   适合：想把周期晶格或纹理连续铺到多片外表面的人，适合补齐 quad mesh cell map、跨多面统一方向和更复杂外壳贴附晶格的建模思路。

19. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Simple Volume Lattices](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/simple-volume-lattices/)** · 新增：2026-07-04 · nTop Learn；课程 lesson，位于 periodic lattice 与 test problem 之间，当前缓存页未见直接 `.ntop` / 下载链接。  
   适合：想先把体积晶格这种最直接的 lattice 填充思路补齐的人，适合在进入测试题前梳理 volume lattice 的基础表达、与 cell map 晶格的差别，以及“先快速铺满体积再细化策略”的入门判断。

20. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Optional: Periodic Lattice Test Problem](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/optional-periodic-lattice-test-problem/)** · 新增：2026-07-04 · nTop Learn；课程 lesson，位于 `Optional Test Problem` 小节，当前缓存页未见直接 `.ntop` / 下载链接。  
   适合：已经跑完 periodic lattice 基础流程、想用一题小练习检验自己是否真正掌握 unit cell 选择、cell map 设置和 lattice 后处理顺序的人，适合把“跟做”过渡到“自己搭”。

21. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Applying Lattice Utilities](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/applying-lattice-utilities/)** · 新增：2026-07-01 · nTop Learn；课程 lesson，位于 `Intro to Lattices` 的 Modifying Lattices 章节。  
   适合：想把 lattice utilities 真正用到工程里的人，适合系统梳理晶格裁剪、延伸、合并、顶点/梁段处理这类后处理思路，补齐从“会生成晶格”到“会整理晶格”的一段空白。

22. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Filtering Lattice Beams](https://learn.ntop.com/courses/210-intro-to-lattices/lessons/filtering-lattice-beams/)** · 新增：2026-07-01 · nTop Learn；课程 lesson，位于 `Intro to Lattices` 的 Modifying Lattices 章节。  
   适合：想控制 beam 数量、连通性和可制造性的人，适合专门理解 beam filtering、删除细碎梁段和整理复杂晶格网络时的判断逻辑。

22. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Optional Follow Along: FE Model and Boundary Conditions](https://learn.ntop.com/courses/340-topology-optimization/lessons/optional-follow-along-fe-model-and-boundary-conditions/)** · 新增：2026-06-09 · nTop Learn；follow-along lesson，提供 `.ntop` 完整文件 + CAD 几何。  
   文件：[`340_2_Complete — FE Model and Boundary Conditions.ntop`](https://files.learn.ntop.com/Courses/340%20Topology%20Optimization/nTop%20Files/340_2_Complete%20%E2%80%94%20FE%20Model%20and%20Boundary%20Conditions.ntop)、[`340_2_Brake Pedal Geometry.x_t`](https://files.learn.ntop.com/Courses/340%20Topology%20Optimization/CAD%20Files/340_2_Brake%20Pedal%20Geometry.x_t)。  
   适合：想把拓扑优化前处理补扎实的人，适合练习 brake pedal 这类真实零件的 FE 模型准备、边界条件搭建和后续 optimization 输入整理。

23. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Objectives and Constraints](https://learn.ntop.com/courses/340-topology-optimization/lessons/follow-along-objectives-and-constraints/)** · 新增：2026-06-09 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + 讲义 PDF，课程页标注 last updated in `nTop 5.12.2`。  
   文件：[`340_8_1 Starter — Objectives and Constraints.ntop`](https://files.learn.ntop.com/Courses/340%20Topology%20Optimization/nTop%20Files/340_8_1%20Starter%20--%20Objectives%20and%20Constraints.ntop)、[`340_8_1 Follow Along - Objectives and Constraints.pdf`](https://files.learn.ntop.com/Courses/340%20Topology%20Optimization/PDFs/340_8_1%20Follow%20Along%20-%20Objectives%20and%20Constraints.pdf)。  
   适合：想把拓扑优化里的 objective、volume fraction 和 constraint 设置吃透的人，适合边看讲义边跟做参数定义与优化目标拆解。

24. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Before We Begin: Topology Optimization](https://learn.ntop.com/courses/340-topology-optimization/lessons/before-we-begin/)** · 新增：2026-07-12 · nTop Learn；课程主线 lesson，开篇导入视频，解释为什么在 nTop 里做 topopt，以及整门课会覆盖哪些输入、求解与后处理环节。  
   适合：刚准备系统补 topopt 课程的人，适合先建立整条 workflow 地图，再回头学 FE、objective、constraint 和 post-processing 各自扮演什么角色。

25. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Topology Optimization Properties and Terminology](https://learn.ntop.com/courses/340-topology-optimization/lessons/topology-optimization-properties-and-terminology/)** · 新增：2026-07-09 · nTop Learn；课程主线 lesson，位于 course 340 开篇，聚焦拓扑优化常见属性、术语与结果解读前的共同语言。  
   适合：想先把 compliance、volume fraction、保留区、制造约束这些词真正对应到 nTop 语境里的人，适合在跟做前先补齐术语框架，减少“会点按钮但不懂含义”。

26. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Review: FE/Simulation Model and Boundary Conditions](https://learn.ntop.com/courses/340-topology-optimization/lessons/review-fe-simulation-model-and-boundary-conditions/)** · 新增：2026-07-11 · nTop Learn；课程主线 lesson，配合示意图回顾 FE mesh、边界选区与载荷/约束输入如何真正喂给拓扑优化。
   适合：想把 FE model、边界条件和后面 topopt 输入关系彻底串起来的人，适合在继续设 objectives / constraints 前先补齐“仿真前处理为什么这样搭”的上下文。

27. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Design Responses](https://learn.ntop.com/courses/340-topology-optimization/lessons/design-responses/)** · 新增：2026-07-10 · nTop Learn；课程主线 lesson，位于拓扑优化前处理与目标设置之间，聚焦如何把位移、应力等响应量转成后续设计判断依据。
   适合：想把仿真结果和拓扑优化目标真正连起来的人，适合先补齐 response field、结果读数与“拿什么衡量设计好坏”的概念桥梁。

28. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Optimization Objectives](https://learn.ntop.com/courses/340-topology-optimization/lessons/optimization-objectives/)** · 新增：2026-07-08 · nTop Learn；课程主线 lesson，位于 `Topology Optimization` 章节，聚焦拓扑优化目标函数的选择与取舍。
   适合：想先把 compliance、stiffness、质量权衡这些目标逻辑想明白的人，适合在跟做前补齐“为什么这样设目标”的概念框架。

29. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Defining Constraints](https://learn.ntop.com/courses/340-topology-optimization/lessons/defining-constraints/)** · 新增：2026-07-08 · nTop Learn；课程主线 lesson，位于 `Topology Optimization` 章节，聚焦体积分数、保留区和制造限制等约束设计。
   适合：想把保留几何、制造方向与优化边界分清楚的人，适合在跑 topopt 前先理顺约束设置，减少“能跑但不合理”的结果。

30. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Topology Optimization](https://learn.ntop.com/courses/340-topology-optimization/lessons/follow-along-topology-optimization/)** · 新增：2026-06-09 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + 讲义 PDF，课程页标注 last updated in `nTop 5.12.2`。
   文件：[`340_10_1 Starter — Topology Optimization.ntop`](https://files.learn.ntop.com/Courses/340%20Topology%20Optimization/nTop%20Files/340_10_1%20Starter%20--%20Topology%20Optimization.ntop)、[`340_10_1 Follow Along - Topology Optimization.pdf`](https://files.learn.ntop.com/Courses/340%20Topology%20Optimization/PDFs/340_10_1%20Follow%20Along%20-%20Topology%20Optimization.pdf)。  
   适合：已经会建 FE 模型、现在想亲手跑完一次 topopt 求解的人，适合顺着 starter file 补齐求解设置、运行节奏和结果判断。

31. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Running Topology Optimization](https://learn.ntop.com/courses/340-topology-optimization/lessons/running-topology-optimization/)** · 新增：2026-06-14 · nTop Learn；课程主线 lesson。
   适合：已经搭好 FE 模型和约束、想补齐求解阶段判断逻辑的人，适合系统理解拓扑优化运行节奏、迭代观察和结果收敛前后的检查点。

32. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Post Processing](https://learn.ntop.com/courses/340-topology-optimization/lessons/post-processing/)** · 新增：2026-07-12 · nTop Learn；课程主线 lesson，位于求解之后，专门讲 raw topopt 结果如何进入重建、平滑和可制造几何整理阶段。  
   适合：已经跑出优化结果、但还没把它真正变成 CAD/制造几何的人，适合先补清后处理主线，再去跟做 starter file 和 complete file。

33. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Post Processing](https://learn.ntop.com/courses/340-topology-optimization/lessons/follow-along-post-processing/)** · 新增：2026-06-13 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + 讲义 PDF，课程页标注 last updated in `nTop 5.12.2`。
   文件：[`340_13_1 Starter — Post Processing.ntop`](https://files.learn.ntop.com/Courses/340%20Topology%20Optimization/nTop%20Files/340_13_1%20Starter%20--%20Post%20Processing.ntop)、[`340_13_1 Follow Along - Post Processing.pdf`](https://files.learn.ntop.com/Courses/340%20Topology%20Optimization/PDFs/340_13_1%20Follow%20Along%20-%20Post%20Processing.pdf)。  
   适合：想把拓扑优化结果真正收尾成可输出几何的人，适合练习 `Implicit Body from Topology Optimization`、`Smoothen Body`、接口重建和最终裁剪这套后处理链路。

34. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Post Processing](https://learn.ntop.com/courses/340-topology-optimization/lessons/download-post-processing/)** · 新增：2026-06-13 · nTop Learn；下载课件，提供 `.ntop` 完整文件，课程页标注 last updated in `nTop 5.12.2`。
   文件：[`340_14_1 Complete — TopOpt & Post Processing.ntop`](https://files.learn.ntop.com/Courses/340%20Topology%20Optimization/nTop%20Files/340_14_1%20Complete%20--%20TopOpt%20%26%20Post%20Processing.ntop)。  
   适合：想直接对照完整成品复盘拓扑优化后处理 notebook 组织方式的人，尤其适合边看成品边回查平滑、布尔并集和接口恢复步骤。

35. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Optional: TopOpt Problem Statement](https://learn.ntop.com/courses/340-topology-optimization/lessons/optional-topopt-problem-statement/)** · 新增：2026-07-10 · nTop Learn；可选测试题页面，提供 `.ntop` starter file，适合把前面目标、约束与求解流程串成一次独立练习。
   适合：想脱离讲解自己完整跑一遍 topopt 小题的人，适合用 starter file 检查 setup 是否真的内化，而不只是照着 follow-along 点按钮。

36. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Answer to TopOpt Test Problem](https://learn.ntop.com/courses/340-topology-optimization/lessons/answer-to-topopt-test-problem/)** · 新增：2026-06-14 · nTop Learn；课程答案页。
   适合：做完前面 follow-along 后想快速对答案的人，适合校验目标函数理解、结果预期和整套 topopt 教学链路有没有吃透。

37. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Topology Optimization Tips and Best Practices](https://learn.ntop.com/courses/340-topology-optimization/lessons/topology-optimization-tips-and-best-practices/)** · 新增：2026-07-09 · nTop Learn；课程主线 lesson，位于 optional problem 之后，聚焦拓扑优化流程里的常见踩坑、结果检查与建模习惯。
   适合：已经跑过 topopt、想把失败重跑和结果质量判断做得更稳的人，适合集中补齐 setup 取舍、后处理前检查点和更工程化的 best practices。

38. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Advanced Topology Optimization](https://learn.ntop.com/lessons/advanced-topology-optimization/)** · 新增：2026-07-11 · nTop Learn；recorded training，聚焦 multiple load cases + multiple constraints 的“从零搭起”拓扑优化流程，并提供 zip 下载包。
   文件：[`Advanced_Topology_Optimization.zip`](https://files.learn.ntop.com/Courses/Recorded%20Trainings/Advanced%20Topology%20Optimization%20-%20Multiple%20Loads%2C%20Multiple%20Conditions/Advanced_Topology_Optimization.zip)。
   适合：已经跑过单工况 topopt、现在想进到多载荷多约束真实工程设定的人，适合直接拆解进阶 notebook 和训练材料里的 objective / constraint 组合方式。

27. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to use Remap Field to scale or translate an object](https://support.ntop.com/hc/en-us/articles/4407263917331-How-to-use-Remap-Field-to-scale-or-translate-an-object)** · 新增：2026-05-24 · Support，更新 2026-04-06；`Example file`：[Remap Field to Scale or Translate Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Fields/Remap%20Field%20to%20Scale%20or%20Translate%20Example.ntop)。  
   适合：把缩放和位移做成 field-driven 变化，练习 Remap Field、渐变变形、阵列过渡和更灵活的隐式建模调参。  

28. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[How to add fillets to lattices](https://support.ntop.com/hc/en-us/articles/360053643474-How-to-add-fillets-to-lattices)** · 新增：2026-05-24 · Support，更新 2026-04-02；3 个 `Example file`。  
   文件：[`fillet_ribs.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/fillet_ribs.ntop)、[`custom_unit_cell_fillet.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/custom_unit_cell_fillet.ntop)、[`fillet_spheres.ntop`](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/fillet_spheres.ntop)。  
   适合：晶格圆角、rib/joint 过渡、custom unit cell 细节修饰，以及提升 lattice 可制造性和外观完成度。  

18. **[Introduction to the Remap Field block](https://support.ntop.com/hc/en-us/articles/4408249667731-Introduction-to-the-Remap-Field-block)** · Support，更新 2026-04-06；40:17 视频 + `Example File`。  
   > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) ![标星](https://img.shields.io/badge/%E6%A0%87%E6%98%9F-red) 已读：2026-05-10 · 五星  
   适合：remap field、mirroring/arraying/orienting、image on body、shape field warping、cylindrical remap。

17. **[How to generate random patterns on the surface of a part](https://support.ntop.com/hc/en-us/articles/1500003975321-How-to-generate-random-patterns-on-the-surface-of-a-part)** · Support；提供 `.ntop` notebook：[Random Pattern on Part Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Random Pattern on Part Example.ntop)。  
   > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
   适合：随机表面图案、纹理扰动、field-driven 外观变化和工艺品表面装饰。

18. **[How to create perforations on any part](https://support.ntop.com/hc/en-us/articles/1500012943262-How-to-create-perforations-on-any-part)** · Support；提供 `.ntop` notebook：[Perforated Part Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Implicit%20Modeling/Perforated Part Example.ntop)。  
   > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
   适合：可变孔洞、穿孔外壳、轻量化表皮和由 field 控制的孔径变化。

19. **[How to generate randomized lattice thickness](https://support.ntop.com/hc/en-us/articles/360041726534-How-to-generate-randomized-lattice-thickness)** · Support，2026-04-02；提供 `.ntop` notebook：[Variable_Voronoi_Lattice_Thicken_Simplex_Noise.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Variable_Voronoi_Lattice_Thicken_Simplex_Noise.ntop)。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
    适合：Simplex Noise、Ramp 控制 beam thickness、Voronoi Volume Lattice、随机泡沫结构。

20. **[How to create a Voronoi surface texture](https://support.ntop.com/hc/en-us/articles/360042365673-How-to-create-a-Voronoi-surface-texture)** · Support，2026-03-02；提供 `.ntop` notebook：[Voronoi Surface Texture Example.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Textures/Voronoi%20Surface%20Texture%20Example.ntop)。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
    适合：Random Points on Mesh、Voronoi Surface Lattice、Boolean Subtract、仿皮革/浮雕/凹纹。

21. **[How to build a structural lattice on a CAD face](https://support.ntop.com/hc/en-us/articles/360042295414-How-to-build-a-structural-lattice-on-a-CAD-face)** · Support，2026-04-02；提供 `.ntop` notebook：[Structural Ribbing.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/Structural%20Ribbing.ntop)。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
    适合：CAD face 上生成 honeycomb / conformal lattice，学习 `Cell Map from CAD Face`。

22. **[How to build a custom lattice unit cell](https://support.ntop.com/hc/en-us/articles/360055403953-How-to-build-a-custom-lattice-unit-cell)** · Support，2026-04-02；提供 `.ntop` notebook：[CustomUnitCellExamples.ntop](https://files.learn.ntop.com/Support%20Article%20Example%20Files/Knowledge%20Base/Lattices/CustomUnitCellExamples.ntop)。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-23 · SEED 2026-05-11  
    适合：custom unit cell、implicit/graph overload、unit cell domain、face-based / CAD sketch / hybrid face-beam lattice。

23. **[How to warp a lattice with sine wave spacing](https://support.ntop.com/hc/en-us/articles/1500002409602-How-to-warp-a-lattice-with-sine-wave-spacing)** · Support，2025-12-19；提供 `Example file` + `Normalize Field` custom block。  
    适合：sine wave field、Remap Field、Normalize Field、空间周期结构变形。

24. **[How to create an FE Mesh for a complex shell lattice](https://support.ntop.com/hc/en-us/articles/360058488094-How-to-create-an-FE-Mesh-for-a-complex-shell-lattice)** · Support，2026-01-13；提供 `Example file`。  
    适合：trimmed shell lattice、faces as mesh、FE Surface Mesh、复杂晶格仿真前处理。

25. **[How to warp the cell size of a Cell Map](https://support.ntop.com/hc/en-us/articles/360060023794-How-to-warp-the-cell-size-of-a-Cell-Map)** · Support，2026-04-02；提供 `Example File`。  
    适合：Warp Cell Map、U/V/W scale fields、linear/radial warp、graded lattice。

26. **[Generating surface textures with procedural modeling](https://support.ntop.com/hc/en-us/articles/360060809134-Generating-surface-textures-with-procedural-modeling)** · Support，2026-03-02；多个 `.ntop` 示例 + 附件。  
    适合：Roughness / Leather / Wood / Marble，噪声场 + Offset + Ramp / Remap Field 做程序纹理。

27. **[Download: Completed Box and Lattice nTop Automate Files](https://learn.ntop.com/courses/330-ntop-automate/lessons/download-completed-box-and-lattice-ntop-automate-files/)** · nTop Learn，Published: 2.1 years ago；提供 `BoxExample.zip`、`LatticeExample.zip`。  
    适合：Intro to nTop Automate 完成版文件、JSON I/O、批处理变体、脚本化调用 nTopCL。

28. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Homogenized Lattice Simulation](https://learn.ntop.com/courses/342-lattice-fea-part-2/lessons/follow-along-homogenized-lattice-simulation/)** · 新增：2026-06-09 · nTop Learn；follow-along lesson，提供 `.ntop` starter file + 讲义 PDF。  
    文件：[`342_8_Starter — Homogenized Lattice FEA.ntop`](https://files.learn.ntop.com/Courses/342%20Lattice%20FEA%20Part%202/nTop%20Files/342_8_Starter%20%E2%80%94%20Homogenized%20Lattice%20FEA.ntop)、[`342_8_Follow Along — Homogenized Lattice FEA.pdf`](https://files.learn.ntop.com/Courses/342%20Lattice%20FEA%20Part%202/Follow%20Along%20PDFs/342_8_Follow%20Along%20%E2%80%94%20Homogenized%20Lattice%20FEA.pdf)。  
    适合：系统补 lattice homogenization 这条仿真路线，适合拿 starter file 跟着做等效材料建模、FEA 设置和结果回看。

29. **[Download: Completed Lattice Simulation nTop Files](https://learn.ntop.com/lessons/download-completed-lattice-simulation-ntop-files-2/)** · nTop Learn，Published: 2.1 years ago；3 个 `.ntop`，last updated in `nTop 5.14.2`。  
    适合：solid elements / beam elements / homogenization 三种 lattice FEA 方法对比。

30. **[Download: Completed Field Driven Bracket](https://learn.ntop.com/courses/220-intro-to-field-driven-design/lessons/download-completed-field-driven-bracket/)** · nTop Learn；提供 `Completed — Field Driven Bracket.ntop`，last updated in `nTop 5.15.2`。  
    适合：Intro to Field-Driven Design 完整小项目，用 distance / ramp / remap 驱动几何。

31. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Core and Baffles](https://learn.ntop.com/courses/heat-exchanger-flow-distribution-and-control/lessons/download-core-and-baffles/)** · 新增：2026-06-06 · nTop Learn；`.ntop` lesson file，课程页标注 last updated in `nTop 5.18.1`。  
    文件：[`HEX2_6_Baffle Generation.ntop`](https://files.learn.ntop.com/Courses/Intro%20to%20Two-Channel%20Heat%20Exchangers%20in%20nTop/2.%20Heat%20Exchanger%20Flow%20Distribution%20and%20Control/HEX2_6_Baffle%20Generation.ntop)。  
    适合：两通道换热器的 core / baffle 参数化建模，适合直接拆解 flow distribution、导流板布局和热管理几何搭建方法。

32. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Download: Variable Shell Thickness](https://learn.ntop.com/courses/320-data-driven-design/lessons/download-variable-shell-thickness/)** · 新增：2026-06-06 · nTop Learn；`.ntop` lesson file，课程页标注 last updated in `nTop 5.18.1`。  
    文件：[`320_11_1.ntop`](https://nTopology.box.com/s/yq09gr6f0zjgu2k4l454gcu03m1j3tf7)。  
    适合：把仿真或标量场结果映射成壳厚变化，适合练习 variable shell、data-driven reinforcement 和性能驱动外形细化。

33. ![新增](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E-brightgreen) **[Follow Along: Model a Double Pipe HEX](https://learn.ntop.com/courses/intro-to-modeling/lessons/follow-along-model-a-double-pipe-hex/)** · 新增：2026-06-08 · nTop Learn；`.ntop` lesson file，课程页标注 last updated in `nTop 5.23.2`。  
    文件：[`Complete -- Model a Double Pipe HEX.ntop`](https://storage.googleapis.com/files-learn/Courses/Intro%20to%20Modeling/Complete%20--%20Model%20a%20Double%20Pipe%20HEX.ntop)。  
    适合：从中心线、厚化、布尔运算到 flange custom block，完整拆一遍双管换热器建模流程，适合补齐热流道几何搭建基本功。

34. **[How to use nTop Automate in ModeFrontier DOE workflows](https://support.ntop.com/hc/en-us/articles/360052078394-How-to-use-nTop-Automate-in-ModeFrontier-DOE-workflows)** · Support，2026-03-16；视频 + `Mode Frontier Example.zip`。  
    适合：ModeFrontier DOE/MDO，JSON 输入输出，nTop Automate 接外部设计探索平台。

35. **[nTop Learn 课程总览：nTop Automate（Course 330）](https://learn.ntop.com/courses/330-ntop-automate/)** · nTop Learn 课程页，含多个 follow-along / completed files。  
    适合：系统学习 CLI、`ntopcl`、批处理、参数探索；再按章节下载对应 `.ntop` / zip。

36. **[nTop Learn 课程总览：Intro to Field-Driven Design（Course 220）](https://learn.ntop.com/courses/220-intro-to-field-driven-design/)** · nTop Learn 课程页，含多个 follow-along / completed files。  
    适合：field 概念、常用 block、组合套路和完整 bracket 小项目复盘。

37. **[How to loft between profiles](https://support.ntop.com/hc/en-us/articles/1500000929422-How-to-loft-between-profiles)** · Support，更新 2026-04-02；提供 `.ntop` `Example File`（`loft_profiles.ntop`）。  
    > ![已读](https://img.shields.io/badge/%E5%B7%B2%E8%AF%BB-red) 已读：2026-05-16  
    适合：在多个 2D profiles 间生成平滑过渡体，练习 loft、截面轮廓、implicit body 与参数化截面建模。

38. **[How to create a surface mesh](https://support.ntop.com/hc/en-us/articles/360038828913-How-to-create-a-surface-mesh)** · Support，更新 2026-04-02；提供 `Example File`。  
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
| 工艺品 / 外观灵感 | Shoe design、TPMS midsole、3D printed shoe、Creating Ribs complete file、Noise Fields、Working with Bitmaps、random pattern、bitmap image texture、procedural textures、bitmap/deboss/knurl |
| 隐式建模理论 | Whitepaper、Implicit modeling for engineering design、B-rep vs implicit |
| Field-driven design | Mix block / Field blending、How to use fields、Two-body field、Periodic Fields、Remap Field block、Remap Field scale/translate |
| Custom Blocks / 有趣形状 | Commonly Used Custom Blocks、CB Stochastic Lattice、Conformal Lattice Skin、Part labeling、Parametric Aircraft / Jet Blocks、Topology Tiles |
| 晶格结构 | Blend TPMS types、Periodic Lattice follow-along、Completed Periodic Lattice、Cell Maps Using CAD Faces、Cell Maps Using Meshes、Simple Volume Lattices、Periodic Lattice Test Problem、Periodic Lattice on Faces follow-along、Periodic Lattice on Faces complete file、Non-Periodic Lattices follow-along、Completed Non-Periodic Lattices、Applying Lattice Utilities、Filtering Lattice Beams、Custom lattice unit cell、Structural lattice on CAD face、Randomized lattice thickness、Fillets to lattices |
| 表面纹理 | Noise Fields、Working with Bitmaps、Random pattern、Voronoi surface texture、Perforations、Surface roughness、Hyper-realistic 3D textures、Procedural textures |
| 拓扑优化 | How to run a topology optimization、Before We Begin、Topology Optimization Properties and Terminology、Review FE / Boundary Conditions、FE Model and Boundary Conditions、Design Responses、Optimization Objectives、Defining Constraints、Running Topology Optimization、Post Processing、Topology Optimization follow-along、TopOpt Test Problem starter、TopOpt & Post Processing complete file、Topology Optimization Tips and Best Practices、Advanced Topology Optimization、Answer to TopOpt Test Problem、Remap Constraint for Topology Optimization |
| 自动化 | nTop Automate course、Preparing Notebook for Automate、Python scripts、ModeFrontier DOE |
| 换热器 / 热管理 | End-to-End Heat Exchanger、Double Pipe HEX、Core and Baffles、Thermal management、nTop Fluids |
| 仿真 / 网格 | Surface mesh、Homogenized Lattice Simulation、Variable Shell Thickness、FE Mesh for complex shell lattice、Lattice Simulation files |
| 航空参数化 | Parametric Aircraft Design、Accelerated Aircraft Modeling Webinar |
