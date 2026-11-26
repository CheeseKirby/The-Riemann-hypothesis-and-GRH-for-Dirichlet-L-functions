# NOTICE — 来源、作者、版权与免责说明

## 1. 证明的原始发布（作者本人）

黎曼假设与 Dirichlet L 函数广义黎曼假设证明的**原始发布地址**是：

- **Levent Alpöge 的发布页**：**<https://alpo.ge/remark.pdf>**（4 页 remark，2026-11-20；作者自述该证明是与 Claude 合作发现的）。
- **该地址是作者本人网站，不是转载**：Levent Alpöge 在哈佛的官方主页 `https://people.math.harvard.edu/~alpoge` 跳转到 <https://alpo.ge>；其 CV、论文列表与 Anthropic / Harvard 任职信息均在该站；Lean FRO 与 Mathlib Initiative 的官方联合声明中 "released" 一词链接即指向该 remark；Scientific American 报道亦称该声明 "posted on his website"。
- **Lean 4 存档（形式化证明本体）**：<https://alpo.ge/lean.tar.gz.part01> … `part14`（175,187 个文件、约 1,740 万行，不含注释）。存档本身未附许可证（原书仓库 README："The archive carries no licence"），本仓库不重新分发。
- **正式论文**：截至 2026-11-27，未检索到该证明的 arXiv 预印本或期刊论文；作者目前以 4 页 remark + Lean 存档的形式发布（remark 中表示将另行正式写出论证）。arXiv:2608.13637（Alpöge & Furman，2026-08）与 Anthropic 研究页 <https://www.anthropic.com/research/riemann-zeta> 是更早的**部分结果**（"至少三分之二的零点单纯且位于临界线上"），不是本证明本身。
- **独立验证**：<https://math.mit.edu/~drew/grh/>（Drew Sutherland，MIT）；<https://mrubinst.github.io/grh-lean-verification/>（Michael Rubinstein，Waterloo）；<https://leanprover-community.github.io/blog/posts/riemann-hypothesis/>（Lean FRO 与 Mathlib Initiative 联合认证，2026-11-21）。

## 2. 本译稿翻译的原书（独立阐释书）

- **书名**：*The Riemann hypothesis and GRH for Dirichlet L-functions — A readable account of the Lean proof in Levent Alpöge's archive*（版本标识 rh-lean-roadmap，November 2026；本译稿依据 2026-11-25 生成、1545 页的 PDF）。
- **原书仓库（本书的原始地址）**：<https://github.com/rh-lean-roadmap/rh-lean-roadmap>；主页 <https://rh-lean-roadmap.github.io/rh-lean-roadmap/>；归档版本 Zenodo v44：<https://doi.org/10.5281/zenodo.24562451>。
- **原书不是 Alpöge 本人发布**：原书仓库 README 明确说明其为独立项目——"The proof is Alpöge's archive; this repository explains its structure... An independent author, not a specialist in this area, set the direction and made the calls; the text and code were written and cross-checked by several AI models, including Anthropic's Claude. Alpöge works at Anthropic; this repository is independent of him and of Anthropic."
- **原书作者与来源**：数学内容来自 Levent Alpöge 的 Lean 存档；原书文本与代码由若干 AI 模型（包括 Anthropic 的 **Claude**）撰写并交叉校对，一位独立作者（非本领域专家、原书未具名）设定方向并作取舍。原书以 **CC BY 4.0** 发布。

## 3. 翻译性质

- 本仓库的中文译文由 **AI 辅助翻译**完成（2026 年 11 月），未经人类数学专家逐页审校。
- 翻译时以原书页面图像为公式的权威依据，公式重排为 LaTeX；术语依据随附《数学术语与语料库》统一。
- 译文中保留 `[原书 p.N]` 页码锚点，便于与原书对照复核。
- 全书仅余 2 处 `<!-- UNCERTAIN -->` 标注（原书字形不可辨或原书疑似笔误处），已在译文中保留并注明。

## 4. 版权与署名

- **原书**：以 **CC BY 4.0** 发布，文字、结构及相关权利归原作者与上游项目所有。
- **本译稿**：是原书的**衍生作品**，按 CC BY 4.0 的相同条件发布；转载、改编或再分发时请保留以下署名并注明修改：

  > 原书：*The Riemann hypothesis and GRH for Dirichlet L-functions — A readable account of the Lean proof in Levent Alpöge's archive*，rh-lean-roadmap，2026，CC BY 4.0（<https://github.com/rh-lean-roadmap/rh-lean-roadmap>）；数学内容来自 Levent Alpöge 的 Lean 存档（原始发布：<https://alpo.ge/remark.pdf>）。中文译本：本仓库（2026），以 CC BY 4.0 发布；译文对原文进行了中文翻译、公式重排与索引标题本地化。

- **Lean 存档**：Alpöge 的 Lean 存档本身未附许可证；本仓库不重新分发该存档，仅作说明与引用。

## 5. 免责

- 本仓库按"现状"提供，不对内容的完整性、准确性作任何明示或暗示的保证；凡译文与原书或 Lean 存档有出入，以原书与存档为准。
- 如原作者或权利人认为本仓库内容不妥，请在仓库中提出 issue，我们将尽快处理（包括移除相关内容）。
