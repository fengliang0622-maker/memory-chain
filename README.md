Memory Chain - 六层记忆架构

基于人类记忆科学设计的AI记忆系统，模拟从碎片信息到价值观形成的完整记忆过程。

## 🌟 特性

- 🧠 **6层记忆架构** - 初始记忆 → 情绪记忆 → 场景记忆 → 语义记忆 → 自我认知 → 价值观
- 🔗 **自动关联** - 发现并链接相关记忆
- 🏷️ **智能分类** - 自动识别内容类型打标签
- 🔍 **语义检索** - 快速调取记忆
- 📝 **摘要生成** - 结构化整理记忆
- 💬 **对话归档** - 自动提取对话关键信息

## 📁 目录结构



      

memory-chain/
├── SKILL.md
├── scripts/
│   ├── memory_chain.py
│   ├── cli.py
│   ├── auto_archive.py
│   └── session_tracker.py
└── references/
    ├── schema.md
    └── examples.md


      


## 🚀 快速开始

```python
from scripts.memory_chain import MemoryChain

mc = MemoryChain()
mc.add_memory(content="今天学到了", layer=1, tags=["学习"])
results = mc.search("学习")


      



⚡ 自动触发



会话结束关键词（再见/拜拜/晚安）

1小时无对话

每天0点定时
