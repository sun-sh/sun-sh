<div align="center">

<h1>Agent / LLM Engineer</h1>

<p>独立构建 Agent 系统，也参与成熟开源项目演进。</p>

<p>
  <a href="mailto:1665738773@qq.com">
    <img src="https://img.shields.io/badge/Open_to_Work-Agent_Roles-2ea44f?style=for-the-badge" alt="正在寻找 Agent 相关工作" />
  </a>
  <a href="mailto:1665738773@qq.com">
    <img src="https://img.shields.io/badge/Email-1665738773%40qq.com-d14836?style=for-the-badge" alt="邮箱：1665738773@qq.com" />
  </a>
</p>

<p>
  <a href="https://github.com/search?q=author%3Asun-sh+is%3Apr+is%3Amerged+repo%3Abytedance%2Fdeer-flow+repo%3ATencent%2FWeKnora&amp;type=pullrequests">
    <img src="https://img.shields.io/github/issues-search?query=author%3Asun-sh%20is%3Apr%20is%3Amerged%20repo%3Abytedance%2Fdeer-flow%20repo%3ATencent%2FWeKnora&amp;label=Merged%20PRs&amp;color=2ea44f&amp;style=flat-square" alt="两个项目中已合并的 PR 总数" />
  </a>
  &nbsp;·&nbsp; 1 个独立项目&nbsp;&nbsp;·&nbsp;&nbsp;2 个开源项目贡献
</p>

</div>

---

## 个人项目

### Atlas BI · 企业级电商 NL2SQL 分析平台

<p>
  <a href="https://github.com/sun-sh/atlas-bi-nl2sql"><strong>sun-sh/atlas-bi-nl2sql</strong></a>
  &nbsp;
  <a href="https://github.com/sun-sh/atlas-bi-nl2sql/actions/workflows/ci.yml">
    <img src="https://github.com/sun-sh/atlas-bi-nl2sql/actions/workflows/ci.yml/badge.svg" alt="Atlas BI CI" />
  </a>
</p>

**用一句话查经营数据，从问题到 SQL、结果与分析依据。**

独立实现电商数据分析工作台，以 LangGraph 串联 Schema 混合检索、SQL 生成与失败自修复；通过 AST 校验和只读执行控制查询边界，支持流式解读、连续追问与查询追踪。

<p>
  <a href="https://github.com/sun-sh/atlas-bi-nl2sql/blob/main/docs/ARCHITECTURE.md">架构设计</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/sun-sh/atlas-bi-nl2sql/blob/main/docs/EVALUATION.md">评测说明</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/sun-sh/atlas-bi-nl2sql">查看项目 →</a>
</p>

<p align="center">
  <a href="https://github.com/sun-sh/atlas-bi-nl2sql">
    <img src="https://raw.githubusercontent.com/sun-sh/atlas-bi-nl2sql/main/docs/atlas-stream-final.png" alt="Atlas BI 分析工作台" width="760" />
  </a>
</p>

**评测结果：** 项目自建 100 条严格模型用例 **100/100 通过**（2026-10-27，固定数据集与当次模型配置）；要求模型生成 SQL 并完成结果解读。

---

## 开源贡献

### DeerFlow

<p>
  <a href="https://github.com/bytedance/deer-flow"><strong>bytedance/deer-flow</strong></a>
  &nbsp;
  <a href="https://github.com/bytedance/deer-flow">
    <img src="https://raw.githubusercontent.com/sun-sh/sun-sh/main/assets/stars/deer-flow.svg" alt="DeerFlow Stars" />
  </a>
  <a href="https://github.com/bytedance/deer-flow/pulls?q=is%3Apr+is%3Amerged+author%3Asun-sh">
    <img src="https://img.shields.io/github/issues-search?query=repo%3Abytedance%2Fdeer-flow%20is%3Apr%20is%3Amerged%20author%3Asun-sh&amp;label=Merged%20PRs&amp;color=2ea44f&amp;style=flat-square" alt="DeerFlow 已合并 PR 数" />
  </a>
</p>

针对 Skill 扫描中可执行文件漏检、项目上传取消后资源清理不完整的问题，完善二进制识别与异步清理流程，并补充边界回归测试；修复已合并至主线。

[查看全部已合并 PR →](https://github.com/bytedance/deer-flow/pulls?q=is%3Apr+is%3Amerged+author%3Asun-sh)

### WeKnora

<p>
  <a href="https://github.com/Tencent/WeKnora"><strong>Tencent/WeKnora</strong></a>
  &nbsp;
  <a href="https://github.com/Tencent/WeKnora">
    <img src="https://raw.githubusercontent.com/sun-sh/sun-sh/main/assets/stars/weknora.svg" alt="WeKnora Stars" />
  </a>
  <a href="https://github.com/Tencent/WeKnora/pulls?q=is%3Apr+is%3Amerged+author%3Asun-sh">
    <img src="https://img.shields.io/github/issues-search?query=repo%3ATencent%2FWeKnora%20is%3Apr%20is%3Amerged%20author%3Asun-sh&amp;label=Merged%20PRs&amp;color=2ea44f&amp;style=flat-square" alt="WeKnora 已合并 PR 数" />
  </a>
</p>

围绕 Agent 与 RAG 链路，修复流式重试残留、跨知识库 Embedding 维度混用、UTF-8 截断和文件处理问题；补充知识图谱任务 panic 保护与仅手动维护的知识库模式，并优化文档来源定位性能，其中 7 个贡献已进入 v0.9.0 发布版本，相关改动已合并至主线。

> **文档来源定位：约 395ms → 10.4ms**<br />
> 将重复全文扫描改为单次扫描构建匹配索引。数据来自本地单次微基准测试，输入为 2,000 行、7 列的 CSV 形态数据。

[查看全部已合并 PR →](https://github.com/Tencent/WeKnora/pulls?q=is%3Apr+is%3Amerged+author%3Asun-sh)

---

<div align="center">

正在寻找 <strong>Agent 相关工作</strong>，欢迎联系。

<a href="mailto:1665738773@qq.com">1665738773@qq.com</a>

</div>
