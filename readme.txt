Izveštaj o statičkoj analizi koda
Metrike
LOC: 79 linija koda

Zapažanja (Statička analiza)
Calculator.java – linija 55: Koristi se generički Exception umesto specifičnog Arithmetic Exception za deljenje nulom.
Calculator.java – linije 23-53: Nedostaje validacija ulaznih podataka u metodama.
Start.java – linija 9: Nedostaje try-catch blok za rukovanje potencijalnim izuzecima iz Calculator klase.
Projekat generalno: Nedostaju Unit testovi koji bi potvrdili ispravnost kalkulacija.