# Zheng Haodi

上海交通大学（Shanghai Jiao Tong University）学生，关注语音识别与端到端语音大模型。

主要使用 Python、NumPy 和 PyTorch（CPU），做可复现、可离线运行的语音工具：从识别后处理到语音理解与对话建模。

## 项目

| 项目 | 研究方向 | 已实现内容 |
|---|---|---|
| [hypofuse](https://github.com/hawaiicoco/hypofuse) | 语音识别后处理 | n-best 清单校验、ROVER 融合与混淆网络、n-gram 重打分与浅融合、置信度校准、CER/WER 切片错误分析 |
| [slotvox](https://github.com/hawaiicoco/slotvox) | 端到端语音理解 | 合成任务型对话工厂、联合意图-槽位模型、流式部分意图、语音 LLM 指令数据管线、回合级评测与报告 |

两个项目都包含命令行工具、可运行示例、契约/黄金测试和 CPU 模型测试，全部离线可复现。

## 当前关注

- 多假设对齐与融合策略的确定性评测，校准曲线的诚实解读。
- 语音-文本统一 token 序列上的联合建模、流式解码与背压语义。
- 合成数据上的可复现训练链路：种子、锁文件与逐提交检查。
