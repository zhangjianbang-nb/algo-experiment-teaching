# AI 算法实验方法全书 · 研究与教学站

**实验怎么设计 · 算法怎么创新 · 实验怎么落地**——一本可以离线打开的单页书。

线上：<https://zhangjianbang-nb.github.io/algo-experiment-teaching/>

## 规模

| 单元 | 数量 | 说明 |
|---|---|---|
| 全书 | 16 卷 / 546 篇长文 | 每篇 3,000–5,200 汉字，独立深读片段 |
| 研究方向 | 6 | 实验设计 / 算法创新 / 表征学习 / 规模化 / 效率 / 评测与复现 |
| 经典算法 | 9 | 含 ResNet、Transformer、Adam、LoRA、Switch Transformer 五个主案例 |
| 核心论文 | 10 + 近年论文 14 | 每篇含主张、对照、机制、边界与可复现判据 |
| 理论课 | 12 | 偏差-方差、假设检验、效应量、预算分配等 |
| 考核题 | 52 | 五层题库：概念 / 计算 / 设计 / 诊断 / 开放 |
| 图示 | 214 | 内联 SVG，零外部依赖 |
| 可见正文 | **4,155,163 字符**（约 239 万汉字） | 正文口径，不含字段名 |

## 打开方式

- 线上直接访问上面的 Pages 地址；
- 离线：下载仓库后双击 `index.html`（file:// 直开，无需服务器、无外部 CDN）；
- 路由：`#/home` `#/map` `#/algos` `#/papers` `#/evolution` `#/summary` `#/book` `#/story` `#/theory` `#/deepdive` `#/exam` `#/appendix`。

## 目录

```
index.html          单文件前端（hash 路由 + 内联样式）
data/               唯一真源 JSON + bundle.js（window.SITE_DATA）
vendor/katex/       本地 KaTeX（离线公式渲染）
figures/            预留图目录
contract.json       验收合同（可见字符下限 3,000,000）
DEPENDENCIES.md     依赖与离线说明
```

## 验收

- `verify_site.py --profile L2 --phase all`：0 error / 0 warning；
- 端到端：16 条路由 + 134 个书页，0 JS 错误、0 横向溢出；
- 214 张 SVG：0 几何越界；
- 近重复扫描：10,088 段，0 对重复。

## 许可

文字与图示为原创整理，案例数字均取自公开论文；引用与出处见各篇「对应」行与论文条目。
