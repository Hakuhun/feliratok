
# Haku fordításai

Sziasztok! Az általam fordított anime feliratok gyűjteménye. A legfrissebb kiadott verziókat mindig a master branchen találhatjátok meg. A különböző feature branchen lévő feliratok általában befejezetlen állapotban vannak, azokat nem érdemes letöltenetek. 

# Hogyan működik?
A git egy verziókövető rendszer, a feliratok ebben a kód adatbázisban lesznek legelőször megtalálhatók. Ha szeretnél minden projektet letölteni -- ez a legegyszerűbb megoldás -- akkor írd be a következő sorokat az általad használt terminál emulátorban (Windows: cmd, Mac: Terminal, Linux: Úgy is tudod hova 😉 )

```bash
    git clone -b master https://github.com/Hakuhun/feliratok.git 
```
**Persze nem várom el, hogy a lelkes anime néző értsen a githez. Ha egy adott feliratra van szükséged, látogass el az adott anime feliratához, ahol a jobb felső sarokba megtalálható "Raw" füllel megnyithatod, és a böngészőből lementheted. (Ctrl+S)**
**Ezen kívül felkerülnek OpenSubtitles oldalára is a kezdetleges feliratok, de ott nincs lehetőségem új verziót megadni, így azokban hibák fordulhatnak elő.**

Az új feliratok időről időre bekerülnek a master branchbe, ha szeretnéd frissíteni a gépeden lévő feliratokat, akkor a terminálodban nyiosd meg a projekt rootját (D:/feliratok pl.) és írd be az alábbi kódot:

```bash
    git stash
    git stash drop
    git pull
```

ha beleírtál volna a feliratokba és emiatt nem töltődnének le az újak, ezekkel a kódokkal eldobhatod a lokális változásokat:

```bash
    git stash
    git stash drop
```

Örömmel várom a merge requesteket azoktól a lelkes fordítóktól, lektoroktól és formázóktól, akik segítenének a projektjeimet rendbe rakni. Ha te is részt vennél a munkában kérlek értesíts a hakuhun@gmail.com címen.

# Projektek

## Mieruko-chan
Az anime adatlapját itt találjátok: https://myanimelist.net/anime/48483/Mieruko-chan  
Projekt állapota: Folyamtban♻️  
A feliratok a SubsPlease videó kiadások alapján készülnek és csak ahhoz a kiadáshoz használható.   
A feliratok pedig [EZEN A LINKEN TALÁLHATÓAK MEG](https://github.com/Hakuhun/feliratok/tree/master/Mieruko-chan) 

----