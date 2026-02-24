# 区块链 API 测试

针对以太坊兼容链 JSON-RPC 接口的自动化测试。

## 覆盖的 RPC 方法
- `eth_blockNumber` / `eth_getBlockByNumber`
- `eth_call` — 只读合约调用
- `eth_getLogs` — 事件日志查询
- `eth_sendRawTransaction` — 交易广播
- `eth_getTransactionReceipt` — 回执查询

## 工具
- **Pytest** + `requests` — HTTP RPC 测试
- **Jest** + `ethers.js` / `viem` — JS 生态测试

## 快速开始
```bash
pip install pytest requests
pytest test_rpc.py -v
```
