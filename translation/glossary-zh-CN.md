# 数学术语与语料库（英→中）

> 规模：核心术语约 700 条；文末附各单元新增术语汇总约 3 300 条，合计约 4 000 条。


本文件是全书统一译名的依据。**所有译稿必须遵循本表**；表中未列出的术语，按"标准数学名词 + 本表构词法"处理，并在译稿末尾用注释列出新增术语（格式：`<!-- NEWTERM: English = 中文 -->`），由统稿人并入本表。

约定：
- 人名一律音译（首见可保留拉丁拼写与否不作要求），**Lean 标识符、文件名、路径、定理编号、公式编号、参考文献编号一律保留原文**。
- 术语后不逐处加英文原文；本表已保证一致性。
- "the archive" = Alpöge 的 Lean 存档（简称"存档"）。

## 0. 总标题与结构

| 英文 | 中文 |
| --- | --- |
| The Riemann hypothesis and GRH for Dirichlet L-functions | 黎曼假设与狄利克雷 L 函数的广义黎曼假设 |
| A readable account of the Lean proof in Levent Alpöge's archive | Levent Alpöge 存档中 Lean 证明的可读版 |
| Contents | 目录 |
| Introduction | 引言 |
| Part | 部分 |
| Chapter | 第……章 |
| Section | 节 |
| Appendix: complete proofs | 附录：完整证明 |
| Index of Lean declarations | Lean 声明索引 |
| Bibliography | 参考文献 |
| Theorem | 定理 |
| Lemma | 引理 |
| Proposition | 命题 |
| Corollary | 推论 |
| Definition | 定义 |
| Remark | 注 |
| Example | 例 |
| Claim | 断言 |
| Proof | 证明 |
| Outline | 概要 |
| Notation | 记号 |
| Convention | 约定 |
| Assumption | 假设 |
| Hypothesis | 假设 |
| Setting | 设定 |
| Data | 数据 |
| Condition | 条件 |
| Statement | 陈述／命题 |
| Definition 1.10 (Two nonvanishing assertions) | 定义 1.10（两条非零断言） |
| Level | 水平／层次（按上下文：conductor level = 导子水平；level structure = 水平结构） |

## 1. 黎曼假设与解析数论

| 英文 | 中文 |
| --- | --- |
| Riemann hypothesis | 黎曼假设 |
| generalized Riemann hypothesis (GRH) | 广义黎曼假设（GRH） |
| explicit zeta statement | 显式 ζ 命题 |
| zeta function | ζ 函数 |
| Dirichlet L-function | 狄利克雷 L 函数 |
| continued Dirichlet L-function | 延拓的狄利克雷 L 函数 |
| completed zeta function | 完备化 ζ 函数 |
| L-value | L 值 |
| critical line | 临界线 |
| critical strip | 临界带 |
| right of the critical line | 临界线右侧 |
| zero | 零点 |
| zero-free | 无零点 |
| zero-free criterion | 无零点判别法 |
| zero-free above θ | 在 Re s > θ 上无零点 |
| zero-density estimate | 零点密度估计 |
| trivial zero | 平凡零点 |
| negative even integer | 负偶数 |
| pole | 极点 |
| residue | 留数 |
| nonvanishing | 非零（性） |
| functional equation | 函数方程 |
| reflection formula | 反射公式 |
| reflection | 反射 |
| Euler factor | 欧拉因子 |
| Euler product | 欧拉乘积 |
| Euler's constant | 欧拉常数 |
| gamma function | 伽马函数 |
| gamma nonvanishing | 伽马函数非零 |
| sign | 符号 |
| constant term | 常数项 |
| principal character | 主特征 |
| primitive character | 本原特征 |
| imprimitive | 非本原的 |
| conductor | 导子 |
| modulus | 模 |
| order of a character | 特征的阶 |
| character sum | 特征和 |
| Dirichlet character | 狄利克雷特征 |
| unitary character | 酉特征 |
| trivial character | 平凡特征 |
| quadratic character | 二次特征 |
| Gauss sum | 高斯和 |
| prime number theorem | 素数定理 |
| prime number theorem in arithmetic progressions | 算术级数中的素数定理 |
| arithmetic progression | 算术级数 |
| prime | 素数 |
| auxiliary prime | 辅助素数 |
| prime sum | 素数和 |
| weighted centred prime sum | 加权中心化素数和 |
| summatory function | 求和函数 |
| sum over | 对……求和 |
| mean-square estimate | 均方估计 |
| moment | 矩 |
| density estimate | 密度估计 |
| short interval | 短区间 |
| primes in short intervals | 短区间中的素数 |
| window | 窗口 |
| window criterion | 窗口判别法 |
| arithmetic window | 算术窗口 |
| Gaussian window | 高斯窗口 |
| downstream window | 下游窗口 |
| window bound | 窗口界 |
| main term | 主项 |
| error term | 误差项 |
| square-root bound | 平方根界 |
| net gain | 净增益 |
| target sum | 目标求和 |
| partial summation | 部分求和（分部求和） |
| integration by parts | 分部积分 |
| logarithm | 对数 |
| log | 对数 |
| optimal | 最优的 |
| sharp | 精确的／最优的 |
| uniform | 一致的（uniform bound：一致界） |
| up to | 至多相差 |
| at most | 至多为 |
| at least | 至少 |
| bounded by | 以……为界 |
| bounded above by | 以……为上界 |
| vanishes | 为零／消失 |
| tends to | 趋于 |
| converges | 收敛 |
| absolutely convergent | 绝对收敛 |
| normal convergence | 正规收敛 |
| analytic continuation | 解析延拓 |
| meromorphic | 亚纯的 |
| holomorphic | 全纯的 |
| regularized holomorphic derivative | 正则化全纯导数 |
| Laurent expansion | 洛朗展开 |
| Fourier expansion | 傅里叶展开 |
| Fourier transform | 傅里叶变换 |
| Poisson summation | 泊松求和 |
| contour | 围道 |
| Cauchy-Schwarz | 柯西–施瓦茨 |
| Parseval | 帕塞瓦尔 |
| Chebyshev | 切比雪夫 |
| Riemann | 黎曼 |
| Dirichlet | 狄利克雷 |
| Euler | 欧拉 |
| Alpöge | Alpöge（人名保留） |
| Claude | Claude（人名保留） |

## 2. 代数数论与类域论

| 英文 | 中文 |
| --- | --- |
| number field | 数域 |
| algebraic number field | 代数数域 |
| ring of integers | 整数环 |
| coefficient number field | 系数域（系数数域） |
| CM field | CM 域 |
| CM type | CM 型 |
| CM extension | CM 扩张 |
| totally complex | 全复的 |
| totally real | 全实的 |
| complex conjugation | 复共轭 |
| real-field restriction | 实域限制 |
| field discriminant | 域判别式 |
| discriminant ideal | 判别式理想 |
| different | 差积 |
| relative different | 相对差积 |
| ideal norm | 理想范数 |
| absolute ideal norm | 绝对理想范数 |
| class number | 类数 |
| class group | 类群 |
| ideal class | 理想类 |
| Picard group | 皮卡群 |
| Picard twist | 皮卡扭曲 |
| ordinary class term | 寻常类项 |
| partial zeta function | 部分 ζ 函数 |
| partial zeta value | 部分 ζ 值 |
| Siegel's mass formula | 西格尔质量公式 |
| mass formula | 质量公式 |
| Galois extension | 伽罗瓦扩张 |
| Galois group | 伽罗瓦群 |
| Galois representation | 伽罗瓦表示 |
| Galois over Q | Q 上伽罗瓦 |
| unramified | 非分歧的 |
| ramified | 分歧的 |
| tame | 温和的 |
| tamely ramified | 温和分歧的 |
| inertia | 惯性（群） |
| inertia group | 惯性群 |
| decomposition group | 分解群 |
| residue field | 剩余域 |
| residue degree | 剩余次数 |
| split prime | 分裂素数 |
| splits in E/F | 在 E/F 中分裂 |
| ramification | 分歧 |
| uniformizer | 一致化子 |
| valuation | 赋值 |
| v_ℓ | ℓ 进赋值 |
| normalized absolute value | 正规化绝对值 |
| place | 位 |
| finite place | 有限位 |
| infinite place (archimedean) | 无穷位（阿基米德位） |
| archimedean | 阿基米德的 |
| non-archimedean | 非阿基米德的 |
| local field | 局部域 |
| local completion | 局部完备化 |
| completion | 完备化 |
| adèle | 阿代尔 |
| finite adèle | 有限阿代尔 |
| idèle | 伊代尔 |
| finite idèle | 有限伊代尔 |
| idèle class group | 伊代尔类群 |
| idèlic reciprocity | 伊代尔互反律 |
| class field theory | 类域论 |
| Artin map | 阿廷映射 |
| Artin symbol | 阿廷符号 |
| reciprocity | 互反律 |
| quadratic reciprocity | 二次互反律 |
| Frobenius | 弗罗贝尼乌斯 |
| geometric Frobenius | 几何弗罗贝尼乌斯 |
| arithmetic Frobenius | 算术弗罗贝尼乌斯 |
| Frobenius orbit | 弗罗贝尼乌斯轨道 |
| Frobenius conjugation | 弗罗贝尼乌斯共轭 |
| cyclotomic field | 分圆域 |
| cyclotomic tower | 分圆塔 |
| cyclotomic character | 分圆特征 |
| roots of unity | 单位根 |
| Kummer | 库默尔 |
| Hilbert | 希尔伯特 |
| Shimura | 志村 |
| Siegel | 西格尔 |
| Hecke | 赫克 |
| Tate | 泰特 |
| Shafarevich | 沙法列维奇 |
| Kato | 加藤 |
| Weil | 韦伊 |
| Serre | 塞尔 |
| Deligne | 德利涅 |
| Grothendieck | 格罗滕迪克 |
| Langlands | 朗兰兹 |
| Arthur | 阿瑟 |
| Selberg | 塞尔伯格 |
| Rallis | 拉利斯 |
| Jacquet | 雅克 |
| Godement | 戈德门 |
| Rankin | 兰金 |
| Green | 格林 |
| Conway | 康威 |
| Ramanujan | 拉马努金 |

## 3. 自守表示与朗兰兹

| 英文 | 中文 |
| --- | --- |
| automorphic representation | 自守表示 |
| cuspidal representation | 尖点表示 |
| cuspidal automorphic representation | 尖点自守表示 |
| polarized cuspidal automorphic representation | 极化尖点自守表示 |
| automorphic form | 自守形式 |
| modular form | 模形式 |
| Hilbert–Siegel modular form | 希尔伯特–西格尔模形式 |
| eigenform | 特征形式 |
| Hecke operator | 赫克算子 |
| Hecke character | 赫克特征 |
| Hecke commutation | 赫克交换性 |
| Hecke module | 赫克模 |
| local Langlands correspondence | 局部朗兰兹对应 |
| weak local Langlands correspondence | 弱局部朗兰兹对应 |
| Langlands parameter | 朗兰兹参数 |
| local factor | 局部因子 |
| global L-function | 整体 L 函数 |
| Bessel function | 贝塞尔函数 |
| Bessel model | 贝塞尔模型 |
| Bessel map | 贝塞尔映射 |
| Whittaker | 惠特克 |
| Whittaker model | 惠特克模型 |
| induced representation | 诱导表示 |
| Jacquet module | 雅克模块 |
| double coset | 双陪集 |
| double-coset construction | 双陪集构造 |
| double-coset filtration | 双陪集滤链 |
| quotient | 商 |
| quotient map | 商映射 |
| disintegration | 分解 |
| isobaric | 等重的 |
| base change | 基变换 |
| descent | 下降 |
| functoriality | 函子性 |
| unitary group | 酉群 |
| definite unitary group | 定酉群 |
| rank | 秩 |
| rank one | 秩一 |
| higher rank | 高秩 |
| cuspidal | 尖点的 |
| spherical | 球面的 |
| spherical function | 球函数 |
| compact-finite vector | 紧致有限向量 |
| smooth vector | 光滑向量 |
| representation | 表示 |
| irreducible | 不可约的 |
| irreducibility | 不可约性 |
| tempered | 温和的（tempered representation：温表示） |
| discrete series | 离散系列 |
| theta lift | 西塔提升 |
| theta correspondence | 西塔对应 |
| theta series | 西塔级数 |
| theta chain | 西塔链 |
| Weil representation | 韦伊表示 |
| lattice theta series | 格西塔级数 |
| Rallis harmonic theta | 拉利斯调和西塔 |
| test vector | 测试向量 |
| test space | 测试空间 |
| matrix coefficient | 矩阵系数 |
| central character | 中心特征 |
| twisting | 扭曲 |
| twist | 扭曲 |
| Picard twist | 皮卡扭曲 |
| automorphic count | 自守计数 |
| deformation rigidity | 形变刚性 |
| deformation | 形变 |
| rigidity | 刚性 |
| covolume | 余体积 |
| covolume bound | 余体积界 |
| polarization | 极化 |
| polarized | 极化的 |
| polarization type | 极化型 |
| Siegel lattice | 西格尔格 |
| lattice | 格 |
| sublattice | 子格 |
| integral lattice | 整格 |
| rank-r lattice | 秩 r 格 |
| period | 周期 |
| period map | 周期映射 |
| period scale | 周期标度 |
| complex place | 复位 |
| Hodge | 霍奇 |
| Hodge lattice | 霍奇格 |
| Hermitian | 埃尔米特的 |
| Hermitian curvature | 埃尔米特曲率 |
| Kähler | 凯勒 |
| Archimedean bound | 阿基米德界 |
| slope | 斜率 |
| slope inequality | 斜率不等式 |
| average slope | 平均斜率 |
| slope bound | 斜率界 |
| height | 高度 |
| Stepanov's inequality | 斯捷潘诺夫不等式 |
| Minkowski | 闵可夫斯基 |
| Minkowski scaling | 闵可夫斯基标度 |
| Harder–Narasimhan | 哈德–纳拉辛汉 |
| tautological | 重言的 |
| cycle | 循环 |
| cohomology | 上同调 |
| cohomological | 上同调的 |
| semistable | 半稳定的 |
| stable | 稳定的 |
| filtration | 滤链 |
| graded | 分次的 |
| Canonical | 典范的 |
| canonical bundle | 典范丛 |
| differential | 微分 |
| differential operator | 微分算子 |
| differential polynomial | 微分多项式 |
| entry (matrix entry) | 矩阵元 |
| entry estimate | 矩阵元估计 |
| local kernel | 局部核 |
| formal kernel | 形式核 |
| kernel | 核 |
| double-coset | 双陪集 |
| coset representative | 陪集代表元 |
| multi-index | 多重指标 |
| factorial | 阶乘 |
| denominator | 分母 |
| numerator | 分子 |
| binomial coefficient | 二项式系数 |
| binomial expansion | 二项式展开 |
| power | 幂 |
| entrywise | 逐元素的 |
| submultiplicative | 次乘性的 |
| norm | 范数 |
| operator norm | 算子范数 |
| maximum norm | 最大范数 |
| ultrametric | 超度量的 |
| twist law | 扭曲律 |
| determinant law | 行列式律 |
| type law | 型律 |
| duality | 对偶性 |
| dual | 对偶 |
| local duality | 局部对偶 |
| Galois cohomology | 伽罗瓦上同调 |
| Euler system | 欧拉系统 |
| Tate–Shafarevich group | 泰特–沙法列维奇群 |
| Tate–Shafarevich-type group | 泰特–沙法列维奇型群 |
| Selmer | 塞尔默 |
| Shafarevich–Tate | 沙法列维奇–泰特 |
| CM subfield | CM 子域 |
| CM subfield of a cyclotomic field | 分圆域的 CM 子域 |

## 4. 分析、渐近与一般数学

| 英文 | 中文 |
| --- | --- |
| constant | 常数 |
| absolute constant | 绝对常数 |
| positive constant | 正常数 |
| absolute | 绝对的 |
| approximate | 近似 |
| approximation | 近似 |
| expansion | 展开 |
| asymptotic expansion | 渐近展开 |
| asymptotic | 渐近的 |
| decays | 衰减 |
| decay | 衰减 |
| growth | 增长 |
| growth bound | 增长界 |
| exponential | 指数的 |
| polynomial | 多项式的 |
| polynomial-norm constant | 多项式范数常数 |
| power series | 幂级数 |
| uniform bound | 一致界 |
| dimension | 维数 |
| dimension bound | 维数界 |
| degree | 次数 |
| finite-dimensional | 有限维的 |
| linear | 线性的 |
| bilinear | 双线性的 |
| symmetric | 对称的 |
| alternating | 交错的 |
| nondegenerate | 非退化的 |
| positive definite | 正定的 |
| definite | 定的 |
| semidefinite | 半定的 |
| trace | 迹 |
| determinant | 行列式 |
| discriminant | 判别式 |
| matrix | 矩阵 |
| diagonal | 对角的 |
| diagonalizable | 可对角化的 |
| eigenvalue | 特征值 |
| eigenvector | 特征向量 |
| spectrum | 谱 |
| spectral | 谱的 |
| orthogonal | 正交的 |
| orthonormal | 标准正交的 |
| Hilbert space | 希尔伯特空间 |
| Banach | 巴拿赫 |
| Cauchy sequence | 柯西列 |
| complete | 完备的 |
| compact | 紧致的 |
| compactly supported | 紧支的 |
| support | 支集 |
| finite support | 有限支集 |
| continuous | 连续的 |
| continuous spectrum | 连续谱 |
| discrete | 离散的 |
| locally constant | 局部常值的 |
| inversion | 反演 |
| Fourier inversion | 傅里叶反演 |
| measure | 测度 |
| Haar measure | 哈尔测度 |
| volume | 体积 |
| integral | 积分 |
| contour integral | 围道积分 |
| sum | 和 |
| product | 积 |
| over | 对……（取遍） |
| runs over | 取遍 |
| ranges over | 取遍 |
| coprime | 互素的 |
| divides | 整除 |
| divided by | 除以 |
| divisor | 除子；因子 |
| proper divisor | 真因子 |
| prime divisor | 素因子 |
| divisible | 可整除 |
| divisibility | 整除性 |
| valuation | 赋值 |
| exponent | 指数 |
| conjugate | 共轭 |
| conjugate sum | 共轭和 |
| complex conjugate | 复共轭 |
| real part | 实部 |
| Re s | Re s（保留） |
| imaginary part | 虚部 |
| positive integer | 正整数 |
| nonnegative | 非负的 |
| nonempty | 非空的 |
| finite | 有限的 |
| infinite | 无限的 |
| arbitrary | 任意的 |
| sufficiently large | 充分大的 |
| large enough | 足够大的 |
| small | 小的 |
| bounded | 有界的 |
| bound | 界 |
| upper bound | 上界 |
| lower bound | 下界 |
| estimate | 估计 |
| inequality | 不等式 |
| equality | 等式 |
| identity | 恒等式 |
| if and only if | 当且仅当 |
| implies | 蕴含 |
| equivalent | 等价的 |
| equivalent to | 等价于 |
| assume | 假设 |
| suppose | 设／假设 |
| fix | 固定 |
| let | 设 |
| denote | 记 |
| write | 记作；写 |
| put | 令 |
| set | 置；令（动词）；集合（名词） |
| satisfy | 满足 |
| satisfy the condition | 满足条件 |
| hold | 成立 |
| holds for | 对……成立 |
| fails | 不成立 |
| as required | 如所要求 |
| as claimed | 如所断言 |
| this proves | 这就证明了 |
| hence | 因此 |
| thus | 于是 |
| therefore | 所以 |
| indeed | 事实上 |
| moreover | 此外 |
| furthermore | 进一步 |
| however | 然而 |
| in particular | 特别地 |
| for instance | 例如 |
| that is | 即 |
| namely | 即 |
| whereas | 而 |
| while | 而（对比）；当……时 |
| unless | 除非 |
| otherwise | 否则 |
| provided that | 只要 |
| since | 由于 |
| because | 因为 |
| it suffices to | 只需 |
| it remains to | 只需 |
| reduce to | 归结为 |
| reduction | 归约 |
| passage to | 过渡到 |
| passage | 过渡 |
| common input | 公共输入 |
| input | 输入 |
| output | 输出 |
| witness | 见证 |
| certificate | 证书 |
| algorithm | 算法 |
| constructive | 构造性的 |
| explicit | 显式的 |
| implicit | 隐式的 |
| canonical | 典范的 |
| natural | 自然的 |
| compatible | 相容的 |
| compatibility | 相容性 |
| choice | 选择 |
| choices work | 这些选择可行 |
| admissible | 容许的 |
| legitimate | 合法的 |
| valid | 有效的 |
| well-defined | 良定义的 |
| injective | 单射的 |
| surjective | 满射的 |
| bijective | 双射的 |
| isomorphism | 同构 |
| isomorphism class | 同构类 |
| automorphism | 自同构 |
| embedding | 嵌入 |
| extension of fields | 域扩张 |
| subfield | 子域 |
| quotient field | 商域 |
| algebraic closure | 代数闭包 |
| separably closed | 可分闭的 |
| finite extension | 有限扩张 |
| Galois | 伽罗瓦 |
| abelian | 阿贝尔的 |
| abelian group | 阿贝尔群 |
| abelian variety | 阿贝尔簇 |
| elliptic curve | 椭圆曲线 |
| Tate module | 泰特模 |
| Galois cohomology | 伽罗瓦上同调 |
| character group | 特征群 |
| group algebra | 群代数 |
| ring | 环 |
| field | 域 |
| module | 模 |
| sheaf | 层 |
| bundle | 丛 |
| vector bundle | 向量丛 |
| line bundle | 线丛 |
| scheme | 概形 |
| stack | 叠 |
| derived | 导出的 |
| exact sequence | 正合序列 |
| long exact sequence | 长正合序列 |
| spectral sequence | 谱序列 |
| short exact sequence | 短正合序列 |
| torsion | 挠 |
| torsion-free | 无挠的 |
| torsion marking | 挠标记 |
| free module | 自由模 |
| projective | 投射的 |
| locally free | 局部自由的 |
| coherent | 凝聚的 |
| ample | 丰富的（ample line bundle：丰富线丛） |
| extension | 扩张 |
| lift | 提升 |
| lifting | 提升 |
| level | 水平 |
| level structure | 水平结构 |
| minimal level | 极小水平 |
| good reduction | 好约化 |
| bad reduction | 坏约化 |
| good place | 好处（good reduction place：好约化位） |
| cover | 覆盖 |
| cover field | 覆盖域 |
| chart | 卡 |
| chart restriction | 卡限制 |
| chart's integral model | 卡的整模型 |
| integral model | 整模型 |
| model | 模型 |

## 5. Lean 与形式化

| 英文 | 中文 |
| --- | --- |
| Lean 4 | Lean 4（不译） |
| Mathlib | Mathlib（不译） |
| archive | 存档 |
| formalization | 形式化 |
| formalize | 形式化 |
| declaration | 声明 |
| theorem statement | 定理陈述 |
| statement | 陈述 |
| proof term | 证明项 |
| kernel | 内核 |
| checked by | 由……检验 |
| verification | 验证 |
| verifier | 验证器 |
| database | 数据库 |
| library | 库 |
| file | 文件 |
| line | 行 |
| namespace | 命名空间 |
| typeclass | 类型类 |
| instance | 实例 |
| definition | 定义 |
| axiom | 公理 |
| tactic | 策略 |
| elaboration | 精化 |
| sorry | （保留 sorry，指未完成证明占位符） |
| compiler | 编译器 |
| independent kernels | 独立内核 |
| certification | 认证 |
| referee | 审稿人 |
| review | 评审 |
| repository | 仓库 |
| source | 源（文件） |
| source code | 源代码 |
| comments | 注释 |
| without comments | 不含注释 |

## 6. 常见句子模式（语料库）

| 英文模式 | 中文模式 |
| --- | --- |
| Let X be a ... | 设 X 为…… |
| For every ε > 0 ... | 对每个 ε > 0，…… |
| Suppose that ... | 假设…… |
| Assume that ... | 假设…… |
| Fix a prime p. | 固定一个素数 p。 |
| Write X for Y. | 记 X 为 Y。 |
| Put X = Y. | 令 X = Y。 |
| Then X satisfies ... | 则 X 满足…… |
| It follows that ... | 由此得到…… |
| We have ... | 有…… |
| There exists ... | 存在…… |
| There is a unique ... | 存在唯一的…… |
| For all ... | 对所有…… |
| By Theorem 1.9, ... | 由定理 1.9，…… |
| Apply Lemma 1.6 to Theorem 1.9. | 对定理 1.9 应用引理 1.6。 |
| This proves the claim. | 这就证明了该断言。 |
| as required | 如所要求 |
| The statement is that ... | 该陈述为…… |
| In this chapter we prove ... | 本章证明…… |
| The proof follows the argument of ... | 证明沿用……的论证。 |
| The goal is ... | 目标是…… |
| We now ... | 现在我们…… |
| Let us ... | 让我们……（少用，多改为陈述句） |
| It remains to show ... | 只需再证明…… |
| Since A, we get B. | 由 A 得 B。 |
| if ..., then ... | 若……，则…… |
| ..., provided ... | 在……的条件下，…… |
| ..., unless ... | 除非……，否则…… |
| with | 带有／满足（按语境） |
| such that | 使得 |
| where ... | 其中…… |
| here ... | 这里…… |
| note that | 注意 |
| recall that | 回忆 |
| by definition | 按定义 |
| by induction | 用归纳法 |
| by induction on n | 对 n 归纳 |
| along | 沿 |
| along the chain | 沿链 |
| along powers of ℓ | 沿 ℓ 的幂 |
| over p | 在 p 之上（above p：p 上方） |
| above p | p 上方 |
| below ℓ | ℓ 下方 |
| at every place above it | 在其上方每个位处 |
| with respect to | 关于 |
| relative to | 相对于 |
| independent of | 与……无关 |
| depends only on | 仅依赖于 |
| proportional to | 与……成正比 |
| of size | 大小为 |
| on the order of | 量级为 |
| up to a constant | 至多相差一个常数 |
| up to bounded error | 至多相差有界误差 |
| in the sense of | 在……意义下 |
| in the order of the book | 按全书的顺序 |
| for the sake of completeness | 为完整起见 |
| without loss of generality | 不失一般性 |
| as before | 如前 |
| as above | 如上 |
| respectively | 分别 |
| the same | 相同的 |
| a factor of | 相差……倍 |
| by a factor of | 相差……倍 |

---

# 新增术语汇总（各块译稿 NEWTERM 汇总）

| Appell–Humbert Hermitian form | 阿佩尔–洪伯特埃尔米特形式 |
| Appell–Humbert form | 阿佩尔–洪伯特形式 |
| Arakelov degree | 阿拉克洛夫次数 |
| Artin kernel | 阿廷核 |
| Atkin–Lehner–Li | 阿特金–莱纳–李 |
| Barsotti–Tate order | Barsotti–Tate 序 |
| Bass stable rank | Bass 稳定秩 |
| Bergman kernel | Bergman 核 |
| Bessel flag | 贝塞尔旗 |
| Bessel slice | 贝塞尔切片 |
| Bessel subgroup | 贝塞尔子群 |
| Bessel unipotent | 贝塞尔单幂幺群 |
| Bochner integrable | Bochner 可积 |
| Bochner integral | 博赫纳积分 |
| Bockstein torsion | Bockstein 挠 |
| Bolzano–Weierstrass theorem | 波尔查诺–魏尔斯特拉斯定理 |
| Borel measurable | Borel 可测 |
| Borel subalgebra | 博雷尔子代数 |
| Brauer–Nesbitt | 布劳尔–内斯比特 |
| Breuil–Kisin module | Breuil–Kisin 模 |
| Bruhat cell | Bruhat 胞 |
| Bruhat cells | 布鲁哈特胞腔 |
| Bruhat order | 布鲁哈特序 |
| Bézout identity | 贝祖恒等式 |
| CM period torus | CM 周期环面 |
| Capelli determinant | 卡佩利行列式 |
| Cartan coordinates | 嘉当坐标 |
| Cartier dual | Cartier 对偶 |
| Casimir expression | 卡西米尔表达式 |
| Cauchy–Binet | 柯西–比内 |
| Cayley Hermitian matrix | 凯莱埃尔米特矩阵 |
| Cayley–Hamilton algebra | Cayley–Hamilton 代数 |
| Chebotarev density | 切博塔廖夫密度 |
| Chow form | Chow 形式 |
| Chowla–Selberg period | Chowla–Selberg 周期 |
| DVR | 离散赋值环（DVR） |
| Deligne–Ribet | 德利涅–里贝 |
| Dieudonné–Dwork criterion | Dieudonné–Dwork 判别法 |
| Eichler map | Eichler 映射 |
| Eichler transvection | Eichler 平延 |
| Eisenstein polynomial | 艾森斯坦多项式 |
| Eisenstein series | 艾森斯坦级数 |
| Euclidean transference inequality | 欧几里得转移不等式 |
| Euler differential operator | 欧拉微分算子 |
| Fejér mean | Fejér 平均 |
| Fischer form | 菲舍尔形式 |
| Fitting ideal | Fitting 理想 |
| Fock array | 福克阵列 |
| Fock degree | 福克次数 |
| Fock line | 福克线 |
| Fock model | Fock 模型 / 福克模型 |
| Fock norm | 福克范数 |
| Fock vector | 福克向量 |
| Fock vectors | 福克向量 |
| Fontaine prism | Fontaine 棱柱 |
| Fourier tuple | 傅里叶元组 |
| Fourier–Jacobi coefficient | 傅里叶–雅可比系数 |
| Frobenius coinvariants | 弗罗贝尼乌斯余不变量 |
| Frobenius conjugate | Frobenius 共轭 |
| Frobenius contraction | 弗罗贝尼乌斯收缩 |
| Frobenius coordinate | 弗罗贝尼乌斯坐标 |
| Frobenius shift | 弗罗贝尼乌斯位移 |
| Frobenius-horizontal frame | Frobenius 水平标架 |
| Frobenius-semisimplified | 弗罗贝尼乌斯半单化 |
| Frobenius-span | Frobenius 张成 |
| Fubini's theorem | 富比尼定理 |
| Galois bridge | 伽罗瓦桥 |
| Gauss norm | 高斯范数 |
| Gauss valuation | Gauss 赋值 |
| Gauss valuation ring | 高斯赋值环 |
| Gauss-norm bound | 高斯范数界 |
| Gauss-norm identification | 高斯范数等同 |
| Gaussian binomial coefficient | 高斯二项式系数 |
| Gaussian coset sum | 高斯陪集和 |
| Gaussian prefactor | 高斯前因子 |
| Gaussian representation | 高斯表示 |
| Gaussian weighted mean square | 高斯加权均方 |
| Gram correction | Gram 修正 |
| Gram determinant | Gram 行列式 / 格拉姆行列式 |
| Gram fibre | 格拉姆纤维 |
| Gram formula | 格拉姆公式 |
| Gram invariant | 格拉姆不变量 |
| Gram lower bound | 格拉姆下界 |
| Gram mean | Gram 平均 |
| Gram multiplier | 格拉姆乘子 |
| Gram pushforward | Gram 前推 |
| Green orbit | 格林轨道 |
| Green type | 格林型 |
| Greenberg–Wiles | 格林伯格–怀尔斯 |
| Harder–Narasimhan filtration | 哈德–纳拉辛汉滤链 |
| Harish–Chandra | Harish–Chandra（保留） / 哈里什–钱德拉 |
| Harish–Chandra module | Harish–Chandra 模 |
| Harish–Chandra parameter | Harish–Chandra 参数 |
| Harish–Chandra parameter tuple | Harish–Chandra 参数组 |
| Hasse derivative | Hasse 导数 / 哈塞导数 |
| Hasse product formula | Hasse 乘积公式 |
| Hecke function | 赫克函数 |
| Hecke quotient | 赫克商 |
| Hecke reading | 赫克读数 |
| Heisenberg group | 海森堡群 |
| Heisenberg modulation | 海森堡调制 |
| Heisenberg translation operator | 海森堡平移算子 |
| Heisenberg–Weyl translation operator | 海森堡–韦伊平移算子 |
| Hensel | 亨泽尔 |
| Hensel's lemma | 亨泽尔引理 |
| Henselian | 亨泽尔的 |
| Henselian local ring | 亨泽尔局部环 |
| Hermite normal form | 埃尔米特标准形 |
| Hermitian form | 埃尔米特形式 |
| Hermitian frame | 埃尔米特标架 |
| Hermitian orthogonal-extension decomposition | 埃尔米特正交扩张分解 |
| Herr boundary | Herr 边界 |
| Herr class | Herr 类 |
| Herr cocycle | Herr 上闭链 |
| Herr pair | Herr 对 |
| Herr representative | Herr 代表 |
| Hilbert class field | 希尔伯特类域 |
| Hilbert–Schmidt ball | 希尔伯特–施密特球 |
| Hilbert–Schmidt image | 希尔伯特–施密特像 |
| Hilbert–Schmidt norm | Hilbert–Schmidt 范数 / 希尔伯特–施密特范数 |
| Hodge Gram matrix | 霍奇 Gram 矩阵 |
| Hodge determinant line | 霍奇行列式线 |
| Hodge number | 霍奇数 |
| Hodge–Tate frame | 霍奇–泰特标架 |
| Hopf order | Hopf 阶 |
| Hurwitz zeta function | Hurwitz ζ 函数（人名保留拉丁拼写） |
| Hurwitz-integral power series | Hurwitz 整幂级数 |
| Iwahori | Iwahori |
| Iwahori module | 岩堀模 |
| Iwahori subgroup | 岩堀子群 |
| Iwasawa | 岩泽 |
| Iwasawa height | 岩泽高度 |
| Jacobi symbol | 雅可比符号 |
| Jacobowitz discriminant class | Jacobowitz 判别式类 |
| Jacobson radical | 雅各布森根 |
| Jacobson ring | 雅各布森环 |
| Jacquet module | 雅克模块 |
| Jacquet–Shalika | 雅克–沙利卡 |
| Jordan–Hölder constituent | 若尔当–赫尔德成分 |
| K-window | K 窗口 |
| Krasner's lemma | 克拉斯纳引理 |
| Kronecker symbol | 克罗内克符号 |
| Kronecker–Weber | 克罗内克–韦伯 |
| Lagrange basis polynomial | 拉格朗日基多项式 |
| Lagrangian subspace | 拉格朗日子空间 |
| Laplace transform | 拉普拉斯变换 |
| Laplace–Stieltjes differentiation formula | 拉普拉斯–斯蒂尔杰斯求导公式 |
| Laurent coefficient | 洛朗系数 |
| Laurent line | 洛朗线 |
| Lebesgue measurability | 勒贝格可测性 |
| Levi | 莱维 |
| Levi block | Levi 块 |
| Levi form | 列维形式 |
| Levi subgroup | 列维子群 |
| Lie derivative | 李导数 |
| Lie scale factor | 李标度因子 |
| Lie-trace signature | Lie 迹符号差 |
| Lyndon word | 林登字 |
| Mellin transform | 梅林变换 |
| Moret-Bailly key section | Moret-Bailly 关键截面 |
| Morita multiplicity | Morita 重数 |
| Nadel vanishing | Nadel 消没 |
| Nakayama's lemma | 中山引理 |
| Neumann series | Neumann 级数 |
| Newton number | 牛顿数 |
| Newton polygon | 牛顿多边形 |
| Newton power sum | 牛顿幂和 |
| Newton slope | 牛顿斜率 |
| Newton's identities | 牛顿恒等式 |
| Noetherian limit reduction | 诺特性极限归约 |
| Nullstellensatz | 零点定理 |
| PEL datum | PEL 数据 |
| PEL object | PEL 对象 |
| Petersson adjoint | 彼得松伴随 |
| Petersson pairing | 彼得松配对 |
| Pieri rule | Pieri 规则 / 皮耶里规则 |
| Poincaré series | 庞加莱级数 |
| R^2-null-value | R^2-零值 |
| Satake multiset | Satake 多重集 |
| Satake parameters | 佐武参数 |
| Satake transform | Satake 变换 / 佐武变换 |
| Satake union | Satake 并 |
| Schrödinger coordinates | 薛定谔坐标 |
| Schrödinger model | 薛定谔模型 |
| Schur alternant | Schur 交错式 |
| Schur complement | Schur 补 |
| Schur lattice | 舒尔格 |
| Schur orthogonality | 舒尔正交性 |
| Schur–Weyl duality | 舒尔–外尔对偶 |
| Selmer length | 塞尔默长度 |
| Selmer ratio | 塞尔默比 |
| Sen decompletion matrix | Sen 去完备化矩阵 |
| Sen multiplicity | Sen 重数 |
| Shapiro's lemma | Shapiro 引理 |
| Siegel induction | 西格尔诱导 |
| Siegel parabolic | 西格尔抛物子群 |
| Siegel ray | Siegel 射线 |
| Siegel set | 西格尔集 |
| Siegel-cone convergence criterion | Siegel 锥收敛判别法 |
| Siegel–Klingen | 西格尔–克林根 |
| Siegel–Weil point | Siegel–Weil 点 |
| Smith coordinates | Smith 坐标 / 史密斯坐标 |
| Smith divisor | Smith 除子 |
| Smith entry | Smith 分量 |
| Smith estimate | 史密斯估计 |
| Smith form | 史密斯标准形 |
| Smith normal form | Smith 标准形 / 史密斯标准形 |
| Smith reduction | 史密斯约化 |
| Tamagawa measure | 玉河测度 |
| Teichmüller label | Teichmüller 标号 |
| Teichmüller lift | 泰希米勒提升 |
| Wach basis | Wach 基 |
| Wach connection | Wach 联络 |
| Wach criterion | Wach 判别法 |
| Wach lattice | Wach 格 |
| Wach representative | Wach 代表元 |
| Weierstrass coordinates | 魏尔斯特拉斯坐标 |
| Weierstrass discriminant | 魏尔斯特拉斯判别式 |
| Weierstrass equation | 魏尔斯特拉斯方程 |
| Weierstrass function | 魏尔斯特拉斯函数 |
| Weil element | 韦伊元素 |
| Weil equivariance | 韦伊等变性 |
| Weil system | 韦伊系统 |
| Weil–Deligne class | 韦伊–德利涅类 |
| Weil–Deligne parameter | 韦伊–德利涅参数 |
| Weil–Deligne space | 韦伊–德利涅空间 |
| Weyl | 外尔 |
| Weyl alternation | 外尔交错化 |
| Weyl chamber | Weyl 腔 |
| Weyl cone | Weyl 锥 |
| Weyl dimension | Weyl 维数 |
| Weyl generator | 外尔生成元 |
| Weyl weight lattice | 外尔权格 |
| Whittaker multiplicity | 惠特克重数 |
| Witt Frobenius | Witt 弗罗贝尼乌斯 |
| Witt basis | Witt 基 |
| Witt decomposition | 维特分解 |
| Witt frame | 维特标架 / 维特框架 |
| Witt index | 维特指数 |
| Witt matrix | Witt 矩阵 |
| Witt middle space | 维特中间空间 |
| Witt ring | 维特环 |
| Witt tower | 维特塔 |
| abelian CM host | 阿贝尔 CM 宿主域 |
| abelian layer index | 阿贝尔层指标 |
| abscissa | 横坐标 |
| absent | 缺失 |
| absolute amplitude estimate | 绝对振幅估计 |
| absolute different | 绝对差积 |
| absolute fractional-ideal norm | 绝对分式理想范数 |
| absolute norm | 绝对范数 |
| absolute summability | 绝对可和性 |
| absolute-convergence region | 绝对收敛区域 |
| absolutely reproducing coefficient | 绝对再生系数 |
| absorption condition | 吸收条件 |
| accumulation point | 聚点 |
| active twist place | 活跃扭曲位 |
| active weight | 活动权重 |
| adapted basis | 适应基 / 适配基 |
| adapted coordinates | 适配坐标 |
| adapted de Rham basis | 适应的 de Rham 基 |
| adapted normal form | 适应正规形式 |
| addition defect | 加法缺陷 |
| additive character | 加法特征 |
| additive covolume | 加法余体积 |
| additive orthogonality | 加性正交性 |
| additive rows | 加性行 |
| additivity defect | 加性缺陷 |
| adelic centralizer | 阿代尔中心化子 |
| adelic class set | 阿代尔类集 |
| adelic quotient measure | 阿代尔商测度 |
| adically continuous | ℓ 进连续的 |
| adjacent-rank mass formula | 相邻秩质量公式 |
| adjacent-rank quotient | 邻秩商 |
| adjacent-weight midpoint | 相邻权中点 |
| adjoint action | 伴随作用 |
| adjoint cocycle | 伴随上闭链 |
| adjoint defect | 伴随缺陷 |
| adjoint involution | 伴随对合 |
| adjoint law | 伴随律 |
| adjoint model identifications | 伴随模型等同 |
| adjoint representation | 伴随表示 |
| adjugate | 伴随矩阵 / 伴随矩阵（adj） / 伴随（伴随矩阵） |
| adjugate identity | 伴随恒等式 |
| adjugate-pairing factor | 伴随配对因子 |
| admissibility | 可接纳性 |
| admissible Gaussian parameter tuple | 容许高斯参数组 |
| admissible Hermitian space | 容许埃尔米特空间 |
| admissible cocycle | 容许上闭链 |
| admissible double orbit | 容许双轨道 |
| admissible family | 容许族 |
| admissible finite module | 容许有限模 |
| admissible for | 对……容许 |
| admissible integer pair | 容许整数对 |
| admissible level modulus | 容许水平模 |
| admissible list | 容许列表 |
| admissible representation | 容许表示 |
| admissible slot coefficient | 容许槽系数 |
| admissible system | 容许系统 |
| admission bound | 接纳界 |
| admitted at | 在……处被接纳 |
| advance/progression-window coefficient | 推进窗口系数 |
| aggregated sum | 聚合和 |
| alcove | alcove（保留原文） |
| algebra of rules | 规则代数 |
| algebraic Hecke character | 代数赫克特征 |
| algebraic integral closedness | 代数整闭性 |
| algebraic integral frame | 代数整标架 |
| all-place expansion | 全位展开 |
| all-row index | 全行指标 |
| all-thick alternative | 全厚替代情形 |
| allowable | 可容许 |
| allowable exponent | 容许指数 |
| allowance | 允许量 / 容许量 / 配额 |
| allowed finite-order character | 容许的有限阶特征 |
| allowed lift | 容许提升 |
| alternating contraction | 交错缩并 |
| alternating deletion sum | 交错删除和 |
| ambient dimension | 环境维数 |
| ambient lattice | 环境格 |
| ambient space | 环绕空间 |
| amplitude | 振幅 |
| amplitude factor | 幅度因子 |
| amplitude inequality | 幅度不等式 |
| amplitude threshold | 振幅阈值 |
| analytic box | 解析盒 |
| analytic closure | 解析封闭性 |
| analytic interface | 解析接口 |
| analytic uniformisation | 解析单值化 |
| angular character | 角特征 |
| angular exponent | 角指数 |
| angular infinity exponent | 角无穷指数 |
| anisotropic | 非迷向的 |
| anisotropy | 非迷向性 |
| annihilation | 湮灭 |
| annihilator | 零化子 |
| annihilator (of a form) | 零化子 |
| annihilator statement | 零化子陈述 |
| anti-invariant entry | 反不变项 |
| anti-invariant unit | 反不变单位 |
| anticyclotomic | 反分圆 / 反循环的 |
| antidiagonal | 反对角的 |
| antipode | 对极 |
| antitone weight | 反单调权 |
| apartment | 公寓 |
| apparent singularity | 表观奇点 |
| approximant | 逼近元 |
| approximate-identity property | 近似恒等性质 |
| archimedean index | 阿基米德指标 |
| archimedean product place | 阿基米德积位 |
| archimedean space | 阿基米德空间 |
| archimedean theta-constant bound | 阿基米德西塔常数界 |
| archive field | 存档字段 |
| area pairing | 面积配对 |
| arithmetic carrier | 算术载体 |
| arithmetic chart | 算术卡 |
| arithmetic column family | 算术列族 |
| arithmetic covolume | 算术余体积 |
| arithmetic curve | 算术曲线 |
| arithmetic datum | 算术数据 |
| arithmetic difference | 算术差 |
| arithmetic differential operator | 算术微分算子 |
| arithmetic flag height functional | 算术旗高度泛函 |
| arithmetic host | 算术宿主 |
| arithmetic host conditions | 算术宿主条件 |
| arithmetic interface | 算术接口 |
| arithmetic involution | 算术对合 |
| arithmetic label | 算术标号 |
| arithmetic length | 算术长度 |
| arithmetic passage | 算术过渡 |
| arithmetic point datum | 算术点数据 |
| arithmetic requirement | 算术要求 |
| arithmetic row system | 算术行系统 |
| arithmetic rows | 算术行 |
| arithmetic space | 算术空间 |
| arithmetic valuation | 算术赋值 |
| arithmetic variety | 算术簇 |
| arithmetic volume | 算术体积 |
| assigned value | 指定值 |
| assignment | 指派 |
| associated graded | 相伴分次 |
| attachment | 关联 / 附属表示 / 附着 |
| augmentation ideal | 增广理想 |
| augmented chain | 增广链 |
| augmented complex | 增广复形 |
| augmented extension | 增广扩张 |
| augmented tuple | 增广元组 |
| autocorrelation coefficient | 自相关系数 |
| auxiliary label | 辅助标号 |
| auxiliary level prime | 辅助水平素数 |
| auxiliary rank | 辅助秩 |
| auxiliary size | 辅助大小 |
| auxiliary weight | 辅助权重 |
| auxiliary-prime bound | 辅助素数界 |
| auxiliary-rank exponent | 辅助秩指数 |
| averaged counting measure | 平均计数测度 |
| averaging projector | 平均投影算子 |
| avoidance set | 回避集 |
| backward interval | 反向区间 |
| bad position | 坏位置 |
| bad rows | 坏行 |
| bad set | 坏集 |
| bad tuple | 坏元组 |
| bad-label weight | 坏标号的权 |
| bad-orbit bound | 坏轨道界 |
| bad-prime set | 坏素数集 |
| balanced form | 平衡形式 |
| ball-packing bound | 球填充界 |
| band condition | 带条件 |
| bandwidth formula | 带宽公式 |
| bar cohomology | bar 上同调 |
| bar cycle | bar 循环 |
| bar cycles | 杠循环 |
| bar prism | 杠棱柱 |
| bar ranks | 杠秩 |
| bare realization | 裸实现 |
| bare-Satake substitution | 佐武代换 |
| barred fibre | 带杠纤维 |
| barred model | 加横线模型 / 带横杠模型 |
| barycentre | 重心 |
| base column exponent | 基本列指数 |
| base forms | 基形式 |
| base frame | 基框架 |
| base idele | 基伊代尔 |
| base level | 基水平 |
| base pair | 基对 |
| base size | 基大小 |
| base spectrum | 基谱 |
| base term | 基项 |
| base-change multiset | 基变换重集 |
| bi-invariant | 双不变的 |
| bi-rigidified | 双刚性化的 |
| biadditive | 双可加 |
| bidegree | 双次数 |
| bideterminant | 双行列式 |
| bideterminant basis | 双行列式基 |
| biextension | 双扩张 |
| biextension cocycle | 双扩张余环 |
| big block | 大块 |
| big-cell | 大胞腔 |
| big-cell section | 大胞腔截面 |
| bigness | 大性 |
| bigraded | 双分次的 |
| binary coordinate | 二元坐标 |
| binary word | 二值词 |
| binomial moments | 二项式矩 |
| bit | 比特 |
| block | 块 |
| block Gram estimate | 块格拉姆估计 |
| block character | 块特征 |
| block depth | 块深度 |
| block dominant | 块支配 |
| block eigenvalue | 块特征值 |
| block lattice | 块格 |
| block level | 块水平 |
| block locus | 块轨迹 |
| block oscillation | 块振幅 |
| block parabolic | 块抛物子群 |
| block parameter | 块参数 |
| block point | 块点 |
| block positivity | 块正性 |
| block projector | 块投影子 |
| block rigidity | 块刚性 |
| block shortening | 块缩短 |
| block size | 块大小 |
| block-end minor | 块端子式 |
| block-triangular | 块三角的 |
| bordered factor | 加边因子 |
| bordered minor | 加边子式 |
| borrow | 借位 |
| bottom core | 底部核心 |
| bottom number | 底部数 |
| bottom pair | 底部对 / 底部配对 / 底配对 |
| bottom theta triple | 底部西塔三元组 |
| bottom weight bound | 底部权界 |
| bottom witness | 底部见证 |
| bottom-weight window | 底权重窗口 |
| bound for the retained character sum | 保留特征和的界 |
| boundary class | 边界类 |
| boundary digit component | 边界数字分量 |
| boundary letter | 边界字母 |
| boundary multiplier | 边界乘子 |
| bounded homomorphism graph | 有界同态图 |
| bounding cochain | 界定上链 |
| bounding matrix | 界矩阵 |
| box conditions | 盒条件 |
| box count | 框数 |
| box height | 盒高度 |
| box weight | 盒子权重 / 盒权重 |
| branch | 分支 |
| branch multiset | 分支多重集 |
| branch rank | 分支秩 |
| branch-permutation group | 分支置换群 |
| branching coefficient | 分支系数 |
| branching rule | 分支规则 |
| bridge (of embeddings) | 桥 |
| bridge entry | 桥接元素 |
| bridge identity | 桥恒等式 |
| built member | 已建成员 |
| built point | 已建点 |
| built-in family normalization | 内置族正规化 |
| bump (function) | 鼓包 |
| bundle supply | 丛供给 |
| cancellation | 消去 |
| candidate prime | 候选素数 |
| candidate set | 候选集 |
| canonical path polynomial | 典范路径多项式 |
| cap | 上限 |
| capacity | 容量 |
| capacity vector | 容量向量 |
| capitulation generator | 投降生成元 |
| carry | 进位 |
| carry inequality | 进位不等式 |
| carry product | 进位乘积 |
| carrying section | 承载截面 |
| carrying-order bound | 承载阶界 |
| ceiling | 上取整 |
| cell | 单元 / 胞腔 |
| cell (identity cell) | 胞腔（恒等胞腔） |
| cell product | 格子乘积 |
| central multiplicity bound | 中心重数界 |
| central parameter | 中心参数 |
| centre bound | 中心界 |
| centred prime sum | 中心化素数和 |
| centred smoothed prime sums | 中心化光滑素数和 |
| centring | 中心化 |
| centring term | 中心化项 |
| chain bound | 链界 |
| chain constants | 链常数 |
| chain cut | 链割 |
| chain data | 链数据 |
| chain data at a host | 宿主处的链数据 |
| chain denominator | 链分母 |
| chain eigenvalue | 链特征值 |
| chain length | 链长 / 链长度 |
| chain order | 链阶 |
| chain prefix | 链前缀 |
| chain window | 链窗口 |
| chamber | 房 / 房（Weyl 房） / 胞腔 |
| chamber eigenspace | 房特征空间 |
| chamber operator | 胞腔算子 |
| change of frame | 框架变换 |
| change-of-variables theorem | 变量替换定理 |
| character class | 特征类 |
| character factor | 特征因子 |
| character frame | 特征框架 |
| character grid | 特征格网 |
| character level | 特征层次 |
| character orthogonality | 特征正交性 |
| character pin | 特征钉 |
| character subclass | 特征子类 |
| character-pair summation | 特征对求和 |
| characteristic tuple | 特征元组 |
| charge | 记账 |
| chart lattice | 卡格 |
| chart lattice test | 卡格检验 |
| chart perturbation | 卡扰动 |
| chart series | 卡级数 |
| chart test | 卡检验 |
| choice of ties | 绑定的选择 |
| choice record | 选择记录 |
| choice spacing | 选择间距 |
| circle extension | 圆扩张 |
| circle maximum | 圆周最大值 |
| class Gram matrix | 类 Gram 矩阵 |
| class and minor counts | 类计数与子式计数 |
| class denominator | 类分母 |
| class expansion | 类展开 |
| class factor | 类因子 |
| class form | 类形式 |
| class lattice | 类格 |
| class mean | 类平均 |
| class order | 类序 |
| class presentation | 类表示 |
| class realization | 类实现 |
| class set | 类集 |
| class sum | 类和 / 类求和 |
| class-sum formula | 类和公式 |
| class-sum pairing | 类和配对 |
| clause | 子句 / 条 |
| cleared-denominator | 清分母 |
| cleared-denominator line | 清分母线 |
| cleared-denominator representative | 清分母代表 |
| clearing condition | 清除条件 |
| clearing integer | 清除整数 |
| clearing power | 清分母幂 / 清除幂 |
| clopen | 开闭子集 / 既开又闭的 |
| closed half-plane | 闭半平面 |
| closed on | 在……上封闭 |
| closedness quantifier | 闭性量词 |
| closure of a defect bound | 缺陷界的封闭性 |
| cloud | 云 |
| cloud coordinate | 云坐标 |
| cloud entry | 云元素 |
| cloud jump | 云跳跃 |
| cloud spread | 云散布 |
| cloud-coordinate scale | 云坐标标度 |
| cloud-window | 云窗口 |
| coarse factorial | 粗阶乘 |
| coboundary | 上边缘 / 余边界 |
| cobounding element | 给出上边缘的元素 |
| cobounding scalar | 余边界标量 |
| cochain | 上链 |
| cochain prism homotopy | 上链棱柱同伦 |
| cocharacter | 余特征 |
| cocycle | 上链 / 上闭链 / 余圈 / 余循环 |
| cocycle / coboundary | 上链／上边缘 |
| cocyclic | 余循环的 |
| codifferent | 余不同 / 余差积 |
| coefficient DVR | 系数 DVR |
| coefficient chain | 系数链 |
| coefficient embedding | 系数嵌入 |
| coefficient family | 系数族 |
| coefficient fibre | 系数纤维 |
| coefficient field | 系数域 |
| coefficient group | 系数群 |
| coefficient induction | 系数归纳 |
| coefficient lattice | 系数格 |
| coefficient list | 系数列表 |
| coefficient lower-bound relation | 系数下界关系 |
| coefficient representation | 系数表示 |
| coefficient space | 系数空间 |
| coefficient tower | 系数塔 |
| coefficient wave action | 系数波作用 |
| coefficient-field condition | 系数域条件 |
| coefficient-place order | 系数位阶 |
| coefficient-to-lattice implication | 系数到格的蕴含 |
| cohomological core | 上同调核心 |
| cohomological window hypothesis | 上同调窗口假设 |
| coincidence locus | 重合轨迹 |
| coinvariant | 余不变的 |
| coinvariant map | 余不变量映射 |
| coinvariant module | 余不变量模 |
| coinvariants | 余不变量 |
| coisometry | 余等距 |
| cokernel exponent | 余核指数 |
| colength | 余长 / 余长度 |
| collapsed exponent | 坍缩指数 |
| collar bound | 环带界 |
| collision sum | 碰撞和 |
| column bound | 列界 |
| column bridge | 列桥 |
| column budget | 列预算 |
| column choice | 列选择 |
| column height | 列高 |
| column isometry | 列等距 |
| column linearity | 列的线性性 |
| column minor | 列子式 |
| column module | 列模 |
| column moment | 列矩 |
| column period | 列周期 |
| column place | 列位 |
| column record | 列记录 |
| column-then-row order | 先列后行次序 |
| commensurable | 可公度的 |
| commensurable lattice | 可公度格 |
| common coordinate row lattice | 公共坐标行格 |
| common cover | 公共覆盖 |
| common denominator condition | 公分母条件 |
| common dual | 公共对偶 |
| common entry estimate | 公共矩阵元估计 |
| common inertia | 公共惯性群 |
| common minimal vector | 公共极小向量 |
| common row lattice | 公共行格 |
| common width | 公共宽度 |
| common window | 公共窗口 |
| common-denominator condition | 公分母条件 |
| common-weight exponent | 公共权重指数 |
| common-weight hypothesis | 公共权重假设 |
| common-weight loss hypothesis | 公共权重损失假设 |
| commutant | 交换子 |
| commutator | 换位子 |
| commuting square | 交换方形 |
| compact Nakayama | 紧 Nakayama 引理 / 紧致 Nakayama |
| compact Weyl product | 紧韦伊乘积 |
| compact annulus | 紧环形区域 |
| compact coefficient class | 紧致系数类 |
| compact dual | 紧对偶 |
| compact type | 紧致型 |
| compact-dual measure | 紧对偶测度 |
| compact-finite | 紧致有限 |
| compact-type conditions | 紧型条件 |
| companion | 同伴 |
| companion matrix | 友矩阵 |
| companion word | 伴随词 |
| comparison factor | 比较因子 |
| comparison field | 比较域 |
| comparison frame | 比较框架 |
| comparison input | 比较输入 |
| comparison multiplier | 比较乘子 |
| comparison operator | 比较算子 |
| compatible expansion | 相容展开 |
| compatible regularisation | 相容正则化 |
| competing plane | 竞争平面 |
| complement lattice | 补格 |
| complementary budget | 互补预算 |
| complementary final set | 互补最终集 |
| complementary period bound | 补余周期界 |
| complementary summand | 补直和项 |
| complementary variable | 补变量 |
| complete choice | 完全选择 |
| complete framed ring | 完全框架环 |
| complete minimum system | 完全极小系统 |
| complete reducibility | 完全可约性 |
| complete ring | 完备环 |
| complete row label | 完整行标号 |
| completed host | 完备化宿主 |
| completed local ring | 完备化局部环 |
| completely split | 完全分裂 |
| completion hypothesis | 完备化假设 |
| complex Hessian | 复 Hessian |
| complex enveloping algebra | 复包络代数 |
| complex input space | 复输入空间 |
| component Bergman supremum | 分量 Bergman 上确界 |
| component coefficient | 分支系数 |
| component decomposition | 分量分解 |
| component propagation | 分量传播 |
| component–lattice pair | 分量–格对 |
| composite formula | 复合公式 |
| composition (of an integer) | 有序分拆 |
| composition factor | 合成因子 |
| compositum | 复合域 |
| compositum inequalities | 复合域不等式 |
| conditioned measure | 条件化测度 |
| conductor bound | 导子界 |
| conductor condition | 导子条件 |
| conductor exponent | 导子指数 |
| conductor pair | 导子对 |
| conductor set | 导子集 |
| cone cohomology | 锥上同调 |
| cone-semipositive | 锥半正 / 锥半正的 |
| congruence depth | 同余深度 |
| congruence kernel | 同余核 |
| congruence length | 同余长度 |
| conjoin | 合取 |
| conjugate pairing | 共轭配对 |
| conjugate place | 共轭位 |
| conjugate self-dual | 共轭自对偶 |
| conjugate twist place | 共轭扭曲位 |
| conjugate-coprime | 共轭互素的 |
| conjugation defect | 共轭缺陷 |
| conjugation orbit | 共轭轨道 |
| connected ordinary formal group | 连通寻常形式群 |
| consistent presentation | 一致表示 |
| constant Laurent coefficient | 常数洛朗系数 |
| constant signature | 常符号差 |
| constant-coefficient reduction | 常系数归约 |
| constructed point | 构造点 |
| construction class | 构造类 |
| construction context | 构造语境 |
| containment budget | 包含预算 |
| containment test | 包含检验 |
| contraction | 缩并 |
| contraction counts | 缩并计数 |
| contraction criterion | 收缩判据 |
| contragredience | 反步 |
| contragredient | 反变表示 / 反步表示 / 对偶表示 |
| contravariant form | 反变形式 |
| convexity bound | 凸性界 |
| convolution power | 卷积幂 |
| coordinate ball | 坐标球 |
| coordinate bilinear pairing | 坐标双线性配对 |
| coordinate column map | 坐标列映射 |
| coordinate derivation | 坐标导子 |
| coordinate response | 坐标响应 |
| coordinate-integrality allowance | 坐标整性容许量 |
| coordinate-subset basis refinement | 坐标子集基加细 |
| coprime | 互素 |
| corank | 余秩 |
| corank one | 余秩一 |
| core depth test | 核心深度检验 |
| core specialization | 核心特化 |
| core type lattice | 核心型格 |
| corestriction | 余限制 |
| corrected curve phase | 修正曲线相位 |
| coset counts | 陪集计数 |
| coset indicator | 陪集指示函数 |
| coset share | 陪集份额 |
| coset vacuum | 陪集真空 |
| coset-sum estimate | 陪集和估计 |
| cosocle | 余基座 |
| cost inequality | 代价不等式 |
| costly | 有代价的 |
| cotangent quotient | 余切商 |
| cotangent weight | 余切权 |
| counit | 余单位 |
| count normalizer | 计数归一化子 |
| counted gain | 计数增益 |
| counted gain / served gain | 计得增益／服务增益 |
| counting constant | 计数常数 |
| counting input | 计数输入 |
| counting measure | 计数测度 |
| counting threshold | 计数阈值 |
| covector | 余向量 |
| covector condition | 余向量条件 |
| covector mark | 余向量标记 |
| cover place | 覆盖位 |
| cover slope | 覆盖斜率 |
| covering property | 覆盖性质 |
| covering radius | 覆盖半径 |
| covolume | 余体积 |
| covolume class | 余体积类 |
| covolume comparison | 余体积比较 |
| creation operator | 创造算子 |
| critical level | 临界水平 |
| cross-block | 交叉块 / 跨块 |
| cross-resultant valuation | 交叉结式赋值 |
| cross-wall | 跨墙 |
| crossed homomorphism | 交叉同态 |
| crystalline | 晶体的 |
| crystalline (representation) | 晶体的（表示） |
| crystalline O-lattice | 晶体 O-格 |
| crystalline admissibility | 晶体容许性 |
| crystalline data | 晶体数据 |
| crystalline full realization | 晶体完全实现 |
| crystalline homology | 晶化同调 |
| crystalline interpolation | 晶体插值 |
| crystalline lattice | 晶体格 |
| cubical | 立方的 |
| cubical law | 立方律 |
| cubical period | 立方周期 |
| cubical trivialisation | 立方平凡化 |
| curve datum | 曲线数据 |
| curve ideal | 曲线理想 |
| curve law | 曲线律 |
| cusp form | 尖点形式 |
| cusp principal parts | 尖点主部 |
| cusp rank | 尖点秩 |
| cusp rapid decay | 尖点快速衰减 |
| cusp scale | 尖点标度 |
| cusp section | 尖点截面 |
| cuspidal attachment | 尖点伴随 / 尖点附着 |
| cuspidal character | 尖点特征 |
| cuspidal decay | 尖点衰减 |
| cuspidal isometry | 尖点等距 |
| cuspidal rapid decrease | 尖点快速递减 |
| cuspidal small model section | 尖点小模型截面 |
| cuspidal support | 尖点支撑 |
| cuspidal theta class | 尖点西塔类 |
| cuspidality | 尖点性 |
| cut | 割 / 割（链割） / 截断 |
| cut (of an isotypic space) | 截片 |
| cut allowance | 割额度 |
| cut cocycle | 切割上闭链 / 割上闭链 / 截断上闭链 |
| cut estimate | 截断估计 |
| cut exponent | 割指数 |
| cut lattice | 割格 / 割格（沿用既有译名） |
| cut remainder exponent | 切割余项指数 |
| cut set | 切割集 |
| cut space | 截断空间 |
| cut width | 截断宽度 |
| cut word | 截断词 |
| cutoff | 截断 |
| cutoff decomposition | 截断分解 |
| cutoff flag | 截断旗 |
| cycle length | 轮换长度 |
| cyclic carries | 循环进位 |
| cyclic carry | 循环进位 |
| cyclic host requirement | 循环宿主要求 |
| cyclic level | 循环层次 |
| cyclic origin | 循环起点 |
| cyclic requirement | 循环要求 |
| cyclic summand | 循环直和项 |
| cyclic word | 循环词 |
| cyclotomic degree bound | 分圆次数界 |
| cyclotomic derivative | 分圆导数 |
| cyclotomic kernel | 分圆核 |
| cyclotomic module | 分圆模 |
| cylinder function | 柱函数 |
| cylinder projector | 柱投影 / 柱投影子 |
| d-sign | $d$-符号 |
| de Rham jump condition | de Rham 跳跃条件 |
| deck correspondence | 覆叠对应 |
| deck eigenvalues | 覆叠特征值 |
| deck group | 覆叠群 |
| deck map | 覆叠映射 |
| deck operator | 覆叠算子 |
| decorated pair | 带装饰对 |
| decorated point | 带标记的点 |
| deep congruence | 深同余 |
| deep cover | 深度覆盖 |
| deep goodness | 深好性 / 深度良好性 |
| deep region | 深区域 |
| deep-congruence estimate | 深同余估计 |
| defect | 亏量 / 偏差 / 缺陷 |
| defect bound | 缺陷界 |
| deficit | 亏量 |
| definite CM theta pair | 定 CM 西塔对 |
| definite Gram comparison | 定格拉姆比较 |
| definite adelic quotient | 定阿代尔商 |
| definite bottom triple | 定底部三元组 |
| definite class | 定类 |
| definite class form | 定类形式 |
| definite column condition | 定列条件 |
| definite comparison | 定比较 |
| definite embedding | 定嵌入 |
| definite face | 定面 |
| definite frame | 定框架 |
| definite genus factor | 定亏格因子 |
| definite genus mass | 定属质量 |
| definite side | 定侧 |
| definite table | 定表 |
| definite trace | 定迹 |
| definite-unitary | 定酉的 |
| degenerate minor relation | 退化子式关系 |
| degenerate part | 退化部分 |
| degeneration trait | 退化 trait |
| degree deficit | 次数亏损 |
| deletion faces | 删除面 |
| denominator coefficient | 分母系数 |
| denominator cost | 分母代价 |
| denominator function | 分母函数 |
| denominator module | 分母模 |
| denominator-loss function | 分母损失函数 |
| denominator-normalised height | 分母正规化高度 |
| dense-vanishing argument | 稠密消没论证 |
| depletion | 耗尽 |
| depth coefficient | 深度系数 |
| depth identity | 深度恒等式 |
| depth lattice | 深度格 |
| depth zero | 深度零 |
| depth-zero base | 深度零基 |
| depth-zero support | 零深度支集 |
| derivation | 导子 |
| descended | 下降的 |
| descending induction | 下降归纳 |
| descent data | 下降数据 |
| design class | 设计类 |
| design supply | 设计供给 |
| determinant cutoff | 行列式截断 |
| determinant double cover | 行列式双覆盖 |
| determinant ideal | 行列式理想 |
| determinant lattice | 行列式格 |
| determinant law | 行列式律 |
| determinant multidegree | 行列式多重次数 |
| determinant order | 行列式阶 |
| determinant ratio | 行列式比 |
| determinant regularity | 行列式正则性 |
| determinant trick | 行列式技巧 |
| determinant twist | 行列式扭曲 |
| determinant-length formula | 行列式长度公式 |
| determinant-shell sequence | 行列式壳序列 |
| diagonal identity | 对角恒等式 |
| diagram size | 图的大小 |
| diamond | 菱形（算子） |
| diamond action | 菱形作用 |
| diamond character | 菱形特征 |
| diamond kernel | 菱形核 |
| diamond relation | 菱形关系 |
| diamond sum | 菱形和 |
| diamond translation | 菱形平移 |
| diamond transport | 菱形传输 |
| dichotomy | 二分法 |
| differential evaluation | 微分求值 |
| differential ideal | 微分理想 |
| differential pairing | 微分配对 |
| differential-operator lift | 微分算子提升 |
| digit block | 数字块 |
| digit class | 数字类 |
| digit component | 数字分量 |
| digit error | 数位误差 |
| digit length | 数字长度 |
| digit loss | 数字损失 |
| digit row | 数位行 |
| digit sum | 数字和 |
| digit-loss constant | 数字损失常数 |
| dilated polydisk | 膨胀多圆盘 |
| direct quotient frame | 直商框架 |
| direct summand | 直和项 |
| direct-sum test lattice | 直和测试格 |
| direction | 方 |
| directional derivative | 方向导数 |
| directional determinant | 方向行列式 |
| discard criterion | 丢弃判别 |
| discarded primes | 被丢弃的素数 |
| discarded proportion | 丢弃比例 |
| discarded set | 弃置集 |
| discrete series | 离散系列 |
| discrete valuation ring (DVR) | 离散赋值环 |
| discrete valuation ring criterion | 离散赋值环判别准则 |
| discrete-series covering | 离散系列覆盖 |
| discrete-series realization | 离散系列实现 |
| discriminant class | 判别式类 |
| discriminant module | 判别式模 |
| discriminant order | 判别式阶 |
| discriminant twelfth-root period | 判别式十二次根周期 |
| disjoint union | 不交并 |
| disjoint-product | 不交乘积 |
| displacement bound | 位移界 |
| distinguished | 特异的 |
| distinguished Gram minor | 指定格拉姆子式 |
| distinguished embedding | 指定嵌入 |
| distinguished line | 指定直线 |
| distinguished local ring | 特异局部环 |
| distinguished place | 指定位 |
| distinguished polynomial | 特异多项式 |
| distinguished prime | 指定素数 |
| distinguished subgroup | 指定子群 |
| distinguished vector | 指定向量 |
| distinguished-place bound | 特定位界 |
| divided column | 除后列 |
| divided column module | 除法之后的列模 |
| divided derivative | 除幂导数 |
| divided diagonal derivative | 除幂对角导数 |
| divided difference | 差商 |
| divided lattice | 除法格 |
| divided power | 分幂 / 除幂 |
| divided power lattice | 除幂格 |
| divided powers | 分割幂 / 除幂 |
| divided root | 除根 |
| divided root operator | 除根算子 |
| divided submodule | 除法子模 |
| divided-power content | 除幂内容 |
| divided-power envelope | 分幂包络 / 除幂包络 |
| divided-power ideal | 除幂理想 |
| divided-power jet | 除幂射流 |
| divided-power operator | 除幂算子 |
| divided-power stability | 除幂稳定性 |
| divided-power thickening | 除幂加厚 |
| divided-power word | 除幂字 / 除幂词 |
| divided-root words | 除根字 |
| division condition | 除法条件 |
| division data | 除法数据 |
| division datum | 除法数据 |
| division ideal | 除法理想 |
| division kernel datum | 除法核数据 |
| division tie | 除法绑定 |
| division ties | 除法联系 |
| divisor bound | 除数界 |
| divisor counting | 除子计数 |
| domain frame | 区域标架 / 域标架 |
| dominance | 主导性 |
| dominance order | 支配序 |
| dominant | 支配的 |
| dominant base weight | 支配基权重 |
| dominant class | 支配类 |
| dominant weight | 主导权重 |
| double orbit | 双轨道 |
| double-coset class set | 双陪集类集 |
| double-coset construction | 双陪集构造 |
| double-definite witness | 双定见证 |
| doubled integral shift | 加倍的整移位 |
| doubling | 倍化 / 倍增 |
| doubling embedding | 倍增嵌入 / 加倍嵌入 |
| doubling height | 加倍高度 |
| doubling integral | 倍增积分 |
| doubling method | 加倍法 |
| down operator | 下算子 |
| down-up calculation | 下–上计算 |
| downward | 向下的 |
| dressed letter matrix | 修饰字母矩阵 |
| dressed scalar | 修饰标量 |
| drop set | 下降集 |
| dual charge | 对偶收费 |
| dual minimizer | 对偶极小元 |
| dual numbers | 对偶数 |
| dual separation | 对偶分离性 |
| dual sheet | 对偶叶 |
| dual-lattice point | 对偶格点 |
| dual-number lift | 对偶数提升 |
| dual-number point | 对偶数点 |
| duality inequality | 对偶不等式 |
| dyadic | 二进的 |
| dyadic block | 二进块 |
| dyadic box | 二进盒 |
| dyadic disk packing | 二进圆盘填充 |
| dyadic estimate | 二进估计 |
| dyadic shell | 二进壳层 |
| dévissage | 逐层剥离 |
| edge denominator | 边缘分母 |
| edge frame | 边框架 |
| edge rank | 边秩 |
| effective class | 有效类 |
| eigen-column theta family | 特征列西塔族 |
| eigenbasis | 特征基 |
| eigenbundle | 特征丛 |
| eigencharacter | 本征特征 |
| eigenframe | 特征标架 |
| eigenlattice | 特征格 |
| eigenlift | 特征提升 |
| eigenline | 特征直线 / 特征线 |
| eigenspace | 特征空间 |
| eigenspan | 特征张成 |
| eigensystem | 特征系统 |
| elementary coefficient | 初等系数 |
| elementary divisor | 初等因子 / 初等除子 |
| elementary divisors | 初等因子 |
| elementary shear | 初等剪切 |
| elementary slot tensor | 初等槽张量 |
| elementary symmetric functions | 初等对称函数 |
| eligible cutoff | 合格截断 |
| eligible family | 合格族 |
| eligible index | 合格指标 |
| eligible model | 合格模型 |
| eligible share | 合格份额 |
| elliptic polynomial | 椭圆多项式 |
| elliptic type | 椭圆型 |
| embedded datum | 嵌入数据 |
| embedding identification | 嵌入识别 |
| empty part | 空的部分 |
| enclosure | 包含区间 |
| end kernel | 端核 |
| endpoint eigenfunction decomposition | 端点特征函数分解 |
| endpoint factor | 端点因子 |
| endpoint mass | 端点质量 |
| endpoint-width constant | 端点宽度常数 |
| enhanced column exponent | 增强列指数 |
| enhanced estimate | 增强估计 |
| enhanced gain | 增强增益 |
| enhanced global gain | 增强整体增益 |
| enhanced input set | 增强输入集 |
| enhanced lattice | 增强格 |
| enhancement budget | 增强预算 |
| enlargement | 扩大 / 放大 |
| entry bound | 元素界 / 矩阵元界 |
| entry datum | 矩阵元数据 |
| entry diagram | 矩阵元图形 |
| entry estimate | 矩阵元估计 |
| entry estimates | 元素估计 |
| entry exponent | 元素指数 / 矩阵元指数 |
| entry hypotheses | 矩阵元假设 |
| entry lattice | 元素格 |
| entry tuple | 元素组 |
| envelope assumption | 包络假设 |
| epsilon factor | ε 因子 |
| equal-diagonal subgroup | 等对角子群 |
| equal-increment clause | 等增量条款 |
| equal-root term | 等根项 |
| equal-word model | 等字模型 |
| equal-word operator | 等字算子 |
| equivariance | 等变性 |
| equivariant character | 等变特征 |
| equivariant coefficient domain | 等变系数域 |
| equivariant function lattice | 等变函数格 |
| equivariant orbit function | 等变轨道函数 |
| error at one translation | 一次平移处的误差 |
| essentially square-integrable | 本质平方可积的 |
| evaluation allowance | 求值容限 |
| evaluation field | 求值域 |
| evaluation pair | 求值对 |
| evaluation point | 求值点 |
| evaluation submodule | 求值子模 |
| evaluation tie | 求值纽带 |
| evaluation-field condition | 求值域条件 |
| even lattice | 偶格 |
| even predecessor | 偶前驱 |
| even-order inert branch | 偶阶惰性分支 |
| exact shift | 精确平移 |
| excellent ring | 优秀环 |
| exceptional character | 例外特征 |
| exceptional lattice | 例外格 |
| exceptional pair | 例外对 |
| exceptional prime sets | 例外素数集 |
| exceptional set | 例外集 |
| exceptional summand | 例外直和项 |
| exceptional tensor | 例外张量 |
| exceptional zero | 例外零点 |
| excess colength | 超出余长度 |
| excess share | 超额份额 |
| excess-share | 超额份额 |
| exchange exponent | 交换指数 |
| exchange involution | 交换对合 |
| exchange matrix | 交换矩阵 |
| excluded distance | 被排除的距离 |
| exclusion set | 排除集 |
| expansion class | 展开类 |
| exponent array | 指数组 |
| exponent vector | 指数向量 |
| exponential loss | 指数损失 |
| exponential substitution | 指数替换 |
| extended adjoint | 扩张伴随 |
| extended different | 扩充差积 / 扩张差积 |
| extended weight | 扩张权 |
| extension by zero | 零扩张 |
| extension weight | 延拓权重 |
| exterior column | 外列 |
| exterior power | 外幂 |
| external tensor product | 外张量积 |
| extra-automorphism | 额外自同构 |
| extremal evaluation | 极值求值 |
| extremal tensor | 极值张量 |
| extremal vector | 极值向量 |
| extreme coordinate | 极端坐标 |
| factor degrees | 因子次数 |
| factorial bound | 阶乘界 |
| factorial pairing | 阶乘配对 |
| factorial unit | 阶乘单位 |
| factorial valuation bound | 阶乘的赋值界 |
| factorial-orthogonal | 阶乘正交 |
| falling factorial | 下降阶乘 |
| family class | 族类 |
| family constant | 族常数 |
| family constant record | 族常数记录 |
| family constants | 族常数 |
| family cutoff | 族截断 |
| family exponent | 族指数 |
| family height exponent | 族高度指数 |
| family selection principle | 族选择原理 |
| family starting scale | 族的起始标度 |
| family threshold | 族阈值 |
| far range | 远区间 |
| far-centre bounds | 远中心界 |
| fibre | 纤维 |
| fibre element | 纤维元 |
| fibre integral | 纤维积分 |
| fibre power | 纤维幂 |
| fibre subspace | 纤维子空间 |
| field (of a datum) | 字段 |
| filling | 填充 / 填装 |
| filling compatibility | 填充相容性 |
| filling identification | 填充识别 |
| filling identity | 填充恒等式 |
| filling map | 填充映射 |
| filtered (φ,N)-module | 过滤 (φ,N)-模 |
| filtration degree | 滤过次数 |
| filtration jump | 滤链跳跃 |
| fine exponent | 精细指数 |
| finite allowance | 有限配额 |
| finite local Tate duality | 有限局部 Tate 对偶 |
| finite locally free | 有限局部自由的 |
| finite quotient | 有限商 |
| finite twist | 有限扭曲 |
| finite-adelic lattice frame | 有限阿代尔格框架 |
| finite-difference term | 有限差项 |
| finite-extension transport | 有限扩张搬运 |
| finite-fibre count | 有限纤维计数 |
| finite-fibre nefness | 有限纤维 nef 性 |
| finite-fibre threshold | 有限纤维阈值 |
| finite-place index selector | 有限位指标选择子 |
| finite-type index | 有限型指标 |
| first distance | 首个距离 |
| first dual minimum | 首个对偶最小值 |
| first occurrence | 首次出现 |
| first sheet | 第一叶 |
| fitted allowance | 拟合容许量 |
| fitted datum | 拟合数据 |
| fitted deep tower | 适配深塔 |
| fitted evaluation datum | 拟合求值数据 |
| fitted grid | 拟合格网 / 拟合网格 |
| fitted point | 拟合点 |
| fitted size | 拟合大小 |
| fitted tower | 拟合塔 |
| five-node | 五节点 |
| fixed-coordinate theta series | 固定坐标西塔级数 |
| flag | 旗标 |
| flag cover | 旗覆盖 |
| flag lattice | 旗格 |
| flag minor | 旗子式 |
| flag normalizer | 旗正规化子 |
| flag radical | 旗根 |
| flag step | 旗步 |
| flag support | 旗支集 |
| flag witness | 旗见证 |
| flag-cover morphism | 旗覆盖态射 |
| flag-lattice filtration | 旗格滤链 |
| flagged point | 带旗点 |
| flat degree | 平坦次数 |
| flat extension | 平坦延拓 |
| flat height | 平坦高度 |
| flat letters | 平坦字母 |
| flat section | 平坦截面 |
| flat weight | 平坦权 / 平坦权重 |
| flat-degree law | 平坦次数律 |
| floored midpoint | 下取整中点 |
| formal arc | 形式弧 |
| formal biextension germ | 形式双扩张胚 |
| formal degree | 形式次数 |
| formal kernel | 形式核 |
| formal thickening | 形式加厚 |
| formal-degree orthogonality relation | 形式次数正交关系 |
| formal-group parameter | 形式群参数 |
| formal-group theorem | 形式群定理 |
| forward difference | 前向差分 |
| forward differences | 前向差分 |
| four-copy local normalization | 四副本局部归一化 |
| four-copy normalization | 四份正规化 |
| four-square theorem | 四平方定理 |
| fourth-power normalization | 四次幂正规化 |
| fractional ideal | 分式理想 |
| fractional-part loss | 分数部分损失 |
| frame | 架 / 标架 / 框架 |
| frame Gram polynomial | 框架格拉姆多项式 |
| frame change | 框架变换 |
| frame coefficient | 标架系数 / 框架系数 |
| frame domain | 架定义域 |
| frame function | 标架函数 |
| frame index | 框架指标 |
| frame input | 框架输入 |
| frame jet | 框架射流 |
| frame map | 标架映射 |
| frame minor | 框架子式 |
| frame passage | 标架过渡 |
| frame quotient | 框架商 |
| frame variable | 框架变量 |
| frame-difference scale | 框架差标度 |
| frame-jet sum | 框架射流和 |
| frame-pairing matrix | 框架配对矩阵 |
| frame-volume ratio | 标架体积比 |
| framed (matrix ring / point) | 框架（矩阵环／点） |
| framed place | 框架位 |
| framed point | 标架点 / 框架点 |
| framed presentation | 带标架表示 / 带框架的表现 |
| full allowance | 全额额度 |
| full cap | 完全上限 |
| full faithfulness | 完全忠实性 |
| full grid | 全格网 |
| full index set | 完全指标集 |
| full lattice | 全格 / 完整格 / 满格 |
| full level | 满水平 |
| full normalized Gram operator | 全归一化格拉姆算子 |
| full representation | 完全表示 |
| full row dimension | 全行维数 |
| full tame test | 完整温和检验 |
| full-level | 全水平 |
| full-rank representative | 满秩代表元 |
| fullness | 满性 |
| functional equation lemma | 函数方程引理 |
| fundamental domain | 基本域 |
| gain | 增益 |
| gain before screening | 筛选前的增益 |
| gamma argument | 伽马自变量 |
| gamma defect | 伽马亏量 |
| gamma quotient | 伽马商 |
| gamma-derivation identity | 伽马求导恒等式 |
| gap | 间隙 |
| gap alternative | 间隙二择一 |
| gap-1 | 间隙 1 |
| gauge | gauge（规范，保留原文） / 规范 |
| general position | 一般位置 |
| generalized eigenspace | 广义特征空间 |
| generator step | 生成元步 / 生成元步骤 |
| generator-and-witness count | 生成元–见证计数 |
| generic | 一般的 / 泛型的 / 通用的 |
| generic degree | 一般次数 |
| generic field | 一般域 |
| generic irreducible | 一般不可约表示 |
| generic mass | 一般质量 |
| generic point | 一般点 |
| generic representation | 通用表示 |
| genericity | 泛性 |
| genericity criterion | 通用性判别法 |
| genuine character | 真正特征 |
| genus | 亏格 |
| genus automorphism | 属自同构 |
| genus mass | 亏格质量 / 属质量 / 种质量 |
| genus mean | 亏格均值 |
| genus-one theta product | 亏格一西塔积 |
| geometric fibre | 几何纤维 |
| geometric main term | 几何主项 |
| geometric normalization | 几何正规化 |
| geometric prime sum | 几何素数和 |
| geometry of numbers | 几何数论 |
| geometry row | 几何行 |
| germ | 芽 |
| global Frobenius-orbit parameters | 整体弗罗贝尼乌斯轨道参数 |
| global cap | 整体上界 |
| global capacities | 整体容量 |
| global price | 整体价格 |
| globalization | 整体化 |
| glued lattice | 粘合格 |
| glued row lattice | 粘合行格 / 胶合行格 |
| gluing | 粘合 |
| gluing finitely many local changes | 黏合有限多个局部改动 |
| good class | 好类 |
| good cover | 好覆盖 |
| good cut | 好割 |
| good datum | 好数据 |
| good direction | 好方向 |
| good idempotent | 好幂等元 |
| good indices | 好指标 |
| good intermediate tuple | 好中间元组 |
| good list | 好列表 |
| good member | 好成员 |
| good model | 好模型 |
| good orbit | 好轨道 |
| good pair | 好对 |
| good projector | 好投影子 |
| good representative | 好代表元 |
| good row | 好行 |
| good set | 好集 |
| good signature | 好符号 |
| good span | 好张成 |
| good spectrum | 良好谱 |
| good type space | 好型空间 |
| good-label injection | 良标号单射 |
| good-orbit condition | 良轨道条件 |
| good-orbit test | 好轨道检验 |
| good-place condition | 好位条件 |
| good-point test | 好点检验 |
| goodness row | 良态行 |
| graded image | 分次像 |
| grid | 格网 |
| grid Weil pair | 网格韦伊对 |
| grid choice | 网格选择 |
| grid conductor exponent | 格网导子指数 |
| grid depth | 格网深度 / 网格深度 |
| grid extension condition | 格网延拓条件 |
| grid integrality allowance | 网格整性容许量 |
| grid key | 网格键 |
| grid modulus allowance | 网格模容许量 |
| grid place datum | 格网位数据 |
| grid weight | 网格权 |
| grid-richness bound | 网格丰富度界 |
| grid-strengthened | 网格加强的 |
| group height | 群高度 |
| group-scheme retract | 群概形收缩 |
| half-different factor | 半差积因子 |
| half-gap | 半间隙 |
| half-group character sum | 半群上的特征和 |
| half-integral | 半整的 |
| half-integral weight multiplier | 半整权乘子 |
| half-level | 半水平 |
| half-level data | 半水平数据 |
| half-level generator | 半级生成元 |
| half-level ideal | 半级理想 |
| half-modulus | 半模 |
| half-period | 半周期 |
| half-period module | 半周期模 |
| half-step inclusion | 半步包含 |
| harmonic level | 调和层 |
| harmonic polynomial | 调和多项式 |
| harmonic projector | 调和投影算子 |
| height allowance | 高度余量 / 高度额度 |
| height comparison | 高度比较 |
| height exponent | 高度指数 |
| height factor | 高度因子 |
| height table | 高度表 |
| height theorem | 高度定理 |
| height valuation family | 高度赋值族 |
| height-counting extension | 高度计数扩张 |
| height-layer volume | 高度层体积 |
| higher toric ratio | 高阶环面比值 |
| highest bideterminant | 最高双行列式 |
| highest minor | 最高子式 |
| highest vector | 最高向量 |
| highest weight | 最高权 |
| highest weight vector | 最高权向量 |
| highest-vector frame | 最高向量标架 |
| highest-weight partition | 最高权分拆 |
| holds eventually | 最终成立 |
| holomorphic Lefschetz | 全纯莱夫谢茨 |
| holomorphic branch | 全纯分支 |
| holomorphic cuspidal family | 全纯尖点族 |
| holomorphic seed | 全纯种子 |
| homothety | 位似 |
| homothety class | 位似类 |
| hook | 钩形 |
| hook formula | 钩公式 |
| hook length | 钩长 |
| hook product | 钩积 |
| hook-length lower bound | 钩长下界 |
| horizontal base model | 水平基模型 |
| horizontal chord | 水平弦 |
| horizontal edge | 水平边 |
| horizontal polar divisor | 水平极除子 |
| horizontal prime | 水平素理想 |
| horizontal series | 水平级数 |
| horizontal strip | 水平带 / 水平条带 |
| horizontal word | 水平字 |
| host | 宿主 |
| host CM extension | 宿主 CM 扩张 |
| host arithmetic | 宿主算术 |
| host character | 宿主特征 |
| host class rule | 宿主类规则 |
| host condition | 宿主条件 |
| host conductor | 宿主导子 |
| host conductor ideal | 宿主导子理想 |
| host constants | 宿主常数 |
| host data | 宿主数据 |
| host element | 宿主元素 |
| host embedding | 宿主嵌入 |
| host field | 宿主域 |
| host ideal | 宿主理想 |
| host inequalities | 宿主不等式 |
| host modulus | 宿主模 |
| host oscillator | 宿主振子 |
| host rank | 宿主秩 |
| host requirement | 宿主要求 |
| host scalar scale | 宿主标量标度 |
| host splitting condition | 宿主分裂条件 |
| hub constant | 枢纽常数 |
| hyperbolic partner | 双曲伙伴 |
| hyperbolic plane | 双曲平面 |
| hypercohomology | 超上同调 |
| hyperspecial | 超特殊 / 超特殊的 |
| hyperspecial factor | 超特殊因子 |
| ideal von Mangoldt weight | 理想的冯·曼戈尔特权 |
| ideal-class point | 理想类点 |
| ideal-curve | 理想曲线 |
| ideal-scalar | 理想标量 |
| idelic norm | 伊代尔范数 |
| idempotent | 幂等元 |
| identification | 识别 |
| identity cell | 恒等胞腔 |
| identity neighborhood | 单位邻域 |
| identity theorem | 恒等定理 |
| implied constant | 蕴含常数 |
| incoming functional | 入向泛函 |
| increment bounds | 增量界 |
| indefinite side | 不定侧 |
| index (indicator) | 指示函数 |
| index condition | 指标条件 |
| index error | 指标误差 |
| index-two | 指标二 |
| index-two kernel | 指数二核 |
| indicator | 示性函数 |
| induced character | 诱导特征 |
| inert class | 惰性类 |
| inert operator | 惰性算子 |
| inert place | 惰性位 |
| inert prime | 惰性素数 |
| inert terms | 惰性项 |
| inert-class | 惰性类 |
| inert-class prime | 惰性类素数 |
| inertia average | 惯性平均 |
| inertia generator | 惯性生成元 |
| inertia involution | 惯性对合 |
| inertia polynomial | 惯性多项式 |
| inertia quotient | 惯性商 |
| inertially equivalent | 惯性等价的 |
| infinitesimal character | 无穷小特征 |
| inflation (of classes) | 膨胀 |
| inflation-restriction | 膨胀–限制 |
| initial column class set | 初始列类集 |
| initial index set | 初始指标集 |
| initial part | 初始部分 |
| initial principal minors | 初始主子式 |
| initial reference class function | 初始参考类函数 |
| initial saving one | 初始节省为一 |
| input lattice | 输入格 |
| integer box weight | 整数箱权 |
| integer weight box | 整数权重盒 |
| integrable upper envelope | 可积上包络 |
| integral basis | 整基 |
| integral chart | 整卡 |
| integral decomposition | 整分解 |
| integral dual | 整对偶 |
| integral finite cohomology | 整有限上同调 |
| integral frame | 整标架 / 整框架 |
| integral group | 整群 |
| integral ideal | 整理想 |
| integral interlacing map | 整交错映射 |
| integral multiplier | 整乘子 |
| integral numerator | 整分子 |
| integral pairing | 整配对 |
| integral scaling | 整标度 |
| integral translation lattice | 整平移格 |
| integral truncation | 整截断 |
| integrated Perron kernel | 积分佩龙核 |
| interior | 内部 |
| interior bit | 内部比特 |
| interior letter | 内部字母 |
| interior letters | 内部字母 |
| interior rank | 内部秩 |
| interlacing | 交织 / 交错 |
| interlacing Capelli eigenspace | 交错 Capelli 特征空间 |
| interlacing Capelli space | 交错 Capelli 空间 |
| interlacing parameter | 交错参数 |
| interlacing row | 交错行 |
| interlacing weight | 交错权重 |
| intermediate coset decoration | 中间陪集装饰 |
| interpolation | 插值 |
| interpolation distribution | 插值分布 |
| interpolation grid | 插值网格 |
| intersection lattice | 交格 |
| intersection number | 相交数 |
| intertwine | 缠绕 |
| intertwiner | 交织算子 / 纠缠算子 / 缠结映射 / 缠结算子 / 缠绕算子 |
| invariant coordinate module | 不变坐标模 |
| invariant differential | 不变微分 |
| invariant projector | 不变投影算子 |
| invariant ring | 不变环 |
| invariant-derivative decay | 不变导数衰减 |
| inverse different | 逆差积 |
| inverse limit | 逆极限 |
| inverse stabilizer weight | 逆稳定化子权 / 逆稳定化子权重 |
| inverse-difference | 逆差 |
| inverse-difference lattice | 反差格 |
| inverse-rank term | 逆秩项 |
| involution | 对合 |
| isobaric transfer | 等重转移 |
| isobaric uniqueness | 等重唯一性 |
| isocrystal | 同晶体 |
| isogenous | 同源的 |
| isogeny | 同源 |
| isogeny identity | 同源恒等式 |
| isogeny norm law | 同源范数律 |
| isometric | 等距的 |
| isometry group | 等距群 |
| isotropic column | 迷向列 |
| isotropic dual vector | 迷向对偶向量 |
| isotropic flag | 迷向旗 |
| isotropic frame | 各向同性标架 / 迷向框架 |
| isotropic half | 迷向半空间 |
| isotropic subspace | 各向同性子空间 / 迷向子空间 |
| isotropic-half composition law | 迷向半部复合律 |
| isotropy | 迷向性 |
| isotypic component | 同型分量 |
| isotypic map | 同型映射 |
| isotypic projection | 同型投影 |
| isotypic quotient | 同型商 |
| isotypic space | 同型空间 |
| isotypic summand | 同型成分 |
| jet | 射流 |
| jet depth | 射流深度 |
| jet family | 射流族 |
| join | 并 |
| join conditions | 连接条件 |
| joint approximation | 联合近似 |
| joint coefficient estimate | 联合系数估计 |
| joint harmonics | 联合调和多项式 |
| joint irreducibility | 联合不可约性 |
| joint space | 联合空间 |
| joint system | 联合系统 |
| joint window condition | 联合窗口条件 |
| joint-harmonic | 联合调和 |
| jump | 跳跃 |
| jump enclosure | 跳跃包围区间 |
| jump multiplicity | 跳跃重数 |
| jump multiset | 跳跃多重集 |
| jump set | 跳跃集 |
| kept block | 保留块 |
| kept set | 留存集 |
| kernel budget | 核预算 |
| kernel pair | 核对 |
| kernel-orthogonality | 核正交性 |
| killing assertion | 零化断言 |
| kind A / kind BC | A 型／BC 型 |
| kind-A positions | A 类位置 |
| kind-BC positions | BC 类位置 |
| klt pair | klt 对 |
| knot/hub constants | 枢纽常数 |
| label cover | 标签覆盖 |
| label datum | 标签数据 |
| label letter | 标签字母 |
| label letters | 标号字母 |
| label realization | 标号实现 |
| label sum | 标签求和 |
| label-range parameter | 标号范围参数 |
| label-sum input | 标号和输入 |
| labelled algebraic weight | 标号代数权 |
| labelled fibre comparison | 带标记的纤维比较 |
| labelled partner | 带标号的伙伴 |
| labelled weight | 标号权 |
| lacunarity | 缺项性 |
| lacunary | 缺项的 |
| lacunary subset | 缺项子集 |
| last degree | 末次数 |
| lattice bound | 格界 |
| lattice character | 格特征 |
| lattice count | 格点计数 |
| lattice norm bound | 格范数界 |
| lattice sum | 格和 |
| lattice tuple | 格元组 |
| lattice vacuum | 格真空 |
| lattice-change operator | 变格算子 |
| lattice-pair coordinates | 格对坐标 |
| lattice-scalar | 格标量 |
| layer | 层 |
| layer Gram determinant | 层格拉姆行列式 |
| layer character | 层特征 |
| layer diagram | 层图 |
| layer hypothesis | 层假设 |
| layer type | 层型 |
| layer weight | 层权 |
| layer-cake | 层饼 |
| layer-cake integration | 分层积分 |
| layer-pair factor | 层对因子 |
| layer-position term | 层位置项 |
| layer-sum estimate | 层和估计 |
| leading frame | 前导标架 |
| leading i-step | 首 i 步 |
| leading minor | 主子式 / 前导子式 / 首项子式 |
| leading minors | 前导子式 |
| leading monomial | 首项单项式 |
| leading principal minor | 前主子式 / 前导主子式 |
| leaf hypothesis | 叶假设 |
| least prime | 最小素理想 |
| least signed weight | 最小有号权 |
| least-power construction | 最小幂构造 |
| ledger specialization | 账本特化 |
| leg (of a correspondence) | 腿 |
| legal representative set | 合法代表元集 |
| length bound | 长度界 |
| length factor | 长度因子 |
| length shell | 长度壳 / 长度壳层 / 长度层 |
| length step | 长度步 / 长度步骤 |
| letter | 字母 |
| letter (positive/negative) | 字母（正／负） |
| letter data | 字母数据 |
| letter logarithm | 字母对数 |
| letter operator | 字母算子 |
| level (Definition 2.5) | 层次 |
| level agreement | 层次一致性 |
| level character | 水平特征 |
| level chart | 水平卡 |
| level coset | 水平陪集 |
| level cover | 水平覆盖 |
| level datum | 水平数据 |
| level factor | 水平因子 |
| level frame | 水平框架 |
| level group | 层级群 / 水平群 |
| level idempotent | 水平幂等元 |
| level indicator | 水平指示子 |
| level label | 水平标号 |
| level lattice | 层次格 |
| level loss | 水平损失 |
| level map | 水平映射 |
| level measure factor | 水平测度因子 |
| level norm | 水平范数 |
| level of a lattice | 格的水平 |
| level place | 水平位 |
| level predicate | 水平谓词 |
| level prime | 水平素数 |
| level primes | 层次的素数 |
| level set | 水平集 |
| level subgroup | 水平子群 |
| level theta function | 水平西塔函数 |
| level transport | 水平搬运 |
| level twist | 水平扭曲 |
| level ultrafilter | 水平超滤 |
| level window | 水平窗口 |
| level-character datum | 水平特征数据 |
| level-character idempotent | 水平特征幂等元 |
| level-equivariant | 水平等变的 |
| level-free | 无水平 / 无水平的 |
| level-geometry laws | 水平几何律 |
| level-one | 一级 |
| level-prime loss | 水平素数损失 |
| level-raising operator | 提升水平算子 |
| level-size constant | 水平大小常数 |
| level-size exponent | 水平尺度指数 |
| lift contraction | 提升缩并 |
| lift lattice | 提升格 |
| lifting-the-exponent identity | 指数提升恒等式 |
| limit superior | 上极限 |
| line approximation | 直线逼近 |
| line character | 线特征 |
| line polarization | 直线极化 |
| line unipotent | 直线幂幺群 |
| linearly disjoint | 线性分离 |
| link | 链接 / 链节 |
| link (of a tower) | 链接 |
| link projection | 链节投影 |
| linkage | 联络 |
| linked | 链接的 |
| linked bundle | 链接丛 |
| linked frame | 链接框架 |
| linked pair | 链接对 |
| linked slot | 链接槽 |
| list concatenation | 列表拼接 |
| local Bessel datum | 局部贝塞尔数据 |
| local Weyl value lattice | 局部外尔值格 |
| local abelianisation | 局部阿贝尔化 |
| local allowance | 局部容许量 |
| local cap | 局部上界 |
| local choice and global intersection | 局部选择与整体交 |
| local class coordinates | 局部类坐标 |
| local cohomological input | 局部上同调输入 |
| local composite | 局部复合 |
| local cyclotomic image | 局部割圆像 |
| local denominator allowance | 局部分母容许量 |
| local different | 局部差积 |
| local factorization theorem | 局部因子分解定理 |
| local finiteness | 局部有限性 |
| local integrality | 局部整性 |
| local model chart | 局部模型卡 |
| local phase measure | 局部相位测度 |
| local position | 局部位置 |
| local principality | 局部主理想性 |
| local saturation index | 局部饱和指标 |
| local square test | 局部平方检验 |
| local system | 局部系统 |
| local theta quotient | 局部西塔商 |
| local values | 局部值 |
| local zero-expansion lemma | 局部零点展开引理 |
| local-error sum | 局部误差和 |
| local-index total | 局部指标总和 |
| local-term support | 局部项支集 |
| localisation | 局部化 |
| localizer | 局部化子 |
| localizing polynomial | 局部化多项式 |
| locally associated | 局部相伴 |
| log discrepancy | 对数差异 |
| log hook | 对数钩 |
| log resolution | 对数消解 |
| log-uniformiser scale | 对数一致化子标度 |
| logarithmic error | 对数误差 |
| logarithmic gauge | 对数规范 |
| logarithmic metric coefficient | 对数度量系数 |
| logarithmic order | 对数阶 |
| logarithmic window | 对数窗口 |
| logarithmic-logarithmic growth | 对数–对数增长 |
| long row | 长行 |
| long-factor test | 长因子检验 |
| long-orbit case | 长轨道情形 |
| loss bound | 损失界 |
| loss function | 损失函数 |
| lossy | 有损的 |
| lost at most | 损失至多 |
| low window | 低窗口 |
| lower edge | 下边 |
| lower model | 下模型 |
| lower semicontinuous | 下半连续 |
| lower tail | 下尾部 |
| lower unitriangular | 下单位三角 |
| lower-neighbor lattice | 下邻近格 |
| lowered representative | 下降代表元 |
| lowering chain | 降低链 |
| lowest compact type | 最低紧致型 |
| lowest type | 最低型 |
| lowest-type decay | 最低型衰减 |
| lowest-type tensor | 最低型张量 |
| lowest-type vector | 最低型向量 |
| lying-over | 躺卧定理 |
| majorant | 优函数 / 控制函数 |
| majorant frame | 优标架 |
| mark | 标记 |
| mark weight interval | 标记权重区间 |
| marked | 带标记的 |
| marked allowance | 标记额度 |
| marked deformation problem | 带标记形变问题 |
| marked diamond sum | 标记菱形和 |
| marked factor | 标记因子 |
| marked first endpoint | 带标号首个端点 |
| marked height-one column | 标记高一次列 |
| marked point | 标点 |
| marked position | 标记位置 |
| marked set | 标记集 |
| marked signature | 带标记的符号差 |
| marked tile | 带标记的瓦片 / 标记瓦片 |
| marking | 标记 |
| marking kernel | 标记核 |
| marking matrix | 标记矩阵 |
| mass conversion | 质量转换 |
| mass data | 质量数据 |
| mass factor | 质量因子 |
| mass normalization | 质量规范化 |
| mass ratio | 质量比 |
| mass-ratio bound | 质量比界 |
| matched square integral | 匹配的方格积分 |
| matching system | 匹配系统 |
| matrix unit | 矩阵单位 |
| maximal central string | 极大中心串 |
| maximal divisible submodule | 极大可除子模 |
| maximal integral lattice | 极大整格 |
| maximal isotropic space | 极大迷向空间 |
| maximal quotient | 极大商 |
| maximal real subfield | 最大实子域 |
| maximiser | 取到最大值者 |
| maximum flow | 最大流 |
| maximum slope | 最大斜率 |
| mean quotient loss | 平均商损失 |
| mean slope | 平均斜率 |
| mean-count estimate | 均值计数估计 |
| mean-slope bound | 平均斜率界 |
| mean-square bound | 均方界 |
| measurable fundamental set | 可测基本集 |
| member | 成员 |
| member modulus | 成员模 |
| member parameter bound | 成员参数界 |
| member point | 成员点 |
| member row | 成员行 |
| member supply | 成员供给 |
| member-point map | 成员点映射 |
| membership condition | 隶属条件 |
| merging pair of blocks | 合并块对 |
| metaplectic | 亚辛的 |
| metaplectic double cover | 亚辛双重覆盖 |
| metrized determinant line | 带度量的行列式线 |
| middle rows | 中间行 |
| middle size threshold | 中间大小阈值 |
| minimal type | 极小型 |
| minimiser | 极小点 |
| minor differential | 子式微分 |
| minor factors | 子式因子 |
| minor label | 子式标号 |
| minor tuple | 子式元组 / 子式组 |
| minor-clearing ideal | 清除子式理想 |
| minor-jet class-tuple coordinate | 子式流类组坐标 |
| minor-moment | 子式矩 |
| minor-moment bound | 子式矩界 |
| mirabolic | mirabolic（保留原文） / 米拉博利 |
| mirabolic subgroup | mirabolic 子群 / 米拉博利子群 |
| mixed Gram determinant | 混合格拉姆行列式 |
| mixed Schrödinger model | 混合薛定谔模型 |
| model group | 模型群 |
| model lattice | 模型格 |
| model slope | 模型斜率 |
| moderate growth | 中等增长 / 适度增长 |
| moderate region | 适度区域 |
| modification | 修改 |
| modular group | 模群 |
| moduli chart | 模卡 |
| modulus-one character | 模 1 特征 |
| mollified Dirichlet polynomial | 磨光的狄利克雷多项式 |
| mollifier | 磨光子 |
| mollifier identity | 磨光恒等式 |
| moment matrix | 矩矩阵 |
| moment order | 矩阶 |
| monic polynomial | 首一多项式 |
| monodromy | 单值 / 单值化 / 单值性 |
| monodromy block | 单值块 |
| monodromy form | 单值形式 |
| monodromy operator | 单值算子 |
| monodromy pairing | 单值配对 |
| monoid | 幺半群 |
| moving degree | 移动次数 |
| moving frame | 移动框架 |
| moving pair | 移动配对 |
| multidegree | 多重次数 |
| multihomogeneous | 多重齐次的 |
| multihomogeneous cone | 多重齐次锥 |
| multilinear map | 多重线性映射 |
| multinomial coefficient | 多项式系数 |
| multiplicative colength | 乘性余长 |
| multiplicative parameter | 乘法参数 |
| multiplicity | 重数 |
| multiplicity free | 重数自由 |
| multiplicity one | 重数一 |
| multiplicity space | 重数空间 |
| multiplicity-free | 无重数的 |
| multiplicity-one interlacing | 重数一交织 |
| multiplier ideal | 乘子理想 |
| multisegment | 多段 / 多线段 / 多重段 |
| multiset | 多重集 / 重集 |
| narrow ray class field | 窄射线类域 |
| narrow ray group | 窄射线群 |
| near range | 近区间 |
| neat | neat（保留） / 整洁的 |
| neat (compact open subgroup) | 整洁的（紧致开子群） |
| neat (neatness) | neat 性（保留原文） |
| neatness | 整洁性 |
| nebentype | nebentype |
| nef | nef（数值有效） |
| negative kernel sum | 负核和 |
| negative signature index | 负符号指标 |
| neighbor sum | 邻近和 |
| neighbour count | 邻格计数 |
| neighbourhood element | 邻元 |
| net budget | 净预算 |
| net gain | 净增益 |
| newform | 新形式 |
| newvector | 新向量 |
| nilpotent chart | 幂零卡 |
| nilpotent divided-power thickening | 幂零除幂加厚 |
| node threshold | 节点阈值 |
| non-klt locus | 非 klt 轨迹 |
| non-zerodivisor | 非零因子 |
| nondegeneracy | 非退化性 |
| nonendoscopic | 非内窥的 / 非内视的 |
| nongeneric | 非一般的 |
| nonnormal | 非正规的 |
| nonreference type | 非参考类型 |
| nonrelevant | 非相关的 |
| nonterminal layer | 非终端层 |
| nonthick | 非厚的 |
| nontop place | 非顶位置 |
| nontop type | 非顶部型 |
| nonunit | 非单位 |
| nonzero odd-order inert | 非零奇阶惰性 |
| nonzero-minor product | 非零子式乘积 |
| norm defect | 范数缺陷 |
| norm map | 范数映射 |
| norm prime | 范数素数 |
| norm theorem | 范数定理 |
| norm valuation bound | 范数赋值界 |
| norm-choice extension | 范数选择扩张 |
| norm-one torus | 范数一环面 |
| norm-power family | 范数幂族 |
| norm-residue isomorphism | 范剩余同构 |
| normal coefficient | 法向系数 |
| normal core | 正规核 |
| normal cores | 正规核 |
| normal datum | 法向数据 |
| normal form | 标准形 |
| normal label | 法向标号 |
| normal variable | 正规变量 |
| normal-crossing boundary | 正规交叉边界 |
| normalization | 规范化 |
| normalization section | 正规化截面 |
| normalized length | 正规化长度 |
| normalized local colength | 正规化局部余长 |
| normalized log covolume | 正规化对数余体积 |
| normalized multiplicative parameter | 正规化乘法参数 |
| normalized step factor | 正规化步因子 |
| normalized sum | 归一化和 |
| normalized tower | 规范化塔 |
| normalized valuation | 正规化赋值 |
| normalizing twist | 规范化扭曲 |
| normed-field version | 赋范域版本 |
| numerator expansion | 分子展开 |
| numerical datum | 数值数据 |
| numerical summation | 数值求和 |
| object layer | 对象层 |
| obstruction count | 障碍计数 |
| obstruction-map formulation | 障碍映射表述 |
| occupied cell | 占据单元 |
| occurring part | 出现的部分 |
| odd cocycle | 奇上闭链 |
| odd module | 奇模 |
| odd-prime hypothesis | 奇素数假设 |
| off-block summand | 块外直和项 |
| off-edge test | 离边检验 |
| off-top embedding | 非顶嵌入 |
| offset width | 偏移宽度 |
| one-box rule | 一格规则 |
| one-entry coefficient | 单元素系数 |
| one-entry period lattice | 单条目周期格 |
| one-layer Fourier identity | 单层傅里叶恒等式 |
| one-layer main term | 单层主项 |
| one-letter bound | 单字母界 |
| one-parameter toroidal chart | 单参数环面卡 |
| one-place condition | 单点条件 |
| one-place exponential | 单位置指数映射 |
| one-position expansion | 单位置展开 |
| one-sided bound on a window | 窗口上的单侧界 |
| one-sided fibre condition | 单侧纤维条件 |
| one-slot slice | 单槽切片 |
| one-step raising construction | 一步提升构造 |
| one-step rule | 一步法则 |
| one-step slice operator | 一步切片算子 |
| one-unit | 1-单位 |
| open condition | 开放条件 |
| open coset | 开陪集 |
| open row | 开放行 |
| opposite block | 异块 |
| opposite pair | 相反配对 |
| opposite-pair vanishing | 反号配对消没 |
| opposite-sign comparison | 反号比较 |
| opposite-sign gap | 反号间隙 / 异号间隙 |
| orbit and jet conditions | 轨道与射流条件 |
| orbit base | 轨道基 |
| orbit base value | 轨道基值 |
| orbit coordinate map | 轨道坐标映射 |
| orbit data | 轨道数据 |
| orbit entry estimates | 轨道矩阵元估计 |
| orbit factor | 轨道因子 |
| orbit span | 轨道张成 |
| orbital amplitude | 轨道振幅 |
| orbital energy | 轨道能量 |
| orbital integral | 轨道积分 |
| orbital measure | 轨道测度 |
| orbital quadratic form | 轨道二次型 |
| orbital vector | 轨道向量 |
| orbital weight | 轨道权 / 轨道权重 |
| order class | 序类 |
| order window | 阶窗口 |
| order-reversing permutation matrix | 反序置换矩阵 |
| ordered exponential cube | 有序指数立方体 |
| ordered nerve | 有序神经 |
| ordered round | 有序一轮 |
| ordered vertex tuples | 有序顶点组 |
| ordered word pair | 有序字对 |
| ordinary (place / part) | 寻常的 |
| ordinary (representation/locus) | 寻常的 |
| ordinary coefficient bound | 寻常系数界 |
| ordinary entry bound | 寻常矩阵元界 |
| ordinary fixed-weight cocycle | 寻常固定权上闭链 |
| ordinary flag | 寻常旗 / 常旗 |
| ordinary global gain | 寻常整体增益 |
| ordinary ideal class | 寻常理想类 |
| ordinary inertia | 寻常惯性 |
| ordinary letter | 寻常字母 |
| ordinary lower quotient | 寻常下商 |
| ordinary operator | 寻常算子 |
| ordinary projector | 寻常投影子 |
| ordinary refinement | 寻常细化 |
| origin | 起源 |
| origin residue disk | 原点剩余圆盘 |
| orthogonal truncation | 正交截断 |
| orthonormal eigenbasis | 标准正交特征基 |
| oscillation | 振幅 |
| oscillator ideal | 振荡理想 |
| oscillator lattice | 振子格 |
| oscillator module | 振荡子模 |
| oscillator representation | 振子表示 |
| oscillator test | 振子测试 |
| oscillator vacuum | 振子真空 |
| oscillatory integral | 振荡积分 |
| outer constants | 外常数 |
| outer ratio | 外比 |
| outgoing period | 出向周期 |
| p-adic coordinate integrality bound | p 进坐标整性界 |
| p-adic period-ring | p 进周期环 |
| p-compatible | p 相容水平 |
| p-typical curve | p 典型曲线 |
| packing | 装填 |
| packing argument | 填充论证 |
| packing bound | 堆积界 |
| page and height conditions | 页条件与高度条件 |
| page function | 页函数 |
| page hypothesis | 页假设 |
| page normalization | 页正规化 |
| pair amplitude | 配对振幅 |
| pair equivalence relation | 配对等价关系 |
| pair row | 素数对行 |
| pair-count | 配对计数 |
| paired algebra | 配对代数 |
| paired-character constant | 配对特征常数 |
| paired-character statement | 配对特征陈述 |
| paired-index | 配对指标 |
| paired-row identity | 配对行恒等式 |
| pairing class | 配对类 |
| pairing factor | 配对因子 |
| pairing laws | 配对律 |
| pairing-index bound | 配对指标界 |
| parabolic decomposition | 抛物分解 |
| parabolic modulus | 抛物模 / 抛物模数 |
| parahoric | 抛物型的 |
| parahoric subgroup | 准抛物子群 |
| parallel infinity exponent | 平行无穷指数 |
| parallelogram identity | 平行四边形恒等式 |
| partial Fourier sum | 部分傅里叶和 |
| partial orbital pairing | 部分轨道配对 |
| participating family | 参与的族 |
| partition | 分拆 |
| partition weight | 分划权 |
| partner class | 伙伴类 |
| partner frame | 伙伴框架 |
| partner frame lattice | 伙伴框架格 |
| partner map | 配对映射 |
| partner space | 伙伴空间 |
| partner-count bound | 伙伴计数界 |
| passage budget | 过渡预算 |
| passage cost | 过渡代价 |
| passage inequality | 过渡不等式 |
| passing fraction | 通过分数 |
| patched | 补丁的（patching 方法） |
| patched valuation family | 拼接赋值族 |
| patching | 拼接 |
| patching lemma | 拼接引理 |
| peak section | 峰截面 |
| perfect duals | 完美对偶 |
| perfect residue field | 完全剩余域 |
| perfectoid | 完美胚 |
| period bridge | 周期桥 |
| period label | 周期标号 |
| period lattice | 周期格 |
| period matrix | 周期矩阵 |
| period test space | 周期测试空间 |
| period-ring data | 周期环数据 |
| periodization | 周期化 |
| permitted model | 容许模型 |
| permitted pair | 允许对 |
| permitted tangent | 容许切向量 |
| permitted translate | 容许平移 |
| permitted-pair conditions | 许可对条件 |
| permutation proportion | 置换比例 |
| perpendicular bisector | 垂直平分线 |
| phase equivalence | 相位等价 |
| phase-normalized lift | 相位归一化提升 |
| piecewise linear | 分段线性的 |
| pin | 钉定 |
| pin (noun) | 钉 |
| pin (verb) | 钉住 |
| pinned | 钉定的 |
| place part | 位部分 |
| planar Lebesgue measure | 平面勒贝格测度 |
| plane projection | 平面投影 |
| plane variable | 平面变量 |
| plurisubharmonic | 多重次调和的 |
| plurisubharmonic potential | 多重次调和的位势 |
| plus component | 加号分量 |
| plus hook | 加钩 |
| plus length | 加号长度 |
| plus-hook sum | 正钩和 |
| point cutoff | 点截断 |
| point embedding | 点嵌入 |
| point evaluation | 点值 |
| point kernel | 点核 |
| point lattice | 点格 |
| point of evaluation | 求值点 |
| point period | 点周期 |
| point separation | 点分离 |
| point size | 点大小 |
| point stabilizer | 点稳定化子 |
| point summand | 逐点求和项 |
| point threshold | 点阈值 |
| point weight | 点权 |
| point-coordinate row | 点坐标行 |
| point-field construction | 点域构造 |
| point-weight square root | 点权平方根 |
| pointwise bound | 逐点界 |
| polar Jacobian | 极坐标 Jacobian |
| polarised fan | 极化扇 |
| polarising function | 极化函数 |
| polarising scalar | 极化标量 |
| polarization (symplectic) | 极化 |
| polarization multiplier | 极化乘子 |
| polarized input | 极化输入 |
| pole data | 极点数据 |
| polydisc | 多圆盘 |
| polynomial form | 多项式形式 |
| polynomial insertion | 多项式插入 |
| polynomial prefactor | 多项式前因子 |
| polynomial value lattice | 多项式值格 |
| polynomial-law coefficient | 多项式律系数 |
| position | 位置 |
| position bounds | 位置界 |
| position data | 位置数据 |
| position map | 位置映射 |
| positioned word | 定位词 |
| positive chamber | 正房 |
| positive lift | 正提升 |
| positive majorant | 正优函数 |
| positive part | 正部 |
| positive row partition | 正行分划 |
| positive trace form | 正迹形式 |
| positive type | 正型 |
| positive weighted character family | 正加权特征族 |
| positive-Gram locus | 正格拉姆轨迹 |
| positive-action column | 正作用列 |
| positive-majorant length | 正控制长度 |
| potential good reduction | 潜在好约化 |
| potential semistability | 潜在半稳定性 |
| potentially crystalline | 潜晶化的 |
| potentially semistable | 潜在半稳定 / 潜在半稳定的 |
| potentially unlinked | 潜在非链接的 |
| power moment | 幂矩 |
| power sum | 幂和 |
| powered letter | 幂次字母 |
| pre-level dimension factor | 前水平维数因子 |
| precision-one evaluation basis | 精度一求值基 |
| prefactor bound | 预因子界 |
| prefix cap | 前缀帽 |
| prefix estimate | 前缀估计 |
| prefix order | 前缀阶 |
| prefix point | 前缀点 |
| prefix projection | 前缀投影 |
| prescribed chain length | 规定的链长 |
| prescribed depth | 规定深度 |
| prescribed ψ-kernel | 指定的 ψ-核 |
| prescribed-column entry bound | 指定列的矩阵元界 |
| prescribed-fan compactification | 指定扇紧化 |
| presentation | 展示 / 表现（环的表现） |
| presentation class | 表示类 |
| price bound | 价格界 |
| price coefficient | 价格系数 |
| price parameter | 代价参数 / 价格参数 |
| primary | 准素 |
| primary (ℓ-primary torsion) | 准素的（ℓ 准素挠） |
| primary decomposition | 准素分解 |
| primary factor | 准素因子 |
| primary fibre | 主纤维 |
| primary part | 准素部分 |
| primary space | 主空间 |
| primary subgroup | 准素子群 |
| primary torsion | 准素挠 |
| prime avoidance | 素回避 / 素理想回避 |
| prime base | 素基 / 素数基 |
| prime class | 素类 |
| prime compatibility | 素相容性 |
| prime cutoff | 素数截断 |
| prime filtration | 素滤链 |
| prime label | 素标签 |
| prime pair | 素数对 |
| prime twist | 素数扭曲 |
| prime window | 素数窗口 |
| prime-count function | 素数计数函数 |
| prime-moving | 素数移动 |
| prime-only clause | 素数条款 |
| prime-power coefficient | 素数幂系数 |
| prime-power modulus budget | 素幂模预算 |
| prime-square bound | 素数平方界 |
| prime-tail summation | 素尾求和 |
| prime-twist character | 素扭曲特征 |
| primed entry | 带撇项 |
| primed tuple | 带撇元组 |
| primitive idempotent | 本原幂等元 |
| primitive reduction | 本原归约 |
| primitive representative | 本原代表元 |
| primitive trace form | 本原迹形式 |
| primitive vector | 原始向量 |
| primitivity | 本原性 |
| primorial | 素数阶乘 / 素数阶乘（保留 $\mathrm{primorial}$） |
| principal congruence group | 主同余群 |
| principal congruence level | 主同余水平 |
| principal congruence subgroup | 主同余子群 |
| principal ideles | 主伊代尔 |
| principal line | 主线丛 |
| principal ray class | 主射线类 |
| principal unit | 主单位 |
| principal units | 主单位 / 主单位群 |
| principal-ideal character formula | 主理想特征公式 |
| principal-level lattice datum | 主水平格数据 |
| principalisation | 主化 |
| principalize | 主化 |
| principally polarised | 主极化的 |
| prismatic | 棱柱的 |
| prismatic Dieudonné functor | 棱柱 Dieudonné 函子 |
| prismatic module | 棱镜模 |
| prismatic realization | 棱柱实现 |
| probability Haar measure | 概率哈尔测度 |
| procyclic | 射有限循环的 / 投射循环的 / 预循环的 |
| product fibre | 乘积纤维 |
| product height | 乘积高度 |
| product mass | 乘积质量 |
| product uniformisation | 乘积一致化 |
| product-test symbol | 乘积检验符号 |
| profinite group | 射有限群 / 投射有限群 |
| projected intertwiner space | 投影缠结算子空间 |
| projection trace | 投影迹 |
| projective theta lattice | 投影西塔格 |
| projector | 投影元 |
| prolongation | 延拓 |
| proper block | 真块 |
| proper-pairing event | 真配对事件 |
| properness | 固有性 |
| proportionality constant | 比例常数 |
| provision | 条款 |
| pseudo-coefficient | 伪系数 |
| pseudocharacter | 伪特征 |
| pullback factor | 拉回因子 |
| punctured neighbourhood | 去心邻域 |
| pure coset data | 纯陪集数据 |
| pure tensor | 纯张量 |
| pure-top term | 纯最高次项 / 纯顶项 |
| pushforward | 前推 |
| q-sign character | q 符号特征 |
| quadratic adjunction | 二次添加 |
| quadratic automorphy condition | 二次自守性条件 |
| quadratic idèle class character | 二次伊代尔类特征 |
| quadratic moment | 二次矩 |
| quadratic witness condition | 二次见证条件 |
| quantifier order | 量词顺序 |
| quantum comatrix identity | 量子余矩阵恒等式 |
| quantum determinant | 量子行列式 |
| quantum-minor operator | 量子子式算子 |
| quasi-period homomorphism | 拟周期同态 |
| quotient Gram matrix | 商格拉姆矩阵 |
| quotient disintegration | 商分解 |
| quotient exponent | 商指数 |
| quotient frame | 商标架 / 商框架 |
| quotient height | 商高 / 商高度 |
| quotient length | 商长度 |
| quotient letter | 商字母 |
| quotient letters | 商字母 |
| quotient load | 商负载 |
| quotient metric | 商度量 |
| quotient volume | 商体积 |
| quotient weight | 商权 |
| quotient-multiplicity relation | 商重数关系 |
| quotient-volume hypothesis | 商体积假设 |
| radial operator datum | 径向算子数据 |
| radical | 根 / 根基 |
| radical constant term | 根常数项 |
| radical criterion | 根判别法 |
| radical vector | 根向量 |
| radicand | 被开方式 |
| raising operator | 升算子 |
| ramification-place set | 分歧位集 |
| ramified submodule | 分歧子模 |
| ramified subspace | 分歧子空间 |
| ramp | 斜坡 |
| rank condition | 秩条件 |
| rank conditions | 秩条件 |
| rank cutoff | 秩截断 |
| rank data | 秩数据 |
| rank extraction | 秩的提取 |
| rank parameter | 秩参数 |
| rank requirement | 秩要求 |
| rank selection condition | 秩选择条件 |
| rank supply | 秩供给 |
| rank threshold | 秩阈值 |
| rank window | 秩窗口 |
| rank-one Bessel period identity | 秩一贝塞尔周期恒等式 |
| rank-one congruence | 秩一同余 |
| rank-supply threshold | 秩供给阈值 |
| rational Witt index | 有理维特指数 |
| rational formal chart | 有理形式卡 |
| rational idempotent | 有理幂等元 |
| rational isotropic line | 有理迷向直线 |
| rational point map | 有理点映射 |
| rational ramified subspace | 有理分歧子空间 |
| rational representative | 有理代表元 |
| rational stabilizer | 有理稳定化子 |
| rational weight space | 有理权空间 |
| raw gain | 原始增益 |
| raw host | 原始宿主 |
| ray character | 射线特征 |
| ray class field | 射线类域 |
| ray class group | 射线类群 |
| ray coordinates | 射线坐标 |
| ray cover | 射线覆盖 |
| ray-class-field statements | 射线类域陈述 |
| reading | 读值 / 读出映射 / 读数 |
| readout | 读出值 |
| real factor | 实因子 |
| real homogeneity | 实齐性 |
| real realization | 实实现 |
| real row function | 实行函数 |
| real share | 实份额 |
| realizable subset | 可实现子集 |
| realization | 实现 |
| reciprocal gamma function | 倒数伽马函数 |
| reciprocal polynomial | 倒多项式 |
| reciprocal-stabilizer class sum | 互反稳定化子类和 |
| reciprocal-stabilizer mass sum | 倒稳定化子质量和 |
| recombination | 重组 |
| reconstruction | 重构 |
| record frame | 记录标架 |
| record valuation family | 记录赋值族 |
| rectangular cutoff | 矩形截断 |
| reduced (algebra) | 约化的 |
| reduced Gram label | 约化 Gram 标号 |
| reduced Gram matrix | 约化格拉姆矩阵 |
| reduced class | 既约类 |
| reduced full Hecke polynomial | 约化完全赫克多项式 |
| reduced jump multiplicity | 约化跳跃重数 |
| reduced kernel | 约化核 |
| reduced norm (nrd) | 约化范数 |
| reduced origin | 约化原点 |
| reduced residue class | 缩剩余类 |
| reduction cell | 约化胞腔 |
| reductive dual pair | 约化双对 |
| reference coordinate isomorphism | 参考坐标同构 |
| reference data | 参照数据 |
| reference depth | 参考深度 |
| reference divisor | 参考除子 |
| reference exponent | 参考指数 |
| reference label | 参考标号 |
| reference layer subspace | 参考层子空间 |
| reference multiplicity map | 参考重数映射 |
| reference parameter | 参考参数 |
| reference realization | 参考实现 |
| reference row | 参考行 |
| reference row space | 参考行空间 |
| reference tuple | 参考元组 |
| regular compact parameter | 正则紧致参数 |
| regular form | 正则形式 |
| regular support condition | 正则支撑条件 |
| regular zero | 正则零点 |
| regularizing exponent | 正则化指数 |
| relative cylinder counts | 相对柱计数 |
| relative determinant | 相对行列式 |
| relative inverse stabilizer covolume | 相对逆稳定化子余体积 |
| relative obstruction space | 相对障碍空间 |
| relator | 关系子 |
| relevant prime | 相关素理想 |
| remainder bound | 余项界 |
| remainder class | 余数类 |
| remainder exponent | 余数指数 |
| remainder functional | 余项泛函 |
| remaining degree | 剩余次数 |
| remaining factor | 剩余因子 |
| removable-singularity criterion | 可去奇点判别法 |
| repeated root | 重根 |
| repetition exponent | 重复指数 |
| replacement cost | 替换代价 |
| representative map | 代表映射 |
| represented density | 表示密度 |
| represented frame | 表示框架 |
| represented label | 被表示的标号 |
| represented-frame bound | 表示框架界 |
| represented-frame genus mean | 表示框架亏格均值 |
| represented-frame normalizer | 表示框架归一化子 |
| reproducing coefficient | 再生系数 |
| reproducing kernel | 再生核 |
| reproduction | 再生 |
| repulsion | 排斥 |
| reserve | 预留量 |
| residual Frobenius polynomial | 剩余弗罗贝尼乌斯多项式 |
| residual Gram polynomial | 剩余格拉姆多项式 |
| residual Hecke eigensystem | 剩余赫克特征系统 |
| residual Selmer vanishing | 剩余塞尔默消灭 |
| residual character | 剩余特征 |
| residual corank | 剩余余秩 |
| residual lattice | 剩余格 |
| residual module | 残余模 |
| residual point | 剩余点 |
| residual prime | 剩余素理想 |
| residual reading | 剩余读数 |
| residual root | 剩余根 |
| residual tableau | 剩余表 |
| residual vector | 残余向量 |
| residual word | 剩余词 |
| residue Frobenius | 剩余弗罗贝尼乌斯 |
| residue box | 剩余盒 |
| residue cardinality | 剩余基数 |
| residue dimension | 剩余维数 |
| residue expansion | 留数展开 |
| residue functional | 剩余泛函 |
| residue functor | 剩余函子 |
| residue module | 剩余模 |
| residue prime | 剩余素数 |
| residue realization | 剩余实现 |
| residue root | 剩余根 |
| residue subgroup | 剩余子群 |
| residue theorem | 留数定理 |
| residue-characteristic assertion | 剩余特征断言 |
| residue-degree rule | 剩余次数规则 |
| resonant | 共振的 |
| response matrix | 响应矩阵 |
| restricted product | 限制乘积 |
| restricted tensor product | 限制张量积 |
| resultant | 结式 |
| retained fraction | 保留份额 |
| retained gain | 保留增益 |
| retraction | 收缩映射 |
| return map | 返回映射 |
| returning coset | 回归陪集 |
| reverse average | 反向平均 |
| reverse diagonal | 反转对角线 |
| reverse lift | 反向提升 |
| reverse polynomial | 逆多项式 |
| reverse-partner loss | 反向伙伴损失 |
| reversed dual edge | 反转对偶边 |
| right derivative | 右导数 |
| right tail | 右尾 |
| right thickening | 右加厚 |
| right-frame | 右框架 |
| rigidification | 刚性化 |
| rigidified line identification | 刚性化线丛等同 |
| rigidify | 刚性化 |
| root class | 根类 |
| root discriminant | 根判别式 / 根判别式（rd(E)） |
| root level | 根水平 |
| root line | 根线 |
| root metric | 根度量 |
| root model | 根模型 |
| root separation | 根分离 |
| root string | 根串 |
| root-coordinate measure | 根坐标测度 |
| root-discriminant | 根判别式 |
| root-of-unity adjustment | 单位根调整 |
| root-of-unity averaging | 单位根平均 |
| root-sum functional | 根和泛函 |
| rounded bound | 取整界 |
| rounded valuation bound | 取整赋值界 |
| rounding error | 取整误差 |
| row | 行（row space = 行空间；row lattice = 行格） |
| row Gram matrix | 行格拉姆矩阵 |
| row and column type | 行型与列型 |
| row arrow | 行箭头 |
| row bridge | 行桥 |
| row budget | 行预算 |
| row chain | 行链 |
| row coefficient field | 行系数域 |
| row data | 行数据 |
| row degrees | 行次数 |
| row depth lattice | 行深度格 |
| row expansion | 行展开式 |
| row frame | 行框架 |
| row generator | 行生成元 |
| row idempotent | 行幂等元 |
| row isometry | 行等距 |
| row label | 行标号 |
| row lattice | 行格 |
| row lift | 行提升 |
| row main term | 行主项 |
| row map | 行映射 |
| row mass | 行质量 |
| row modulus exponent | 行模指数 |
| row passage | 行过渡 |
| row place | 行位 |
| row polynomial | 行多项式 |
| row realization | 行实现 |
| row selection | 行选择 |
| row spread | 行展布 / 行跨度 |
| row test | 行测试 |
| row weight | 行权 |
| row-kernel | 行核 |
| row-layer space | 行层空间 |
| row-metric defect | 行度量缺陷 |
| row-window | 行窗口 |
| run | 游程 |
| same-row ordered pair | 同行有序对 |
| sandwich inclusion | 夹逼包含 |
| saturated direct summand | 饱和直和项 |
| saturated ideal | 饱和理想 |
| saturated inclusion | 饱和包含 |
| saturated isotropic sublattice | 饱和迷向子格 |
| saturated quotient size | 饱和商大小 |
| saturated submodule | 饱和子模 |
| saturation | 饱和 / 饱和性 |
| scalar budget | 标量预算 |
| scalar homogeneity | 标量齐性 |
| scalar model | 标量模型 |
| scalar partner | 标量伙伴 |
| scalar-partner classes | 标量伙伴类 |
| scale | 标度 |
| scale parameter | 标度参数 |
| scale width | 标度宽度 |
| scheme-theoretic image | 概形论像 |
| screened gain | 筛选后的增益 |
| second complement | 第二补 |
| second sheet | 第二叶 |
| section | 截面 |
| section factor | 截面因子 |
| section lattice | 截面格 |
| see-saw transfer | 跷跷板转移 |
| seed | 种子 |
| seed test | 种子检验 |
| seen flag | 已见旗标 |
| seesaw comparison scalar | 跷跷板比较标量 |
| seesaw constant | 跷跷板常数 |
| seesaw factor | 跷跷板因子 |
| seesaw identity | 跷跷板恒等式 |
| seesaw product | 跷跷板积 |
| seesaw proportionality constant | 跷跷板比例常数 |
| seesaw tower | 跷跷板塔 |
| seesaw transfer | 跷跷板传输 |
| segment | 段 / 线段 |
| segment law | 段法则 |
| selected column | 选定列 |
| selected indefinite realisation | 选定的不定实现 |
| selection rule | 选择规则 |
| selector | 选择子 |
| self-adjoint | 自伴的 |
| self-dual | 自对偶 |
| self-dual host | 自对偶宿主 |
| self-dual lattice | 自对偶格 |
| self-dual vacuum | 自对偶真空 |
| self-twist | 自扭曲 |
| self-twist of the restriction | 限制的自扭曲 |
| semi-direct product | 半直积 |
| semiabelian scheme | 半阿贝尔概形 |
| semiabelian uniformisation | 半阿贝尔统一化 |
| semicharacter | 半特征 |
| semicharacter law | 半特征律 |
| semidefinite cone | 半定锥 |
| semilinear | 半线性的 |
| semilinear identification | 半线性等同 |
| semilocal ring | 半局部环 |
| seminegativity | 半负性 |
| semipositive | 半正的 |
| semistandard tableau | 半标准杨表 / 半标准表 |
| separable locus | 可分轨迹 |
| separable norm polynomial | 可分范数多项式 |
| separated ordinary | 分离寻常 / 分离寻常的 |
| separating element | 分离元素 |
| separating test | 分离测试 |
| series projector | 系列投影算子 |
| served gain | 服务增益 |
| served prime | 被服务的素数 |
| served primes | 被服务的素数 |
| service | 服务 |
| service condition | 服务条件 |
| sesquilinearity | 半双线性 |
| set division | 集除法 |
| seven-stage tuple | 七阶段组 |
| share | 份额 |
| share bound | 份额界 |
| share coefficient | 份额系数 |
| sheet | 片（sheet zero = 片零） |
| sheet splitting | 分片分裂 |
| shell | 壳层 |
| shift | 平移 |
| shift killer | 平移零化子 |
| shift of a lattice | 格的移位 |
| shifted window | 平移窗口 |
| short exact lattice sequence | 短正合格序列 |
| short model | 短模型 |
| short section | 短截面 |
| short value | 短值 |
| short-value identity | 短值恒等式 |
| short-word alternative | 短词替代情形 |
| shuffle algebra | 洗牌代数 |
| sign | 正负号 |
| sign character | 符号特征 |
| signal class | 信号类 |
| signal prime | 信号素数 |
| signature | 符号 / 符号差 |
| signature domain | 符号域 / 符号差区域 |
| signature flag | 符号差旗 |
| signature index | 符号指标 |
| signature matrix | 符号矩阵 |
| signed capacity | 带号容量 |
| signed index | 带符号指标 |
| signed initial minor | 带符号初始子式 |
| signed jump window | 带符号跳跃窗口 |
| signed label | 带号标签 |
| signed marking | 带符号标记 |
| similitude | 相似 / 相似因子 / 相似（变换） |
| similitude form | 相似形式 |
| similitude relation | 相似关系 |
| simple normal crossings | 简单正规交叉 |
| simple pole | 单极点 |
| simplicial presheaf | 单纯预层 |
| simultaneous approximation | 同时逼近 |
| simultaneous assertion | 同时断言 |
| single-place coefficient bound | 单点系数界 |
| single-side product estimate | 单侧乘积估计 |
| singleton | 单点集 |
| singleton character | 单元素特征 |
| singleton shortening | 单点缩短 |
| singleton wave | 单字母波 |
| singleton word | 单字母词 |
| singular strata | 奇异分层 |
| singular values | 奇异值 |
| size bound | 大小界 |
| size bounds | 大小界 |
| size budget | 尺寸预算 |
| size condition | 大小条件 |
| size datum | 大小数据 / 尺寸数据 |
| size fact | 大小事实 |
| size inequality | 大小不等式 |
| size test | 大小检验 |
| size, splitting and modulus conditions | 大小、分裂与模条件 |
| size-window bound | 尺寸窗口界 |
| skew adjoint | 斜伴随的 |
| skew invariant | 斜不变量 |
| skew-Hermitian | 斜埃尔米特的 |
| skew-Hermitian space | 斜埃尔米特空间 |
| skew-adjoint | 斜伴随的 |
| slack | 松弛量 |
| slash action | 斜作用 |
| slice budget | 切片预算 |
| slice closure | 切片封闭性 |
| slice coefficient | 切片系数 |
| slope | 斜率 |
| slope spread | 斜率散布 |
| slot | 槽 / 槽位 |
| slot coefficient | 槽系数 |
| slot lift | 槽提升 |
| slot space | 槽空间 |
| slot tensor | 槽张量 |
| small block | 小块 |
| small lift | 小提升 |
| small section | 小截面 |
| small set | 小集合 |
| small-prime share coefficient | 小素数份额系数 |
| small-prime splitting condition | 小素数分裂条件 |
| small-share model | 小份额模型 |
| small-side condition | 小侧条件 |
| small-side saving | 小侧节省 |
| smooth Bessel map | 光滑贝塞尔映射 |
| smooth cyclicity | 光滑循环性 |
| smooth factorizable test | 光滑可分解的检验 |
| smooth globalization | 光滑整体化 |
| smoothed Hermitian root line | 光滑化埃尔米特根线 |
| smoothed explicit formula | 光滑显式公式 |
| smoothing coefficient | 光滑化系数 |
| smoothing loss constant | 光滑化损失常数 |
| socle-semisimplicity | 基座半单性 |
| source differences | 源差 |
| source rank | 源秩 |
| source realization | 源实现 |
| spacing bound | 间距界 |
| sparse-thick cut | 稀疏厚切割 |
| special fibre | 特殊纤维 |
| special-fibre | 特殊纤维 |
| special-fibre component | 特殊纤维分支 |
| specialization map | 专门化映射 |
| spectral lifting operator | 谱提升算子 |
| spectral projector | 谱投影算子 |
| spectral rank | 谱秩 |
| spectral realization | 谱实现 |
| spectral row | 谱行 |
| spectral test | 谱检验 |
| sphere count | 球面计数 |
| spherical Hecke polynomial | 球面赫克多项式 |
| spherical generator | 球面生成元 |
| spherical logarithmic mean | 球面对数平均 |
| spherical module | 球面模 |
| spherical test | 球面检验 |
| spherical transfer | 球面传输 |
| spherical vector | 球面向量 |
| sphericity | 球面性 |
| split bound | 分裂界 |
| split congruence assembly | 分裂同余装配 |
| split exact tangent sequence | 分裂正合正切序列 |
| split gap | 分裂间隙 |
| split lattice model | 分裂格模型 |
| split local idempotent | 分裂局部幂等元 |
| split place | 分裂位 |
| split spherical algebra | 分裂球面代数 |
| split support | 分裂支撑 |
| split term lattice | 分裂项格 |
| split uniformisation | 分裂一致化 |
| split-group package | 分裂群包 |
| split-place condition | 分裂位条件 |
| splitting algebra | 分裂代数 |
| splitting bound | 分裂界 |
| splitting character | 分裂特征 |
| splitting exponent | 分裂指数 |
| splitting scalar | 分裂标量 |
| splitting-character | 分裂特征 |
| spread | 扩散 / 散布 / 跨度 |
| spreading-out prime | 铺开素数 |
| square (grid cell) | 方格 |
| square presentation | 方阵表示 |
| square-field condition | 平方域条件 / 方格域条件 |
| square-recursive | 平方递归 / 平方递推 |
| square-recursive regime | 平方递归状态 |
| square-recursive size datum | 平方递归的尺度数据 / 平方递推规模数据 |
| square-zero | 平方零 |
| square-zero subgroup | 平方零子群 |
| squareclass | 平方类 |
| squared-integral amplitude estimate | 平方积分振幅估计 |
| squared-norm condition | 平方范数条件 |
| squarefree | 无平方因子 |
| squarefree kernel | 无平方因子核 |
| stabilizer | 稳定化子 |
| stabilizer argument | 稳定化子论证 |
| stabilizer denominator | 稳定化子分母 |
| stabilizer loss | 稳定化子损失 |
| stabilizer-weighted inner product | 稳定化子加权内积 |
| stable selection | 稳定选择 |
| stable term | 稳定项 |
| stage | 阶段 |
| stage hypothesis | 阶段假设 |
| staged lower bounds | 分阶段下界 |
| staircase fractional-ideal tuple | 阶梯分式理想组 |
| standard genus | 标准属 |
| standard lattice | 标准格 |
| standard layer | 标准层 |
| standard parabolic | 标准抛物子群 |
| standard tableau | 标准表 |
| standing constants | 常设常数 |
| star-compatible | 星相容 |
| start data | 起点数据 |
| starting rank | 起始秩 |
| stationary phase | 驻相法 |
| step character | 步长特征 |
| step function | 阶梯函数 |
| straightening | 拉直 / 直线化 |
| stratum | 分层 |
| stretched-exponential | 拉伸指数 |
| strict class | 严格类 |
| strict group | 严格群 |
| strict henselisation | 严格亨泽尔化 |
| strict sign | 严格符号 |
| strict-chain length | 严格链长 |
| strictly upper triangular | 严格上三角 |
| string | 字符串 |
| string (Zelevinsky) | 串 |
| strip constant | 条带常数 |
| strong multiplicity one | 强重数一 |
| stronger gaps | 更强的间隙 |
| strongly measurable | 强可测 |
| sub-quotient | 子商 |
| subgroup character projector | 子群特征投影子 |
| subline | 子线 |
| submean | 次均值 |
| successive extraction of leading coefficients | 首项系数的逐次提取 |
| successive minima | 相继极小 / 连续极小 |
| successive quotient | 逐次商 |
| successive-minima bound | 逐次极小界 |
| successive-minima inequality | 逐次极小不等式 |
| sum choice | 和选择 |
| summation by parts | 分部求和 |
| summation of the table | 表格求和 |
| sup norm | 上确界范数 |
| sup-norm lattice | 上确界范数格 |
| supercuspidal | 超尖点的 |
| supply of hosts | 宿主供给 |
| support condition | 支集条件 |
| support locus | 支集轨迹 |
| surplus letter | 盈余字母 |
| surplus letters | 盈余字母 |
| surviving character | 幸存特征 |
| surviving set | 存活集 |
| switch coordinates | 切换坐标 |
| switch height | 切换高度 |
| symbol | 符号 |
| symbol map | 符号映射 |
| symplectic basis | 辛基 |
| table point | 表点 |
| tableau | tableau（保留原词） / tableau（杨表型表） / 表格 |
| tableau basis | 表格基 |
| tableau degree bound | 表格次数界 |
| tableau lattice | tableau 格 |
| tagged multiplicities | 带标记重数 |
| tame character | 温和特征 |
| tame descent | 温和下降 |
| tame distinctness | 温和互异性 |
| tame inertia | 温和惯性 |
| tame test | 温和检验 |
| tame type | 温和型 |
| tame type place | 温和型位 |
| tangent law | 切线律 |
| target prime-sum bound | 目标素数和界 |
| target readings | 目标读数 |
| target value lattice | 靶值格 |
| tautological line | 重言线 |
| telescoping | 叠缩 |
| tensor isometry | 张量等距 |
| tensor lattice | 张量格 |
| terminal budget | 终端预算 |
| terminal class coordinates | 终端类坐标 |
| terminal comparison | 终端比较 |
| terminal contraction | 终端收缩 |
| terminal denominator | 终端分母 |
| terminal differentiation operator | 终端微分算子 |
| terminal discriminant | 终端判别式 |
| terminal error | 末端误差 |
| terminal estimate | 终端估计 |
| terminal fibre | 终止纤维 |
| terminal fundamental potential | 终端基本位势 |
| terminal hypothesis | 终端假设 |
| terminal lattice | 终端格 |
| terminal layer | 终端层 |
| terminal level character | 终端水平特征 |
| terminal lift | 终止提升 / 终端提升 |
| terminal map | 终端映射 |
| terminal minor | 终止子式 |
| terminal operator | 终端算子 |
| terminal pairing | 终端配对 |
| terminal radial coordinate | 终端径向坐标 |
| terminal size coefficient | 末端大小系数 |
| terminal table | 终端表 |
| terminal tableau | 终端表 |
| terminal valuation | 终端赋值 |
| terminal vector | 终端向量 |
| terminal-flag | 终止旗 |
| termwise transformation | 逐项变换 |
| test algebra | 测试代数 |
| test class | 测试类 |
| test cohomology | 测试上同调 |
| test functional | 测试泛函 |
| test identification | 测试等同 |
| test lattice | 测试格 |
| test metric | 测试度量 |
| test place | 检验位 |
| test set | 测试集 |
| test trait | 检验 trait |
| the remaining characters | 其余特征 |
| theorem of the cube | 立方定理 |
| theta chart | 西塔卡 |
| theta condition | 西塔条件 |
| theta constant | 西塔常数 |
| theta family | 西塔族 |
| theta function with characteristics | 带特征的西塔函数 |
| theta generator | 西塔生成元 |
| theta group | 西塔群 |
| theta kernel | 西塔核 |
| theta lattice | 西塔格 |
| theta lift | 西塔提升 |
| theta line | 西塔线 |
| theta mean | 西塔均值 |
| theta module | 西塔模 |
| theta null | 西塔零值 |
| theta quotient | theta 商 |
| theta rule | 西塔规则 |
| theta section | 西塔截面 |
| theta test | 西塔测试 |
| theta transformation criterion | 西塔变换判别法 |
| theta translation | 西塔平移 |
| theta translation formula | 西塔平移公式 |
| theta weight | 西塔权 |
| theta-group translate | 西塔群平移 |
| theta-jet | 西塔流 |
| theta-line | theta 线 |
| theta-null vector | theta 零向量 |
| theta-supremum estimate | 西塔上确界估计 |
| thick (prime) | 厚的（素理想） |
| thick / nonthick | 厚的／非厚的 |
| thick / thin position | 厚位置／薄位置 |
| thick contribution | 厚贡献 |
| thick density | 厚密度 / 厚度密度 |
| thick host labels | 厚宿主标签 |
| thick index set | 厚指标集 |
| thick label | 厚标号 / 厚标签 |
| thick position | 厚位置 |
| thick prime | 厚素理想 |
| thick region | 厚区域 |
| thick set | 厚集 |
| thick weight scale | 厚权标度 |
| thick word | 厚词 |
| thick-position adjustment | 厚位置调整 |
| thick-set rank term | 厚集秩项 |
| thickening | 加厚 |
| thickening functor | 加厚函子 |
| thickness | 厚度 |
| thickness constant | 厚度常数 |
| thin character sums | 薄特征和 |
| thin position | 薄位置 |
| thin value | 薄值 |
| thin weight interval | 薄权重区间 |
| thin weight scale | 薄权标度 |
| thin-character bound | 薄特征界 |
| thin-character hypotheses | 薄特征假设 |
| thin-position bound | 薄位置界 |
| thin-scale condition | 薄标度条件 |
| thin-scale estimate | 薄标度估计 |
| thin-value | 薄值 |
| three-half-period product bound | 三半周期乘积界 |
| three-sided division data | 三侧除法数据 |
| threshold | 阈值 |
| threshold datum | 阈值数据 |
| tie | 平局 / 并列 / 系结 / 纽带 / 绑定 / 联系 / 配对 |
| tie (four ties) | 关联（四个关联） |
| tie factor | 并列因子 |
| tied arithmetic comparison | 绑定算术比较 |
| tied comparison | 绑定比较 |
| tied equal-word model | 绑定的等词模型 |
| tied model | 绑定模型 |
| tied pair | 系结对 |
| tied quotient | 绑定商 |
| tied sections | 绑定截面 |
| tied term | 成对项 |
| tied test lattice | 系定测试格 |
| ties | 匹配关系 |
| tight weight | 紧的权 |
| tightness | 紧性 |
| tile | 瓦片 / 瓦片（marked tile：带标记的瓦片） |
| tilt | 倾斜 |
| tolerance | 容差 |
| top Chern proportionality | 顶陈比例性 |
| top arithmetic self-intersection | 顶算术自交 |
| top bijection | 顶部双射 |
| top budget | 最高次预算 |
| top density | 顶密度 |
| top label | 顶标号 |
| top labels | 顶标号 |
| top position | 顶位置 |
| top positions | 顶位置 / 顶层位置 / 顶部位置 |
| top row | 顶行 |
| top set | 顶集 |
| top triple | 顶部三元组 |
| top type | 顶部型 |
| top weight | 顶权 |
| top weights | 顶权重 |
| top-count | 顶计数 |
| top-kernel | 顶层核 |
| top-level block point | 顶层块点 |
| top-position set | 顶位置集 |
| top-set share | 顶集份额 |
| top-weight scale | 顶权标度 |
| top-weight term | 顶权重项 |
| toral | 环面的 |
| toral support | 环面支撑 |
| toral test | 环面检验 |
| toric | 环面的 |
| toric bound | 环面界 |
| toric denominator | 环面分母 |
| toric-value identity | 环面值恒等式 |
| toroidal compactification | 环面紧化 |
| torsion disk | 挠圆盘 |
| torsion expansion | 挠展开 |
| torsion frame | 挠框架 |
| torsion translate | 挠平移 |
| torsion-enumeration integer | 挠枚举整数 |
| torsor | 主齐性空间 / 挠子 |
| torus Lie algebra | 环面李代数 |
| torus average | 环面平均 |
| torus rescaling | 环面重标度 |
| torus scalar | 环面标量 |
| torus scaling | 环面伸缩 |
| total bound | 总界 |
| total layer loss | 总层损失 |
| total mass | 总质量 |
| total rational cohomology | 总有理上同调 |
| total variation | 全变差 |
| tower calculation | 塔计算 |
| tower data | 塔数据 |
| tower divisibility | 塔整除性 |
| tower group | 塔群 |
| trace basis | 迹基 |
| trace bound | 迹界 |
| trace class | 迹类 |
| trace dual | 迹对偶 |
| trace duality | 迹对偶 |
| trace lattice | 迹格 |
| trace linearity | 迹的线性性 |
| trace map | 迹映射 |
| trace pairing | 迹配对 |
| trace power | 迹幂 |
| trace weight | 迹权 |
| trace-dual | 迹对偶 |
| trace-dual basis | 迹对偶基 |
| trace-dual transform | 迹对偶变换 |
| trait | trait（一维正则局部环，保留原文） / trait（保留） / trait（完备离散赋值环） / trait（离散赋值 trait） / trait（离散赋值环的谱） / trait（离散赋值环的谱，保留原文） / trait（谱为离散赋值环的概形；此处指具有有限剩余域者） / trait（赋值环谱） / 性状 |
| trans-position operator | 换位算子 |
| transference bound | 转移界 |
| transgression | 超渡 |
| translation determinant | 平移行列式 |
| translation equivalence relation | 平移等价关系 |
| translation map | 平移映射 |
| transported flag | 迁移的旗 |
| transported polynomial | 输运多项式 |
| transvection | 平延 |
| transvection integral | 平延积分 |
| transvection step parameter | 平延步长参数 |
| trial pair | 试探对 / 试验对 |
| trial weight | 试验权重 |
| triangle identity | 三角恒等式 |
| triangular locus | 三角轨迹 |
| truncated explicit formula | 截断显式公式 |
| truncated exponential | 截断指数 |
| truncated group coefficient | 截断群系数 |
| truncated phase | 截断相位 |
| tuple dimension | 元组维数 |
| tuple twist | 组扭曲 |
| twist exclusion data | 扭曲排除数据 |
| twist index | 扭指标 |
| twist representation | 扭曲表示 |
| twist selection | 扭曲选择 |
| twist selector | 扭曲选择子 |
| twist-good | 扭曲良好 |
| twist-good cut family | 扭曲良好割族 |
| twisted Haar measure | 扭曲哈尔测度 |
| twisted centralizer | 扭曲中心化子 |
| twisted chain | 扭曲链 |
| twisted form | 扭曲形式 |
| twisted layer space | 扭曲层空间 |
| twisted lift | 扭曲提升 |
| twisted place | 扭位 / 扭曲位 |
| twisted-square triple | 扭曲平方三元组 |
| twisted-support condition | 扭曲支撑条件 |
| twisting data | 扭曲数据 |
| two-case separation condition | 两情形分离条件 |
| two-run | 双轮 |
| two-sided point | 双侧点 / 双边点 |
| two-torsion-normalized | 按二挠归一化的 |
| type lattice | 型格 |
| type locus | 型轨迹 |
| type prime | 型素数 |
| type projector | 型投影算子 / 类型投影 |
| type threshold | 型阈值 |
| type-locus | 型轨迹 |
| type-prime exponent | 类型素数指数 |
| typed formal factor | 带型形式因子 |
| typed measure | 定型测度 |
| ultrametric inequality | 超度量不等式 |
| unfolding | 展开 / 展开法 |
| unfolding constant | 展开常数 |
| unframed Weyl lattice | 无框架外尔格 |
| uniform negative budget | 一致的负预算 |
| uniform stabilizer bound | 一致稳定化子界 |
| uniform thick sum | 均匀厚和 |
| uniformisation | 一致化 |
| uniformiser | 一致化子 |
| uniformiser radical | 一致化子根理想 |
| uniformization | 一致化 |
| uniformized tower cover | 一致化塔覆盖 |
| uniformizer power | 一致化子幂 |
| uniformizer root | 一致化子根 |
| unimodular | 单模的 |
| unimodular gluing | 幺模粘合 |
| unimodular lattice | 幺模格 |
| unimodular row | 单模行 |
| unipotent | 幂幺 / 幂幺的 |
| unipotent coinvariants | 幂幺余不变量 |
| unipotent conjugating coordinate | 幺幂共轭坐标 |
| unipotent coordinate map | 幺幂坐标映射 |
| unipotent group | 单幂群 / 幂幺群 |
| unipotent index | 幺幂指标 |
| unipotent radical | 单幂根 / 单幂根基 / 幂幺根 / 幺幂根 |
| unipotent reduction | 幂幺约化 |
| unique functional | 唯一泛函 |
| unit ball | 单位球 |
| unit circle | 单位圆 |
| unit integral | 单位积分 |
| unit polydisc | 单位多圆盘 |
| unit relation | 单位关系 |
| unit scale | 单位标度 / 可逆标度 |
| unit series | 单位级数 |
| unit-circle condition | 单位圆条件 |
| unit-hyperplane assertion | 单位超平面断言 |
| unit-window zero count | 单位窗口零点计数 |
| unitary descent | 酉下降 |
| unitary summand | 酉分量 |
| unitriangular | 单位三角 / 单位三角的 / 幺幂三角的 |
| unitriangular coordinates | 单位三角坐标 |
| universal norm polynomial | 泛范数多项式 |
| universally catenary | 泛链性的 |
| unkilled two-torsion point | 未消去的二挠点 / 未被杀死的二扭点 / 未被消去的二挠点 |
| unlinked | 无链接的 / 无链接的；potentially unlinked = 潜在无链接的 / 非链接的 / 非链接的；unlinking = 非链接性 |
| unlinked (place) | 不链接的（位） |
| unlinked character | 非链接特征 |
| unlinked place | 不链接的位 |
| unlinking | 不链接性 |
| unmodified entry bound | 未修正的矩阵元界 |
| unmodified lift | 未修改的提升 |
| unobstructed | 无障碍的 |
| unprojected evaluation | 未投影求值 |
| unscaled kernel | 未缩放核 |
| unsigned local reference mass | 无符号局部参考质量 |
| untilt | untilt（保留原文） |
| unused node | 未用节点 |
| upper block parabolic | 上块抛物子群 |
| upper tail | 上尾部 |
| upper triangular | 上三角 |
| upper unitriangular | 上单位三角的 |
| upper unitriangular group | 上单位三角群 |
| upper unitriangular subgroup | 上单位三角子群 |
| upper-integral-unipotent | 上整幺幂 |
| upper-neighbor relation | 上邻关系 |
| upward | 向上的 |
| upward/downward order | 上行阶／下行阶 |
| usable place | 可用位 |
| vacuum lattice | 真空格 |
| vacuum theta product | 真空西塔积 |
| vacuum valuation shell | 真空赋值壳 |
| vacuum vector | 真空向量 |
| valuation budget | 赋值预算 |
| valuation domain | 赋值整环 |
| valuation property | 赋值性质 |
| valuation spectrum | 赋值谱 |
| valuation-like idempotent splitting | 类赋值幂等分裂 |
| valuative criterion | 赋值判别法 |
| value lattice | 值格 |
| variant of the square | 平方定理 |
| vector mark | 向量标记 |
| vertical determinant factor | 垂直行列式因子 |
| vertical edge | 竖直边 |
| vertical factor | 竖直因子 |
| vertical zero | 竖直零点 |
| very cuspidal | 非常尖点的 |
| virtual character | 虚拟特征 |
| volume ties | 体积绑定 |
| von Mangoldt function | 冯·曼戈尔特函数 |
| wall embedding | 墙嵌入 |
| wall gap | 墙间隙 / 墙隙 / 壁间隙 |
| wall patch | 墙片 |
| wave grid | 波网格 |
| wave interpolation identity | 波插值恒等式 |
| wave multiplier | 波乘子 |
| weak admissibility | 弱容许性 |
| weak approximation | 弱逼近 |
| weak attachment | 弱附着 |
| weak descent | 弱下降 |
| weak unitary descent | 弱酉下降 |
| weakly compatible representation | 弱相容表示 |
| weight diagram | 权图 |
| weight dictionary | 权字典 |
| weight extraction | 权提取 / 权重提取 |
| weight graded | 权重分次的 |
| weight lattice | 权格 |
| weight law | 权重律 |
| weight ring | 权环 |
| weight spread | 权展布 / 权重散布 |
| weight type | 权型 |
| weight-change inequality | 权变不等式 |
| weight-division length | 权重除长 |
| weight-gap constant | 权间隙常数 |
| weight-gap criterion | 权间隙判别法 |
| weight-gap inequality | 权重间隙不等式 |
| weight-size requirement | 重量–尺度要求 |
| weight-spread bound | 权重展布界 |
| weight-window width | 权窗口宽度 |
| weight-zero algebra | 权零代数 |
| weight-zero product | 零权乘积 |
| weighted coefficient integral | 加权系数积分 |
| weighted differentiability condition | 加权可微性条件 |
| weighted length | 加权长度 |
| weighted multiplicity | 加权重数 |
| weighted norm | 加权范数 |
| weighted order | 加权阶 |
| weighted theta series | 加权西塔级数 |
| wild inertia | 野惯性 / 野惯性群 |
| window and tile conditions | 窗口条件与瓦片条件 |
| window assertion | 窗口断言 |
| window coefficient | 窗口系数 |
| window family | 窗口族 |
| window pair | 窗口对 |
| window point | 窗口点 |
| witness | 见证 |
| witness condition | 见证条件 |
| witness interval | 见证区间 |
| witness place | 见证位 |
| word | 词 |
| word budget | 词预算 |
| word fold | 词折叠 |
| word frame | 词框架 |
| word length | 词长 |
| word polynomial | 字多项式 / 词多项式 |
| word prime | 字素数 |
| word set | 字集 |
| word shift | 字移位 |
| word space | 词空间 |
| word weight | 词权 |
| word window | 词窗口 |
| wordwise | 逐词的 |
| wordwise inequality | 逐词不等式 |
| working class | 工作类 |
| wrap coefficient | 回绕系数 |
| zero count | 零点计数 |
| zero evaluation | 零求值 |
| zero gap | 零点间隙 |
| zero monodromy | 零单值 |
| zero multiplicity | 零点重数 |
| zero-Gram | 零格拉姆 |
| zero-density estimate | 零点密度估计 |
| zero-density exclusion | 零点密度排除 |
| zero-free box hypothesis | 无零点盒假设 |
| zero-shift inert | 零移位惰性 |
| zero-shift lattice | 零位移格 |
| zeroth-layer column lattice | 第零层列格 |
| zeroth-layer column slope | 第零层列斜率 |
| zonal coefficient | 带球系数 |
| zonal spherical function | 球带函数 |
| étale module | 平展模 |
| étale translation estimate | 平展平移估计 |
| ℓ-prepared | ℓ 预备的 |
| 格拉姆 volume | 格拉姆 体积 |