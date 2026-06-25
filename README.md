# Paper Knowledge Base

结构化文献知识卡片库 — AI 可查询的论文深度评析

## 结构

```
paper-knowledge/
├── index.html           # 人类可读首页
├── CNAME                # yakeworld.github.io
├── cards/
│   ├── index.json       # AI 查询索引
│   ├── {doi}.yaml       # 单篇知识卡片
│   └── ...
```

## 查询协议

- `GET /cards/index.json` → 全库索引
- `GET /cards/{doi}.yaml` → 单篇卡片
- 卡片 YAML 包含5模块：写作质量 / 实验设计 / 结果提取 / 引用质量 / 活卡片

## 使用规则

- ✅ 知识提取和结构化可安全复用
- ✅ 已验证数值可直接引用
- ❌ 不分发原始 PDF 全文
