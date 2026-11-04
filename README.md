<h1 align="center">贾仕遥 · Achieve</h1>

<p align="center"><b>大模型应用开发（Agent / RAG）</b> · 4 年互联网研发经验 · 杭州</p>

<p align="center">
  <a href="mailto:jsy_come_on@163.com"><img src="https://img.shields.io/badge/Email-jsy_come_on@163.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/achieve-jsy"><img src="https://img.shields.io/badge/GitHub-achieve--jsy-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG-6B46C1?style=flat-square"/>
  <img src="https://img.shields.io/badge/Milvus-00A1EA?style=flat-square"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>

---

## 关于我

- 现在：**杭州边锋网络** · AI 应用开发工程师（CTO 直属），负责 AI 中台底座核心模块，从 0 到 1 打造内部标准化 AI 应用开发平台
- 之前：杭州星迈互动 · 高级开发工程师（AI 应用方向）；杭州魔点科技 · Java 开发工程师（基础平台部）
- 方向：**Agent 编排**（LangGraph / ReAct / Planner-Executor-Reviewer）、**RAG 检索与评测**、**大模型工程化**（网关 / 路由 / 观测）、Java & Go 后端与微服务架构
- 习惯：用 TDD / SDD 把 AI 应用从「原型能跑」推到「生产可维护」

## 技术能力

| 方向 | 内容 |
|---|---|
| AI 应用 | LangGraph 多 Agent 编排、ReAct、Planner-Executor-Reviewer、意图槽位治理、多轮任务会话、工具调用编排、vLLM 部署 |
| RAG | 文档解析路由（MarkItDown / MinerU / AnyDocs）、父子块切分、Milvus 向量 + ES 全文 + 知识图谱三路召回、RRF 融合、LLM-as-Judge 评测与 badcase 回流 |
| 后端 | Go / Java / Python；Spring Boot、MyBatis-Plus、Dubbo、FastAPI；分布式事务、分布式锁、线程池与异步编排 |
| 中间件与存储 | MySQL（索引 / 事务 / MVCC / 分库分表）、Redis、Elasticsearch、RabbitMQ、RocketMQ、MQTT、Mycat |
| 工程与运维 | Docker、Nginx、Linux、Langfuse 全链路观测、Arthas 线上排查、CI/CD |
| 前端 | Vue、React、Umi、Element Plus、Ant Design、ECharts |

## 项目亮点

**企业级任务式智能体服务平台（慧办公 · MO 小智）** — LangGraph 会话编排 + 混合检索知识库，落地会议预约、访客登记、语音呼叫等自助任务

- 意图识别准确率 92%+，多轮任务连续率 +18%，任务执行成功率 88%+
- MySQL + ES + Milvus 混合召回，命中率 +15%，首答可用率 85%+
- 多租户知识库分层与路由，支撑 5W+ 租户接入

**企业级 RAG 知识库（Xlib）** — 统一「摄入 → 检索 → 融合 → 引用 → 调用」链路，覆盖制度、游戏规则、SDD 文档、客服等场景

- 解析引擎注册表 + 定向降级，端到端解析成功率 ≥98%，上下文完整性 +30%
- 三路召回 + RRF 融合：Recall@5 +25~40%，NDCG@10 +15%
- 快答 / 精答双路径：P95 ≤ 500ms，结论可溯源；线上答案准确率 70% → 88%+

**魔点智能云平台（权限与会议）** — 一体化智能会议管理平台，服务超万家企业

- RBAC + ABAC 混合权限重构；亿级通讯录敏感字段加密脱敏（拦截器 + TypeHandler，灰度平滑）
- 会议模块 0→1，Mycat 分库分表；钉钉 RDS 回调吞吐 100 → 1000+ QPS

**研发 / 业务管线抽象平台（xflow）** — 流程引擎与制品契约驱动，覆盖 5+ 条业务线

- 新业务流程搭建周期 7 天 → 半天，流程代码重复量下降 65%
- 三重门禁 + 产物双检，AI 跳步拦截率 100%，人工返工率 -50%
- opencode 容器化 Agent 运行时：SSE 事件流驱动、配额与快照回滚、Langfuse 全链路观测

## 开源 / 个人项目

| 项目 | 说明 |
|---|---|
| [llm-gateway](https://github.com/achieve-jsy/llm-gateway) | 统一大模型网关：OpenAI 兼容入口 + 多厂商模型组调度 + 管理台（Go + Vue3） |
| [lan-proxy-gateway](https://github.com/achieve-jsy/lan-proxy-gateway) | 把一台电脑变成整屋的代理网关：mihomo / TUN / 链式代理（Go） |
| [mac_desk_arrangement](https://github.com/achieve-jsy/mac_desk_arrangement) | macOS 多显示器窗口布局管理，一键排列与快照恢复（Tauri + Rust） |
| [monitor_bian](https://github.com/achieve-jsy/monitor_bian) | 币圈合约持仓监控终端（Rust TUI） |
| [nba2kol2_script](https://github.com/achieve-jsy/nba2kol2_script) | NBA 2KOL2 自动化脚本 |

## GitHub 数据

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=achieve-jsy&show_icons=true&hide_border=true&theme=transparent&include_all_commits=true"/>
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=achieve-jsy&layout=compact&hide_border=true&theme=transparent"/>
</p>

---

<p align="center"><i>把复杂的东西收敛成一个干净接口，把踩过的坑变成能直接用的工具。</i></p>