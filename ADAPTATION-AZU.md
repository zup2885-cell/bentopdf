# 阿祖 PDF 工具 · 适配说明

2026-11-11：基于本仓库现有 BentoPDF 2.8.11 源码，使用上游的 Simple Mode 和 GitHub Pages 部署流程。

修改包括：中文品牌名、静态 A 标识、页脚来源与完整源码链接。保留原有工具实现、翻译、版权与 LICENSE。完整适配源码以本仓库默认分支为准，按 AGPL-3.0 提供。

构建：`SIMPLE_MODE=true BASE_URL=/bentopdf SITE_URL=https://zup2885-cell.github.io/bentopdf ALLOW_INDEXING=true npm run build`。

GitHub Pages 的内容来自本账号的构建结果，不是把官方网页嵌入进来。PDF 处理在浏览器执行；部分大型处理组件与 OCR 语言包仍根据上游配置按需下载，不能承诺完全离线。PDF 合并、拆分等具体功能需分别验收，不把首页可打开当作全部功能测试通过。

上游：https://github.com/alam00000/bentopdf 。原始 README 保留在本仓库说明的下方；许可证见 LICENSE。
