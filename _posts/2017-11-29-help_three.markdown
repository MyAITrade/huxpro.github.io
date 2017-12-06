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

## Three Bodies in Options World: Stock Movement, Volatility and Time

In the world of options, the price of options is affected by many factors,
but three of the most important factors are: underlying stock movement, volatility and time.

If you do not have a good understanding of these three factors, sometimes things that you can not figure out will happen.
For example, before publishing the stock earnings, you buy call or put options and the underlying stock performs very well but your options have dropped
and sometimes even two directions of the options are falling.
You buy call options that are approaching exercise date, and obviously the stock goes up as well,
but your call is still down. The reason is because you do not understand how those three factors affect the price of the option.

Next, we will explain them one by one.

## Time

In the those three factors, time is the most certain factor, as one day is reduced by one day. This is why novices buy options and veterans sell options.

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
but the price of this call option with strike 305 and expire at 12-08-2017 decrease 7.22%.
This is because even the increasing of the underlying stock can make this option's price increase 8.85%.
But the volatility and time factors make the price of this option decease 12.99% and 6.17%.
So from theory, this option's price will decease 7.22%.


-  [Download Software From App Store][1]

[1]: http://itunes.apple.com/us/app/id1228960496







































