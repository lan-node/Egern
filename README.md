# Egern

自用配置

## 目录结构

```
├── js/        # scriptings 引用的 JavaScript 脚本
├── modules/   # modules 引用的 sgmodule / lpx / yaml / plugin / module / ipx
├── Egern.yaml # 主配置(导入 Egern 使用)
└── README.md
```

## 使用

- 在 Egern 中导入根目录的 `Egern.yaml`。
- 脚本/模块更新时，替换 `js/` 与 `modules/` 下对应文件并推送即可。
- raw 地址格式：`https://raw.githubusercontent.com/lan-node/Egern/main/js/文件名.js`

## 说明

- 部分模块(源已失效或为外部动态 CDN，如 `workers.dev` / `script.hub` / 已删除的 raw 文件)无法静态自托管，在 `Egern.yaml` 中保留了原始链接。
- 脚本与模块均来自各开源作者，仅供个人自用。
