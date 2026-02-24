# 测试模板

常用测试脚本模板，可直接复制后按需修改。

## 模板列表

| 文件 | 说明 |
|------|------|
| `api-test.py` | Pytest HTTP API 测试基础模板 |
| `contract-test.js` | Hardhat 合约测试基础模板 |
| `k6-load.js` | k6 负载测试脚本模板 |
| `locust-scenario.py` | Locust 压测场景模板 |

## 使用方式
```bash
# 复制模板到对应目录后修改
cp templates/api-test.py web3/api-testing/test_rpc.py
```

## 模板规范
- 每个模板包含必要的注释说明可配置项
- 保持最小依赖，避免引入不必要的库
