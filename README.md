# 《黎曼假设与狄利克雷 L 函数的广义黎曼假设》中文全译

> *The Riemann hypothesis and GRH for Dirichlet L-functions — A readable account of the Lean proof in Levent Alpöge's archive*（rh-lean-roadmap，2026 年 11 月，1545 页）的**中文全译本**。

本仓库是这部数学书的中文翻译成果：原书正文（页 1–1422）已全部译出，公式经逐页对照原书页面图像核对后重排为 LaTeX；书末 Lean 声明索引保留 Lean 标识符原文、仅译章节标题；参考文献按学术惯例保留原文。

---

## 一、仓库内容

| 文件 | 内容 | 规模 |
| --- | --- | --- |
| [`translation/RiemannHypothesis-and-GRH_zh-CN.pdf`](translation/RiemannHypothesis-and-GRH_zh-CN.pdf) | **中文全译排版本**（A4，公式已排版，含书名页、译者说明、目录、正文、Lean 声明索引、参考文献） | 1 182 页 / 23.3 MB |
| [`translation/RiemannHypothesis-and-GRH_zh-CN.md`](translation/RiemannHypothesis-and-GRH_zh-CN.md) | **中文全译 Markdown 源稿**（LaTeX 公式、定理/引理/证明环境、`[原书 p.N]` 页码锚点） | 约 **90.3 万汉字**（6.5 MB） |
| [`translation/glossary-zh-CN.md`](translation/glossary-zh-CN.md) | **数学术语与语料库**：英→中核心术语约 700 条 + 各章新增术语汇总约 3 300 条（合计约 4 000 条） | 0.14 MB |
| [`translation/translation-notes.md`](translation/translation-notes.md) | 交付说明：文件清单、翻译流程、体例与已知局限 | — |
| [`docs/translation-spec.md`](docs/translation-spec.md) | 翻译规范：公式写法、定理环境、Lean 行保留、术语与文风要求 | — |
| [`docs/PIPELINE.md`](docs/PIPELINE.md) | 翻译与排版流程说明（解析、切分、并行翻译、质检、排版） | — |
| [`NOTICE.md`](NOTICE.md) | 来源、版权与免责说明 | — |

## 二、原文、作者与原始地址

本仓库涉及**两份不同的材料**，来源与作者必须区分清楚：

### （1）证明的原始发布（作者本人）——Levent Alpöge

- **证明的原始发布地址**：**<https://alpo.ge/remark.pdf>**（4 页，2026 年 11 月 20 日）。
- **该网址是作者本人的发布页，不是转载**：Levent Alpöge 在哈佛的官方主页 `https://people.math.harvard.edu/~alpoge` 会**自动跳转**到 <https://alpo.ge>（其个人网站，内含其 CV、论文列表与 Anthropic/Harvard 任职信息）；Lean FRO 与 Mathlib Initiative 的官方联合声明中，"released"一词的链接即指向 <https://alpo.ge/remark.pdf>；Scientific American 报道亦称 Alpöge 的声明"posted on his website"。
- **Lean 4 存档（形式化证明本体）**：<https://alpo.ge/lean.tar.gz.part01> … `part14`（175,187 个文件、约 1,740 万行；校验说明见原书仓库）。remark 中自述"I believe I have, working with Claude, discovered a proof of the Riemann hypothesis"，即该证明是他**与 Claude 合作发现**的。
- **正式论文状态（截至 2026-11-27）**：未检索到该 RH/GRH 证明的 arXiv 预印本或期刊论文；目前作者发布的正式材料是上述 4 页 remark 与 Lean 存档（作者在 remark 中表示将另行正式写出论证）。请注意：arXiv:2608.13637（Alpöge & Furman，2026-08）与 Anthropic 研究页 <https://www.anthropic.com/research/riemann-zeta>（2026-08 发布）是**更早的部分结果**（"至少三分之二的零点单纯且位于临界线上"），**不是** 2026-11-20 的黎曼假设证明本身。
- **独立验证**：Drew Sutherland（MIT）的验证报告 <https://math.mit.edu/~drew/grh/>；Michael Rubinstein（Waterloo）的复核页 <https://mrubinst.github.io/grh-lean-verification/>；Lean FRO 与 Mathlib Initiative 联合认证（2026-11-21）<https://leanprover-community.github.io/blog/posts/riemann-hypothesis/>。
- **媒体报道（供参考）**：Nature，<https://doi.org/10.1038/d41586-026-03812-7>；Scientific American，<https://www.scientificamerican.com/article/anthropic-mathematician-claims-to-prove-riemann-hypothesis-most-famous-problem-in-all-of-math/>。

> 若在网上看到以 "ripemann-hypothesis-lean" 等命名的 GitHub 镜像仓库，那些是第三方镜像，均标注来源为 `alpo.ge`；原始发布地址是上面的 `alpo.ge`。

### （2）本译稿翻译的原书（独立阐释书，不是 Alpöge 的论文）

- **原书**：*The Riemann hypothesis and GRH for Dirichlet L-functions — A readable account of the Lean proof in Levent Alpöge's archive*（版本标识 rh-lean-roadmap，November 2026，本译稿依据 2026-11-25 生成、1545 页的 PDF）。
- **原书仓库（本书的原始地址）**：<https://github.com/rh-lean-roadmap/rh-lean-roadmap>；主页 <https://rh-lean-roadmap.github.io/rh-lean-roadmap/>；归档版本 Zenodo v44：<https://doi.org/10.5281/zenodo.24562451>。原书以 **CC BY 4.0** 发布。
- **该仓库不是 Alpöge 本人发布**：其 README 明确写道 "The proof is Alpöge's archive; this repository explains its structure... An independent author, not a specialist in this area, set the direction and made the calls; the text and code were written and cross-checked by several AI models, including Anthropic's Claude. Alpöge works at Anthropic; this repository is independent of him and of Anthropic."
- 因此：**原书的数学内容来自 Alpöge 的存档**，但**原书文本与代码由若干 AI 模型（含 Claude）与一位未具名的独立作者写成**，属于独立阐释项目；它是本译稿的翻译对象，而非黎曼假设证明的原始发布。

> **版本说明**：本译稿依据 **1545 页**版本（2026-11-25）；上游仓库当前 `docs/book.pdf` 为 **1582 页**（Zenodo v44），两者可能存在少量差异。如遇不一致，以原书与 Lean 存档为准。

## 三、原书与翻译规模

**原书结构**：引言 + 10 个部分 + 41 章 + 附录《完整证明》（约 922 页）+ Lean 声明索引（约 111 页）+ 参考文献（约 12 页），PDF 共 1545 页。

**翻译规模**：

| 指标 | 数量 |
| --- | --- |
| 翻译单元 | 237 个（全部完成，0 缺失） |
| 译文汉字数 | 约 **903 000** 字 |
| 独立公式 | **5 826** 条 |
| 行内公式 | 约 **92 600** 处 |
| 编号公式（原书编号保留） | **1 214** 条 |
| Lean 声明行（原样保留） | **3 565** 行 |

**体例**：

- 定理、引理、命题、定义、推论、证明的编号与顺序与原书一一对应（如"**定理 1.1**（黎曼假设）""**证明**。"）；
- 公式一律改写为 LaTeX，原书公式编号保留（`\tag{...}`）；
- 译文在每个原书页起始处标注 `[原书 p.N]`，目录页码为原书印刷页码，可据此对照原书；
- 人名保留拉丁拼写（Alpöge、Riemann、Dirichlet 等）；Lean 标识符、文件名、路径、文献编号不译。

## 四、翻译方法（简述）

1. **解析**：逐页提取 PDF 文本层，并把 1545 页逐页渲染为 144 dpi 页面图像。原书 LaTeX 排版 PDF 的文本层中，分式、上下标、∑/∫、cases 环境等常被拆散或错映射（例如 ∑ 被提取成字母 X、≠ 被提取成 6=），因此**公式一律以页面图像为权威依据**逐式核对后写成 LaTeX。
2. **先立规范与语料库**：先编写《翻译规范》与《数学术语与语料库》，统一术语、记号、公式写法与文风，再开始翻译。
3. **并行翻译**：全书按页切分为 237 个翻译单元，分批并行翻译；每单元流程为"读规范 → 读原文 → 逐页看图核对公式 → 写译文 → 自检"。
4. **统稿与质检**：统一术语与章节标题、清理多余符号；自动校验 237/237 单元页码覆盖、公式定界符平衡、无英文残留；并抽样复审 20 个单元（覆盖正文与附录），对照页面图像修正了 40 余处公式、术语与译文错误。
5. **排版**：按单元分块用 MathJax 渲染、打印为 PDF 后合并，再生成目录、Lean 声明索引与参考文献。

详细流程与统计数据见 [`docs/PIPELINE.md`](docs/PIPELINE.md)。

## 五、如何阅读

- **直接阅读 PDF**：[`translation/RiemannHypothesis-and-GRH_zh-CN.pdf`](translation/RiemannHypothesis-and-GRH_zh-CN.pdf)。
- **阅读/二次编辑 Markdown**：`translation/RiemannHypothesis-and-GRH_zh-CN.md` 中的公式为 LaTeX，可用支持 LaTeX 的 Markdown 工具（Typora、Obsidian、VS Code + Markdown+Math、pandoc 等）渲染；`$$...$$` 为独立公式，`$...$` 为行内公式。
- **查术语**：[`translation/glossary-zh-CN.md`](translation/glossary-zh-CN.md)，按英文术语字母序排列。

## 六、已知局限

- 本译稿为 **AI 辅助翻译**，未经人类数学专家逐页审校；凡译文与原书或 Lean 存档有出入之处，以原书与存档为准。
- 全书仅余 **2 处** `<!-- UNCERTAIN -->` 标注（一处因原书字形不可辨、一处因原书本身疑为笔误），均已在译文中按页面图像保留并注明。
- 原书为 LaTeX 排版 PDF，个别公式在文本层与图像模糊处按上下文与图像判读；如发现个别符号与原文不符，可对照原书对应页核对。
- Lean 声明索引保留 Lean 标识符与文件路径原文，仅译章节标题；参考文献保留原文（学术惯例）。
- 原书由多个 AI 模型依据 Lean 4 存档写成（原书"About this text"自述），其数学内容属于 Alpöge 的 Lean 存档；本仓库只提供中文翻译整理。

## 七、版权与免责

- **原书**：原书及其上游仓库以 **CC BY 4.0**（Attribution 4.0 International）许可发布（见[上游 LICENSE](https://github.com/rh-lean-roadmap/rh-lean-roadmap/blob/main/LICENSE)）。
- **本译稿**：本仓库的中文译文是原书的**衍生作品**，同样以 **CC BY 4.0** 许可发布。转载、改编或再分发时，请保留以下署名并注明修改：

  > 原书：*The Riemann hypothesis and GRH for Dirichlet L-functions — A readable account of the Lean proof in Levent Alpöge's archive*，rh-lean-roadmap，2026，CC BY 4.0（<https://github.com/rh-lean-roadmap/rh-lean-roadmap>）；数学内容来自 Levent Alpöge 的 Lean 存档。中文译本：本仓库（2026），以 CC BY 4.0 发布；译文对原文进行了中文翻译、公式重排与索引标题本地化。

- **Lean 存档**：Alpöge 的 Lean 存档本身未附许可证（上游 README："The archive carries no licence"），本仓库不重新分发该存档，仅作说明与引用。
- 本仓库按"现状"提供，不对内容的准确性作明示或暗示的保证；凡译文与原书或 Lean 存档有出入，以原书与存档为准。
- 如原作者或权利人认为本仓库内容不妥，请在仓库中提出 issue，我们将尽快处理。


## 八、致谢

- 原书：*The Riemann hypothesis and GRH for Dirichlet L-functions*（rh-lean-roadmap, November 2026）。
- 数学内容：Levent Alpöge 的 Lean 4 存档；Lean 与 Mathlib 社区。
- 排版：MathJax；页面渲染与 PDF 生成使用 PDFium / LibreOffice Kit 与 Edge headless。

---

## English summary

This repository contains a **complete Chinese translation** of the book *The Riemann hypothesis and GRH for Dirichlet L-functions — A readable account of the Lean proof in Levent Alpöge's archive* (rh-lean-roadmap, November 2026, 1,545 pages).

- **Coverage**: the full main text (pages 1–1422): introduction, Parts I–IX (chapters 1–40), the complete-proofs appendix and chapter 41. The Lean-declaration index keeps Lean identifiers verbatim and translates only chapter headings; the bibliography is kept in its original language.
- **Scale**: 237 translation units, ~903,000 Chinese characters, 5,826 display formulas, ~92,600 inline formulas, 1,214 numbered equations, 3,565 Lean declaration lines.
- **Files**: a typeset 1,182-page PDF, the LaTeX-formula Markdown source, a bilingual terminology corpus, translation notes, and the translation specification.
- **Method**: every formula was checked against rendered page images (the PDF text layer is unreliable for LaTeX math) and rewritten in LaTeX; terminology was fixed in a corpus first; automated QA verified page coverage, delimiter balance and absence of untranslated prose, followed by sampled human-style review of 20 units.
- **Caveat**: AI-assisted translation, not reviewed by human mathematicians; two `UNCERTAIN` notes remain. The original text and its mathematical content belong to their respective rights holders; this repository is for academic reading and research only.

Translation completed November 2026.
