# EGA 简体中文版：格罗滕迪克《代数几何学原理》（Éléments de géométrie algébrique）

本仓库是亚历山大·格罗滕迪克（Alexander Grothendieck）在让·迪厄多内（Jean Dieudonné）协助下撰写的《代数几何学原理》（*Éléments de géométrie algébrique*，简称 EGA）的大陆简体中文译本。原著于 1960–1967 年发表在 *Publications mathématiques de l'IHÉS* 第 4、8、11、17、20、24、28、32 期。本仓库包含 EGA I、EGA II、EGA III-1 与 EGA III-2 的完整译文（含第 0 章 §§1–13），以及 EGA IV 第一分册中第 0 章 §§14–23 与第 IV 章 §1 的译文。

## 制作方式

翻译、订正和排版均由人工智能完成。EGA I–III 的翻译、订正整合、排版、构建和机器核验由 OpenAI Codex 的 GPT-5.6 Sol（Ultra 推理强度）完成；EGA IV 第一分册由 GPT-5.6 Sol 翻译，GPT-6 Astra（Ultra）负责检查、订正和组装。译文以 NUMDAM 上的法文印本和法文转写本为依据，英文社区译本（ryankeleti/ega）只作次要参照（见“来源与署名”）。四册都做了结构、公式、标签、交叉引用、字体、链接和逐页版面的检查。

## 状态

EGA I–III 已全部译完；EGA IV 只译出第一分册的一部分。译文中可能仍有错误。

## 其他语言版本

- 法文：[ega-fr](https://github.com/KokunoYumeto/ega-fr)——原印本的完整转写（存真版与订正版）。
- 英文：[ega-en](https://github.com/KokunoYumeto/ega-en)——完整译本（引言、第 0–IV 章）。
- 西班牙文：[ega-fga-es](https://github.com/KokunoYumeto/ega-fga-es)——EGA II、EGA III、EGA IV 第三、四分册；EGA IV 第一分册仅第 0 章。
- 巴西葡萄牙文：[ega-fga-sga-pt-br](https://github.com/KokunoYumeto/ega-fga-sga-pt-br)——EGA II、EGA III-1、EGA IV 第三分册、EGA I 第 I 章；其余部分只有个别小节。
- 越南文：[ega-fga-sga-vi](https://github.com/KokunoYumeto/ega-fga-sga-vi)——EGA II、EGA III-1、EGA I 第 I 章；其余部分只有个别小节。
- 韩文：[ega-ko](https://github.com/KokunoYumeto/ega-ko)——EGA I–III；EGA IV 第一分册的第 0 章 §§14–23 与第 IV 章 §1。

本项目所有 EGA、FGA、SGA 版本的总目录见 [ega-fga-sga](https://github.com/KokunoYumeto/ega-fga-sga)。

## 内容

2026 年 9 月 23 日版，每册都有 PDF、完整单文件 LaTeX 和可重建该册的源代码 ZIP：

| 册次 | PDF | 完整单文件 LaTeX | 完整源代码 ZIP |
|---|---|---|---|
| EGA I | [阅读](releases/2026-09-23-ega-i-iii/01_ega1-zh-hans-cn.pdf) | [编辑](releases/2026-09-23-ega-i-iii/02_ega1-zh-hans-cn.tex) | [重建](releases/2026-09-23-ega-i-iii/03_ega1-zh-hans-cn-source.zip) |
| EGA II | [阅读](releases/2026-09-23-ega-i-iii/04_ega2-zh-hans-cn.pdf) | [编辑](releases/2026-09-23-ega-i-iii/05_ega2-zh-hans-cn.tex) | [重建](releases/2026-09-23-ega-i-iii/06_ega2-zh-hans-cn-source.zip) |
| EGA III-1 | [阅读](releases/2026-09-23-ega-i-iii/07_ega3-1-zh-hans-cn.pdf) | [编辑](releases/2026-09-23-ega-i-iii/08_ega3-1-zh-hans-cn.tex) | [重建](releases/2026-09-23-ega-i-iii/09_ega3-1-zh-hans-cn-source.zip) |
| EGA III-2 | [阅读](releases/2026-09-23-ega-i-iii/10_ega3-2-zh-hans-cn.pdf) | [编辑](releases/2026-09-23-ega-i-iii/11_ega3-2-zh-hans-cn.tex) | [重建](releases/2026-09-23-ega-i-iii/12_ega3-2-zh-hans-cn-source.zip) |

EGA IV 第一分册（第 0 章 §§14–23、第 IV 章 §1、参考文献和索引）的可编辑译文在 [editions/EGA_IV_1](editions/EGA_IV_1/README.md)，用 XeLaTeX 编译 `main.tex`。各册的核验记录在 [releases/2026-09-23-ega-i-iii](releases/2026-09-23-ega-i-iii)；更早的版本见 [GitHub 发布页](https://github.com/KokunoYumeto/ega-zh-hans-cn/releases)。

## 来源与署名

- 原著：Alexandre Grothendieck, avec la collaboration de Jean Dieudonné, *Éléments de géométrie algébrique*,
  *Publications mathématiques de l'IHÉS*（1960–1967），见 [NUMDAM](https://www.numdam.org/journals/PMIHES/)。EGA IV 第一分册为第 20 期（1964）第 5–259 页（[法文原文](https://numdam.org/item/PMIHES_1964__20__5_0/)）。
- 参照资料：[法文 EGA 版](https://github.com/KokunoYumeto/ega-fr/releases/tag/ega-fr-2026-10-24-r19)，以及英文社区译本 [ryankeleti/ega](https://github.com/ryankeleti/ega/tree/3d7afe28c99d1887ccdb85acf2ca1afd93fb1971) （版本 3d7afe2）。该英文译本的贡献者为 Mateo Carmona、Tim Holzschuh、Tim Hosgood、Ryan Keleti、Thiago Solovera & Nery 和 Wayne Yang，各自的范围见其 [分节署名](https://github.com/ryankeleti/ega/blob/3d7afe28c99d1887ccdb85acf2ca1afd93fb1971/README.md)。他们不是中文译文的译者。
- EGA IV 第一分册沿用法文 TeX 的数学记号和原始标签。

## 权利

在出版者对人工智能完成的翻译、订正和排版享有任何权利的范围内，这些权利依 [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.zh-hans) 贡献到公有领域。这不影响原著以及上述人工译本的权利，也不授予使用它们的许可。完整说明见 [RIGHTS_NOTICE.md](RIGHTS_NOTICE.md)。
