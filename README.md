# Ally Invest

Ally Invest is an online brokerage platform offering commission-free self-directed trading of US stocks, ETFs, and options with no account minimums. The platform provides REST APIs for managing self-directed investment accounts, placing trades, accessing streaming real-time market data, retrieving account balances and holdings, managing watchlists, and querying market quotes and news.

## APIs

- **Accounts API** - Account balances, holdings, and transaction history
- **Orders API** - Place, preview, and manage equity and options orders (FIXML format)
- **Market Data API** - Quotes, option chains, news search, time-and-sales, top lists
- **Streaming API** - Real-time quote streaming via persistent HTTP connections
- **Watchlists API** - Create and manage symbol watchlists
- **Member API** - Authenticated member profile information

## Authentication

OAuth 1.0 with four credentials: Consumer Key, Consumer Secret, OAuth Token, and OAuth Token Secret. Credentials are obtained through the Ally Invest developer registration process for existing brokerage account holders.

## Pricing

API access is free for registered Ally Invest account holders. Brokerage transaction fees apply when orders are executed:

- US Stocks and ETFs: $0 commission
- Options: $0.50 per contract
- No account minimum for self-directed cash accounts

## Resources

- [Documentation](https://www.ally.com/api/invest/documentation/getting-started/)
- [Commissions and Fees](https://www.ally.com/invest/commissions-and-fees/)
- [Rate Limiting](https://www.ally.com/api/invest/documentation/rate-limiting/)
- [Attribution Guidelines](https://www.ally.com/api/invest/documentation/attribution-guidelines/)
- [API Agreement](https://www.ally.com/content/dam/pdf/invest/api-agreement.pdf)

## Maintainer

Kin Lane (kin@apievangelist.com)
