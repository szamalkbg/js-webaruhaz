**index.html:** A program főoldala. Itt érhetőek el a termékek és a legtöbb funkció. Innen navigálhat el a felhasználó máshová. Felépítés szemantikus elemekkel:
*nav, nav
article, aside
footer, footer*

**stilus.css:** Az index.html-ben a bootsrap 5-ön kívül itt adható meg egyéb stílus és rendezés.

**main.js:** Az index.html head-ben modulosan meghívott fő függvény, amely dinamikusan kezelhetővé teszi az oldalt.. Betöltéskor itt futnak le a kódok, amelyeket más javascript fájlokból importálunk.

**fuggvenyek.js:** Ide kerülnek metódusokba rendezve az oldal függvényei. Itt kezeljük a terméklistákat, a szürőket, a keresés funkcióit, a kukába helyezést, a termék hozzáadást, a személyes adatok függvényeit, a kosárba helyezést, az admin oldalt és a felugró ablakokat.

**termekek.js:**  Itt generáljuk a termékeket kártyákként. Javascriptbe helyezve a html dokumentumban a megadott helyen generálódik. Ez lehetővé teszi a termékek egyszerübb szerkeztését.


> Todo:
> 
>  - [ ] htmlből elemek áthelyezése txt fájlba termekek.js-en belül
>  - [ ] személyes adatok menüben ürlapok kialakítása, regex beállítása
>  - [ ] kosár menüben az összeg ár megjelenítése
>  - [ ] szürőnél ár szerint csökkenő/nővekvő sorrendbe helyezés
>  - [ ] név alapú kereső funkció kialakítása
>  - [ ] admin menüben termékek listába helyezése, hozzáadás/törlés funkció
