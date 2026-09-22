# Crypto Monitor Remote Config

Crypto Monitor 的公开邀请链接配置仓库。

## 更新邀请链接

编辑 [`docs/referrals.json`](docs/referrals.json)：

1. 把对应交易所的 `referralURL` 填为完整邀请链接。
2. 把 `enabled` 改为 `true` 后，该交易所才会在 APP 中显示。
3. `sort` 数值越小，显示顺序越靠前。
4. 更新 `updatedAt`，然后提交修改。

示例：

```json
{
  "id": "binance",
  "enabled": true,
  "sort": 10,
  "referralURL": "https://www.binance.com/your-referral-link"
}
```

不要在此仓库保存 API Key、Secret Key、Passphrase 或任何其他敏感信息。

## 在线配置地址

<https://xulijian1009.github.io/crypto-monitor-config/referrals.json>
