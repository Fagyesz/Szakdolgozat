# Szakdolgozat 
***Készítette: Vincze Flórián***

## Új Élet Baptista Gyülekezet web alkalmazása

### Dolgozat célja: 
Fontos szerepet tölt be az emberek életében a hit és Istennel való kapcsolat. Ebben a modern világban már szükséggé vált, hogy ne csak személyesen, hanem online is tartsuk, hozzunk létre új kapcsolatokat, illetve megosszuk gondolatainkat, tájékoztassuk eseményeinket testvéreinkkel, ismerőseinkkel. Egy olyan webalkalmazás készítésével szeretném segíteni az „Új Élet Baptista Gyülekezetet”, amellyel testvéreikkel való kommunikációt, információ megosztást, illetve új emberekkel való megismerést és segítség nyújtást segíti elő

### Implementáció terv:
Az alkalmazás három rétegből fog állni, frontend, backend és adatbázis réteg. A frontend egy webes felület lesz, aminek elkészítéséhez: JavaScript alapú megjelenítés, az adatcsere AJAX hívásokkal valósul meg, tehát a megjelenítő réteg az API-n keresztül kommunikál a backend réteggel. Itt Angular-t és Ionic-ot fogok használni. A backendet a Laravel Keretrenszerrel valósítom meg. Az adatbázis SQL alapú.