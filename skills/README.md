# Skills

存放可复用的 AI skills，每个 skill 使用一个独立目录。

建议结构：

```text
skills/
└── <skill-name>/
    ├── SKILL.md
    ├── scripts/       # 可选：辅助脚本
    ├── references/    # 可选：参考资料
    └── assets/        # 可选：模板或资源
```

`SKILL.md` 用于记录名称、用途、适用场景和执行步骤；具体格式与安装方式遵循使用该 skill 的工具规范。

添加 skill 时，一并记录依赖项、所需配置和使用示例。
