A mozgás három részre osztható:

**1. Történetmesélés közben**
Amikor nincsen utazás vagy stresszes esemény, akkor a játékosok szabadon mozoghatnak. Ezt nem szükséges külön számolni.

**2. Utazás közben**
Amennyiben a játékosok nagyobb távolságot tesznek meg, azaz utaznak, az összes karakter közül a legkisebb SPD-szel, és külön a legkisebb CON-nal rendelkező karakterek értékeit kell figyelembe venni (ez lehet ugyanaz a karakter is). Hasonló módon még a legkisebb LCK értéket is figyelembe kell venni. A SPD módosító alapján lehet eldönteni hány nappal később vagy hamarabb érkeznek meg a területre. A CON-nal pedig, hogy utazás közben mennyi extra élelem fogy el.
Az utazás ideje: $$napok = (\frac{(5 - SPD)*km}{100}) * max((\frac{(5 - LCK)}{2}), 0.5)$$
Az alapértelmezett élelem fogyás a következő: $$ fogyaspont = (napok + TGH)*karakterek $$
Az élelmiszerek közül a fogyáspontoknak megfelelő mennyiségű élelmiszerpontot el kell távolítani a felszerelés közül. Egy étel akár több élelmiszer ponttal is rendelkezhet, de egy élelmiszer egésze el kell, hogy használódjon amennyiben azt már megkezdték. Ez alól egyes élelmiszerek a leírásukban ítélkezhetnek másképp.
Amennyiben nincs elég élelmiszerpont, a játékosok életéből le kell vonni mindennap egy éhség értéket. $$ éhségérték = elteltnapok * MIN(0,TGH) * 10 $$
Ahol az eltelt napok az utolsó étkezés óta eltelt nap. És az éhségérték levonása minden nap külön kell, hogy megtörténjen.

Az utolsó érték pedig a LUC érték, ami alapján pedig az utazás közben történt hátrányok mennyisége számolható ki. Egy hátrány lehet egy ellenség megjelenése akár utazás közben, akár alvás közben (bár ez nem feltétlen jelenti azt, hogy támadnak is), de lehet valamilyen speciális kihívás amit a játékosoknak meg kell oldaniuk, vagy elfogadniuk a következményüket (például a lovashintó kereke meghibásodik, cserébe két nappal tovább tart az út).

**3. Stresszes események közben**
Stresszes események közben a játékosok alapértelmezetten 3 hexagon (3 méter) megtételére jogosultak. A DEX értékből származó módosító pedig ezt módosítja további/kevesebb hexagonokkal.