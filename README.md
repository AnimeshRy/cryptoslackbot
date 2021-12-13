# Cryptocurrency Slack Bot

Used to automate Slack notifications of cryptocurrency prices.

### Python Modules
```
requests
slackclient
```
### Cryptocurrency API

I've used the API and endpoint below:
```
https://api.coingecko.com/api/v3/simple/price
```

with the parameters below:

```
?ids=bitcoin&vs_currencies=usd
```

### Cron setup

Configure a Cron job for the script wrapper to run every 10 minutes.

```
*/10 * * * * /path/to/cryptocurrency_slack_bot/run_bot.sh
