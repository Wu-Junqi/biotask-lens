# BioTask Lens

**生物医药科研任务解析 · Biomedical research tasks, explained.**

[English](README.en.md) · [推荐题目](https://github.com/Wu-Junqi/biotask-lens/issues/new/choose) · [交流出题思路](https://github.com/Wu-Junqi/biotask-lens/discussions)

BioTask Lens 收集有代表性的科研任务，将科学问题、输入输出、关键判断、评分方法与参考作答连起来讲，帮助研究者理解别人怎样出题，并获得设计新任务的思路。

**网站公开地址正在准备，发布后会在此更新。** 目前可以通过本仓库推荐题目、交流想法或反馈内容问题。

![题库概览](assets/overview.png)

## 在这里可以学到什么

- **理解任务**：研究问题是什么，Agent得到什么材料，需要交付什么结果。
- **理解难点**：通过具体情境看清关键科学判断，以及它如何影响结果。
- **理解评价**：评分在比较什么，参考作答为什么得分或失分。
- **借鉴设计**：怎样准备数据、定义可检查的产物，并设计有意义的评价方法。

内容以单道任务的设计与分析为主线，参考Agent运行帮助说明具体表现。

## 三个案例

| 案例 | 科学问题 | 可以借鉴的设计 |
| --- | --- | --- |
| 钙通道随机模拟 | 通道数量改变时，振荡周期和稳定性如何变化？ | 同时检查平均行为、随机波动和守恒。 |
| 基因调控网络推断 | 谁调控谁，是激活还是抑制？ | 将边、方向、符号及网络结构分别评价。 |
| 生物传感器主动学习 | 怎样在有限实验轮次中提高目标响应与选择性？ | 同时评价发现质量和未测变体的预测。 |

当前整理了 **21道任务**，附 **15份参考运行记录**：11份已评分、4份超时未评分。参考配置为 Qwen3.8 Max + Codex CLI；具体条件与评分来源在各题中说明。

<details>
<summary>查看示意情境：把科学难点与评分联系起来</summary>

![任务难点与评价示例](assets/task-example.png)

</details>

<details>
<summary>查看出题启发：从一个案例迁移到新题目</summary>

![出题方法示例](assets/design-example.png)

</details>

## 欢迎参与

- **发现一道值得介绍的题目？** [推荐公开题目、论文或管线](https://github.com/Wu-Junqi/biotask-lens/issues/new?template=recommend-task.yml)。
- **在研究中遇到一个有价值的Agent任务？** [提供任务梗概](https://github.com/Wu-Junqi/biotask-lens/issues/new?template=task-idea.yml)。问题、输入和预期结果先讲清楚即可。
- **发现介绍或评分解释有问题？** [反馈内容问题](https://github.com/Wu-Junqi/biotask-lens/issues/new?template=content-feedback.yml)。
- **想讨论出题方法？** [到Discussions交流](https://github.com/Wu-Junqi/biotask-lens/discussions)。

任务线索可以逐步完善。采纳的贡献会注明来源与贡献者。具体参与方式见 [贡献说明](CONTRIBUTING.md)。

## 更新与关注

网站上线地址、代表案例和内容更新会在本仓库公布。可以通过 Star 收藏项目，并在 GitHub 的 Watch 设置中选择希望接收的通知。

维护者：[Wu-Junqi](https://github.com/Wu-Junqi)。题目导读保留原始来源，原题及研究成果归其原作者。
