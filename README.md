# threeJourney

[https://gaohaoyang.github.io/threeJourney/](https://gaohaoyang.github.io/threeJourney/)

Three.js Journey

Chapter 01: Basics (基础篇)
本章节的目的是带你从零开始，建立对 3D 网页开发的基本认知，并搭建起第一个可运行的场景。

01. Introduction (引言)

目的： 了解课程结构、讲师背景以及 3D 网页开发的现状。

02. What is WebGL and why use Three.js (什么是 WebGL 以及为何使用 Three.js)

目的： 解释底层 API (WebGL) 的复杂性，以及 Three.js 如何简化开发流程，提升生产力。

03. First Three.js Project (第一个 Three.js 项目)

目的： 学习如何引入库，创建四大核心要素：场景 (Scene)、物体 (Mesh)、相机 (Camera) 和渲染器 (Renderer)。

04. Transform objects (转换物体)

目的： 掌握物体的移动 (Position)、旋转 (Rotation) 和缩放 (Scale)，理解三维坐标系。

05. Animations (动画)

目的： 学习 requestAnimationFrame 的原理，如何根据时间步长实现平滑的 3D 动画。

06. Cameras (相机)

目的： 深入研究透视相机 (Perspective) 和正交相机 (Orthographic)，以及如何使用 OrbitControls 进行交互。

07. Fullscreen and resizing (全屏与自适应)

目的： 处理浏览器窗口变化时的画布适配，确保 3D 场景在各种设备上都能完美填充。

08. Geometries (几何体)

目的： 了解 BufferGeometry 的核心概念，学习如何通过顶点数据构建各种形状。

09. Debug UI (调试界面)

目的： 集成 Lil-gui 等工具，实现在页面上实时调整 3D 参数（如颜色、位置），极大提高开发效率。

10. Textures (纹理)

目的： 学习如何加载图片并映射到物体表面，理解纹理过滤 (Filtering) 和 mipmapping。

11. Materials (材质)

目的： 探索各种材质（MeshBasic, MeshNormal, MeshStandard 等），了解它们对光线的不同反应。

12. 3D Text (3D 文本)

目的： 学习使用 FontLoader 加载字体，并将文字渲染为三维几何体。

13. Go live (上线发布)

目的： 学习如何打包项目并部署到 Vercel 或 Netlify 等平台。

Chapter 02: Classic techniques (经典技术篇)
进入进阶阶段，学习让场景更趋向真实的必备技术。

14. Lights (灯光)

目的： 掌握环境光、点光源、聚光灯等各种光源的使用场景和性能成本。

15. Shadows (阴影)

目的： 学习阴影贴图的原理，解决 3D 空间中物体间复杂的投影关系。

16. Haunted House (闹鬼小屋项目)

目的： 综合实战课。利用前面学到的几何体、材质、灯光搭建一个完整的氛围场景。

17. Particles (粒子系统)

目的： 学习如何渲染成千上万个点，用于制作雨雪、星空或烟雾效果。

18. Galaxy Generator (星系生成器)

目的： 练习数学算法，通过代码随机生成旋涡状的彩色银河。

19. Scroll based animation (基于滚动的动画)

目的： 将 3D 场景与传统的网页滚动行为结合，制作沉浸式叙事网页。

Chapter 03: Advanced techniques (高级技术篇)
解决复杂交互、模型引入及性能架构问题。

20. Physics (物理引擎)

目的： 引入 Cannon.js，实现重力、碰撞、反弹等真实物理反馈。

21. Imported models (导入模型)

目的： 学习如何加载外部软件（如 Blender）导出的 GLTF 模型。

22. Raycaster and Mouse Events (射线检测与鼠标事件)

目的： 实现鼠标点击 3D 物体的交互功能。

23. Custom models with Blender (使用 Blender 自定义模型)

目的： 学习 3D 建模基础，为自己量身定制场景模型。

24. Environment map (环境贴图)

目的： 使用 HDR 或立方体贴图实现精美的金属反射和全局照明效果。

25. Realistic render (写实渲染)

目的： 调整色彩空间、曝光、伽马校正，让渲染效果达到照片级真实。

26. Code structuring for bigger projects (大型项目的代码组织)

目的： 学习使用面向对象 (OOP) 和类 (Class) 来管理复杂的代码逻辑。

Chapter 04: Shaders (着色器篇)
这是课程的核心高难度部分，教你直接操控 GPU。

27. Shaders (着色器基础)

目的： 学习 GLSL 语言，理解顶点着色器和片元着色器的底层逻辑。

28. Shader patterns (着色器图案)

目的： 通过数学公式在 Shader 中绘制各种几何图案。

29. Raging sea (汹涌的大海)

目的： 利用正弦/余弦函数在着色器中模拟波浪起伏。

30. Animated galaxy (动态星系)

目的： 将之前的星系生成器升级为 Shader 版本，获得更强性能和特效。

31. Modified materials (修改内置材质)

目的： 学习如何在 Three.js 的标准材质中注入自己的着色器代码。

32. Coffee Smoke (咖啡烟雾)

目的： 使用片元着色器模拟流体烟雾的动态扩散。

33. Hologram (全息投影)

目的： 制作具有扫描线和半透明效果的未来感全息特效。

34. Fireworks (烟花)

目的： 结合粒子与 Shader 实现烟花的发射、爆炸和消散。

35. Lights Shading (灯光着色)

目的： 在自定义着色器中手动计算光照算法（漫反射、镜面反射）。

36. Raging Sea Shading (大海着色进阶)

目的： 为之前的波浪添加光照效果和深浅颜色变化。

37. Halftone Shading (半色调/漫画风着色)

目的： 实现复古漫画印刷风格的波点渲染。

38. Earth (地球)

目的： 制作一个带云层、大气层以及昼夜变换的高级地球渲染。

39. Particles Cursor Animation (粒子鼠标动画)

目的： 实现粒子跟随鼠标移动并产生排斥或吸引的互动效果。

40. Particles Morphing (粒子形态变换)

目的： 让数万个粒子在不同的 3D 模型形状之间平滑转换。

41. GPGPU Flow Field Particles (GPGPU 流场粒子)

目的： 学习利用 GPU 计算粒子位置，实现百万级粒子的复杂流体运动。

42. Wobbly Sphere (摇摆球体)

目的： 使用噪声函数让球体像果冻一样不规则律动。

后续 43-44 涉及切片模型和程序化生成地形等 Shader 应用。

Chapter 05: Extra (额外补充篇)
45. Post-processing (后处理)

目的： 给渲染后的画面添加滤镜（如景深、辉光、噪点）。

46. Performance tips (性能优化建议)

目的： 学习如何监控帧率，减少绘制调用 (Draw calls)，优化内存。

47. Intro and loading progress (入场动画与加载进度)

目的： 制作加载条，解决大资源加载时的黑屏问题。

48. Mixing HTML and WebGL (HTML 与 WebGL 混合)

目的： 在 3D 空间中精确定位 HTML 标签（如浮动标签）。

Chapter 06: Portal Scene (传送门场景实战)
49-52 章节： 这是一个完整的端到端实战。涵盖了从 Blender 建模、烘焙 (Baking) 光照贴图、导出到 Three.js 还原、并添加 Shader 传送门特效的全过程。

Chapter 07: React Three Fiber (React 开发篇)
将 3D 技术带入现代前端开发框架。

53-55 章节： 基础配置。学习如何用声明式语法写 3D 代码。

56-63 章节： 迁移技术。将之前学到的 Debug、环境、模型加载、鼠标事件、后处理等在 React 环境下重新实现。

64. Fun and Simple Portfolio (趣味个人作品集)

目的： 制作一个可以在浏览器里操作的小型 3D 展示页面。

65. Physics (React 版物理)

目的： 在 R3F 中使用 Rapier 物理库。

66. Create a game (创建一个游戏)

目的： 终极考核。利用 React 和 Three.js 开发一个具有关卡、物理和计分系统的完整 3D 游戏。
