# 文献速递工作台

重庆大学经管院邵兵家网商研究中心课题组文献速递制作工具（Design by mohaixin22），支持从期刊目录页一键提取文章、批量翻译、格式化输出。

## 在线使用

👉 [点击打开工具]( https://mohaixin22-byte.github.io/-/)

> 也可下载 `index.html` 到本地，用 Chrome / Edge 打开直接使用，无需安装任何软件。

## 功能介绍
① 期刊配置：选择目标期刊（JAMS / JM / JMR / JCR / MS / PM / MISQ / JCP / ISR），填写卷期信息和采编团队。

② 录入文章：支持三种方式导入文章：
- 批量导入：粘贴编号列表或 JSON 数组，一键解析
- 解析HTML目录：粘贴期刊目录页源码，自动提取标题
- 逐篇粘贴书签：配合书签工具，在每篇文章页面一键复制标题 + 作者 + 摘要

③ 翻译：生成结构化提示词 → 发给 Claude 翻译 → 将结果粘贴回工具自动导入，无需 API。

④ 预览输出：一键生成标准文献速递格式文本（中英双语目录 + 摘要区），直接复制使用。

## 书签工具使用流程

1. 在工具"录入文章"页面，将目录提取器和文章提取器两个书签拖到浏览器书签栏
2. 打开期刊目录页 → 点击「目录提取器」→ 复制到工具「批量导入」
3. 逐篇打开文章页面 → 点击「文章提取器」→ 粘贴到工具「逐篇粘贴书签」

## 支持期刊

| 缩写 | 全称 | 出版商 |
|------|------|--------|
| JAMS | Journal of the Academy of Marketing Science | Springer |
| JM | Journal of Marketing | SAGE |
| JMR | Journal of Marketing Research | SAGE |
| JCR | Journal of Consumer Research | OUP |
| MS | Marketing Science | INFORMS |
| PM | Psychology & Marketing | Wiley |
| MISQ | MIS Quarterly | MISQ |
| JCP | Journal of Consumer Psychology | Wiley |
| ISR | Information Systems Research | INFORMS |

## 注意事项

- 各人数据存储在本地浏览器，互不干扰
- 翻译需配合 Claude 对话使用(其它ai也可以，自行修改prompts)（工具会自动生成提示词）
- 书签在不同期刊网站的兼容性不同，如遇抓取失败可手动粘贴内容


