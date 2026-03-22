# Crypto Fee Calculator

A practical guide and reference for understanding cryptocurrency trading fees across major exchanges.

## Why Trading Fees Matter

Most traders focus on picking the right coins while ignoring a factor that can consume 20-30% of their annual returns: trading fees. This repository provides transparent fee comparisons and calculations to help you minimize costs.

## Exchange Fee Comparison (March 2026)

| Exchange | Maker Fee | Taker Fee | Withdrawal (BTC) | Fee Token Discount |
|----------|-----------|-----------|-------------------|--------------------|
| Binance | 0.10% | 0.10% | 0.0000054 BTC | 25% (BNB) |
| Coinbase Advanced | 0.04% | 0.06% | Network fee | None |
| Kraken | 0.16% | 0.26% | 0.00002 BTC | None |
| OKX | 0.08% | 0.10% | 0.0001 BTC | None |
| Bybit | 0.10% | 0.10% | 0.0002 BTC | None |

*Fees shown are for the lowest (default) tier. Higher volume tiers reduce fees further.*

## Fee Impact Calculator

### Formula

```
Annual Fee Cost = Number of Trades x Average Trade Size x Fee Rate x 2
```

The x2 accounts for both entry and exit trades.

### Example Scenarios

**Casual Trader** (10 trades/month, $1,000 avg size, 0.1% fee):
- Monthly fees: $20
- Annual fees: $240
- On $10,000 portfolio: 2.4% annual drag

**Active Trader** (100 trades/month, $2,000 avg size, 0.1% fee):
- Monthly fees: $400
- Annual fees: $4,800
- On $50,000 portfolio: 9.6% annual drag

**Day Trader** (500 trades/month, $5,000 avg size, 0.1% fee):
- Monthly fees: $5,000
- Annual fees: $60,000
- On $100,000 portfolio: 60% annual drag

## How to Reduce Fees

1. **Use limit orders** — Maker fees are typically lower than taker fees
2. **Hold exchange tokens** — Binance offers 25% discount with BNB
3. **Use referral codes** — Get additional fee discounts at signup. Check [promocode.network/binance](https://promocode.network/binance) for current codes
4. **Increase volume tier** — Consolidate trading on one exchange to reach higher tiers
5. **Avoid unnecessary trades** — Each trade costs money, so trade with intention

## Understanding Fee Models

### Maker-Taker
You pay a lower fee when your order adds liquidity to the order book (limit orders that do not immediately fill) and a higher fee when your order removes liquidity (market orders or limit orders that fill immediately).

### Flat Fee
A single fee rate regardless of order type. Simpler but typically more expensive for high-frequency traders.

### Spread-Based
No explicit fee, but the exchange profits from the difference between buy and sell prices. Often the most expensive model, but it is hidden from the user.

## Important Notes

- Fees change frequently — always verify on the exchange website
- Withdrawal fees vary by cryptocurrency and network congestion
- Some exchanges offer zero-fee promotions for specific trading pairs
- Deposit fees are rare but exist on some platforms for certain payment methods

## Resources

- [Binance Fee Schedule](https://www.binance.com/en/fee/schedule)
- [Current Exchange Promo Codes](https://promocode.network)

## Contributing

Feel free to open issues or submit pull requests with updated fee data or additional exchanges.

## License

MIT License — use this data freely.
