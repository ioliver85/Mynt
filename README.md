<img src="https://raw.githubusercontent.com/sthewissen/Mynt/master/img/myntlogo.png" alt="Mynt" width="400" />

Finding this useful? Consider a donation!

[![Donate with Bitcoin](https://en.cryptobadges.io/badge/small/17AM4MFXuyC72HSur44foWBxSDGUPgZJwD)](https://en.cryptobadges.io/donate/17AM4MFXuyC72HSur44foWBxSDGUPgZJwD)

[![Donate with Ethereum](https://en.cryptobadges.io/badge/small/0xa6281eb66b919cfa471dc304d326588844fc1228)](https://en.cryptobadges.io/donate/0xa6281eb66b919cfa471dc304d326588844fc1228)

[![Donate with Litecoin](https://en.cryptobadges.io/badge/small/LZ2sL2ZSWLCoG2X39SzEaqXSYTDL7k9Wpz)](https://en.cryptobadges.io/donate/LZ2sL2ZSWLCoG2X39SzEaqXSYTDL7k9Wpz)

<a target="_blank" href="https://join.slack.com/t/mynt-bot/shared_invite/enQtMzI3ODgzNTE1OTg3LTMyMGQyNTUxNTg2ODEwMjBjMDE0YzI5NDU3ZGI0MzVjMjBhYzBlNWE5MTMwMzIyZTViNmM2YTUxYzZhYjcyMTA"><img src="https://upload.wikimedia.org/wikipedia/commons/b/b9/Slack_Technologies_Logo.svg" alt="Join us on Slack!" width="100" /></a>

# Mynt
Welcome to the Mynt cryptocurrency trade bot! This bot enables you to trade cryptocurrencies in an automated fashion and comes with a lot of different configuration options. It is a .NET based trade bot that runs at set intervals to find trades and monitor them for sell conditions.

### Features

- Comes with 25 built-in indicators
- Comes with 50 built-in strategies
- Create your own strategies using indicators and price data
- Runs on multiple platforms
   - Azure Functions
   - Console app
   - Windows service
- Supports multiple data storage engines
   - Azure Table Storage
   - SQL Server
   - SQLite
- Supports multiple exchanges
   - Binance
   - Bitfinex
   - Bittrex
   - Poloniex
- Ability to send notifications about your trades
   - Slack
   - Telegram
   - Discord
   
### History
   
A lot of the logic is based on the [Freqtrade] bot and was converted to C#. This software was initially created for educational purposes only. Don't risk money which you are afraid to lose. The bot runs at a pre-defined interval of 1 hour, since that matches the candle data it retrieves from the exchange. This bot was first mentioned in [one of my blogposts].

### Documentation

* [Installation (Azure)](https://github.com/sthewissen/Mynt/wiki/Installation-(Azure))
* [Installation (Local)](https://github.com/sthewissen/Mynt/wiki/Installation-(Local))
* [Configuration](https://github.com/sthewissen/Mynt/wiki/Configuration)
* [Indicators](https://github.com/sthewissen/Mynt/wiki/Indicators)
* [Strategies](https://github.com/sthewissen/Mynt/wiki/Strategies)
* [Notifications](https://github.com/sthewissen/Mynt/wiki/Notifications)
* [Backtesting](https://github.com/sthewissen/Mynt/wiki/Backtesting)

### Additional tools used

- ExchangeSharp - https://github.com/jjxtra/ExchangeSharp
- TA-Lib wrapper - https://www.nuget.org/packages/TA-Lib/

### Contributing

Feel like this bot is missing a feature? Pull requests are welcome! A few pointers for contributions:

- Create your PR against the develop branch, not master.
- If you are unsure, discuss the feature in an issue before a PR.

   [Freqtrade]: <https://github.com/gcarq/freqtrade>
   [Come find us on Slack!]: <https://join.slack.com/t/mynt-bot/shared_invite/enQtMzI3ODgzNTE1OTg3LTMyMGQyNTUxNTg2ODEwMjBjMDE0YzI5NDU3ZGI0MzVjMjBhYzBlNWE5MTMwMzIyZTViNmM2YTUxYzZhYjcyMTA>
   [one of my blogposts]: <https://www.thewissen.io/building-cryptocurrency-trading-bot-using-azure-part-1>
