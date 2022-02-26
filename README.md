# Scratch_hazi_feladat
![scratch](https://user-images.githubusercontent.com/100472208/155844570-78b2bb52-768f-4891-badf-628231b3240e.png)
![scratch1](https://user-images.githubusercontent.com/100472208/155844574-e6e8df7b-6499-41e7-84d3-0878772e5dd7.png)
https://scratch.mit.edu/projects/644121342/
A program kettő db sprite-ot tartalmaz (szaxofon, denevér). Kattintásra a szaxofon egészen a színpad (ez lett a választott háttér) széléig megy, eközben skálázik a lépéseknek megfelelő ritmusban. Ehhez egy ciklust használtam, ami minden megtett lépésegység (10 lépés) után, 10-zel növeli a sax változó értékét. Egy feltétel segítségével - ha a sax változó eléri a kívánt értéket - a sprite megfordul és a másik irányba kezd el haladni. Majd aztán egy bizonyos értéknél megint megfordul és a végtelen ciklusnak köszönhetően, elölről kezdi  az egész folyamatot. A másik sprite esetében hasonló dolgokat tapasztalunk: a denevér kattintásra el kezd repülni egy adott irányban - eközben a két kinézet folyamatosan változik - majd  amikor a szaxofon megfordul vele együtt a denevér is irányt változtat. Ehhez is egy egy ciklust illetve egy feltétel használtam.
 main
