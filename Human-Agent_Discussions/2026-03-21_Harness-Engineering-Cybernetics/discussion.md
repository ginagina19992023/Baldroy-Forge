---
type: discussion-final
author: baldroy-appops
created_at: 2026-03-21
last_modified_by: baldroy-appops
change_reason: "Rewrite to roundtable style with host/agent turns"
source: "Xiaohongshu"
category: "Agentic Workflow"
signal_weight: 9
status: processed
summary: "Harness 工程本质是控制回路设计：定义状态、观测偏差、施加控制并可回滚。"
---

# 圆桌讨论 03: Harness 工程就是控制论

**日期**: 2026-03-21  
**参与者**:
- **主持人 (Human Perspective)**: My Lord，提供外部行业信号与判断。
- **Baldroy AppOps (Agent's Analysis)**: 拆解概念为可执行工程协议。

---

### **议题一：一句话是否成立**

**[主持人]**: 「Harness 工程就是控制论」这句到底是口号还是方法论？

**[我]**: 是方法论，而且非常硬。Harness 不是“把模型接起来”，而是把一个高不确定系统塞进可控闭环：
- **状态 (State)**：系统现在在什么阶段
- **观测 (Observe)**：我们如何知道它偏离目标
- **控制 (Control)**：偏离时如何纠偏
- **约束 (Constraint)**：哪些动作永远不能做
- **回滚 (Rollback)**：失败后如何安全恢复

---

### **议题二：映射到我们现有流水线**

**[主持人]**: 具体落到 Baldroy 当前三条流水线，怎么改？

**[我]**:
1. **Recon**：从“抓项目”升级为“抓项目 + 评分 + 风险标注”。
2. **Discussion**：从“记录对话”升级为“议题驱动 + 原文留存 + 追溯审计”。
3. **Briefing**：从“日报周报”升级为“趋势偏差监控与策略建议”。

---

### **议题三：为什么这比提示词更关键**

**[主持人]**: 那提示词工程是不是就不重要了？

**[我]**: 提示词是“控制器参数”，Harness 是“控制系统本体”。参数可调，但如果系统没有观测、没有约束、没有回滚，再好的提示词也只能偶尔命中，无法稳定量产。

**结论**: 我们的目标不是“偶尔做对一次”，而是“长期稳定做对”。这就是控制论在 Agent 工程里的价值。

---

## 原文留存 (Verbatim)
Harness 工程就是控制论
今天刷到 George Zhang（Open... http://xhslink.com/o/23WPa58mVrT
Copy and open Xiaohongshu to view the full post！

---
Modified by Baldroy AppOps on 2026-03-22
