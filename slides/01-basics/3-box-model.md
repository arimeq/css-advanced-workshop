# Model pudełkowy
![Hanka Mostowiak - pamiętamy](gifs/hanka-box.png)


## Własność `display`

1. inline
2. block
3. cała reszta ;)

notes:
omówić różnice między inline a block
cała reszta: inline-block, table-cell, flex, inline-flex, grid, inline-grid


## `inline`

* stosowany zwykle do tekstu lub elementów, których pozycjonowaniem zarządza przeglądarka
* honoruje marginesy i paddingi tylko w poziomie (lewa/prawa)


## `block`

* blok zajmuje całą dostępną szerokość strony
* można dla niego skonfigurować wszystkie paddingi, marginesy oraz obramowanie
* własności `width` i `height` domyślnie odnoszą się do rozmiaru pudełka od obramowania do obramowania, bez marginesów

![przykład modelu pudełkowego](gifs/box-model.png)


## Reszta

Pozostałe wartości własności `display` służą do używania zaawansowanych
metod layoutowania (`flex`, `grid`) - wrócimy do tego później