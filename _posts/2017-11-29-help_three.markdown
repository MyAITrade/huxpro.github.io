---
layout:       help
title:        "Three Bodies in Option World"
subtitle:     "Stock Movement, Volatility and Time"
date:         2017-11-29 12:00:00
catalog:      true
multilingual: false
tags:
    - Help
---

## Three Factors in Options World: Stock Price Change, Volatility and Time

In the world of options, the price of options is affected by many factors,
but three of the most important factors are: underlying stock price movement, volatility and time.

If you do not have a good understanding of these three factors, sometimes things that you can not figure out will happen.
For example, before publishing the stock earnings, you buy call or put options and the underlying stock performs very well but your options have dropped
and sometimes even both call option price and put option price are falling.
You buy call options that are approaching exercise date, and obviously the stock price goes up as well,
but your call option price is still falling. The reason is according to that you do not understand how those three factors affect option price.

Next, we will explain them one by one.

## Time

In the those three factors, time is the most certain factor, as time deceases one by one. This is why novices buy options and veterans sell options.

<img src="{{ site.baseurl }}/img/three/three_time.jpg" alt="Time lost" class="inline"/>

From this figure, you can find that the time value of the option will decease fast as it approaches expire date.

<img src="{{ site.baseurl }}/img/three/three_tsla.png" alt="TSLA" class="inline"/>

This figure will give you a estimation of how those three factors influence option price.
* Delta Impact: shows you how the related stock price change influence the option price change percentage
* Vega Impact: shows you how the implied volatility change influence the option price change percentage
* Theta Impact: shows you how the time decease one day influence the option price change percentage

Theory option price change percentage is the value calculated using the BS model and market change is the real option price change percentage by the market.
There are some gap between those two values.

From this figure you can find that the price of underlying stock TSLA increases 0.43%,
but the price of this call option with strike price 305 and expire on 12-08-2017 decreases 7.22%.
This is because even the increasing of the underlying stock can make this option's price increases 8.85%.
But the volatility and time factors make the price of this option decease 12.99% and 6.17%.
So from theory, this option's price will decease 7.22%.

## Stock Price Change

For option price, the rising of related stock price will make call option price rise and put option price fall and the falling of
related stock price will make the put option price rise and call option price fall.

For in the money options, most of the influence of the option price comes from related stock price movement.
So if you just use stock price change factor to make your trade, please choose the in the money options.

## Implied Volatility

Implied Volatility stands for the market expected stock price movement on option expiration.

If you come across options that yield expensive premiums due to high implied volatility,
understand that there is a reason for this. Check the news to see what caused such high company expectations and high demand for the options.
It is not uncommon to see implied volatility plateau ahead of earnings announcements, merger and acquisition rumors, product approvals and other news events.
Because this is when a lot of price movement takes place, the demand to participate in such events will drive option prices higher.
Keep in mind that after the market anticipated event occurs, implied volatility will collapse and revert back to its mean.

When you see options trading with high implied volatility levels, consider selling strategies.
As option premiums become relatively expensive, they are less attractive to purchase and more desirable to sell.
Such strategies include covered calls, naked puts, short straddles and credit spreads.
By contrast, there will be times when you discover relatively cheap options, such as when implied volatility is trading at or near relative to historical lows.
Many option investors use this opportunity to purchase long-dated options and look to hold them through a forecasted volatility increase.

When you discover options that are trading with low implied volatility levels, consider buying strategies.
With relatively cheap time premiums, options are more attractive to purchase and less desirable to sell.
Such strategies include buying calls, puts, long straddles and debit spreads.

-  [Download Software From App Store][1]

[1]: http://itunes.apple.com/us/app/id1228960496







































