# Baidu Pan megosztási link nem működik: mit jelentenek az üzenetek

Megnyit egy `pan.baidu.com`-linket, és fájllista helyett egy rövid kínai üzenetet kap. Ez az oldal elmondja, mit jelent az üzenet, és mit tehet.

## Először ellenőrizze a címet

Egy ép link így néz ki: `https://pan.baidu.com/s/1…`, az `1` után betűk és számjegyek hosszú sorával. Megnyitás után a böngésző ehelyett ezt is mutathatja: `https://pan.baidu.com/share/init?surl=…`. Ez ugyanaz a megosztás.

Ha a link másoláskor csonka maradt, nem fog megnyílni. Másolja ki újra az eredeti üzenetből, egészen a végéig.

## Mit akar mondani az oldal

| Amit lát | Mit jelent | Ki tudja megoldani |
| --- | --- | --- |
| Egy mező, amely négy karaktert kér | A megosztás védett. A [hozzáférési kód](extraction-code.md) kell hozzá | Ön, a tulajdonostól kapott kóddal |
| Üzenet arról, hogy elkésett, és a megosztást visszavonták | A tulajdonos megszüntette a megosztást, vagy a Baidu eltávolította a fájlokat | A tulajdonos |
| Üzenet jogsértésről vagy tiltott tartalomról | A Baidu letiltotta a megosztást | Senki: a megosztás letiltva marad |
| Fájllista azzal a megjegyzéssel, hogy egyes fájlokat kiszűrtek | A megosztás egy része sértette a Baidu szabályait, ezért rejtve van | A tulajdonos |
| Üzenet arról, hogy a megosztás már nem érvényes | A megosztás lejárt | A tulajdonos |

A böngésző fordító funkciója segít megkülönböztetni ezeket az üzeneteket.

## Mit tegyen

- **A rendszer elutasítja a kódot:** karakterről karakterre vesse össze az eredeti üzenettel. Lásd: [Hozzáférési kód](extraction-code.md).
- **A megosztást visszavonták, vagy lejárt:** kérje meg a tulajdonost, hogy ossza meg újra a fájlokat, és küldje el Önnek az új linket és kódot.
- **A megosztás le van tiltva:** nincs mit letölteni. Kérdezze meg a tulajdonost, elérhetők-e a fájlok máshol.

## Ellenőrizze, mielőtt bármit fizetne

Próbálja ki a linket a [PanPull linkellenőrzőjében](https://panpull.com/hu?utm_source=github&utm_medium=tutorial#link-checker). Az ellenőrzés ingyenes. Egy olvasható megosztásnál visszakapja a fájlok számát, a teljes méretet és az árat. Ha nem olvasható, helyette hibaüzenetet kap, és nem számolunk fel semmit.

Egyetlen szolgáltatás sem tudja visszahozni a törölt, visszavont vagy letiltott megosztást. Ha egy megosztás a PanPullon nem sikerül, de a tulajdonosnál gond nélkül megnyílik, próbálja újra kicsit később: lehet, hogy átmeneti a hiba.

Bővebben a PanPull blogján: [Nem működik a Baidu-megosztási link? Ezt ellenőrizze](https://panpull.com/hu/blog/baidu-share-unavailable-checklist?utm_source=github&utm_medium=tutorial).

---

**Van egy Baidu-linkje? [Ellenőrizze a PanPullon](https://panpull.com/hu?utm_source=github&utm_medium=tutorial#link-checker)**, és előbb nézze meg a méretet és az árat. 150 MB-ig ingyenes.

[Az összes útmutató](README.md) · [Más nyelvek](../README.md#languages)
