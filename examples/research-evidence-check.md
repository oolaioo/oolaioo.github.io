# 承安 · 科研主张证据核查

预置流程演示：示例输入与输出为预先编写的内容，不代表实时模型运行或医院正式交付。
适用岗位：IVD 研发 / 科研团队 / 个人研究者
当前阶段：方法设计

## 输入

1. 待核查问题：BioCheck 在 SciFact 上的评估结果，能否推广到全部医学主张？
2. 公开材料：2026-08-24 预印本《Generating Biomedical Fact-Checking Reports with RL-Enhanced Agentic Search》。
3. 核查范围：原论文的评估任务、训练数据和局限讨论；不把摘要中的性能变化当作通用医学可靠性证明。

## 处理步骤

1. 把问题拆成两层：论文测量了什么，以及“全部医学主张”比原评估范围多出了哪些场景。
2. 对照原文摘要、实验与局限部分，提取 SciFact、HealthFC、训练样本及证据不足情形的说明。
3. 将提取结果写成已知事实、局限与证据不足三栏，保留论文链接供逐条回查。

## 示例输出

1. 已知事实：论文研究的是借助 PubMed 检索生成结构化事实核查报告，并在 SciFact、HealthFC 等任务上评估；原文局限讨论称 SciFact 训练集约有 500 条标注样本。
2. 局限：原文指出训练数据缺少常见的 Not Enough Info 情形；从 PubMed 摘要中的科研主张转向一般健康信息存在分布差异，HealthFC 上的改善也较有限。
3. 核查结论：不能据此推广到全部医学主张。对未测试的领域、人群、语言和证据不足场景，当前来源不能提供普遍有效性证明；本例没有独立重跑论文评估。

## 人工复核

这是对公开论文范围与局限的人工来源核查演示。可回查原文摘要、实验及局限部分；未调用 BioCheck 模型，不将该外部工具或论文成果归为承安自有成果。

## 依据

- BioCheck Agent：Generating Biomedical Fact-Checking Reports with RL-Enhanced Agentic Search（预印本）（2026-08-24）：https://arxiv.org/html/2608.23811v1

联系承安：微信 moshabei666 · bapeimarsk@gmail.com
