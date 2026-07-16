文献速递工作台 v1.0
文献速递制作工具（Design by mohaixin22），支持从期刊目录页一键提取文章、批量翻译、一键导出格式化 Word 文档。
在线使用
👉 点击打开工具 v1.0

也可下载 index.html 到本地，用 Chrome / Edge 打开直接使用，无需安装任何软件。

功能介绍
① 期刊配置：选择目标期刊（JAMS / JM / JMR / JCR / MS / PM / MISQ / JCP / ISR），填写卷期信息和采编团队。
② 录入文章：智能识别粘贴内容类型，支持多种导入方式：

自动识别：粘贴 HTML 源码 / JSON 数组 / 编号列表 / 书签提取内容，无需手动选择
配合书签工具在文章页面一键复制标题 + 作者 + 摘要

③ 翻译：生成专业提示词（含营销 / IS 学科术语规范）→ 发给任意 AI → 将结果粘贴回工具自动导入，无需 API。
④ 预览输出：生成标准文献速递格式，可复制到剪贴板，或一键导出 Word（.docx） / Markdown 文件。
✨ 一键导出 Word（v1.0 核心功能）
告别手动排版！点击「导出 Word」即可下载排版完成的 .docx，所有格式自动套用，打开即成品：

页面：A4，上下边距 2.54cm、左右边距 3.17cm
中英文双字体：西文 Times New Roman，中文宋体 / 微软雅黑，分别精确指定
字号 / 行距：标题 16.5pt、正文 12pt、节标题 14pt；多倍行距（1.2 / 1.5 倍）舒展不拥挤
颜色体系：节标题深藏蓝 #1F4E79、目录 / 标题中蓝 #315EA3、摘要编号深红 #C00000，一键着色
智能分段：目录、摘要区自动编号，「作者 / Abstract / 摘要」标签着色加粗、正文黑色，层次分明


导出基于纯前端 docx.js，无需服务器、无需上传，数据全程留在本地浏览器。

书签工具使用流程

在工具「录入文章」页面，将两个书签拖到浏览器书签栏
打开期刊目录页 → 点击「目录提取器」→ 复制到工具「智能导入」
逐篇打开文章页面 → 点击「文章提取器」→ 粘贴到工具「智能导入」

支持期刊
缩写全称级别出版商JAMSJournal of the Academy of Marketing ScienceFT 50SpringerJMJournal of MarketingUTD 24SAGEJMRJournal of Marketing ResearchUTD 24SAGEJCRJournal of Consumer ResearchUTD 24OUPMSMarketing ScienceUTD 24INFORMSPMPsychology & MarketingABS 3WileyMISQMIS QuarterlyUTD 24MISQJCPJournal of Consumer PsychologyABS 4WileyISRInformation Systems ResearchUTD 24INFORMS
注意事项

数据存储在本地浏览器，各人互不干扰
翻译需配合任意 AI 对话使用，工具会自动生成专业提示词
书签在不同期刊网站的兼容性不同，如遇抓取失败可手动粘贴内容
首次导出 Word 需联网加载排版库（docx.js），之后浏览器会自动缓存

v1.0 更新内容
新增

🎯 一键导出 Word（.docx）：精确还原文献速递排版规范——A4 页边距、中英文双字体、字号行距、多色着色、智能分段，导出即成品，无需再手动排版
页眉标注作者署名（Design by mohaixin22）

优化

期刊配置页改为均衡的 3×3 卡片网格，视觉更清爽大方
预览输出精简：专注「完整输出」，导出方式聚焦 Word / Markdown
界面精简：移除撤销 / 恢复按钮，保留一键重置
首页移除重复的书签工具（保留在「录入文章」页）
月份统一为阿拉伯数字显示（预览与 Word 输出一致）

修复

移除摘要「疑似未截断（>800字）」的误报（学术长摘要属正常）
摘要区文章编号与标题之间不再有多余空格

历史版本
<details>
<summary>v0.8 更新内容</summary>
新增

粘贴内容自动识别类型，无需手动选择解析方式
摘要质量自动检测（过短 / 未以句号结尾）
撤销 / 恢复功能，最多保留 20 步历史
翻译进度条实时显示
翻译提示词升级，加入营销 & IS 学科术语规范
解析器容错增强，AI 格式轻微偏差时仍可正确导入
支持导出 Markdown / TXT 文件
分节复制（完整 / 头部 / 目录 / 摘要）
历史记录面板，最多保存 10 条，支持一键加载

修复

修复进度条在文章数为 0 时的报错
文章列表展开 / 收起交互优化
