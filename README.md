# QA Automation

Web3 与 API 自动化测试学习仓库。

## 目录结构

```
qa-automation/
├── web3/                    # Web3 相关自动化测试
│   ├── contract-testing/    # 智能合约单元与集成测试
│   └── api-testing/         # 区块链 JSON-RPC 接口测试
├── performance/             # 性能与压力测试
├── notes/                   # 学习笔记
└── templates/               # 常用测试模板
```

## 各模块说明

| 目录 | 用途 |
|------|------|
| [web3/](./web3/) | Hardhat/Foundry 合约测试 + RPC 接口测试 |
| [web3/contract-testing/](./web3/contract-testing/) | 智能合约测试用例 |
| [web3/api-testing/](./web3/api-testing/) | JSON-RPC / REST API 测试 |
| [performance/](./performance/) | k6 / Locust 负载测试 |
| [notes/](./notes/) | 踩坑记录与最佳实践 |
| [templates/](./templates/) | 可复用的测试脚本模板 |

## 技术栈

- **合约测试**: Hardhat, Foundry
- **API 测试**: Pytest, Jest, Ethers.js, Viem
- **性能测试**: k6, Locust
- **语言**: JavaScript / TypeScript, Python, Solidity
