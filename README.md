# 🌍 人类知识提取开源计划

> **Synthos 技能**: `paper-knowledge-base` v2.0  
> 将每一篇认真读过的论文，变成AI可以直接查询的结构化知识

## 核心理念

**一次分析，任意AI复用。**

AI不应该重复劳动——每篇论文被认真分析一次后，生成结构化知识卡片，其他AI直接查询即可。无需重新下载、重新阅读、重新理解。

## 卡片结构（8章节全文级复现）

每张卡片36KB YAML，覆盖论文全文：

| 章节 | 内容 |
|:-----|:------|
| ① 摘要 | 完整分析性重述，标注关键数值 |
| ② 引言 | 逐段CARDS分析 + 全文复现 |
| ③ 结果 | 全部子节 + 全部表格数据 |
| ④ 讨论 | 理论体系分析 + 更优表达建议 |
| ⑤ 方法 | 模型/数据/训练/统计完整复现 |
| ⑥ 补充数据 | 混淆矩阵/读者表等结构化 |
| ⑦ 引用分析 | 四层功能框架评估 |
| ⑧ 活卡片 | 论文发表至今的进展追踪 |

## AI查询协议

```bash
# 查询所有卡片
curl -sL https://yakeworld.github.io/paper-knowledge/cards/index.json

# 查询单篇卡片（0.6秒返回36KB结构化数据）
curl -sL https://yakeworld.github.io/paper-knowledge/cards/10.1038_s41586-019-1799-6.yaml
```

## 版权合规

全文以分析性重述呈现，不复制原文，基于《著作权法》第二十二条合理使用。

## 当前卡片

| 论文 | 大小 | 章节 | 数值 |
|:-----|:----:|:----:|:----:|
| McKinney et al. (2020) Nature | 36KB | 8 | 12 |

## 相关链接

- **平台**: [Synthos](https://github.com/yakeworld/Synthos) — 自进化科研平台
- **技能**: `paper-knowledge-base` v2.0
- **仓库**: https://github.com/yakeworld/paper-knowledge
- **在线查询**: https://yakeworld.github.io/paper-knowledge/
