---
title: Complete housing model, Catalonia
date: 2021-08-01
description: Dades sobre l'evolució del mercat d'habitatge. El model consta de sis variables principals (preu, inflació, compravendes, crèdit, demografia i ocupació).
tag: Price, Volume, Credit, Labor, Demography
author: Galetaire
---

import Image from 'next/image'

# Complete housing model, Catalonia

<Image
  src="/images/model.png"
  alt="Photo"
  width={1294}
  height={612}
  priority
  className="next-image"
/>
<center>_Exemple del model general de l'habitatge a Catalunya._</center>

- **Inflació**: percentatge d'inflació mitjana de l'any en concret, p.ex. 4% l'any 2007.
- **Atur**: percentatge d'atur mitjà de l'any en concret, p.ex. 15% l'any 1998.
- **Població**: variació percentual anual en el nombre de població, p.ex. -1% l'any 2017 (respecte de l'any 2016
- **Preu(-i), sense inflació**: variació percentual anual del preu ajustat a la inflació, p.ex. +3% l'any 1990 (respecte de l'any 1989).
- **Preu(+i), amb inflació**: variació percentual anual del preu sense ajustar-ho a la inflació, p.ex. +9% l'any 1990 (respecte de l'any 1989).
- **Crèdit**: variació percentual anual en el nombre d'hipoteques formalitzades, p.ex. +24% l'any 2015 (respecte de l'any 2014).
- **Compravenda**: variació percentual anual en el nombre de compravendes, p.ex. -15% l'any 2011 (respecte de l'any 2010).

# Interpretation and observations

El model general agrupa les sis variables que consider fonamentals per entendre el mercat de l'habitatge: preu, volum, inflació, crèdit, demografia i ocupació. Cal esmentar que totes les variables estan representades en percentatges, però hi ha dos blocs que s'han de llegir de manera diferent:

1. **Atur i Inflació**: representat en la mitjana percentual de l'any en concret.
2. **Població, Compravenda, Crèdit, Preu+i (amb inflació), Preu-i (sense inflació)**: representat en la variació percentual respecte de l'any anterior.

A la imatge principal podem veure la gràfica que representa el model general per a Catalunya. A tall d'exemple farem un parell d'interpretacions:

- **Observació A**: Podem observar com la inflació s'ha anat reduint. L'any 1989 superava el 5%, i l'any 2020 fou negativa (l'àrea vermella està per sota de 0%).
- **Observació B**: Podem observar com la població des de l'any 2010 s'està reduint any rere any. En canvi entre els anys 2002 i 2006 la població va augmentar bastant, a causa de l'onada immigratòria que hi va haver.
- **Observació C**: Podem observar que quan l'atur augmenta, l'evolució del preu de l'habitatge tendeix a ser negatiu, tant tenint en compte la inflació (+i) com no (-i).
- **Observació D**: És interessant observar com entre l'any 1986 i 1990 la pujada del preu de l'habitatge estava dominada per l'elevada inflació, i això ho sabem perquè la barra de preu és totalment negre, preu (+i), superposant per complet a la barra taronja.
- **Observació E**: La barra taronja, preu (-i), ens informa de la de/re-valorització dels habitatges, descomptant la inflació. En aquest sentit, aquells anys que podem observar la barra taronja, sabem quin és el nivell de revalorització o devalorització que sofreix l'habitatge. Per exemple, l'any 2013 va haver-hi una forta devalorització, i l'any 2017 una forta revalorització.

Aquestes només són algunes observacions, n'hi ha més que se'n poden fer de la gràfica, però ja depenen del coneixement i del bon ull de cadascú.
