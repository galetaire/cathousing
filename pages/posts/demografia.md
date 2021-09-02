---
title: Home sales and demographic rhythm
date: 2021-08-01
description: Data on the evolution of the number of home sales in relation to the purchasing-age-population, which is between 25 and 50 years old.
tag: Demography, Volume
author: Galetaire
---

import Image from 'next/image'

# Home sales and demographic rhythm

<Image
  src="/images/demografia.png"
  alt="Photo"
  width={990}
  height={547}
  priority
  className="next-image"
/>

- Compravendes (barres); població entre 25 i 50 anys (línies amb punts) i herències d'habitatges (línia porpra).

# Interpretation and observations

L’indicador PEC — acrònim de Població en edat de compra; en anglès el podríem anomenar PAP, acrònim de Purchasing-age population —, és un indicador per a analitzar l’estat del mercat de l’habitatge.

Quina és la idea darrera d’aquest?, es dibuixen dos sostres basats en la demografia d’una regió concreta — en el cas de l’exemple seria de Catalunya —. El superior suposa que tothom en algun moment comprarà un habitatge individualment, i l’inferior suposa que tothom en algun moment comprarà un habitatge en parella.

Aleshores, el PEC es crea a través del nombre de persones entre 25 i 50 anys en un any i lloc determinat, i després es creua amb el nombre de compravendes del mateix any i lloc. El límit superior, (PEC/26), és el nombre mitjà de persones per generació — el 26 és perquè hi ha 26 generacions entre 25 i 50 anys —. I el límit inferior, (PEC/26)/2, és el nombre mitjà de parelles per generació — el 2 és per tal de modelitzar el nombre potencial de parelles —.

A la imatge principal podem veure-ho representat gràficament. A tall de resum, les dades les podem interpretar de la següent manera:

- Si el nombre de compravendes supera el sostre superior, ens indica que el mercat està en una situació de **superàvit**, sovint ens pot indicar la creació d’una **bombolla**, com bé es pot veure que succeïa a Catalunya l’any 2003-2006, i que va acabar esclatant amb força poc després.
- Si el nombre de compravendes està per sota del sostre inferior, ens indica que el mercat està en una situació de **dèficit**, assenyalant-nos una zona de **depressió** i una possible oportunitat d’inversió, com foren els anys 2009-2014.
- Si el nombre de compravendes es troba entre els dos sostres, implica que el mercat es troba en una **zona estable**, que segons la seva situació en referència a l’òptima — just a la meitat —, també ens pot indicar si està en expansió o en equilibri. Actualment estam dins aquesta zona estable.
