# NOTICE — 来源、作者、版权与免责说明

## 1. 原书与原始地址

本仓库中的中文翻译所对应的英文原书为：

- **书名**：*The Riemann hypothesis and GRH for Dirichlet L-functions — A readable account of the Lean proof in Levent Alpöge's archive*
- **版本标识**：rh-lean-roadmap（November 2026）
- **原书仓库（原始地址）**：<https://github.com/rh-lean-roadmap/rh-lean-roadmap>
- **原书主页**：<https://rh-lean-roadmap.github.io/rh-lean-roadmap/>
- **原书归档版本**：Zenodo v44，<https://doi.org/10.5281/zenodo.24562451>
- **原书许可**：**CC BY 4.0**（Attribution 4.0 International，见上游仓库 `LICENSE`）

## 2. 证明的原始发布与作者

- **数学证明**：Alpöge 的 Lean 4 存档（175,187 个文件、约 1,740 万行，不含注释）。
- **原始发布（作者本人说明）**：Levent Alpöge（Anthropic, PBC；Harvard Society of Fellows）于 2026 年 11 月 20 日发布 `remark`：<https://alpo.ge/remark.pdf>。文中自述其**与 Claude 合作**发现了黎曼假设的证明（"I believe I have, working with Claude, discovered a proof of the Riemann Hypothesis"），并给出论证时间线。
- **Lean 存档下载**：<https://alpo.ge/lean.tar.gz.part01> … `part14`（校验与解包说明见原书仓库 README）。
- **社区认证**：Lean FRO 与 Mathlib Initiative 于 2026 年 11 月 21 日发表联合声明，认证该陈述与证明正确：<https://leanprover-community.github.io/blog/posts/riemann-hypothesis/>。
- **独立验证报告**：Drew Sutherland，<https://math.mit.edu/~drew/grh/>。
- **原书正文与代码的作者**：由若干 AI 模型（包括 Anthropic 的 **Claude**）撰写并交叉校对；一位独立作者（非本领域专家、原书未具名）设定方向并作取舍（据原书仓库 README "About this repository"）。原书正文自述 "written by several AI models, including Claude"。Alpöge 在 Anthropic 工作；原书仓库及其说明独立于他本人与 Anthropic。数学内容以 Lean 存档为准。

> 本译稿依据的是 **2026-11-25 生成、1545 页**的原书 PDF；上游仓库当前的 `docs/book.pdf` 为 1582 页（Zenodo v44），两者可能存在少量差异。

## 3. 翻译性质

- 本仓库的中文译文由 **AI 辅助翻译**完成（2026 年 11 月），未经人类数学专家逐页审校。
- 翻译时以原书页面图像为公式的权威依据，公式重排为 LaTeX；术语依据随附《数学术语与语料库》统一。
- 译文中保留 `[原书 p.N]` 页码锚点，便于与原书对照复核。
- 全书仅余 2 处 `<!-- UNCERTAIN -->` 标注（原书字形不可辨或原书疑似笔误处），已在译文中保留并注明。

## 4. 版权与署名

- **原书**：以 **CC BY 4.0** 发布，文字、结构及相关权利归原作者与上游项目所有。
- **本译稿**：是原书的**衍生作品**，按 CC BY 4.0 的相同条件发布；转载、改编或再分发时请保留以下署名并注明修改：

  > 原书：*The Riemann hypothesis and GRH for Dirichlet L-functions — A readable account of the Lean proof in Levent Alpöge's archive*，rh-lean-roadmap，2026，CC BY 4.0（<https://github.com/rh-lean-roadmap/rh-lean-roadmap>）；数学内容来自 Levent Alpöge 的 Lean 存档。中文译本：本仓库（2026），以 CC BY 4.0 发布；译文对原文进行了中文翻译、公式重排与索引标题本地化。

- **Lean 存档**：Alpöge 的 Lean 存档本身未附许可证（上游 README："The archive carries no licence"）。本仓库不重新分发该存档，仅作说明与引用。

## 5. 免责

- 本仓库按"现状"提供，不对内容的完整性、准确性作任何明示或暗示的保证；凡译文与原书或 Lean 存档有出入，以原书与存档为准。
- 如原作者或权利人认为本仓库内容不妥，请在仓库中提出 issue，我们将尽快处理（包括移除相关内容）。
