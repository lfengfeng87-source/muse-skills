---
name: implement
description: 按照一份规格说明或一组工单，把其中描述的工作实现出来时使用。
---

中文名：按单实现（机器标识 implement）
来源：改编自 FeatherHunter/dsh-mattpocock-skills-deck 的中文版技能（原技能集作者 Matt Pocock，本库 MIT 许可证）。

# 按单实现

把用户在规格说明或工单里描述的工作实现出来。

如果用户递来的是一个工单引用，先从议题跟踪器（GitHub Issues 或本地文件，按 setup-matt-pocock-skills 技能的配置）把它取回来，并在动手之前说明它的标题。如果这个引用指代不明，就先问清楚。

尽可能在事先约定好的接缝处，用 tdd 技能测试先行地实现。

过程中定期跑类型检查，定期跑单个测试文件，最后完整跑一遍整个测试套件。

做完之后，用 code-review 技能评审这次的工作。

把工作提交到当前分支。
