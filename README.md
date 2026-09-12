# ThinkPrism 多维思辨透镜 (Cherry Studio MiniApp)

> 输入任一命题，通过第一性原理、反向拆解、极端压力测试与决策边界四重视角，层层剥离认知盲区。专为 **Cherry Studio** 打造的深度思维推演工具。

---

## 一、核心透镜矩阵

| 认知透镜 | 核心问题 | 产出价值 |
| :--- | :--- | :--- |
| 🎯 **第一性原理 (First Principles)** | 这个事物的本质事实与物理基底是什么？剥离经验主义后剩下什么？ | 打破思维定势，找到不可简化的基石与创新路径 |
| 🔬 **反向拆解 (Deconstruction)** | 如果目标是彻底搞砸这件事，该怎么做？最隐蔽的崩溃路径在哪？ | 逆向思维暴露单点故障，前置防御毁灭性风险 |
| 💣 **极端压力测试 (Stress-Testing)** | 资源×10倍或压缩至1/10、时间极度紧迫时，系统会在哪里断裂？ | 识别系统的非线性脆弱点，评估真实容灾承载力 |
| 🧭 **决策边界 (Decision Boundary)** | 这个结论在什么条件下成立？在什么临界点上必须彻底推翻重来？ | 标定认知适用范围，划定策略失效与退出的红线 |

---

## 二、核心功能与特色

1. **四维透镜并发流式推演**：
   - 接入原生 `window.cherry.ai.chat` 接口，支持深度推演与多维洞察生成；
   - 具备**纯前端离线仿真双轨机制**：无 AI 环境时亦可体验完整推演逻辑。
2. **多模式支持**：
   - **极速扫描模式**：快速抓取关键矛盾与盲区核心；
   - **深度拆解模式**：展开详尽逻辑链条与实操决策边界。
3. **一键双格式交付**：
   - **导出 Markdown**：排版清晰的思辨全案文档，适合沉淀知识库或团队复盘；
   - **导出 JSON**：结构化数据，方便后续自动化处理或二次加工。
4. **Local-First 历史档案管理**：
   - 本地持久化推演历史（最近 20 条），支持历史快速回溯与重新推演。

---

## 三、安装与使用说明

### 方式 A：Cherry Studio 在线一键安装（推荐）
1. 打开 Cherry Studio 客户端；
2. 进入「小程序 / Mini Apps」管理器；
3. 点击右上角「从网络安装」，输入以下托管清单 URL：
   ```text
   https://duzhilei951.github.io/think-prism/manifest.json
   ```
4. 确认权限授权后即可开箱即用。

### 方式 B：本地离线安装
1. 下载仓库中的 [`think-prism.miniapp`](https://raw.githubusercontent.com/duzhilei951/think-prism/main/think-prism.miniapp)；
2. 在 Cherry Studio 的「小程序」页面中，点击「从本地安装」并选择该文件即可。

---

## 四、项目结构

```text
miniapps/think-prism/
├── icon.png                 # 256x256 高清应用图标
├── index.html               # 纯前端单文件应用（自包含样式、交互与双轨推演引擎）
├── manifest.json            # Cherry Studio 小程序配置清单
├── think-prism.miniapp      # 一键安装包（Zip 规范包）
├── releases/                # 历史版本发布包
│   └── 1.0.0/
│       └── think-prism.miniapp
└── README.md                # 本说明文档
```
