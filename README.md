## Style
#### Styl to zbiór atrybtów określająych wygląd pojedynczego widoku.


## Theme
#### Motyw to zbiór atrybytów określających wygląd całej aplikacji, aktywności lub danej hierarchii widoków.

## Style vs Theme
#### Zarówno style jak i motywy definiuje się za pomocą par klucz-wartość mapujących atrybuty do zasobów.

#### Styl określa atrybuty konkretnego widoku, np. przycisku. Każdy atrybut określony w stylu można równie dobrze zdefiniować osobno w pliku `layout`.

#### Motyw definiuje kolekcję nazwanych zasobów, które mogą być wykorzystywane przez style, układy, widoki itp. Atrybuty w motywach używają semantycznych nazw, takich jak np. `colorPrimary`.

#### Style i motywy zaprojaktowane tak aby się dopełniały. Dla przykładu: Motyw może zdefiniować kolory takie jak `colorPrimary` i `ColorSecondar`, natomiast styl przypisać je do konkretnego przycisku.
