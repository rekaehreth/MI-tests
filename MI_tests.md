[TOC]

# MI tests in the 2020/20201/1 semester 

Ebben a dokumentumban megtalálható az összes kérdés a 2020/2021/1-es MI előadást ellenőrző canvas tesztekből, illetve a hozzájuk tartozó ~~helytelen válaszok~~ és helyes válaszok. Elsőként a helyes válasz(ok) vannak feltűntetve. 

## Első teszt - MI fogalma

### Az alábbiak közül melyik NEM utal a mesterséges intelligencia jelenlétére egy szoftverben? 
- A szoftver optimális megoldást talál a kitűzött problémához. 
- ~~A megoldandó feladatnak hatalmas a problématere.~~
- ~~A szoftverbe különleges technológiák vannak beépítve.~~ 
- ~~A szoftver viselkedése intelligens jegyeket mutat.~~

### Mire utal egy algoritmussal kapcsolatban a kombinatorikus robbanás fogalma? 
- Az algoritmus kezelhetetlenül nagy memóriát igényel és/vagy a futási ideje óriási. 
- ~~Az algoritmus NP-teljes.~~
- ~~Az ilyen algoritmus nagyságrendekkel több megoldást tud előállítani adott időegység alatt.~~
- ~~Az algoritmus végtelen iklusba tud kerülni.~~

### Mit várunk el egy útkereső algoritmustól? 
- Azt, hogy egy irányított gráfban egy adott csúcsból kiinduló megadott csúcsok valamelyikébe érkező irányított utat találjon meg. 
- ~~Azt, hogy megadja egy irányított gráfban egy adott csúcsból kiinduló összes többi csúcsba vezető valamelyik utat.~~
- ~~Azt, hogy egy irányított gráfban egy adott csúcsból kiinduló megadott csúcsok valamelyikébe érkező optimális költségű irányított utat találjon meg.~~
- ~~Azt, hogy megadja egy irányított gráfban egy adott csúcsból kiinduló összes többi csúcsba vezető optimális költségű utat.~~

### Hogyan definiáljuk az optimális költség fogalmát? 
- Egy csúcsból egy másik csúcsba vezető utak költségeinek minimuma. 
- Egy csúcsból csúcsok halmazába vezető utak költségeinek minimuma. 
- ~~Egy csúcsból csúcsok halmazába vezető utak költségeinek infímuma.~~
- ~~Egy csúcsból egy másik csúcsba vezető utak költségeinek infímuma.~~

### Mely állítások igazak az alábbiak közül? 
- A kínai szoba elmélet az MI szkeptikusok érveit erősíti
- A Turing kiritérium cáfolataként született meg a kínai szoba elmélet. 
- ~~A Turing kritérium és a kínai szoba elméletegyaránt az erős MI hívők érveit erősítik.~~
- ~~A Turing kritérium az MI szkleptikusok érveit erősíti.~~

### Mikor nevezhetünk egy feladatot útkeresési problémának? 
- Amikor a megoldás egy irányított gráf egy útjának feleltethető meg.
- Amikor a feladat problématerének elemei ugyanazon csúcsból kiinduló irányított utak.
- ~~Csak akkor, ha a feladat olyan állapottér modellel rendelkezik, amelyben a megoldást egy műveletsorozat írja le.~~
- ~~Amikor egy gráfban keressük egy adott csúcsból az összes többibe vezető optimális utakat.~~

### Hogyan nyerhető ki egy útkeresési probléma megoldásakor kapott útból a feladat megoldása? 
- Sokszor az út élei mutatják a feladat megoldásához szükséges lépéseket. 
- Néha az út végpontja szimbolizálja a feladat egy megoldását. 
- ~~Az út csúcsai a feladatok különböző megoldásai.~~
- ~~Az út élei a feladat különböző megoldásait szimbolizálják.~~

### Mely állítások igazak egy 𝛿-gráfra?
- Csúcsaiból véges sok irányított él indul ki.
- Végtelen sok csúcsa lehet. 
- ~~Csúcsaiba véges sok irányított él fut be.~~
- ~~Éleinek költsége pozitív valós szám.~~

### Egy útkeresési feladat gráfreprezentációjához meg kell adni a ... 
- startcsúcsot
- reprezentációs gráfot
- ~~megoldási utakat~~
- ~~alkalmazandó heurisztikákat~~

### Az alábbiak közül melyek tartoznak a Turing kritériumok közé? 
- automatikus következtetés
- természetes nyelvű kommunikáció
- megszerzett ismeret tárolása
- ~~optimális megoldás megtalálása~~

### Allítsa párba: mely fogalmak kapcsolhatók egymáshoz!
| Fogalom | Pár | 
| ------- | --- |
| hatalmas problématér | kombinatorikus robbanás | 
| kínai szoba elmélet | MI szkeptikusok | 
| útkeresési feladat | probléma modell | 
| heurisztika | intuíció |

### Egy hiperút egy bejárása
- a hiperút összes hiperélét legalább egyszer érinti.
- a hiperút egy hiperélét legfeljebb annyiszor érinti, ahány közönséges irányított út vezet a hiperútban a hiperút kezdőcsúcsából a hiperél kezdőcsúcsába. 
- ~~kört nem tartalmazhat.~~
- ~~a hiperút egy hiperélét legfeljebb annyiszor érinti, ahány közönséges irányított út vezet a hiperútban a hiperút kezdőcsúcsából a hiperél kezdőcsúcsába.~~

## Második teszt - Modellezés

### Hogyan NEM csökkenthető egy állapottér modell bonyolultásga? 
- Csökkentjük a célállapotok számát. 
- ~~Növeljük az állapotok számát, de új műveleteket vezetünk be.~~ 
- ~~Szigorítjuk az állapotok invariáns tulajdonságát.~~
- ~~Szigorítjuk a műveletek értelmezési tartományát.~~

### Mitől NEM függ egy reprezentációs gráf bonyolultsága? 
- A csúcsai be-fokának számától. 
- ~~A csúcsainak és éleinek számától.~~
- ~~A csúcsai ki-fokának számától.~~ 
- ~~A köreinek gyakoriságától, és hosszuk sokféleségétől.~~ 

### Melyik NEM része a probléma dekompozíciós modellnek? 
- Az állapotok definiálása. 
- ~~Az egyszerű problémák megadása.~~
- ~~Dekompozíciós műveletek definiálása.~~
- ~~A kiinduló probléma leírása.~~ 

### Milyen egy dekompozíciós operátor? 
- Egy problémát több problémának a sorozatára képez le. 
- ~~Egy problémát több problémának a halmazára képez le.~~
- ~~Egy problémát megadott problémák egyikével helyettesít.~~ 
- ~~Egy probléma-sorozatot részsorozatokra bont fel.~~

### Az alábbiak közül melyek NEM elemei az állapottér modellnek? 
- állapotgráf
- heurisztika 
- ~~műveletek~~
- ~~kezdő állapot vagy annak leírása~~

### Mely állítások igazak az állapotgráfra az alábbiak közül? 
- Csúcsai az állapotokat szimbolizálják. 
- Startcsúcsa a kezdőállapotot szimbolizálja. 
- Élei a műveletek végrehajtásait szimbolizálják. 
- ~~Célcsúcsai a modellezett feladat megoldásai.~~

### Az alábbi feladat-modellezések közül melyeknél NEM egyezett meg a problématér a reprezentációs gráf startcsúcsból kivezető útjaival? 
- integrál számítás
- n-királynő probléma
- ~~Hanoi-tornyai probléma~~ 
- ~~8-as kirakó játék~~

### Melyik ot-okozati összefüggések igazak az alábbiak közül? 
- Az állapotgráf csúcsainak száma kihat a megoldó algoritmus hatékonyságára. 
- Az állapotgráfbeli körök hossza és száma kihat a problématér bonyolultságára. 
- ~~A megoldó algoritmus számíási bonyolultsága kihat a problématér bonyolultságára.~~
- ~~Az optimális megoldások száma kihat az állapotgráf bonyolultságára.~~

### Hogyan csökkenthető egy állapottér modellben a műveletek kiszámítási bonyolultsága? 
- Az állapotokat extra információval egészítjük ki. 
- Szigorítjuk az állapotok invariáns állítását. 
- ~~Több heurisztikát építünk be a modellbe.~~
- ~~Szigorítjuk a műveletek előfeltételét.~~ 

### Mely fogalmak kapcsolhatók egymáshoz? 
| Fogalom | Pár | 
| ------- | --- | 
| dekompozíciós operátor | hiperél | 
| állapot | csúcs | 
| művelet | irányított él | 
| dekompozíciós folyamat | hiperút| 

### Melyek a feltételei a visszafelé haladú keresésnek? 
- A reprezentációs gráf kétirányú éleket tartalmazzon és legyen ismert valamelyik célállapot. 
- ~~A reprezentációs gráf startcsúcsából az összes célcsúcsba vezető úton kétirányú élek legyenek.~~
- ~~A reprezentációs gráf kétirányú éleket tartalmazzon és legyen ismert az összes célállapot.~~
- ~~A reprezentációs gráf startcsúcsából valamelyik célcsúcsba vezető úton kétirányú élek legyenek.~~

### Mi célt szolgál a probléma-redukciós operátor? 
- Az állapottér modell egy műveletére megadja, hogy a művelet segítségével mely állapotokból lehet eljutni adott állapotok egyikébe. 
- ~~Egy állapottér modell egy műveletének inverze.~~
- ~~Megadja, hogy egy állapot mely állapotokból érhető el egy állapottér modellben.~~
- ~~Egy problémát egyszerűbb problémákra vezet vissza.~~

## Harmadik teszt - Lokális keresések

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

## Negyedik teszt - Visszalépéses keresés

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

## Ötödik teszt - Gráfkeresés

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

## Hatodik teszt

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

## Hetedik teszt

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

## Nyolcadik
### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

## Kilencedik teszt

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

## Tizedik teszt

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

## Tizenegyedik teszt

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 
## Tizenkettedik teszt 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 