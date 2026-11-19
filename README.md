# muse-skills

吴发的 Muse 自定义技能仓库。

## 用途
- 统一存放以后创建的所有自定义技能
- 每个技能一个文件夹，放在 `skills/<技能名>/` 下，必须包含 `SKILL.md`
- 自动整理：新建技能时同步更新 `INDEX.md` 索引（名称、用途、创建日期、状态）

## 结构
- `skills/` — 正式技能
- `templates/skill-template/` — 新技能模板
- `archive/` — 已停用技能
- `INDEX.md` — 技能总索引
- `RULES.md` — 存放与整理规则

## 状态说明
- active：正在使用
- draft：草稿，未启用
- archived：已停用，移到 archive/
