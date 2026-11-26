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

## 二、原书与翻译规模

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

## 三、翻译方法（简述）

1. **解析**：逐页提取 PDF 文本层，并把 1545 页逐页渲染为 144 dpi 页面图像。原书 LaTeX 排版 PDF 的文本层中，分式、上下标、∑/∫、cases 环境等常被拆散或错映射（例如 ∑ 被提取成字母 X、≠ 被提取成 6=），因此**公式一律以页面图像为权威依据**逐式核对后写成 LaTeX。
2. **先立规范与语料库**：先编写《翻译规范》与《数学术语与语料库》，统一术语、记号、公式写法与文风，再开始翻译。
3. **并行翻译**：全书按页切分为 237 个翻译单元，分批并行翻译；每单元流程为"读规范 → 读原文 → 逐页看图核对公式 → 写译文 → 自检"。
4. **统稿与质检**：统一术语与章节标题、清理多余符号；自动校验 237/237 单元页码覆盖、公式定界符平衡、无英文残留；并抽样复审 20 个单元（覆盖正文与附录），对照页面图像修正了 40 余处公式、术语与译文错误。
5. **排版**：按单元分块用 MathJax 渲染、打印为 PDF 后合并，再生成目录、Lean 声明索引与参考文献。

详细流程与统计数据见 [`docs/PIPELINE.md`](docs/PIPELINE.md)。

## 四、如何阅读

- **直接阅读 PDF**：[`translation/RiemannHypothesis-and-GRH_zh-CN.pdf`](translation/RiemannHypothesis-and-GRH_zh-CN.pdf)。
- **阅读/二次编辑 Markdown**：`translation/RiemannHypothesis-and-GRH_zh-CN.md` 中的公式为 LaTeX，可用支持 LaTeX 的 Markdown 工具（Typora、Obsidian、VS Code + Markdown+Math、pandoc 等）渲染；`$$...$$` 为独立公式，`$...$` 为行内公式。
- **查术语**：[`translation/glossary-zh-CN.md`](translation/glossary-zh-CN.md)，按英文术语字母序排列。

## 五、已知局限

- 本译稿为 **AI 辅助翻译**，未经人类数学专家逐页审校；凡译文与原书或 Lean 存档有出入之处，以原书与存档为准。
- 全书仅余 **2 处** `<!-- UNCERTAIN -->` 标注（一处因原书字形不可辨、一处因原书本身疑为笔误），均已在译文中按页面图像保留并注明。
- 原书为 LaTeX 排版 PDF，个别公式在文本层与图像模糊处按上下文与图像判读；如发现个别符号与原文不符，可对照原书对应页核对。
- Lean 声明索引保留 Lean 标识符与文件路径原文，仅译章节标题；参考文献保留原文（学术惯例）。
- 原书由多个 AI 模型依据 Lean 4 存档写成（原书"About this text"自述），其数学内容属于 Alpöge 的 Lean 存档；本仓库只提供中文翻译整理。

## 六、版权与免责

- 原书文字、数学内容及相关权利归原作者与相关权利人所有；本仓库为**学术阅读与研究用途**的中文翻译整理，**不主张对原文的任何权利**，也不对译文授予商业使用许可。
- 如原作者或权利人认为本仓库内容不妥，请在本仓库提出 issue，我们会尽快处理（包括移除相关内容）。
- 详见 [`NOTICE.md`](NOTICE.md)。

## 七、致谢

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
