# 承安 · 科研文献证据表

预置流程演示：示例输入与输出为预先编写的内容，不代表实时模型运行或医院正式交付。
适用岗位：IVD 企业 / 课题组 / 个人研究者
当前阶段：方法设计

## 输入

1. 公开论文 1：TrialMind《Accelerating clinical evidence synthesis with large language models》，2025-08-08。
2. 公开论文 2：BioCheck《Generating Biomedical Fact-Checking Reports with RL-Enhanced Agentic Search》，2026-08-24 预印本。
3. 公开论文 3：LABBench2《An Improved Benchmark for AI Systems Performing Biology Research》，2026-05-05 的 v2 版本。

## 处理步骤

1. 用同样字段读取三篇原文：任务、输入、输出、评估范围和人工复核位置。
2. 只摘录原文能够支持的功能与范围，不把不同任务上的评估数字放在一起排产品名次。
3. 把比较结果转成选用建议，并单独列出向 IVD、诊断或新研究场景迁移时需要补做的验证。

## 示例输出

1. TrialMind｜临床证据综合：围绕文献筛选、信息提取与人工审查组织流程；原文评估主要面向肿瘤治疗，不能直接证明对 IVD 或诊断证据同样有效。适合借鉴可回查的证据提取表。
2. BioCheck｜主张核查：通过 PubMed 检索生成带证据与分析的报告；原文承认训练数据较少、缺少证据不足样本且存在场景迁移限制。适合借鉴支持、反对、证据不足的核查结构。
3. LABBench2｜科研能力评估：提供近 1,900 项更贴近实际科研的任务，用于检验 AI 是否能完成具体工作。它是评估基准，不是自动完成研究的产品；适合借鉴任务级验收，而非用回答流畅度代表可用性。

## 人工复核

三条是基于公开原文的范围提取，不是承安运行三种系统后的测评。它们分别研究证据综合、事实核查与能力评估，不能直接比较胜负；所有来源均为外部研究成果。

## 依据

- TrialMind：Accelerating clinical evidence synthesis with large language models（2025-08-08）：https://www.nature.com/articles/s41746-025-01840-7
- BioCheck：Generating Biomedical Fact-Checking Reports with RL-Enhanced Agentic Search（预印本）（2026-08-24）：https://arxiv.org/html/2608.23811v1
- LABBench2：An Improved Benchmark for AI Systems Performing Biology Research（v2）（2026-05-05）：https://arxiv.org/abs/2604.09554v2

联系承安：微信 moshabei666 · bapeimarsk@gmail.com
