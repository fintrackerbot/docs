# ❓ Frequently Asked Questions

Get quick answers to the most common questions about Fin Tracker Bot.

## General Questions

### What is Fin Tracker Bot?

Fin Tracker Bot is an intelligent Telegram bot that provides comprehensive analysis of Ethereum smart contracts and tokens. It combines real-time market data, AI-powered analysis, and security assessment to help users make informed decisions.

### What blockchains does the bot support?

Currently, Fin Tracker Bot supports **Ethereum mainnet** tokens and smart contracts. The bot is optimized for ERC-20 tokens but can analyze other types of Ethereum contracts as well.

### How do I start using the bot?

Simply search for the bot on Telegram, start a conversation, and send any Ethereum contract address. The bot will immediately provide detailed analysis.

## Feature Questions

### How accurate is the AI analysis?

The AI analysis uses Claude Sonnet 3.7 and combines contract data with real-time market information. While highly sophisticated, it should be used as **one factor** in your research, not the only factor. Always do your own research.

### How often is the data updated?

- **Price/Trading Data**: Updated in real-time from DexScreener
- **Contract Data**: Refreshed with each new query
- **AI Analysis**: Generated fresh for comprehensive insights

### Can I analyze any contract address?

Yes, you can analyze any valid Ethereum contract address (42 characters starting with 0x). The bot works best with ERC-20 tokens but can handle other contract types.

### What makes a token "safe" vs "risky"?

Key safety factors include:

- ✅ Contract verified on Etherscan
- ✅ Ownership renounced or trusted team
- ✅ Reasonable tax rates (<10%)
- ✅ Sufficient liquidity (>$10k)
- ✅ Active social presence
- ✅ No major red flags from AI analysis

### Why don't some tokens show trading data?

Trading data comes from DexScreener. If a token isn't actively traded on supported DEXs, or is very new, trading data may be limited or unavailable.

### Can I get price alerts or notifications?

Currently, the bot doesn't support price alerts, but you can use the refresh button to check updated prices anytime without re-typing the contract address.

## Usage Questions

### How do I refresh data for a token?

Click the **🔄 Refresh Data** button on any analysis result, or send the contract address again to get the latest updated information.

### What's the difference between analysis types?

- **Trading-Focused**: Market dynamics, entry/exit points, position sizing
- **Security Audit**: Contract security, admin controls, vulnerabilities
- **General Analysis**: Balanced overview combining all aspects

### Can I analyze the same token multiple times?

Yes! You can always refresh data or re-run AI analysis to get the most current insights.

## Troubleshooting

### Bot says "invalid address" - what's wrong?

Ensure you're sending a valid Ethereum contract address:

- Must be 42 characters long (including 0x prefix)
- Contains only hexadecimal characters (0-9, a-f)
- Copy from reliable sources like Etherscan
- Check for extra spaces or characters

### AI analysis failed or taking too long

**Solutions**:

- Wait 30 seconds and try again
- Ensure basic token info loads first
- Try again during off-peak hours
- Check if the contract is verified (unverified contracts have limited data)

### Trading data shows "No data available"

This means:

- Token isn't actively traded on supported DEXs
- Very new token without sufficient trading history
- Token may be on unsupported exchanges
- This is normal for many contracts

### How should I use the analysis results?

- Use as **one factor** in your research
- Always do additional due diligence
- Never invest based solely on bot analysis
- Start with small amounts when testing new strategies
- Understand that all cryptocurrency investments carry risk

## Advanced Features

### What is "Clog Behavior" analysis?

Clog Behavior analysis examines advanced trading mechanics including:

- Maximum transaction limits
- Anti-whale measures
- Automatic swap-back settings
- Tax distribution mechanisms
  This helps understand how the contract manages large transactions.

---

## Still Have Questions?

If you can't find the answer you're looking for:

1. **Check our troubleshooting guide** for technical issues
2. **Try the search function** in this documentation
3. **Contact our support team** with specific details
4. **Join our community** for peer assistance

Remember: Fin Tracker Bot is a research tool. Always do your own research and never invest more than you can afford to lose! 🛡️
