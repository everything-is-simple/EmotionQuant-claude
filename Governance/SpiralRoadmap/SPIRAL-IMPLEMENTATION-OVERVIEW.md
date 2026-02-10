# New System Spiral Implementation Overview

**Status**: active
**Cadence**: 7 days per spiral (default)
**Closure Rule**: `run + test + artifact + review + sync`

---

## Spiral Mainline

| Spiral | Primary Goal | Entry Deliverable | Exit Criteria |
|---|---|---|---|
| S00 | 新系统基线建模 | 架构边界 + 契约清单 | 评审通过 |
| S01 | 数据最小闭环 | 可运行数据链路 + 自动化测试 | 数据可复现 |
| S02 | 信号最小闭环 | MSS/IRS/PAS 最小输出 | 信号可追溯 |
| S03 | 集成验证闭环 | Gate 决策 + 基线报告 | 门禁稳定 |
| S04 | 回测闭环 | 回测报告 + 指标摘要 | 指标可重现 |
| S05 | 交易模拟闭环 | 订单/持仓/风控日志 | 日内可重放 |
| S06 | 展示分析闭环 | GUI + 日报导出 | 端到端可演示 |
| S07 | 稳定化闭环 | 一致性报告 + 债务清单 | 收敛达标 |

---

## Current Spiral

- Spiral: `S00`
- Goal: 新系统边界与契约固化
- In Scope: 数据契约、模块接口、验收门禁
- Out Scope: 实盘交易接入

## Closure Checklist (Required)

- [ ] run
- [ ] test
- [ ] artifact
- [ ] review
- [ ] sync
