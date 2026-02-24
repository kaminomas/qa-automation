# Web3 自动化测试

Web3 相关的自动化测试实践，涵盖智能合约测试和链上 API 测试。

## 子目录

### contract-testing/
智能合约单元测试与集成测试，主要工具：
- Hardhat / Foundry — 合约测试框架
- Ethers.js / Viem — 合约交互

### api-testing/
区块链节点 RPC 接口测试，主要工具：
- Pytest / Jest — 测试框架
- 覆盖 eth_call、eth_getLogs、eth_sendRawTransaction 等核心 RPC 方法

## 参考
- [Hardhat 文档](https://hardhat.org/docs)
- [Foundry Book](https://book.getfoundry.sh)
