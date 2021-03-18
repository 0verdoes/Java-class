Ezen az órán egy leegyszerűsített játékot fogunk megvalósítani.
Ehhez minden file-t a game package-en belülre helyezzetek el.
Készítsetek egy Player osztályt.
> - legyen neki x, y double koordinátája.
> - egy int ami az egészségügyi állapotát reprezentálja.
> - Illetve egy járműve és egy fegyvere is lehet.
> - Legyen lehetősége egy játékosnak mozogni koordinátájától 5 távolságra, de ha van járműve, akkor a jármű sebbeségével egyenlő távolságra engedjük mozogni. Amennyiben ennél messzebb szeretne mozogni a játékos, dobjunk hibát.
> - Legyen továbbá lehetősége egy játékosnak megsebeznie egy másikat, amennyiben elég közel van hozzá (pl.: 3 távolságnyira). Ez a távolság legyen a játékos fegyverének a hatótávolsága, ha van neki. Itt is érvényes, hogyha messzebbre szeretne támadni a játékos, mint szabad neki akkor dobjunk hibát.
> - Legyen egy **saveToFile()** metodúsunk, ami a paraméterként kapott fájlba írja ki a játékos adatait.

A járműveket és fegyvereket egy-egy Enum-mal oldjátok meg, amik a game.tools package-be kerül.
> - A járműnek legyen sebességem.
> - A fegyvernek legyen hatótávolsága és sebzése, amit okoz.
> - Járműből és fegyverből is legalább 2 fajta szerepeljen a felsoroló típusban.
> - Legyen toString() metodúsa mind a két Enum-nak!

Legyen egy main függvényünk, ami egy fájlból beolvas egy számot (legyen N), majd N Player adataid a fájl-ból soronként beolvassa. És ez alapján létrehoz egy N hosszú Player tömböt.
Itt a fájl kezelésre használjunk try with resource struktúrát! Ezután teszteljük le, hogy müködnek-e a játékos műveletei!
