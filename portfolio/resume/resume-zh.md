# 盖剑秋
移动端与全栈开发

求职意向：移动端开发 / 大前端开发 / 全栈开发

+86 13182870092 · +86 13182970092  
gaijianqiu@gmail.com · 616096372@qq.com
[Portfolio](https://kennaki.github.io/portfolio/)

## 个人简介

**擅长 AI 驱动研发（vibe coding），利用 Claude Code、Codex 加速代码实现，将工程经验投入架构取舍、复杂系统集成、疑难问题定位与精细化体验打磨。**

以原生端与商用 SDK 为技术基础，近期独立完成 Java/Flink API 安全分析链路及 Web 改造交付，覆盖需求拆解、开发验证、部署与排障。2023 年晋升移动端组长，2025 年晋升研发组副组长，开始带领团队，主导鸿蒙 SDK 研发与发布。

## 工作经历

### 国网电力科学研究院有限公司 · 驻场项目
2022.04 — 至今 · 研发组副组长（2025） / 移动端组长（2023） / iOS 开发

- 负责移动安全检测与安全接入 SDK 的研发维护，主导鸿蒙 SDK 研发与发版；由端侧开发拓展至团队协作与全栈交付。
- 单人使用 Claude Code、Codex 构建 API 实时分析链路，从 Mac mini 虚拟机环境搭建到内网部署，协调资源完成端到端交付。
- 主导 2024、2025 年科技项目可研、概要设计、详细设计文档编写及北京汇报；跨端承担 Android 耗电问题首问责任，定位并推动修复，以技术证据支持责任边界澄清及后续合作。

### 南京华米科技
2020.02 — 2022.03 · iOS 开发 / 设备功能模块化项目负责人

- 推进 CBB 组件化方案调研与落地，承担设备功能模块化项目的任务拆解、资源协调和进度管理。
- 开发维护小米运动、Zepp 的健康、表盘、实验室和世界时钟模块，积累蓝牙设备集成与功能复用经验；推动 SwiftUI 调研、Git hook 工具及技术文档沉淀。

### 更早经历
涂鸦智能（2018.10—2020.01）：商用 SDK、Wi-Fi 配网、ODM 定制及 CI/CD；与华米阶段共同形成蓝牙、BLE Mesh 和模块化经验。有货（2016.03—2018.10）：潮牌电商、React Native、直播推流、小程序及 Native A/B 测试。途牛旅游项目及早期移动开发（2012.10—2016.01，其中途牛任职 2014.03—2016.01）：iPad 大屏电商与旅游详情页，深化 Objective-C Runtime、RunLoop 等原生基础。

## 教育与语言
南京中医药大学 · 全日制本科 · 管理学学士 · 2012 年毕业。英语：CET-6 高分通过，能够用英语口头表达自己的想法，雅思备考中；具备英文技术文档阅读与商用 SDK 手册编写经验。

## 精选项目

### 移动 API 安全监测系统
单人全栈交付 · AI 辅助研发

- 从零搭建 Zeek→Kafka→Flink→Elasticsearch 分析链路，接管改造既有 Spring MVC Web 工程，替换供应商黑盒查询接口，新增 API 资产聚合与展示。
- 实现窗口聚合、令牌与设备/IP 关联检测，以及基于约十万条设备记录的 H5 信息补全；完善风险、敏感数据、态势图表、筛选与导出。
- 独立协调并完成从 ARM 开发环境到 x86 隔离内网的部署，解决离线依赖、镜像缓存、字段解析、索引类型及时间/计数口径问题，沉淀测试与交接材料。

Java / Flink / Zeek / Kafka / Elasticsearch / MySQL / Spring MVC / Docker / Kubernetes
[项目详解](https://kennaki.github.io/portfolio/projects/api-security.html)

### 移动应用安全监测 SDK
iOS 研发负责人 · 原生安全与稳定性

- 供应商停止支持后，利用 AI 辅助重建与增强检测逻辑，覆盖越狱、调试、运行期注入、Hook 及网络环境风险，形成分层检测与真机正反例自测流程。
- 完善 Mach-O 导入槽与 Chained Fixups 检测、IMP 来源校验及运行期复检；通过真实样本排查检测盲区与正常设备误报。
- 重构前后台及网络变化驱动的检测调度，加入有界事件缓存与分路重试；围绕并发、定时器生命周期及宿主稳定性持续排障，输出复现步骤与验证记录。

Objective-C / C / C++ / Runtime / Mach-O / GCD / LLDB
[项目详解](https://kennaki.github.io/portfolio/projects/mobile-security.html)

### 安全接入平台 SDK · ISCP / SSAG
iOS SDK 与底层网络研发维护

- 维护从 Objective-C 接口到 C/C++ 安全隧道的完整调用链，改造基于 kqueue 的代理 I/O，完善 ACL 本地端口映射与连接状态回调。
- 针对网络切换、并发重连及资源释放崩溃开展跨层定位，完善状态保护、重连防抖、DNS 与端口缓存治理。
- 覆盖 Wi-Fi/蜂窝切换、前后台和来电中断等场景，沉淀集成说明、故障分析及回归思路，支持业务应用接入。

Objective-C / C / C++ / Socket / OpenSSL / kqueue / Network.framework
[项目详解](https://kennaki.github.io/portfolio/projects/secure-access.html)

[早期项目与技术实践](https://kennaki.github.io/portfolio/#earlier)
