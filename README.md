# Unity-ResourceHub

收集并整理平时见到的实用 Unity 资源，避免回头再找的时候遗忘。

## 📑 目录

- [🚀 精选推荐](#-精选推荐)
- [🎮 游戏框架 & 架构](#-游戏框架--架构)
- [🌐 网络 & 同步](#-网络--同步)
- [🛠️ 编辑器工具](#-编辑器工具)
- [🎨 UI 组件 & 扩展](#-ui-组件--扩展)
- [⚙️ 物理 & 数学 & 寻路](#-物理--数学--寻路)
- [✨ 图形 & 着色器](#-图形--着色器)
- [🎬 动画 & 缓动](#-动画--缓动)
- [🔊 音频 & 多媒体](#-音频--多媒体)
- [🧠 AI & 大模型](#-ai--大模型)
- [📦 资源管理 & 加载](#-资源管理--加载)
- [📱 平台 & 原生](#-平台--原生)
- [⚔️ 技能 & 属性系统](#-技能--属性系统)
- [📚 学习资源](#-学习资源)
- [📂 优质合集](#-优质合集)
- [🔧 工具 & 其他](#-工具--其他)
- [📁 相关文件](#-相关文件)

---

## 🚀 精选推荐

最常用、最值得关注的资源：

- [UniTask](https://github.com/Cysharp/UniTask) - 零分配 async/await，Unity 异步标准
- [VContainer](https://github.com/hadashiA/VContainer) - 高性能 DI 容器
- [LitMotion](https://github.com/AnnulusGames/LitMotion) - 高性能缓动库
- [DOTween](https://github.com/Demigiant/dotween) - 经典缓动引擎，生态成熟
- [Mirror](https://github.com/MirrorNetworking/Mirror) - 排名第一的 Unity 网络开源库
- [Entitas](https://github.com/sschmid/Entitas) - 经典 ECS 框架
- [HybridCLR](https://github.com/focus-creative-games/hybridclr) - 原生 C# 热更新解决方案
- [Tri-Inspector](https://github.com/codewriter-packages/Tri-Inspector) - Inspector 属性扩展（Odin 平替）
- [EasyButtons](https://github.com/madsbangh/EasyButtons) - 自定义编辑器按钮
- [uPools](https://github.com/AnnulusGames/uPools) - 高性能对象池
- [DotRecast](https://github.com/ikpil/DotRecast) - NavMesh 导航库
- [X-PostProcessing-Library](https://github.com/QianMo/X-PostProcessing-Library) - 后处理效果库
- [QFramework](https://github.com/liangxiegame/QFramework) - 国内常用 Unity 快速开发框架

---

## 🎮 游戏框架 & 架构

### 完整框架

- [Fantasy](https://github.com/qq362946/Fantasy) - C# 游戏服务器框架
- [MyFramework](https://github.com/ZHOURUIH/MyFramework) - 完整游戏框架
- [QFramework](https://github.com/liangxiegame/QFramework) - Unity 快速开发框架（UI/架构/工具链）
- [GameFrameX](https://github.com/AlianBlank/GameFrameX) - 双端共享代码的分布式游戏框架
- [KSFramework](https://github.com/mr-kelly/KSFramework) - 整合 KEngine 的 Unity 框架
- [BDFramework.Core](https://github.com/yimengfan/BDFramework.Core) - 基于 ILRuntime 的热更框架
- [loxodon-framework](https://github.com/vovgou/loxodon-framework) - MVVM 跨平台 UI 框架
- [ColaFrameWork](https://github.com/XINCGer/ColaFrameWork) - 轻量级游戏框架
- [GDX](https://github.com/dotBunny/GDX) - 游戏开发扩展库（数学/集合/工具）

### ECS

- [Entitas](https://github.com/sschmid/Entitas) - 经典 ECS 框架
- [Arch](https://github.com/genaray/Arch) - 轻量级 ECS 框架
- [Morpeh](https://github.com/scellecs/morpeh) - 纯 .NET ECS 框架
- [DefaultEcs](https://github.com/Doraku/DefaultEcs) - 高性能纯 .NET ECS 框架
- [Svelto.ECS](https://github.com/sebas77/Svelto.ECS) - 混合范式 ECS 框架
- [DragonECS](https://github.com/DCFApixels/DragonECS) - 轻量级 ECS 框架
- [Friflo.Engine.ECS](https://github.com/friflo/Friflo.Engine.ECS) - 高效 ECS 框架
- [Latios-Framework](https://github.com/Dreaming381/Latios-Framework) - DOTS 扩展框架
- [ECSAnimation](https://github.com/MrLiuYX/ECSAnimation) - ECS 动画系统（万人同屏）
- [NSprites](https://github.com/Antoshidza/NSprites) - DOTS 精灵渲染
- [ecs-faq](https://github.com/SanderMertens/ecs-faq) - ECS 常见问题解答

### 依赖注入

- [VContainer](https://github.com/hadashiA/VContainer) - 高性能 DI 容器
- [Zenject](https://github.com/modesttree/Zenject) - 依赖注入框架
- [Binject](https://github.com/somedeveloper00/Binject) - 轻量级依赖注入
- [Reflex](https://github.com/gustavopsantos/Reflex) - 依赖反射框架
- [initArgs](https://assetstore.unity.com/packages/tools/utilities/init-args-200530) - 简单依赖注入

---

## 🌐 网络 & 同步

### 网络同步方案

- [Mirror](https://github.com/MirrorNetworking/Mirror) - 排名第一的 Unity 网络开源库
- [Fish-Net](https://github.com/FirstGearGames/FishNet) - 高性能网络库（预测/回滚/状态同步）
- [Netcode for GameObjects](https://github.com/Unity-Technologies/com.unity.netcode.gameobjects) - Unity 官方网络 SDK
- [NetickForUnity](https://github.com/NetickNetworking/NetickForUnity) - 网络同步解决方案
- [colyseus-unity](https://github.com/colyseus/colyseus-unity-sdk) - Colyseus 多人游戏 SDK
- [TinySync](https://github.com/Ariesybs/TinySync) - 帧同步
- [ParrelSync](https://github.com/VeriorPies/ParrelSync) - 多客户端测试工具
- [MultiplayerNetworkingResources](https://github.com/0xFA11/MultiplayerNetworkingResources) - 多人游戏网络资源合集

### 回滚 & 预测

- [DelayNoMoreUnity](https://github.com/genxium/DelayNoMoreUnity) - 回滚式网络方案
- [ecs](https://github.com/chromealex/ecs) - ECS 全状态自动回滚

### 游戏服务器

- [Nakama](https://github.com/heroiclabs/nakama) - 开源游戏后端服务器
- [NoahGameFrame](https://github.com/ketoo/NoahGameFrame) - 快速开发游戏服务器框架
- [GeekServer](https://github.com/leeveel/GeekServer) - 纯 C# 游戏服务器框架

### C# 网络库

- [Riptide](https://github.com/RiptideNetworking/Riptide) - 轻量级高性能网络库
- [kcp](https://github.com/KumoKyaku/kcp) - KCP 协议 C# 实现
- [LiteNetLib](https://github.com/RevenantX/LiteNetLib) - 轻量级 UDP 网络库
- [HiSocket](https://github.com/hiram3512/HiSocket) - 高性能套接字库
- [Megumin.Net](https://github.com/KumoKyaku/Megumin.Net) - 网络通信库
- [TouchSocket](https://github.com/RRQM/TouchSocket) - 跨平台网络通信库
- [NetCoreServer](https://github.com/chronoxor/NetCoreServer) - 超快速低延迟异步套接字服务器
- [NativeWebSocket](https://github.com/endel/NativeWebSocket) - Unity WebSocket 客户端
- [websocket-sharp](https://github.com/sta/websocket-sharp) - WebSocket 协议 C# 实现（支持安全链接/身份认证/cookies）

---

## 🛠️ 编辑器工具

### Inspector & 属性

- [Tri-Inspector](https://github.com/codewriter-packages/Tri-Inspector) - 编辑器显示扩展（Odin 平替）
- [EditorAttributes](https://github.com/v0lt13/EditorAttributes) - Odin 类似扩展
- [Alchemy](https://github.com/AnnulusGames/Alchemy) - 编辑器增强工具
- [SaintsField](https://github.com/TylerTemp/SaintsField) - Inspector 增强
- [SerializeReferenceDropdown](https://github.com/AlexeyTaranov/SerializeReferenceDropdown) - 可序列化引用下拉框
- [Unity-SerializeReferenceExtensions](https://github.com/mackysoft/Unity-SerializeReferenceExtensions) - SerializeReference 高级扩展
- [EasyButtons](https://github.com/madsbangh/EasyButtons) - 自定义编辑器按钮

### 效率工具

- [FastScriptReload](https://github.com/handzlikchris/FastScriptReload) - 脚本热重载
- [Unity.TransformSetterInterceptor](https://github.com/handzlikchris/Unity.TransformSetterInterceptor) - Transform 变化追踪
- [unity-texture-apply-async](https://github.com/gilzoide/unity-texture-apply-async) - 异步纹理应用
- [UnityEditorJunkie](https://github.com/roboryantron/UnityEditorJunkie) - 枚举搜索等工具
- [code-analysis-3-7-editor-only](https://github.com/merryyellow/code-analysis-3-7-editor-only) - Roslyn 代码分析
- [FolderTag](https://github.com/liyingsong99/FolderTag) - 文件夹折叠管理
- [unity-editor-icons](https://github.com/halak/unity-editor-icons) - Unity 编辑器图标集合
- [ScaleNineSlicer](https://github.com/utkaka/ScaleNineSlicer) - 九宫格切图编辑器
- [lineburst](https://github.com/bassmit/lineburst) - 线条效果工具
- [TexturePropertyTool](https://github.com/alex520lq/TexturePropertyTool) - 批量修改贴图压缩格式
- [MissingReferencesUnity](https://github.com/liortal53/MissingReferencesUnity) - 场景缺失引用检查
- [Unity Resource Checker](https://github.com/handcircus/Unity-Resource-Checker) - 资源使用分析器
- [Asset Usage Detector](https://github.com/yasirkula/UnityAssetUsageDetector) - 资源引用检测
- [Compile Time Tracker](https://github.com/DarrenTsung/DTCompileTimeTracker) - 编译时间追踪
- [unity3d-rainbow-folders](https://github.com/Borod4r/unity3d-rainbow-folders) - 文件夹彩色图标
- [Mulligan Renamer](https://github.com/redbluegames/unity-mulligan-renamer) - 批量重命名工具
- [UnityToolchainsTrick](https://github.com/XINCGer/UnityToolchainsTrick) - Unity 工具链技巧合集

### GUI & 节点编辑

- [RapidGUI](https://github.com/fuqunaga/RapidGUI) - IMGUI 快速原型扩展
- [NodeGraphProcessor](https://github.com/alelievr/NodeGraphProcessor) - 节点图编辑器框架
- [xNode](https://github.com/Siccity/xNode) - 轻量级节点编辑器框架
- [ActionEditor](https://github.com/NoBugCn/ActionEditor) - 技能编辑器

### 工具集合集

- [MyBox](https://github.com/Deadcows/MyBox) - Unity 属性、工具、扩展集
- [Tools](https://github.com/alex520lq/Tools) - 常用 Unity 工具类扩展
- [Unity-Dev-Tools](https://github.com/alex520lq/Unity-Dev-Tools) - 收集各种 Unity 库
- [demilib](https://github.com/alex520lq/demilib) - Unity 工具与工具库
- [My_Useful_Unity_Codes](https://github.com/alex520lq/My_Useful_Unity_Codes) - 游戏开发有用脚本收集

---

## 🎨 UI 组件 & 扩展

### UI 框架

- [Unity-Async-UIFrame](https://github.com/alex520lq/Unity-Async-UIFrame) - 异步 UI 框架（无第三方依赖）
- [UIFlow](https://github.com/LizzyFox-code/UIFlow) - UI 流程管理框架
- [StatefulUI](https://github.com/dmitry-ivashenko/StatefulUI) - 状态化 UI 组件

### UI 组件

- [UnityProgressBar](https://github.com/AnnulusGames/UnityProgressBar) - 进度条组件
- [RadialProgressBar](https://github.com/alex520lq/RadialProgressBar) - 可定制径向进度条
- [EnhancedOnScreenStick](https://github.com/AnnulusGames/EnhancedOnScreenStick) - 增强型虚拟摇杆
- [UniJoystick](https://github.com/alex520lq/UniJoystick) - 摇杆/触控板组件
- [UITableViewForUnity](https://github.com/zhaozilong1988/UITableViewForUnity) - 高性能表格视图
- [FancyScrollView](https://github.com/setchi/FancyScrollView) - 高度灵活的滚动视图组件
- [LoopScrollRect](https://github.com/qiankanglai/LoopScrollRect) - UGUI 循环滚动优化
- [Unity-UI-Rounded-Corners](https://github.com/kirevdokimov/Unity-UI-Rounded-Corners) - UI 图像圆角自动生成
- [Unity-Theme](https://github.com/IvanMurzak/Unity-Theme) - 更改游戏界面主题

### UI 特效

- [UIEffect](https://github.com/mob-sakai/UIEffect) - uGUI 特效组件
- [SoftMaskForUGUI](https://github.com/mob-sakai/SoftMaskForUGUI) - UI 软遮罩组件
- [ParticleEffectForUGUI](https://github.com/mob-sakai/ParticleEffectForUGUI) - UI 粒子渲染（无额外相机）
- [EmojiText](https://github.com/alex520lq/EmojiText) - UGUI 表情系统
- [CharTweener](https://github.com/alex520lq/CharTweener) - 文本字符动画
- [TMPEffects](https://github.com/Luca3317/TMPEffects) - TMP 文本动画效果（自定义标签）
- [TextInlineSprite](https://github.com/coding2233/TextInlineSprite) - UGUI 图文混排

### UI 编辑工具

- [FairyGUI-Editor](https://github.com/fairygui/FairyGUI-Editor) - FairyGUI 编辑器
- [UGUI-Editor](https://github.com/alex520lq/UGUI-Editor) - UGUI 编辑器效率工具
- [Unity-AlignTools](https://github.com/alex520lq/Unity-AlignTools) - GUI 对象对齐插件
- [FullPSD2UGUI](https://github.com/alex520lq/FullPSD2UGUI) - PSD 转 UGUI
- [Auto9Slicer](https://github.com/kyubuns/Auto9Slicer) - 自动九宫格生成器
- [unity-safe-area-layout](https://github.com/gilzoide/unity-safe-area-layout) - 刘海屏安全区域控制

---

## ⚙️ 物理 & 数学 & 寻路

### 物理引擎

- [ReactPhysics3D](https://www.reactphysics3d.com/documentation/) - 3D 物理引擎
- [Box2D](https://github.com/erincatto/Box2D) - 2D 物理引擎
- [bepuphysics2](https://github.com/bepu/bepuphysics2) - 纯 C# 实时物理模拟库（确定性可用）
- [BulletSharp](https://github.com/AndresTraks/BulletSharp) - Bullet 物理引擎 C# 绑定
- [Box2DSharp](https://github.com/Zonciu/Box2DSharp) - Box2D C# 移植
- [Unity-Collider-Optimizer](https://github.com/aniketrajnish/Unity-Collider-Optimizer) - 碰撞体优化

### 数学库

- [Mathfs](https://github.com/FreyaHolmer/Mathfs) - 数学库
- [Unity.Mathematics.FixedPoint](https://github.com/alex520lq/Unity.Mathematics.FixedPoint) - Unity 定点数学扩展
- [TPhysics](https://github.com/alex520lq/TPhysics) - 定点物理库
- [LogicPhysics](https://github.com/alex520lq/LogicPhysics) - 定点数学库

### 算法

- [C-Sharp 算法](https://github.com/TheAlgorithms/C-Sharp) - C# 算法实现
- [advanced-algorithms](https://github.com/justcoding121/advanced-algorithms) - C# 高级算法实现
- [Computational-geometry](https://github.com/Habrador/Computational-geometry) - 计算几何/网格简化

### 寻路 & 避障

- [DotRecast](https://github.com/ikpil/DotRecast) - NavMesh 导航库
- [com.nebukam.orca](https://github.com/Nebukam/com.nebukam.orca) - ORCA/RVO2 实现
- [RVO2-CS](https://github.com/snape/RVO2-CS) - RVO2 碰撞避障 C# 实现
- [RVO2Unity](https://github.com/aillieo/RVO2-Unity) - RVO2 Unity 版
- [unity-pathfinding](https://github.com/sturdyspoon/unity-pathfinding) - A* Tilemaps
- [Simple-optimized-A-Pathfinder](https://github.com/alex520lq/Simple-optimized-A-Pathfinder) - 简单优化网格寻路

### 空间查询

- [KNN](https://github.com/alex520lq/KNN) - DOTS 快速最近邻查找
- [GPUNearestNeighbor](https://github.com/kodai100/Unity_GPUNearestNeighbor) - GPU 空间查询

### 教程

- [Ten-Minute-Physics-Unity](https://github.com/Habrador/Ten-Minute-Physics-Unity) - 十分钟物理教程
- [Game-Physics-Cookbook](https://github.com/alex520lq/Game-Physics-Cookbook) - 游戏物理算法实现（书）
- [learn-physics](https://github.com/alex520lq/learn-physics) - 物理引擎学习（中文，自实现简易引擎）

---

## ✨ 图形 & 着色器

### 卡通渲染

- [RealToon Pro](https://assetstore.unity.com/packages/vfx/shaders/realtoon-pro-anime-toon-shader-65518) - 高质量卡通渲染
- [Toony Colors Pro 2](https://assetstore.unity.com/packages/vfx/shaders/toony-colors-pro-2-8105) - 专业卡通渲染
- [UnityChanToonShaderVer2_Project](https://github.com/unity3d-jp/UnityChanToonShaderVer2_Project) - Unity 日本官方卡通渲染
- [UnityURPToonLitShaderExample](https://github.com/ColinLeung-NiloCat/UnityURPToonLitShaderExample) - URP 卡通着色器
- [kShading](https://github.com/Kink3d/kShading) - 风格化着色器集合
- [MToon](https://github.com/Santarh/MToon) - VRM 卡通渲染着色器
- [Kamakura Shaders](https://github.com/kayac/kamakura-shaders) - 非真实感渲染着色器集合

### 后处理 & 特效

- [X-PostProcessing-Library](https://github.com/QianMo/X-PostProcessing-Library) - 后处理效果库
- [NovaShader](https://github.com/CyberAgentGameEntertainment/NovaShader) - 高级着色器库
- [3D_ChineseInkPaintingStyleShader](https://github.com/alex520lq/3D_ChineseInkPaintingStyleShader) - 3D 中国风水墨渲染
- [fog-of-war](https://github.com/alex520lq/fog-of-war) - 高性能战争迷雾系统
- [sprite-glow](https://github.com/elringus/sprite-glow) - 2D 精灵发光效果

### 水相关

- [Crest](https://github.com/wave-harmonic/crest) - 高级海洋系统
- [NaughtyWaterBuoyancy](https://github.com/dbrizov/NaughtyWaterBuoyancy) - 水面浮力系统
- [Unity-Water-Shaders](https://github.com/Parrot222/Unity-Water-Shaders) - 水体着色器集合
- [FusionWater](https://github.com/nailuj05/FusionWater) - 高级水体效果

### 网格 & 模型

- [UnityMeshSimplifier](https://github.com/Whinarn/UnityMeshSimplifier) - 网格简化
- [HLOD](https://github.com/alex520lq/HLOD) - HLOD for Unity
- [unity-polygon-2d-editor](https://github.com/alex520lq/unity-polygon-2d-editor) - 2D 多边形碰撞生成网格
- [kMirrors](https://github.com/Kink3d/kMirrors) - URP 镜面反射
- [kDecals](https://github.com/Kink3d/kDecals) - URP 贴花系统

### Shader 学习 & 合集

- [Awesome-Unity-Shader](https://github.com/QianMo/Awesome-Unity-Shader) - Unity Shader 资源合集（浅墨）
- [Unity_Shaders_Book](https://github.com/candycat1992/Unity_Shaders_Book) - 《Unity Shader 入门精要》源码
- [ShaderTutorials](https://github.com/ronja-tutorials/ShaderTutorials) - Shader 教程（英文）
- [FishManShaderTutorial](https://github.com/JiepengTan/FishManShaderTutorial) - Shader 中级教程（中文）
- [3d-game-shaders-for-beginners](https://github.com/lettier/3d-game-shaders-for-beginners) - 3D 游戏 Shader 初学者入门（SSAO/景深/法线贴图）

---

## 🎬 动画 & 缓动

- [LitMotion](https://github.com/AnnulusGames/LitMotion) - 高性能缓动库
- [DOTween](https://github.com/Demigiant/dotween) - 经典缓动引擎，生态成熟
- [PrimeTween](https://github.com/KyryloKuzyk/PrimeTween) - 性能优化的缓动系统
- [Animation-Sequencer](https://github.com/brunomikoski/Animation-Sequencer) - 动画序列可视化工具
- [TweenPlayables](https://github.com/AnnulusGames/TweenPlayables) - 可播放缓动组件

---

## 🔊 音频 & 多媒体

### 音频

- [Unity-UI-Audio-Collection](https://github.com/DevsDaddy/Unity-UI-Audio-Collection) - UI 音效集合
- [Lasp](https://github.com/keijiro/Lasp) - 音频可视化与声音效果
- [cscore](https://github.com/filoe/cscore) - 高级音频库
- [Simple-Unity-Audio-Manager](https://github.com/jackyyang09/Simple-Unity-Audio-Manager) - 简易分布式音频管理器
- [Unity-Audio-Manager](https://github.com/MathewHDYT/Unity-Audio-Manager) - 音频管理器插件
- [NAudio.Lame-For-Unity](https://github.com/3wz/Lame-For-Unity) - WAV 转 MP3（录音压缩上传）
- [unityAudioDemo](https://github.com/alex520lq/unityAudioDemo) - 录音并保存 MP3

### 多媒体

- [ffmpeg-kit](https://github.com/arthenica/ffmpeg-kit) - FFmpeg 音视频处理库

---

## 🧠 AI & 大模型

- [Locus](https://github.com/alex520lq/Locus) - 开源 Unity Dev Agent
- [dotcraft-unity](https://github.com/alex520lq/dotcraft-unity) - Unity 编辑器 AI 集成（MCP 网关，Roslyn）
- [unity-AI-Chat-Toolkit](https://github.com/alex520lq/unity-AI-Chat-Toolkit) - LLM 聊天 + 语音服务（多平台）
- [Stable-Diffusion-Unity-Integration](https://github.com/alex520lq/Stable-Diffusion-Unity-Integration) - Stable Diffusion 集成
- [piper.unity](https://github.com/alex520lq/piper.unity) - 本地 TTS 语音合成
- [AIShader](https://github.com/keijiro/AIShader) - AI 辅助着色器生成
- [Text-To-Material-Unity](https://github.com/aniketrajnish/Text-To-Material-Unity) - 文本转材质生成

---

## 📦 资源管理 & 加载

### 对象池 & 集合

- [uPools](https://github.com/AnnulusGames/uPools) - 高性能对象池
- [ObservableCollections](https://github.com/Cysharp/ObservableCollections) - 可观察集合库

### 资源加载 & 缓存

- [Unity-ImageLoader](https://github.com/IvanMurzak/Unity-ImageLoader) - 图片加载 Cache
- [davinci](https://github.com/shamsdev/davinci) - 图片加载 Cache
- [Unity-AudioLoader](https://github.com/IvanMurzak/Unity-AudioLoader) - 声音加载 Cache
- [sprite-dicing](https://github.com/elringus/sprite-dicing) - 图片分割工具
- [SmartAddresser](https://github.com/CyberAgentGameEntertainment/SmartAddresser) - Addressables 智能增强工具

### 热更新

- [HybridCLR](https://github.com/focus-creative-games/hybridclr) - 原生 C# 热更新解决方案（零成本）
- [Assemblies-Hotfix-Toolkit-Unity](https://github.com/alex520lq/Assemblies-Hotfix-Toolkit-Unity) - 程序集热更工具

---

## 📱 平台 & 原生

### 移动平台

- [UnityMobileSupport](https://github.com/CyberAgentGameEntertainment/UnityMobileSupport) - 移动平台支持
- [BlankDeviceUniqueIdentifier](https://github.com/AlianBlank/BlankDeviceUniqueIdentifier) - 设备唯一 ID
- [MemoryInfoPlugin-for-Unity](https://github.com/alex520lq/MemoryInfoPlugin-for-Unity) - Android/iOS 内存信息工具
- [UnityNativeShare](https://github.com/yasirkula/UnityNativeShare) - 原生分享插件

### 安全 & 防护

- [GameShield](https://github.com/DevsDaddy/GameShield) - Unity 防护方案
- [FastBugly](https://github.com/alex520lq/FastBugly) - 快速接入新版 Bugly

### 云服务

- [UnityAliyunOSSUploader](https://github.com/StartNight/UnityAliyunOSSUploader) - 阿里云 OSS 上传工具

### 广告 & 服务

- [QuickAdmobIntegrator](https://github.com/IShix-g/QuickAdmobIntegrator) - AdMob 快速集成工具
- [play-games-plugin-for-unity](https://github.com/playgameservices/play-games-plugin-for-unity) - Google Play 游戏服务

### WebGL

- [UnityWebGL-LoadingTest](https://github.com/alex520lq/UnityWebGL-LoadingTest) - WebGL 平台构建对比

---

## ⚔️ 技能 & 属性系统

- [Stat-System](https://github.com/meredoth/Stat-System) - 可扩展角色属性系统
- [gameplay-ability-system-for-unity](https://github.com/No78Vino/gameplay-ability-system-for-unity) - 游戏技能系统
- [UnityGameplayAbilitySystem](https://github.com/alex520lq/UnityGameplayAbilitySystem) - 统一技能系统框架
- [EGamePlay](https://github.com/m969/EGamePlay) - 轻量易扩展的战斗技能框架
- [Unity-Buff-System](https://github.com/NoSLoofah/Unity-Buff-System) - Unity Buff 系统
- [SkillSystem](https://github.com/dongweiPeng/SkillSystem) - 技能系统框架

---

## 👤 数字人

- [metahuman_overview](https://github.com/YUANZHUO-BNU/metahuman_overview) - 数字人技术概览

---

## 📚 学习资源

### 设计模式

- [Unity-Programming-Patterns](https://github.com/Habrador/Unity-Programming-Patterns) - Unity 设计模式
- [Unity-Design-Pattern](https://github.com/QianMo/Unity-Design-Pattern) - Unity 设计模式（GoF 23 种）

### C# 学习

- [DotNetGuide](https://github.com/YSGStudyHards/DotNetGuide) - C# 学习指南

### 书籍合集

- [编程书籍](https://github.com/mymmsc/books/tree/master) - 编程相关书籍集合
- [游戏开发书籍](https://github.com/zengfeng/books) - 游戏开发书籍
- [free-programming-books-zh_CN](https://github.com/justjavac/free-programming-books-zh_CN) - 免费编程书籍中文合集

---

## 📂 优质合集

- [awesome-unity](https://github.com/RyanNielson/awesome-unity) - Unity 资源精选集合
- [awesome-unity-games](https://github.com/akinmustafa/awesome-unity-games) - Unity 游戏集合
- [awesome-unity-open-source-on-github](https://github.com/baba-s/awesome-unity-open-source-on-github) - GitHub 上优秀的 Unity 开源项目（800+）
- [Unity3DTraining](https://github.com/XINCGer/Unity3DTraining) - Unity3D 学习与实战训练
- [GameDev](https://github.com/crazyshader/GameDev) - 游戏开发资源集合
- [Unity-Script-Collection](https://github.com/michidk/Unity-Script-Collection) - Unity 脚本集合
- [GameAndUnity-TechLib](https://github.com/m969/GameAndUnity-TechLib) - 游戏与 Unity 技术库
- [UnityLibrary](https://github.com/UnityCommunity/UnityLibrary) - Unity 社区脚本库
- [Game-Networking-Resources](https://github.com/MFatihMAR/Game-Networking-Resources) - 游戏网络资源合集

---

## 🔧 工具 & 其他

### 交互 & 输入

- [EasyInteractive](https://github.com/HalfADog/EasyInteractive) - 交互系统
- [Unity-Gyroscope-Parallax](https://github.com/IvanMurzak/Unity-Gyroscope-Parallax) - 陀螺仪视差效果
- [InputManager](https://github.com/daemon3000/InputManager) - 强大的输入管理器
- [TouchScript](https://github.com/TouchScript/TouchScript) - 多点触控库

### 曲线 & 几何

- [UnityBezierSolution](https://github.com/yasirkula/UnityBezierSolution) - 贝塞尔曲线工具
- [DualGrid](https://github.com/skner-dev/DualGrid) - 双网格系统

### 文本

- [Unity-TextMeshPro-Chinese-Characters-Set](https://github.com/wy-luke/Unity-TextMeshPro-Chinese-Characters-Set) - TMP 中文字符集

### Spine

- [SpineUtility](https://github.com/alex520lq/SpineUtility) - Spine 适配 UGUI 容器大小
- [spine-runtimes](https://github.com/EsotericSoftware/spine-runtimes) - Spine 官方运行库

### 行为树 & AI

- [NPBehave](https://github.com/meniku/NPBehave) - 事件驱动行为树
- [fluid-behavior-tree](https://github.com/ashblue/fluid-behavior-tree) - 代码式行为树
- [GOAP](https://github.com/crashkonijn/GOAP) - 多线程目标导向行动规划
- [UnitySteer](https://github.com/ricardojmendez/UnitySteer) - 群体操控/避障/路径跟随

### 程序化生成

- [ProceduralToolkit](https://github.com/Syomus/ProceduralToolkit) - 程序化网格生成工具集
- [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) - WFC 算法实现
- [Edgar-Unity](https://github.com/OndrejNepozitek/Edgar-Unity) - 程序化随机关卡生成

### 调试 & 日志

- [uREPL](https://github.com/hecomi/uREPL) - 运行时 C# 表达式求值
- [UberLogger](https://github.com/bbbscarter/UberLogger) - 高级日志系统
- [Lunar Mobile Console](https://github.com/SpaceMadness/lunar-unity-console) - 移动端调试控制台
- [unity-debug-overlay](https://github.com/pandr/unity-debug-overlay) - 高性能调试覆盖层

### 序列化 & 数据

- [flatbuffers](https://github.com/google/flatbuffers) - 高性能序列化库（游戏常用）
- [ZLinq](https://github.com/Cysharp/ZLinq) - 零分配 LINQ 实现

### 反编译 & 资源提取

- [AssetStudio](https://github.com/zhangjiequan/AssetStudio) - Unity 资源查看工具
- [AssetStudio_Tuanjie](https://github.com/SiMaLaoShi/AssetStudio_Tuanjie) - 资源提取工具
- [Learn-Frida](https://github.com/kylesmile1103/Learn-Frida) - Frida 逆向工程学习

### 其他

- [goxel](https://github.com/guillaumechereau/goxel) - 体素编辑器
- [download.unity.com](https://github.com/AlianBlank/download.unity.com) - Unity 下载重定向
- [stb](https://github.com/nothings/stb) - C 语言单头文件库合集（图像/字体/音频等）
- [UnityMainThreadDispatcher](https://github.com/PimDeWitte/UnityMainThreadDispatcher) - 主线程调度器
- [ToolGood.Words](https://github.com/toolgood/ToolGood.Words) - 敏感词过滤库

---

## 📁 相关文件

- [Fork-Index.md](./Fork-Index.md) - 已删除 fork 仓库完整索引（按分类记录，便于回溯原仓库）
- [games.md](./games.md) - 开源游戏 & 小游戏参考（按类型分类）
- [prompts/](./prompts/) - AI 提示词集合（RIPER-5 系列）
- [assets/](./assets/) - 二进制资源文件
