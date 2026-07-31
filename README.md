![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)

# 生成式AI技术与应用图集 | AIGC Diagram Sets

本仓库收录了一系列与生成式AI（AIGC）相关的路线图、思考导图等图集。每个图集聚焦一个独立的主题，
并存放在 [`sets/`](./sets/) 目录下的独立子目录中。每个子目录都有自己的 `README.md`（及其语言译本），
用于导览该图集下的所有版本与语言。

## Localization

各图集的原始语言可能不同（多数为中文）。如某图集提供了其他语言的版本，会在该图集自己的
README 中给出链接，例如 `README.en.md`。

## LICENSE

This work is licensed under a
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## 图集列表

| 图集 | 简介 | 语言 |
| --- | --- | --- |
| [生成式AI的应用路线图](./sets/generative-ai-controllability/README.md) | 以“可控性”为主线，梳理生成式AI的演进规律与应用场景 | 中文 / [English](./sets/generative-ai-controllability/README.en.md) |
| [大模型技术与应用思考导图](./sets/llm-multimodal-thinking-map/README.md) | 大模型与多模态AI的技术演进和应用思考导图 | 中文 |
| [2026：通向企业级AI能力的关键路径](./sets/enterprise-ai-critical-path/README.md) | AICP：企业构建AI能力过程中的关键路径图集 | 中文 / [English](./sets/enterprise-ai-critical-path/README.en.md) |

## 新增图集

新增一个图集时，请在 `sets/` 下创建一个新的子目录（使用能概括主题的英文短横线命名），并遵循以下结构：

```
sets/<图集名称>/
  README.md            # 该图集的导览（原始语言优先）
  README.en.md          # 可选：其他语言的译本
  diagrams/
    <序号>-<主题>.<语言代码>.png   # 例如 01-topic.zh.png / 01-topic.en.png
```

单一语言的图集可以省略语言译本 README，但图片文件名仍需带上语言代码（如 `.zh.png`），
以便未来补充其他语言版本时保持命名一致。最后在本文件的图集列表表格中添加一行链接。
