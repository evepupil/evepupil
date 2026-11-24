# Roadmap

| 里程碑 | 目标 | 状态 | 依赖 | 模块文档 | 退出标准 |
| --- | --- | --- | --- | --- | --- |
| M0 | 完成 GitHub 个人主页首版视觉和内容改版 | 已完成 | 无 | [GitHub 个人主页](模块设计/GitHub个人主页.md) | README 在 GitHub 正常渲染，横幅与图片可加载 |
| M1 | 瑞士网格 × 包豪斯像素海报风重构（对齐 smem.chaosyn.com 视觉语言） | 已完成 | M0 | [GitHub 个人主页](模块设计/GitHub个人主页.md) | 全部 22 张双主题像素海报 SVG 通过 XML 校验，Light / Dark 渲染无文字溢出，2×2 海报卡与单张 TokenBoard 对齐生效 |

## 当前进度

M1 已完成。全页已统一为与 `smem.chaosyn.com` 同源的瑞士包豪斯像素海报风格（克制低频眨眼/光标动效、不刺眼不频闪），涵盖分栏像素大字 + 小狐狸肖像 Hero、直角站点按钮、2×2 编织纹项目海报卡（`NextDevTpl` / `CloudMind` / `SMem` / `DeverDesk`）与单张 `TokenBoard` 卡片。
