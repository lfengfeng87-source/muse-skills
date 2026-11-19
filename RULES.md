# 存放与自动整理规则

1. 以后新建的自定义技能，源文件统一存入本仓库 `skills/<kebab-case-技能名>/SKILL.md`，同时在 Muse 本地 `~/workspace/custom-skills/` 保留可用副本。
2. 文件夹名用英文 kebab-case，SKILL.md 标题和说明可用中文。
3. 每次新建、改名、停用技能，同步更新 INDEX.md。
4. 技能带脚本时，脚本放在该技能文件夹内，不散落到其他目录。
5. 不在技能文件中存放密码、API Key、令牌等秘密；需要凭证时走 Muse 安全存储。
6. 推送到 GitHub 前检查一遍文件清单，避免把本地缓存和临时文件带进去（见 .gitignore）。
