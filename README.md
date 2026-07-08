# 文献速递工作台 v0.8

文献速递制作工具（Design by mohaixin22），支持从期刊目录页一键提取文章、批量翻译、格式化输出。

## 在线使用

👉 [点击打开工具 v0.8](https://mohaixin22-byte.github.io/-/)

> 也可下载 `index.html` 到本地，用 Chrome / Edge 打开直接使用，无需安装任何软件。

## 功能介绍

**① 期刊配置**：选择目标期刊（JAMS / JM / JMR / JCR / MS / PM / MISQ / JCP / ISR），填写卷期信息和采编团队。

**② 录入文章**：智能识别粘贴内容类型，支持四种导入方式：
- 自动识别：粘贴 HTML 源码 / JSON 数组 / 编号列表 / 书签提取内容，无需手动选择
- 配合书签工具在文章页面一键复制标题 + 作者 + 摘要

**③ 翻译**：生成专业提示词（含营销/IS学科术语规范）→ 发给任意 AI → 将结果粘贴回工具自动导入，无需 API。

**④ 预览输出**：生成标准文献速递格式，支持分节复制（完整 / 头部 / 目录 / 摘要），并可导出 Markdown 或 TXT 文件。

## 书签工具使用流程

1. 在工具「录入文章」页面，将两个书签拖到浏览器书签栏
2. 打开期刊目录页 → 点击「目录提取器」→ 复制到工具「智能导入」
3. 逐篇打开文章页面 → 点击「文章提取器」→ 粘贴到工具「智能导入」

## 支持期刊

| 缩写 | 全称 | 级别 | 出版商 |
|------|------|------|--------|
| JAMS | Journal of the Academy of Marketing Science | FT 50 | Springer |
| JM | Journal of Marketing | UTD 24 | SAGE |
| JMR | Journal of Marketing Research | UTD 24 | SAGE |
| JCR | Journal of Consumer Research | UTD 24 | OUP |
| MS | Marketing Science | UTD 24 | INFORMS |
| PM | Psychology & Marketing | ABS 3 | Wiley |
| MISQ | MIS Quarterly | UTD 24 | MISQ |
| JCP | Journal of Consumer Psychology | ABS 4 | Wiley |
| ISR | Information Systems Research | UTD 24 | INFORMS |

## 注意事项

- 数据存储在本地浏览器，各人互不干扰
- 翻译需配合任意 AI 对话使用（Claude / ChatGPT / DeepSeek 均可），工具会自动生成专业提示词
- 书签在不同期刊网站的兼容性不同，如遇抓取失败可手动粘贴内容

## v0.8 更新内容

**新增**
- 粘贴内容自动识别类型，无需手动选择解析方式
- 摘要质量自动检测（过短 / 疑似未截断 / 未以句号结尾）
- 撤销 / 恢复功能，最多保留 20 步历史
- 翻译进度条实时显示
- 翻译提示词升级，加入营销 & IS 学科术语规范
- 解析器容错增强，AI 格式轻微偏差时仍可正确导入
- 支持导出 Markdown / TXT 文件
- 分节复制（完整 / 头部 / 目录 / 摘要）
- 历史记录面板，最多保存 10 条，支持一键加载

**修复**
- 修复进度条在文章数为 0 时的报错
- 文章列表展开 / 收起交互优化
