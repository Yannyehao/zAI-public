# 模块地图

此页是截至 2026-09-10 的公开职责快照。模块名称对应私有系统；点击名称进入同名文件夹，每个目录有独立 README，不包含私有源码。

| 模块 | 输入与职责 | 产物大类 | 状态 |
|---|---|---|---|
| [zpipeline](../zpipeline/README.md) | 同步并处理个人资料 | 文稿与同步状态 | 已有实现 |
| [zdocs](../zdocs/README.md) / [ztxt](../ztxt/README.md) | 组织文稿和文本镜像 | 可索引文本 | 已有实现 |
| [zsearch](../zsearch/README.md) | 对文本建立全文索引 | 检索结果 | 已有实现 |
| [zrag](../zrag/README.md) | 本地向量化、检索与问答 | 回答和来源列表 | 已有实现 |
| [zclip](../zclip/README.md) | 分阶段处理录播，人工审阅与验收 | 学习笔记和剪辑产物 | 已有流程，持续完善 |
| [zdownload](../zdownload/README.md) | 获取盘后行情 | 行情数据与运行状态 | 维护中 |
| [zradar](../zradar/README.md) | 扫描、分析、归档与候选跟踪 | 候选卡、复盘页、状态记录 | 运行维护与能力迭代 |
| [zgui](../zgui/README.md) | 聚合健康状态、提供诊断 | 本地运维页面与状态信息 | 维护中 |
| [zai_shared](../zai_shared/README.md) | 复用启动、状态等通用逻辑 | 共享基础能力 | 已有实现 |
| [zboard](../zboard/README.md) | 从已有记录组织项目看板 | 项目汇总与指标证据 | 已有实现，持续迭代 |

技术构成包括 Python、Meilisearch、BGE-M3、Chroma、LLM 问答、FastAPI 与 Windows 任务调度；部分向量化工作在本地 GPU 上完成。具体配置、凭证与部署路径不公开。

历史上的 [zsummary](../zsummary/README.md) 已并入视频学习工作流，不重复包装成新增能力。[zdict](../zdict/README.md) 和 [zanki](../zanki/README.md) 是规划占位，不计入已有能力。方向见[路线图](roadmap.md)。

阅读：[学习与运维架构](architecture.md) · [交易辅助](trading.md)
