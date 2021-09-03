---
title: Complete housing model of Catalonia
date: 2021-08-01
description: Data on the evolution of the housing market. The model consists of six main variables (price, inflation, home sales, credit, demographics and employment).
tag: Price, Volume, Credit, Labor, Demography
author: Galetaire
---

import Image from 'next/image'

# Complete housing model of Catalonia

<Image
  src="/images/model.png"
  alt="Photo"
  width={1294}
  height={595}
  priority
  className="next-image"
/>

- **Inflation**: average inflation rate for any given year, e.g. 4% in 2007.
- **Unemployment**: average unemployment rate for any given year, e.g. 15% in 1998.
- **Population**: annual percentage change of the total population, e.g. -1% in 2017 (compared to 2016).
- **Price (-i), minus inflation**: annual percentage change in the inflation-adjusted price, e.g. +3% in 1990 (relative to 1989).
- **Price (+i), plus inflation**: annual percentage change in the nominal price, e.g. +9% in 1990 (relative to 1989).
- **Credit**: annual percentage change in the number of mortgages approved, e.g. +24% in 2015 (compared with 2014).
- **Home sales**: annual percentage change in the number of home sales, e.g. -15% in 2011 (compared with 2010).

# Interpretation and observations

The model groups together the six variables that I consider essential in order to understand the housing market: price, volume, inflation, credit, demographics and employment. All the variables are represented in percentages. A couple of interpretations from the chart:

- **Observation A**: We can see how inflation has been decreasing. In 1989 it was above 5%, and in 2020 it was negative (the red area is below 0%).
- **Observation B**: We can see how the population has been decreasing on a yearly basis since 2010. On the other hand, between 2002 and 2006, the population increased a lot, due to an inmigration wave.
- **Observation C**: We can observe that when unemployment increases, the evolution of the price of housing tends to be negative, both taking into account inflation (+i) and not (-i).
- **Observation D**: It is interesting to note how between 1986 and 1990 the rise in house prices was dominated by high inflation. We know this because the price bar is completely black, price (+i) is overlapping completely the price (-i).
- **Observation E**: The orange bar, price (-i), informs us of the de/revaluation of housing. For example, in 2013, there was a strong devaluation, and in 2017 a strong revaluation.
