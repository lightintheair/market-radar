# Market Radar · 墨西哥跨境电商市场看板

可视化看板：https://lightintheair.github.io/market-radar/

## 数据结构

每日数据存储在 `data/YYYY-MM-DD.json`，`data/index.json` 维护所有已有日期列表。

## 数据字段说明

```json
{
  "date": "2026-03-31",
  "time": "17:00",
  "fx": {
    "mxn_cny": 0.3780,
    "mxn_usd": 0.0519
  },
  "platform": [
    { "title": "动态标题", "date": "2026-03-31", "source": "AliExpress", "level": "info" }
  ]
}
```
