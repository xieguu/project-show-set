# 其它项目存储区

这里用于存放简历之外的其它项目，每个项目使用一个独立目录。

## 新增项目规范

复制 `project-template/`，重命名为项目英文短名，例如：

```text
projects/
├── project-template/
├── project-a/
│   ├── README.md
│   ├── demo/       # 视频、GIF 或在线演示说明
│   ├── docs/       # 项目文档、截图
│   └── assets/     # 图片、封面等静态资源
└── project-b/
```

项目 README 建议固定包含：项目简介、技术栈、源码地址、在线演示、视频地址、文档地址和运行方式。

## 预留项目地址

| 项目 | 源码地址 | 在线演示 | 视频 / 文档 | 状态 |
| --- | --- | --- | --- | --- |
| 项目 A | `PROJECT_A_REPO_URL` | `PROJECT_A_DEMO_URL` | `PROJECT_A_MEDIA_URL` | 待补充 |
| 项目 B | `PROJECT_B_REPO_URL` | `PROJECT_B_DEMO_URL` | `PROJECT_B_MEDIA_URL` | 待补充 |
| 项目 C | `PROJECT_C_REPO_URL` | `PROJECT_C_DEMO_URL` | `PROJECT_C_MEDIA_URL` | 待补充 |

将占位符替换为真实链接后，再同步更新根目录 `README.md` 和 `docs/index.html` 的项目卡片。
