---
title: Housing market cycle indicator
date: 2021-08-01
description: Model to predict real-estate cycles. Showing data on the evolution of housing prices (inflation-adjusted), crossed with the demographic curve (rainbow).
tag: Price, Demography
author: Galetaire
---

import Image from 'next/image'

# Housing market cycle indicator: the rainbow model, Catalonia

<Image
  src="/images/rainbow.png"
  alt="Reload chart"
  width={}
  height={}
  priority
  className="next-image"
/>

- **Red** = strong overprice; **Orange** = slightly overprice; **Yellow** = neutral; **Green** = slightly underprice; **Blue** = strong underprice.

# Interpretation and observations

The rainbow curve describes a demographic channel in order to evaluate bull or bear market conditions in the price of housing. The equation, derived from the demographic curve (quadratic polynomial), has been price-adjusted. This is an experimental indicator, open to improvements and corrections.

Equations chart:

<Image
  src="/images/rainbowsource.png"
  alt="Reload chart"
  priority
  className="next-image"
/>

Full dataset chart, from 1964 to 2060:

<Image
  src="/images/rainbowmax.png"
  alt="Reload chart"
  width={}
  height={}
  priority
  className="next-image"
/>
