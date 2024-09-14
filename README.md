# FINC3017 Investments and Portfolio Management Assignment 1

**Due: 11:59PM, 20 September 2024**

**Objective**
The objective of Assignment 1 is to gain a deeper understanding of modern portfolio theory and the CAPM. The assignment consists of two parts. In the first part, you need to apply the portfolio theory to ten US stocks. In the second part, you need to evaluate if the returns of the ten stocks can be explained by the CAPM.

**Part 1**
You are hired as an investment consultant by a hedge fund that focuses on the following ten US stocks: Exxon Mobile (ticker XOM), PepsiCo (ticker PEP), 3M (ticker MMM), Walter Disney (ticker DIS), McDonald’s (ticker MCD), Nike (ticker NKE), Adobe (ticker ADBE), Starbucks (ticker SBUX), Ralph Lauren (ticker RL), and Costco (ticker COST). Your task is to submit a professional report for your manager to address the following investment issues. Your analysis is based on implementing the Markowitz approach and monthly returns of the ten stocks over the sample period from January 2000 to December 2023, as contained in the Excel file ‘Assignment1_data’.

1. Discuss the risk return characteristics of the ten stocks. Generate a table that reports summary statistics of stock returns including mean, standard deviation, skewness, minimum, and maximum. You also need to prepare a cumulative return plot.
2. Plot and describe the investment opportunity set and efficient frontier of the ten stocks without and with the risk-free asset. Moreover, highlight the ten stocks on the same mean variance diagram. Generate a table that reports the weight of each stock in the tangency portfolio as well as the expected return and standard deviation of the tangency portfolio. Assume the risk-free rate is 2% per annum.
3. There are two individual investors, John and Alice who are interested in investing in your fund. Both investors’ utility is represented by: $U = E(r)-\frac{1}{2}\sigma^2$. John has a risk aversion coefficient ($\gamma$) of 4 and $1 million USD to invest, and Amy has a risk aversion coefficient of 12 and $2 million USD to invest. Prepare a table that shows the portfolio allocation (in dollar amount) to the ten stocks and risk-free asset you would recommend to the two investors to maximise their utilities, as well as the expected returns, standard deviations, and Sharpe ratios of these recommended portfolios. Also, highlight the recommended portfolios for both investors on the same mean variance diagram used in question 2.

**Additional Information**
• Express returns, standard deviations, and Sharpe ratios in annual term.
• Set the initial weights to equal weights when conducting each optimization with Solver.
• The data provided is adapted from real stock market data. You should only use the data provided to you in completing this report (you are not required to gather any additional data). Further, ignore any potential transaction costs, fees, and taxes in determining your responses.

**Part 2**
Using the above ten stocks as test assets, evaluate the ability of the CAPM to explain the variations in returns among these stocks.
1. Plot average excess returns of the 10 stocks against their CAPM betas and discuss your findings.
2. Use the Fama-MacBeth regression approach to evaluate the performance of the CAPM and discuss your findings.
3. Discuss the current literature on the empirical performance of the CAPM (word limit: 300).

**Additional Information**
• Estimate the betas using full sample information.
• For Fama-MacBeth regressions, report both coefficient estimates and t-stats in a table.
• Use monthly returns of t-bills, provided in Assignment1_data’, as a proxy for risk-free rate.
• Attach the references at the end of your report.

**Marking**
Marks will be awarded for correct quantitative analysis, the clarity of your discussion, and editorial aspects of your report (the report, tables, and figures should be professionally formatted). In preparing your report, it is recommended that you label your answer to each question clearly.

Reports will be checked by Turnitin and actions will be taken if academic dishonesty or plagiarism is suspected.

**Submission**
You need to prepare two files for submission in Canvas.
1. a written report that contains your results and discussions. Submit your report as a pdf document via the ‘Assignment 1’ link in Canvas.
2. your workings. Submit your workings as an Excel spreadsheet (or code if using an alternative computing program) via ‘Assignment 1 – Supporting workings’ link in Canvas. Your workings will not be directly graded.
3. you will lose 3 marks for wrong submissions.

# FINC3017 投资与投资组合管理作业 1

**截止日期：2024 年 9 月 20 日晚上 11:59**

**目标**
作业 1 的目标是深入理解现代投资组合理论和资本资产定价模型（CAPM）。该作业由两部分组成。在第一部分中，你需要将投资组合理论应用于十只美国股票。在第二部分中，你需要评估这十只股票的收益是否可以用 CAPM 来解释。

**第一部分**
你被一家对冲基金聘为投资顾问，该基金关注以下十只美国股票：埃克森美孚（股票代码 XOM）、百事可乐（股票代码 PEP）、3M（股票代码 MMM）、华特迪士尼（股票代码 DIS）、麦当劳（股票代码 MCD）、耐克（股票代码 NKE）、奥多比（股票代码 ADBE）、星巴克（股票代码 SBUX）、拉夫·劳伦（股票代码 RL）和好市多（股票代码 COST）。你的任务是向你的经理提交一份专业报告，以解决以下投资问题。你的分析基于实施马科维茨方法以及 2000 年 1 月至 2023 年 12 月样本期间这十只股票的月度收益，数据包含在 Excel 文件“Assignment1_data”中。

1. 讨论这十只股票的风险收益特征。生成一个表格，报告股票收益的汇总统计信息，包括均值、标准差、偏度、最小值和最大值。你还需要准备一个累积收益图。
2. 绘制并描述这十只股票在无风险资产和有风险资产情况下的投资机会集和有效前沿。此外，在同一均值方差图上突出显示这十只股票。生成一个表格，报告切线投资组合中每只股票的权重以及切线投资组合的预期收益和标准差。假设无风险利率为每年 2%。
3. 有两个个人投资者，约翰和爱丽丝，他们对投资你的基金感兴趣。两个投资者的效用函数为：$U = E(r)-\frac{1}{2}\sigma^2$。约翰的风险厌恶系数（$\gamma$）为 4，有 100 万美元可供投资，而爱丽丝的风险厌恶系数为 12，有 200 万美元可供投资。准备一个表格，显示你向这两个投资者推荐的对十只股票和无风险资产的投资组合分配（以美元金额表示），以及这些推荐投资组合的预期收益、标准差和夏普比率。同时，在问题 2 中使用的同一均值方差图上突出显示这两个投资者的推荐投资组合。

**附加信息**
• 以年为单位表示收益、标准差和夏普比率。
• 在使用 Solver 进行每次优化时，将初始权重设置为等权重。
• 提供的数据是根据实际股票市场数据改编的。在完成本报告时，你只能使用提供给你的数据（无需收集任何其他数据）。此外，在确定你的回答时，忽略任何潜在的交易成本、费用和税收。

**第二部分**
使用上述十只股票作为测试资产，评估 CAPM 解释这些股票收益变化的能力。
1. 绘制这十只股票的平均超额收益与其 CAPM 贝塔系数的关系图，并讨论你的发现。
2. 使用法玛 - 麦克贝斯回归方法评估 CAPM 的性能，并讨论你的发现。
3. 讨论关于 CAPM 实证性能的当前文献（字数限制：300）。

**附加信息**
• 使用全样本信息估计贝塔系数。
• 对于法玛 - 麦克贝斯回归，在表格中报告系数估计值和 t 统计量。
• 使用“Assignment1_data”中提供的短期国库券月度收益作为无风险利率的代理。
• 在报告末尾附上参考文献。

**评分**
评分将根据正确的定量分析、讨论的清晰度以及报告的编辑方面（报告、表格和图表应专业格式化）进行。在准备报告时，建议你清楚地标注对每个问题的回答。

报告将由 Turnitin 检查，如果怀疑有学术不端或剽窃行为，将采取行动。

**提交**
你需要在 Canvas 上准备两个文件进行提交。
1. 一份包含你的结果和讨论的书面报告。通过 Canvas 上的“作业 1”链接以 PDF 文档形式提交你的报告。
2. 你的工作文件。通过 Canvas 上的“作业 1 - 支持性工作文件”链接以 Excel 电子表格（如果使用其他计算程序，则为代码）形式提交你的工作文件。你的工作文件将不会直接评分。
3. 提交错误将扣 3 分。
# FINC3017 Assignment 1

# CS Tutor | 计算机编程辅导 | Code Help | Programming Help

# WeChat: cstutorcs

# Email: tutorcs@163.com

# QQ: 749389476

# 非中介, 直接联系程序员本人
