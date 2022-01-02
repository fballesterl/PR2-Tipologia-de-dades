# PR2-Tipologia-de-dades

## Descripció

Extreu informació sobre les 20 criptomonedes més importants del mercat. La informació s'extreu de la pàgina web [Cryptocurrency Market Capitalizations](https://coinmarketcap.com/es/all/views/all/).

## Membres de la Pràctica 1

Francesc Ballester Lecina i Oriol Raurell Gan.

## Arxius

* `top_criptocurrencies.csv`: Conjunt de dades generat.
* `src/PR1_M2951_fballesterl_oraurell.py`: Fitxer amb la implementació de web scraping desenvolupat en python.
* `PR1_M2951_fballesterl_oraurell.pdf`: Document amb les respostes plantejades a la pràctica.

## Conjunt de dades

El conjunt de dades conté informació actualitzada sobre les 20 principals criptomonedes del mercat.

Els atributs que apareixen en el conjunt de dades són:
* `Nom`: Nom de la criptomoneda. 
* `Simbol`: Simbol de la criptomoneda. 
* `Cap. de mercat` : Valor de capitalització de mercat.
* `Preu` : Preu de la criptomoneda en dolars.
* `En circiulació` : Nombre de criptomonedes que hiha en circulació.
* `Volum(24h)` : Volum de dolars tractat en les 24h.
* `%1h` : Variació del preu de la criptomoneda en 1h.
* `%24h` : Variació del preu de la criptomoneda en 24h.
* `%7d` : Variació del preu de la criptomoneda respecte la setmana anterior.
* `Dia`: Dia de la extracció.
* `Hour`: Hora de la extracció.
