# 盖剑秋
iOS / 移动安全 / 全栈开发

求职意向：iOS 开发 / 移动端开发 / 大前端开发 / 全栈开发

+86 13182870092 · +86 13182970092  
gaijianqiu@gmail.com · 616096372@qq.com
[Portfolio](https://kennaki.github.io/portfolio/)

## 个人简介

**擅长 AI 驱动研发（vibe coding），利用 Claude Code、Codex 加速代码实现，将工程经验投入架构取舍、复杂系统集成、疑难问题定位与精细化体验打磨。**

专注 iOS 原生开发与运行时安全，供应商停止支持后自主研发 hookengine 静态库，构建越狱、调试、注入与 Hook 风险检测，并持续完善误报治理和宿主稳定性。以 Objective-C/C/C++、Runtime 与 Mach-O 为基础，将安全能力交付为可集成的 SDK。近期独立完成 Java/Flink API 安全分析链路及 Web 改造交付，覆盖需求拆解、开发验证、部署与排障。2023 年晋升移动端组长，2025 年晋升研发组副组长，开始带领团队，主导鸿蒙 SDK 研发与发布。

## 工作经历

### 国网电力科学研究院有限公司 · 驻场项目
2022.04 — 至今 · 研发组副组长（2025） / 移动端组长（2023） / iOS 开发

- 自主研发移动安全监测 SDK 的 hookengine 静态库，负责安全接入 SDK 研发维护，主导鸿蒙 SDK 研发与发版；由端侧开发拓展至团队协作与全栈交付。
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

### iOS 安全监测 SDK · 自研 hookengine 静态库
iOS 研发负责人 · 原生安全与稳定性

- 供应商停止支持后，独立负责 hookengine 静态库的自主研发，借助 Claude Code、Codex 从零构建核心检测逻辑，覆盖越狱、调试、动态库注入、Hook 与网络环境风险。
- 实现 Mach-O 传统符号指针表与 Chained Fixups 导入槽检测，结合磁盘原始导入信息与运行时目标交叉校验，处理 PAC 指针差异，补齐现代链接机制下的检测路径。
- 基于 Objective-C Runtime 校验关键方法 IMP 所属镜像，结合系统库、主程序与允许列表识别异常来源，并校验 dladdr 等检测依赖，减少检测入口被篡改带来的盲区。
- 重构前后台及网络变化驱动的检测调度，加入有界事件缓存与分路重试；围绕并发、定时器生命周期及宿主稳定性持续排障，输出复现步骤与验证记录。
- 围绕真实越狱、Frida 注入、Method Swizzling 与 GOT 改写开展正反例验证；排查正常设备误报、移除异常后的恢复与再次触发，形成复现步骤、命中证据和自测记录。

Objective-C / C / C++ / Runtime / Mach-O / GCD / LLDB
[项目详解](https://kennaki.github.io/portfolio/projects/mobile-security.html)

### 安全接入平台 SDK · ISCP / SSAG
iOS SDK 与底层网络研发维护

- 维护从 Objective-C 接口到 C/C++ 安全隧道的完整调用链，改造基于 kqueue 的代理 I/O，完善 ACL 本地端口映射与连接状态回调。
- 针对网络切换、并发重连及资源释放崩溃开展跨层定位，完善状态保护、重连防抖、DNS 与端口缓存治理。
- 覆盖 Wi-Fi/蜂窝切换、前后台和来电中断等场景，沉淀集成说明、故障分析及回归思路，支持业务应用接入。
- 将业务侧连接失败拆解为接口状态、异步回调、网络路径及底层资源问题，跨 Objective-C 与 C/C++ 调用链追踪，兼顾 SDK 接口可用性与宿主生命周期。

Objective-C / C / C++ / Socket / OpenSSL / kqueue / Network.framework
[项目详解](https://kennaki.github.io/portfolio/projects/secure-access.html)

### 移动 API 安全监测系统
单人全栈交付 · AI 辅助研发

- 从零搭建 Zeek→Kafka→Flink→Elasticsearch 分析链路，接管改造既有 Spring MVC Web 工程，替换供应商黑盒查询接口，新增 API 资产聚合与展示。
- 实现窗口聚合、令牌与设备/IP 关联检测，以及基于约十万条设备记录的 H5 信息补全；完善风险、敏感数据、态势图表、筛选与导出。
- 独立协调并完成从 ARM 开发环境到 x86 隔离内网的部署，解决离线依赖、镜像缓存、字段解析、索引类型及时间/计数口径问题，沉淀测试与交接材料。
- 将 API、Host、Method 作为资产维度，区分访问明细与聚合资产；排查多分析作业重复计数、时区与缺失时间桶问题，统一图表统计口径。
- 逐层核对源码、JAR、镜像与实际运行实例，定位旧镜像缓存和多模块依赖问题；以测试脚本、已证实根因与交接材料支持内网交付。

Java / Flink / Zeek / Kafka / Elasticsearch / MySQL / Spring MVC / Docker / Kubernetes
[项目详解](https://kennaki.github.io/portfolio/projects/api-security.html)

早期项目与技术实践: [https://kennaki.github.io/portfolio/#earlier](https://kennaki.github.io/portfolio/#earlier)
