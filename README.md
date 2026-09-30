<div align="center">

![Zheng Haodi — 语音识别 × 端到端语音大模型](assets/header.svg)

[![Shenzhen Technology University](https://img.shields.io/badge/Shanghai_Jiao_Tong_University-SJTU-0d9488?style=flat-square)](https://github.com/hawaiicoco)
![speech recognition](https://img.shields.io/badge/focus-speech_recognition-7c3aed?style=flat-square)
![end-to-end spoken LM](https://img.shields.io/badge/focus-end--to--end_spoken_LM-0d9488?style=flat-square)
![offline-first](https://img.shields.io/badge/offline--first-always-5b7183?style=flat-square)
![reproducible](https://img.shields.io/badge/reproducible-seeded_%2B_locked-5b7183?style=flat-square)

</div>

![研究旅程：hypofuse → slotvox](assets/journey.svg)

## 项目

| 项目 | 研究方向 | 已实现内容 |
|---|---|---|
| [hypofuse](https://github.com/hawaiicoco/hypofuse) | 语音识别后处理 | n-best 清单校验、ROVER 融合与混淆网络、n-gram 重打分与浅融合、置信度校准、CER/WER 切片错误分析 |
| [slotvox](https://github.com/hawaiicoco/slotvox) | 端到端语音理解 | 合成任务型对话工厂、联合意图-槽位模型、流式部分意图、语音 LLM 指令数据管线、回合级评测与报告 |

两个项目都包含命令行工具、可运行示例、契约/黄金测试和 CPU 模型测试，全部离线可复现。

## 技术栈

![Python](https://img.shields.io/badge/Python-3.11%2B-3776ab?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-core-013243?style=flat-square&logo=numpy&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-CPU_extra-ee4c2c?style=flat-square&logo=pytorch&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-2000%2B_cases-0a9edc?style=flat-square)
![ruff](https://img.shields.io/badge/ruff-format_%2B_lint-d7ff64?style=flat-square)
![hatchling](https://img.shields.io/badge/hatchling-wheel_%2B_sdist-4c566a?style=flat-square)

## 活动

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hawaiicoco/hawaiicoco/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hawaiicoco/hawaiicoco/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/hawaiicoco/hawaiicoco/output/github-snake.svg" />
</picture>

## 当前关注

- 多假设对齐与融合策略的确定性评测，校准曲线的诚实解读。
- 语音-文本统一 token 序列上的联合建模、流式解码与背压语义。
- 合成数据上的可复现训练链路：种子、锁文件与逐提交检查。
