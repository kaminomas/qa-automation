# 性能测试

针对 Web 服务、API 及区块链节点的性能与压力测试。

## 测试方向
- **负载测试** — 模拟正常业务峰值流量
- **压力测试** — 寻找系统极限与瓶颈
- **链上 TPS** — 测量区块链节点的交易吞吐量

## 主要工具
- [k6](https://k6.io) — JavaScript 脚本驱动的负载测试
- [Locust](https://locust.io) — Python 驱动的分布式压测
- [wrk](https://github.com/wg/wrk) — HTTP 基准测试

## 目录约定
```
performance/
├── k6/          # k6 脚本
├── locust/      # Locust 场景
└── reports/     # 测试报告（git ignore）
```
