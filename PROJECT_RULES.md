用户偏好
- 解释与步骤用中文
- 安装位置为项目级：D:\4Environment\OpenCode\claude-scientific-skills-geo\.claude\skills

命名与目录规范
- 项目治理文件固定为 PROJECT_OVERVIEW.md、PROJECT_PROGRESS.md、PROJECT_RULES.md
- 技能目录保持原仓库命名（英文）以确保兼容

下载与安装规范
- 使用 git sparse-checkout 仅下载选定目录
- 不下载不相关学科的技能
- 安装完成后仅保留选定目录于项目级 .claude/skills

测试与验证
- 以“目录存在性 + 文件清单可读”为最小验收
- 若需依赖安装，再按具体 SKILL.md 提示执行

提交约定
- 本项目不默认执行 git commit；如需提交，先由用户指定版本名称
