# Illyes-napi-jelentkezes
Új és továbbfejlesztett illyés napi jelentkező felület

A lényege ennek a projektnek a lényege az illyés napi jelentkezés felületének funkcióinak kibővítése, és a felület esztétikai feljavítása.
A funkciók:
  -reszponzív (mobil platformokra való optimalizáció)
  -A jelentkezés lépesekre való lebontása (csak a szükséges opciókat kapja meg a felhasználó)
  -A saját, résztvevő, és osztály előadások megtekintése
  -A fájlokat igénylő előadásokhoz fájlok feltöltése
  -előadási sorrendek, szabályzatok, eredmények, és zsűritagok megtekintése
  -Az osztályok saját fiókot kapnak, de a diákoknak és tanároknak regisztrálniuk kell, tanári fiókkal nem lehet előadásra regisztrálni, csakis megtekinteni az    amúgyis publikus információkat, és személyes regisztráció alapján az osztályfőnökök megkaphatják az osztályfőnök fiókot, amellyel az osztály összes előadását részletesen láthatják (beleértve mind az osztályprodukciókat, és az osztály tagjai által regisztrált produkciólat) emellett szerkeszthetik is azokat.
  -regisztráció: Családnév, keresztnév, email-cím, jelszó, tanár/diák, ha diák akkor osztály + emailos hitelesítés

fióktípusok:
  -diák: regisztrálni (és szerkeszteni) tud egyéni előadással, és megtekinteni a publikus információkat
  -tanár: meg tudja tekinteni a publikus információkat
  -osztály: jelentkezhet osztályprodukcióval, megtekintheti a publikus információkat
  -osztályfőnök: (egy osztályfőnök tanári fiókja személyes hitelesítés után) jelentkezhet osztályprodukcióval, és megtekintheti és szerkesztheti osztályának összes produkcióját és megtekintheti a publikos információkat
  -admin fiók: látja az összes előadást, nyomtatható formákat lekérhet
  -stúdiós fiók: hozzáfér a feltöltött fájlokhoz, hozzáfér a sorrendhez, hozzáfér az előadás módhoz(!!!), megtekintheti a publikus információkat
  -super_user: hozzáfér mindenhez (törlés, migrálás, akármi)
  
publikus információ:
  -amint kész van, az előadások sorrendje
  -szabályzat
  -zsűritagok
  
BACKEND:
  sql kliens: Mysql
  python
  
FRONTEND:
  php
  html + css + javascript template
