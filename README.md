# Vezba: napraviti modal

**Napraviti standardni modal element (*popup window* ili iskacuci prozor).**

Prozor se otvara preko sadrzaja stranice, tako sto se na sredini ekrana pojavi sam modal, a ostatak sadrzaja stranice posivi. 

Da biste napravili zeljeni prikaz, potrebno je sledece:
- *overlay* element (prekrivac), koji ima providnost oko 0.5 i koji se prikazuje od ivice do ivice ekrana
- modal prozor, velicine oko 480 x 240 piksela, koji se prikazuje preko prekrivaca

Takodje je potrebno da modal ima sledecu funkcionalnost:
- Otvara se pritiskom na odredjeno dugme
- Zatvara se klikom na `x` u gornjem desnom uglu prozorceta

Savet: prekrivac treba da ima veci `z-index` nego sadrzaj stranice, a modal treba da ima veci `z-index` od prekrivaca.

Bonus: mozete dodati blur efekat na *overlay*.

## Radovi
