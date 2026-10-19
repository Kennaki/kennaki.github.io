# Jianqiu (Kensyuu) Gai
iOS, Mobile Security & Full-Stack Engineer

Target roles: iOS / Mobile / Frontend & Cross-Platform / Full-Stack Engineering

+86 13182870092 · +86 13182970092  
gaijianqiu@gmail.com · 616096372@qq.com
[Portfolio](https://kennaki.github.io/portfolio/)

## Profile

**AI-accelerated builder with over a decade of engineering judgment. Use Claude Code and Codex to accelerate routine implementation and server-side logic, focusing my expertise on deep native OS integration, complex troubleshooting, and precise interaction and UI details. Investigate poorly documented behavior through source analysis, runtime inspection, and real-device validation, turning generated code into reliable, maintainable products.**

Independently developed the hookengine static library for iOS security, applying Runtime, Mach-O and modern linking knowledge to hook detection, false-positive analysis and host-app lifecycle issues. Delivered an API security analytics pipeline and web modernization as a solo developer, owning the work from environment deployment through validation of data and metrics.

I hold visas or entry permits for Hong Kong, Australia, New Zealand, Japan, and the Schengen Area, and am available to travel for in-person interviews. I passed CET-6 with a high score, can express my ideas in spoken English, and am currently preparing for IELTS.

## Experience

### State Grid Electric Power Research Institute
Apr 2022 — Present · On-site contracted role · Deputy R&D Team Lead (2025) / Mobile Team Lead (2023)

- Independently develop the hookengine static library for mobile security monitoring and maintain secure-access SDKs; lead HarmonyOS SDK delivery, expanding responsibility from iOS engineering to team coordination and full-stack delivery.
- Sole developer of an AI-assisted API analytics pipeline, coordinating resources from Mac mini VM setup through deployment in an isolated internal environment.
- Lead feasibility, high-level and detailed design documentation for 2024–2025 technology projects and technical presentations in Beijing. Take cross-platform ownership of an Android battery issue, identify and help fix the cause, and use evidence to clarify responsibility and support follow-on collaboration.

### Huami Technology · Nanjing
Feb 2020 — Mar 2022 · iOS Engineer / Device Feature Modularization Project Lead

- Research and implement CBB modularization; break down device-feature work, coordinate engineering resources and manage delivery.
- Develop health, watch-face, lab and world-clock modules for Mi Fit and Zepp; work on Bluetooth device integration and reuse. Contribute SwiftUI evaluation, Git hook tooling and technical documentation.

### Earlier experience
Tuya Smart (Oct 2018–Jan 2020): commercial SDKs, Wi-Fi provisioning, ODM and CI/CD; Bluetooth, BLE Mesh and modularization across Tuya and Huami. Yoho (Mar 2016–Oct 2018): fashion commerce, React Native, live streaming, mini programs and A/B testing. Tuniu projects and early mobile work (Oct 2012–Jan 2016; Tuniu employment Mar 2014–Jan 2016): iPad commerce, travel pages, Objective-C Runtime and RunLoop.

## Education
B.Mgt., Nanjing University of Chinese Medicine, 2012. Experience reading technical documentation and writing commercial SDK manuals.

## Selected projects

### iOS Security SDK · Independently Developed hookengine
iOS technical owner · Native security & reliability

- Independently develop the hookengine static library after vendor support ended, using Claude Code and Codex to build the core detection logic from scratch: jailbreak, debugging, dynamic-library injection, hooks and network risks.
- Implement traditional Mach-O symbol-pointer and Chained Fixups import-slot inspection. Cross-check original on-disk imports against runtime targets and handle PAC pointer differences to cover modern linking layouts.
- Trace critical Objective-C method IMPs to their images, combining system-library, main-binary and allowlist checks. Validate detection dependencies such as dladdr to address tampered inspection paths.
- Rework foreground/background and network-triggered scheduling, bounded event storage and per-destination retries; troubleshoot concurrency, timer lifecycle and host-app stability issues.
- Validate with real jailbreak, Frida injection, Method Swizzling and GOT-rebinding cases plus clean-device controls. Investigate false positives, recovery and repeat triggers; retain reproducible steps and evidence.

Objective-C / C / C++ / Runtime / Mach-O / GCD / LLDB
[Case study](https://kennaki.github.io/portfolio/projects/mobile-security.html#english)

### Secure Access SDKs · ISCP / SSAG
iOS SDK & low-level networking

- Maintain the Objective-C-to-C/C++ secure-tunnel integration; rework proxy I/O around kqueue, ACL-based local port mapping and connection-state callbacks.
- Diagnose network-switching, concurrent reconnect and teardown crashes across layers; improve shared-state protection, debouncing, DNS caching and port-cache handling.
- Address Wi-Fi/cellular changes, app lifecycle and call interruptions; produce integration notes, incident analyses and regression guidance for consuming apps.
- Trace connection failures through API state, asynchronous callbacks, network paths and native resources across Objective-C and C/C++; align SDK behavior with host-app lifecycle constraints.

Objective-C / C / C++ / Sockets / OpenSSL / kqueue / Network.framework
[Case study](https://kennaki.github.io/portfolio/projects/secure-access.html#english)

### Mobile API Security Analytics
Solo full-stack delivery · AI-assisted development

- Build the Zeek-to-Kafka-to-Flink-to-Elasticsearch pipeline from scratch; modernize an existing Spring MVC web application, replace a vendor query service and add API asset aggregation and views.
- Implement windowed aggregation, token/device/IP correlation and H5 enrichment against an approximately 100,000-record device index; improve risk views, charts, filters and exports.
- Coordinate delivery from ARM development to isolated x86 infrastructure. Resolve offline dependency, stale-image, parsing, index-mapping, timezone and counting issues; document tests and handoff procedures.
- Model assets by API, host and method separately from request events. Resolve duplicate counts across analysis jobs, timezone discrepancies and missing time buckets to make dashboard metrics consistent.
- Trace source, JARs, container images and running instances to identify stale images and multi-module dependency issues; support intranet delivery with test scripts, confirmed root causes and handoff notes.

Java / Flink / Zeek / Kafka / Elasticsearch / MySQL / Spring MVC / Docker / Kubernetes
[Case study](https://kennaki.github.io/portfolio/projects/api-security.html#english)

Earlier projects & engineering practice: [https://kennaki.github.io/portfolio/#earlier](https://kennaki.github.io/portfolio/#earlier)
