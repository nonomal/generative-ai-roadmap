![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)

# AIGC Diagram Sets

This repository hosts a collection of roadmaps, thinking maps, and other diagram sets related to
generative AI (AIGC). Each diagram set covers one independent topic and lives in its own
subdirectory under [`sets/`](./sets/). Every set subdirectory has its own `README.md` (and
translations, where available) so you can navigate all versions and languages of that set.

This file is a translation of [the original Chinese index](./README.md).

## Localization

The original language of each diagram set may vary (most are in Chinese). If a set has versions in
other languages, links to them (e.g. `README.en.md`) are provided in that set's own README.

## LICENSE

This work is licensed under a
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Diagram sets

| Set | Description | Languages |
| --- | --- | --- |
| [The Roadmap of Generative AI](./sets/generative-ai-controllability/README.en.md) | Evolution and application scenarios of generative AI, organized around "controllability" | [中文](./sets/generative-ai-controllability/README.md) / English |
| [LLM and Multimodal Thinking Map](./sets/llm-multimodal-thinking-map/README.md) | A thinking map on the technical evolution and applications of LLMs and multimodal AI | 中文 only |
| [2026 - The Critical Path to Enterprise AI Capability](./sets/enterprise-ai-critical-path/README.en.md) | AICP: the critical path enterprises follow while building AI capability | [中文](./sets/enterprise-ai-critical-path/README.md) / English |

## Adding a new diagram set

To add a new diagram set, create a new subdirectory under `sets/` (named with a short, descriptive
English slug) following this structure:

```
sets/<set-slug>/
  README.md            # Guide for this set (original language first)
  README.en.md          # Optional: translation(s)
  diagrams/
    <index>-<topic>.<lang-code>.png   # e.g. 01-topic.zh.png / 01-topic.en.png
```

A single-language set can skip the translated README, but image filenames should still carry an
explicit language code (e.g. `.zh.png`) so the naming stays consistent if a translation is added
later. Finally, add a row linking to the new set in the table above.
