# Roadmap

| 里程碑 | 目标 | 状态 | 依赖 | 模块文档 | 退出标准 |
| --- | --- | --- | --- | --- | --- |
| M0 | 完成 GitHub 个人主页首版视觉和内容改版 | 已完成 | 无 | [GitHub 个人主页](模块设计/GitHub个人主页.md) | README 在 GitHub 正常渲染，横幅与图片可加载，项目入口有效 |
| M1 | 像素风小狐狸横版闯关动态 SVG + 无 emoji 自然排版重构 | 已完成 | M0 | [GitHub 个人主页](模块设计/GitHub个人主页.md) | 昼夜双主题像素动画 SVG 通过 XML 校验，Light / Dark 渲染正常，2×2 项目表格与单张 TokenBoard 卡片干净对齐 |

## 当前进度

M1 已完成。主页顶部已替换为昼夜自适应的小狐狸像素风横版闯关动画（`assets/fox-stage-light.svg` / `assets/fox-stage-dark.svg`），正文去除全部 emoji 与模板化口号，代表项目升级为 `NextDevTpl`、`CloudMind`、`SMem`、`DeverDesk` 对称 2×2 矩阵，底部精简为单张 `TokenBoard` 实时卡片。
