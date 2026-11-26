# 交付说明

## 一、交付文件

| 文件 | 说明 |
| --- | --- |
| `黎曼假设与GRH_中文译稿.pdf` | 中文全译排版本，1182 页，23.3 MB（A4，公式用 MathJax 排版，图表无，公式 5000+ 条） |
| `黎曼假设与GRH_中文译稿.md` | 中文全译 Markdown 源稿（LaTeX 公式、定理环境、原书页码锚点），约 475 万字符 / 90.3 万汉字 |
| `数学术语与语料库.md` | 数学术语与语料库：约 700 条核心术语（英→中）+ 各章新增术语汇总（约 3300 条，合计约 4000 条），是全书统一译名的依据 |
| `work/` | 翻译工程中间产物（页面图像、逐页文本层、单元源文件、单元译稿、规范与术语表等），供复核 |

## 二、翻译对象与规模

- 原书：*The Riemann hypothesis and GRH for Dirichlet L-functions — A readable account of the Lean proof in Levent Alpöge's archive*（rh-lean-roadmap，November 2026），PDF 共 **1545 页**。
- 结构：引言 + 10 个部分 + 41 章 + 附录（完整证明，922 页）+ Lean 声明索引（111 页）+ 参考文献（12 页）。
- 全书正文（页 1–1422）**全部译出**：237 个翻译单元、237/237 完成，约 **90.3 万汉字**，含 5 826 条独立公式、约 9.3 万处行内公式、1 214 条编号公式、3 565 行 Lean 声明。
- 书末 Lean 声明索引按学术惯例保留 Lean 标识符原文、仅译章节标题；参考文献保留原文，仅译标题。

## 三、原文、作者与原始地址

- **原书**：*The Riemann hypothesis and GRH for Dirichlet L-functions — A readable account of the Lean proof in Levent Alpöge's archive*（版本标识 rh-lean-roadmap，2026 年 11 月，本译稿依据 2026-11-25 生成、1545 页的 PDF）。
- **原书仓库（原始地址）**：<https://github.com/rh-lean-roadmap/rh-lean-roadmap>；主页 <https://rh-lean-roadmap.github.io/rh-lean-roadmap/>；归档版本 Zenodo v44：<https://doi.org/10.5281/zenodo.24562451>。原书以 **CC BY 4.0** 发布，本译稿作为衍生作品亦以 CC BY 4.0 发布（署名见 `NOTICE.md`）。
- **证明的原始发布**：Levent Alpöge（Anthropic, PBC；Harvard Society of Fellows）于 2026 年 11 月 20 日发布 `remark`：<https://alpo.ge/remark.pdf>；文中自述该证明是其**与 Claude 合作**发现的，并附论证时间线。
- **Lean 4 存档**：<https://alpo.ge/lean.tar.gz.part01> … `part14`（175,187 个文件、约 1,740 万行）。
- **社区认证**（Lean FRO 与 Mathlib Initiative，2026-11-21）：<https://leanprover-community.github.io/blog/posts/riemann-hypothesis/>；**独立验证报告**（Drew Sutherland）：<https://math.mit.edu/~drew/grh/>。
- **作者与来源**：数学证明与 Lean 存档为 Levent Alpöge 的存档；原书正文与代码由若干 AI 模型（包括 Anthropic 的 Claude）撰写并交叉校对，一位独立作者（非本领域专家、原书未具名）设定方向并作取舍（据原书仓库 README "About this repository"）。上游仓库另有 21 页中文导读（`docs/reading-guide-zh.pdf`），与本译稿不同。
- **版本差异提示**：上游仓库当前 `docs/book.pdf` 为 1582 页（Zenodo v44），本译稿依据的 1545 页版本与之可能存在少量差异；如遇不一致，以原书与 Lean 存档为准。

## 四、翻译流程

1. **解析**：逐页提取 PDF 文本层，并将 1545 页逐页渲染为 144 dpi 页面图像——文本层中的公式（分式、上下标、∑/∫、cases 等）常被拆散或错映射，翻译时**以页面图像为权威依据**逐式核对。
2. **体例与语料库**：先建立《数学术语与语料库》与《翻译规范》（定理/引理/定义/证明环境、公式 LaTeX 写法、Lean 行保留、原书页码锚点、书名/栏目体例），再开始翻译。
3. **并行翻译**：237 个单元分批由并行子代理翻译，每单元均含"读规范→读原文→逐页看图→写译文→自检"流程；术语、记号、编号逐块统一。
4. **统稿与质检**：统一术语（如 entry=矩阵元、thin position=薄位置 等）、统一章节标题、删除多余证明结束符、修复数学定界符问题；自动校验 237/237 单元页码覆盖、公式定界符平衡、无英文残留；抽样复审 20 个单元（覆盖正文与附录），修正 40 余处公式/术语/译文错误。
5. **排版**：按单元分块用 MathJax 排版、Edge 打印为 PDF，再合并；目录、Lean 声明索引、参考文献单独生成。

## 五、体例说明

- 定理、引理、命题、定义、推论、证明的编号与顺序与原书一一对应（如"**定理 1.1**（黎曼假设）""**证明**。"）。
- 公式一律改写为 LaTeX 并排版（原书编号保留为 `\tag{...}`）。
- 原书页码锚点：译文在每页起始处标注 `[原书 p.N]`；目录中的页码为**原书印刷页码**。
- 人名保留拉丁拼写（Alpöge、Riemann、Dirichlet 等）；Lean 标识符、文件名、路径、文献编号不译。
- 书眉、页码等版式元素按中文书习惯重新排版，不逐页复刻原书。

## 六、已知局限

- 本译稿为 AI 辅助翻译，未经人类数学专家逐页审校；凡译文与原书或 Lean 存档有出入之处，以原书与存档为准。
- 全书仅余 2 处 `<!-- UNCERTAIN -->` 标注（chunk-0182 的重定标因子理想符号、chunk-0223 原书自身疑为笔误的等式），均已在译文中按页面图像保留并注明。
- 原书为 LaTeX 排版 PDF，个别公式在文本层与图像模糊处已按上下文与图像判读；如发现个别符号与原文不符，可据 `work/src` 与 `work/pages`（原书逐页图像）复核。
