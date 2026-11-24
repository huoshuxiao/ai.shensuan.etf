# AGENTS.md

通过验证各种指数的组合找到趋势规律，在低点买入在高点卖出，每次给出1到2只ETF的交易建议，给出买入或卖出价格。

## 目标

追求长期收益，接受短期波动

## 需求

- 以敏捷的方式管理项目，将进度输出到 `看板.md` 
- 先出设计文档到 `docs` 目录下，评审后再根据设计实现代码逻辑
- 程序分阶段实现，缺乏金融领域专业知识，人工审查逻辑有困难，每个阶段都要有自动化验收程序，出markdown的验收报告
- 程序自动化，智能化
- 用统计学、数学、金融学、经济学、政治经济学等多学科，多维分析给出投资建议，买入或卖出或空仓或持有等

### 数据

- 数据质量，用程序进行标准化验收，不通过人工人眼验证，连续性，一致性，遵循最佳实践

### 前端展示

- 以适合的图表展示指数组合的买卖点
- 根据买卖建议计算投资胜率

### 目录

```text
 config
 data
 docs
 logs
 reports
 src/main/python/com/sun/shensuan/etf/
 src/test/python/com/sun/shensuan/etf/
```

## 机器装机 (可选)

- 机器配置，ubuntu 20.04，16G内存，2G显存，i7-6700HQ
- 本地大模型qwen2.5:7b。不开思考
- ollama
- docker
- miniconda3

## 参照

- [沪深300VS十年国债](https://zhuanlan.zhihu.com/p/597095545)
- [AI 多 Agent 量化投资系统](https://github.com/2464404039/a-share-agents)
- [AI Hedge Fund API (v2.0)](https://github.com/tbdavid2019/ai-hedge-fund-API)
- [Alpha Desk](https://github.com/JingHao-Leon/dsh-alpha-desk)
- [TradingAgents](https://github.com/TauricResearch/TradingAgents)
- [TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN/tree/v3.0)
- [TradingAgents-Astock](https://github.com/simonlin1212/TradingAgents-astock)
- [aiagents-stock](https://github.com/oficcejo/aiagents-stock)
- [AI Hedge Fund](https://github.com/virattt/ai-hedge-fund/tree/main)
- [海龟投资网 — 投资分析数据平台](https://www.haiguitouzi.com/index.html)
