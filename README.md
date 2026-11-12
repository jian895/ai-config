# ai-config

供各个 AI / 自动化工具共享读取的业务配置。

## 文件

| 文件 | 内容 |
|---|---|
| `brand_restock_rules.json` | 品牌采购触发表：每个品牌的补货周期、到货天数、安全库存、临时补货、起订金额等规则 |

`brand_restock_rules.json` 自带字段说明（`fields`）和触发规则（`rules`），AI 读这一个文件即可理解并执行。

## 读取方式

仓库公开，直接访问即可，无需 Token：

```
https://raw.githubusercontent.com/jian895/ai-config/main/brand_restock_rules.json
```

注意：仓库公开，请勿在此存放敏感信息。

## 更新

直接在 GitHub 网页上编辑 JSON 并提交，或让 Claude 代为更新。历史版本可在 Commits 中查看和回退。
