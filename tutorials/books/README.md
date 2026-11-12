# Books：因子投资经典书核心笔记

这里把 `F:\0_交易日志\factor` 下四本因子投资书，提炼成 4 本 0 基础可读的 Jupyter Notebook。不是原书翻译，也不替代原书；每本只抓“核心框架 + 关键公式 + 一个可运行小例子 + 对一人量化的用法”。

| 笔记 | 对应原书 | 你会学到 |
|---|---|---|
| `01_七因子投资_核心笔记.ipynb` | Berkin & Swedroe, *Your Complete Guide to Factor-Based Investing* (2016) | 市场 beta、size、value、momentum、profitability/quality、term、carry；五条筛选标准；多因子分散化 |
| `02_SmartBeta与因子投资_核心笔记.ipynb` | Ghayur, Heaney & Platt, *Equity Smart Beta and Factor Investing for Practitioners* (2019) | smart beta 与因子投资、加权方案、因子规格、风险/收益分解、成本与容量、多因子组合 |
| `03_因子投资方法与实践_核心笔记.ipynb` | 石川、刘洋溢、连祥斌《因子投资：方法与实践》(2020) | 统一公式、排序法、Fama–MacBeth、Newey–West、A 股主流因子、异象与多重检验、实践 |
| `04_因子日历2024_核心笔记.ipynb` | 《因子日历2024》（量化投资与机器学习） | 因子日历怎么读、怎么做日/月监控、热力图/回撤/滚动指标；方法型解读 |
| `05_深度学习量化金融_核心笔记.ipynb` | Andrew Green, *Deep Learning in Quantitative Finance* (Wiley) | 前馈网络/训练/正则化/CNN/序列/生成模型；衍生品定价、PDE/BSDE、deep MC、波动率曲面、校准、XVA、合成数据、deep hedging |
| `06_强化学习金融_核心笔记.ipynb` | Yves Hilpisch, *Reinforcement Learning for Finance* (O'Reilly) | RL/DQL、MDP/Bellman、Q-learning/DQN、算法交易、动态对冲、动态资产配置、最优执行；模拟数据与金融 RL 陷阱 |
| `07_期货交易策略_核心笔记.ipynb` | Robert Carver, *Advanced Futures Trading Strategies* (Harriman House) | 期货合约/展期/波动率目标；30 个策略的家族（趋势/carry/突破/价值/偏度/均值回归/相对价值）；合约选择、执行、现金/复利、风险管理 |

## 说明

- `因子日历2024` 原 PDF 是纯图片扫描件，没有文字层；对应笔记写的是“因子日历的通用读法与监控方法”，**不逐页复刻、不编造具体页面数字**。
- 原书 PDF 未放入本仓库（版权原因）；笔记是学习提纲，遇到关键结论请回原书核对。
- 笔记中的代码数据均为合成/教学数据，收益、IC、Sharpe 只用于演示方法，不代表真实市场。
- 阅读顺序建议：`01 → 02 → 03 → 04`；如果只做期货/期权，可先读 01、04、07，再读 03 的方法论部分。`05`/`06` 是深度学习/强化学习方向，基础不够可以先跳过，读完主线 08/11 再回来。

## 怎么用

在 `tutorials/` 目录下启动 Jupyter：

```bash
cd tutorials
jupyter lab
```

打开 `books/` 下对应 notebook。
