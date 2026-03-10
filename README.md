# A股量化分析工具

A股量化数据分析工具集，包含两个核心模块：

## 模块

### 1. AkShare 数据接口 (akshare-stock)

基于 AkShare 库的 A 股量化数据分析工具。

**功能：**
- 实时行情查询
- 历史 K 线数据（日/周/月）
- 财务数据分析
- 板块/行业分析
- 资金流向监控
- 龙虎榜数据
- 新股/IPO 信息
- 融资融券数据

**安装：**
```bash
pip install akshare
```

**使用：**
详见 `akshare-stock/SKILL.md`

### 2. 技术分析工具 (stock-technical-analysis)

股票技术分析 API 工具。

**功能：**
- K 线形态识别
- 均线分析（MA, EMA）
- 技术指标（RSI, MACD, Bollinger Bands）
- 趋势判断

**费用：** 每次调用 0.001 USDT

**使用：**
详见 `stock-technical-analysis/SKILL.md`

## 快速开始

1. 克隆仓库：
```bash
git clone https://github.com/bearofcode/a-stock-analyzer.git
cd a-stock-analyzer
```

2. 安装依赖：
```bash
pip install akshare
```

3. 查看文档：
```bash
cat akshare-stock/SKILL.md
```

## 注意事项

- 数据仅供学术研究，不构成投资建议
- 接口可能因目标网站变动而失效
- 建议添加异常处理和重试机制

## License

MIT
