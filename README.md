<div align="center">
  <h1>智能体环境工程手册</h1>
  <p><strong>Agentic Environment Engineering Handbook</strong></p>
  <p>从 Prompt、Context、Harness 与 Loop，到环境建模、合成、评测、协同演化和生产运行时治理。</p>
  <p><code>单文件 HTML</code> · <code>中文</code> · <code>MIT License</code></p>
</div>

<hr>

<h2>定位</h2>
<p>这是一份中文研究型手册，梳理 AI 工程控制面从 Prompt、Context、Harness 与 Loop，逐步外扩到完整 Agent 环境的过程。精确术语 <strong>Agentic Environment Engineering</strong> 已出现在 2026 年研究综述，相邻术语也见于 EurekAgent 论文与实现，但目前仍不是行业标准。</p>
<ul>
  <li>区分模型厂商的官方定义、团队工程案例与开放协议；</li>
  <li>区分原始论文、预印本、开源实现和实践者观点；</li>
  <li>区分生产运行环境与训练、评测使用的模拟环境。</li>
</ul>

<h2>手册包含</h2>
<ul>
  <li>Prompt → Context → Harness → Loop → Environment 的概念地图；</li>
  <li>POMDP 形式化、八个环境属性轴与八个应用领域；</li>
  <li>Symbolic / Neural 环境合成与四维环境质量评测；</li>
  <li>四条 Agent 演化路径与三条环境演化路径；</li>
  <li>生产环境原语、运行时状态、权限、评估和人工接管；</li>
  <li>18 条可公开访问的分级来源与术语边界说明。</li>
</ul>

<h2>本地查看</h2>
<p>无需安装依赖。直接在浏览器中打开 <code>index.html</code> 即可：</p>
<pre><code>git clone &lt;你的仓库地址&gt;
cd agentic-environment-engineering-handbook
open index.html</code></pre>

<h2>发布到 GitHub Pages</h2>
<p>仓库已包含 <code>.github/workflows/pages.yml</code>。将内容推送到 <code>main</code> 分支后，在 GitHub 仓库的 Pages 设置中选择 <strong>GitHub Actions</strong> 作为部署源即可。工作流会发布仓库根目录中的静态站点。</p>

<h2>项目结构</h2>
<pre><code>agentic-environment-engineering-handbook/
├── index.html                 # 手册主体：样式、交互与内容均内嵌
├── README.md                  # GitHub 首页说明（使用 HTML 编写）
├── LICENSE                    # MIT 协议
├── .gitignore
└── .github/
    └── workflows/
        └── pages.yml          # GitHub Pages 自动部署</code></pre>

<h2>引用与贡献</h2>
<p>欢迎补充一手资料、修正来源链接或完善概念边界。涉及事实性结论的修改，请附原始论文、模型厂商官方文档或作者原文；不要只引用二次解读。</p>

<p><sub>整理时间：2026 年 7 月。第三方文章、论文与产品资料的版权归原作者所有。</sub></p>
