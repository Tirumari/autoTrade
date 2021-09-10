# Trading Bot

## trading in:
* microfutures available in indexes like NASDAQ/SMP500/etc
  * contracts on future prices of stocks
    * contracts == 'derivative of stock'
    * guarantees you buying a certain amount of stock at a certain amount of time
* options
  * potentially harder to trade via algorithms

## the algo needs to:
* look at the month candles on the ticker
    * then week
    * then day
* **IF** direction for all three is 'up', then using the;
* exponential moving average,
* **IF** price is below EMA but still moving up, **THEN** purchase

## ideal setup:
* ninjaTrader
* Mondays and Fridays
* bond futures as well as micro-futures
* trade at London Open
    * job reports come out on American time
* focus on first 30 minutes

## to look up:
* 'shorting' the market
* how to use user accounts to trade with
* multiple account to log into bot
* trading strategy parameters
    * stop loss and profit
* S & P
* Margin calls
* red panda academy
* iex API
