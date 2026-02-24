# 智能合约测试

使用 Hardhat 或 Foundry 对智能合约进行单元测试和集成测试。

## 测试范围
- 合约函数的正常路径与边界条件
- 权限控制（onlyOwner、AccessControl 等）
- 事件（Event）触发验证
- Revert 与自定义错误断言
- Gas 消耗基准测试

## 快速开始（Hardhat）
```bash
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
npx hardhat test
```

## 快速开始（Foundry）
```bash
forge init
forge test -vvv
```
