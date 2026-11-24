# GitHub 个人主页模块

- **模块定位**：延续 `smem.chaosyn.com` 的瑞士网格 × 包豪斯几何像素海报风格，在克制不闪烁的前提下统一展示个人身份、小狐狸像素肖像、2×2 旗舰项目海报卡与 TokenBoard 遥测数据。
- **对应代码**：[`README.md`](../../README.md)、[`assets/`](../../assets/)、[`PRODUCT.md`](../../PRODUCT.md)、[`DESIGN.md`](../../DESIGN.md)
- **当前状态**：已完成
- **最近更新时间**：2026-11-24

## 核心构成

1. **分栏像素海报 Hero（`assets/hero-*.svg`）**：
   - 左栏采用与 `smem.chaosyn.com` 同源的 **9 行粗体几何像素大字 `EVEPUPIL`**、双行领域与语言栈说明，以及带柔和慢闪光标的 `$` 终端栏；
   - 右栏铺设标志性的 **Orchid 粉紫正交 `+` 像素编织底纹**（深色模式转为沉稳暗紫），居中带硬边像素阴影的 **28×28 头像小狐狸几何像素肖像框**（每 5.2 秒平静眨眼一次，支持 `prefers-reduced-motion`）；
   - 底部四栏以 9 行像素数字呈现 `04`（主力系统）、`66`（公开仓库）、`91B`（AI Tokens）、`MCP`（本地与边缘栈）。
2. **直角方框快捷入口（`assets/btn-*.svg`）**：前置 `chaosyn.com`、`blog.chaosyn.com`、`smem.chaosyn.com` 与 `@evepupil` 知乎入口。
3. **无边框干扰的 2×2 像素编织项目海报卡（`assets/card-*.svg`）**：
   - `NextDevTpl`（电光蓝十字编织）、`CloudMind`（翡翠绿格纹编织）、`SMem`（兰花粉 `+` 编织）、`DeverDesk`（琥珀黄篮纹编织）各自配有专属 `16×16` 几何像素徽标、直角黑底编号签与技术规格栏，两两并排占满版心，彻底摆脱 GitHub 默认灰框表格的简陋感。
4. **单卡遥测收尾（`TokenBoard`）**：以同风格 `(telemetry)` 像素分隔条引出原生清晰尺寸（`520px`）的 `TokenBoard` 卡片。
