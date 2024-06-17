# 胡海川
<img src="./image.png" alt="Profile Picture" style="width:100px; float:right; margin-top: -50px;" />

- 电话: (+86) 19952751509
- 邮箱: huhaichuan2024@gmail.com

## 其他信息

- 性别：男
- 年龄：24

## 教育背景

### 南京大学，软件工程，本科
*2018.9 - 2022.6*
- **GPA**：87/100 25%

### 南京大学，软件工程，硕士
*2022.9 - 2024.6*
- **GPA**：85/100

## 科研经历

### 翻译机测试，负责实验部分
*2022.9 - 2023.3*
- Machine Translation Testing via Syntactic Tree Pruning, TOSEM, 2024
- [doi: https://arxiv.org/abs/2401.00751](https://arxiv.org/abs/2401.00751)
- 采用差分测试的手段检测翻译引擎(Google Bing等)的翻译结果是否存在语法语义的偏差。具体实现上，先利用Stanford CoreNLP分析原句和翻译句的语法结构，然后对句子的语法树进行剪枝以保留句子的主干部分，最后通过计算距离来评估原句和翻译句是否一致。在实验过程中，我对语法树剪枝算法进行优化，以保证在语义不变的情况下简化句子的语法结构。除此以外，我还负责数据统计与分析工作。

### 补丁验证，负责实验并撰稿，第二作者
*2023.6 - 2024.6*
- On the Effectiveness of Code Representation in Automated Patch Correctness Assessment, 已投TOSEM 2024
- 是一篇Empirical Study工作，评估了4类代码特征(Feature Sequence Tree Graph)以及11类模型在补丁验证任务上的效果，并通过消融实验来测试不同特征组合对补丁验证结果的影响。我在实验设计前调研了10篇左右近期相关论文，统计Benchmark并整理数据集。然后对各类代码特征的提取工具进行调研，在此基础上对相关论文进行复现。在模型选择上，我调研了近年来影响广泛的模型，从中选取了先前工作使用较多的模型，并对模型的结构进行改进以支持更大规模的输入。在实验后期，我对实验结果进行分析评估以比较不同模型和特征间的优劣，并选取了性能较好的模型和特征来进行消融实验。

### Copilot & Incident Analytics
*2024.4 - 2024.6*
- Microsoft Suzhou
- 来源于我在微软团队实习的项目。在项目中我基于GPT-4, GPT-4o等先进大语言模型构建了Incident咨询系统，并基于Copilot构建团队内部的知识问答系统。其中，Incident咨询系统接收目标Incident，通过Embedding来比较该Incident和历史Incident的相似性，获取最相关的Incident作为参考。除此以外，Incident咨询系统还会拉取目标Incident下相关的Discussion和Resource Change等信息，通过综合分析给出Incident的解决方案。在Copilot项目中，我使用内部文档库作为语料库对Copilot进行微调，为Copilot提供特定领域的知识。在工程实现上，我实现了文档库和Copilot数据集之间的同步更新机制，以保证Copilot能了解到最新的团队情况。

## 实习经历

### 阿里云，杭州
*2021.6 - 2021.8*
- **职责**：负责管控MySQL集群的机器，使用Go语言编写脚本，定期检查集群状态并修复集群故障。

### 阿里国际，杭州
*2023.6 - 2023.9*
- **职责**：设计并执行了MySQL数据库迁移，迁移了约2亿数据记录，保证数据迁移过程中的一致性和完整性。

## 其他

### 语言能力
- **CET4**：587
- **CET6**：588

### 荣誉奖项
- 2019 人民奖学金二等
- 2020 花旗杯金融大赛三等奖
- 2023 Vivo Hackathon 一等奖
