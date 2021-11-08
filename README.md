# tanosveny
Tanösvény ajánló weblap

verzió 1.0

Megvalósításra került az MVC framework alap működése. Controllerek, modellek, nézetek néhány oldalnál már működnek.
Adatbázisban fel van véve a tanösvény táblái, menüpontok, felhasználók és az általuk írt vélemények.
Lehetőség van bejelentkezésre az adatbázisban előre beállított felhasználókkal. A fejlécben megjelennek a felhasználó adatai.
A bejentkezettek hozzáférést kaptak a Hírek oldalhoz, olvashatják az előre feltöltött véleményeket.
A többi oldal egyelőre nincs elkészítve.
Reszpozívitás Bootstrapt 5-el van biztosítva.

verzió 2.0

Bővöltek a funkciók:
- Kezdő oldal bővült.
- A bejelentkezés mellett lehetőség van regisztrációra is.
- A bejelenkezett írhat új vélemény.
- Létre lett hozva a Tanosvények oldal (helyi SOAP még nincs).
- Létre lett hozva az Árfolyam oldal (lekérdezés, táblázat, grafikon).

verzió 3.0 - végleges

Implementálva lett a helyi soap-szerver.
test.php (teszt script a soap-szerver ellenőrzésére).
A Tanösvények oldal a helyi SOAP-ot használja.
Külső webtárhelyen is meg lett valósítva.
