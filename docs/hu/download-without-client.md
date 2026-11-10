# Baidu Pan asztali kliens nélkül: letöltés böngészőben Windowson, Macen és Linuxon

Rákattint a letöltés gombra egy Baidu Pan-megosztáson, és egy kínai felugró ablak közli, hogy előbb telepítse a Baidu Netdisket. Nyugodtan figyelmen kívül hagyhatja. Megmutatjuk, miért jelenik meg az ablak, mit kérne Öntől a kliens, és hogyan juthat hozzá ugyanazokhoz a fájlokhoz csupán a böngészőjével.

## Miért jelenik meg a felugró ablak?

A Baidu weboldala csak kis, egyedi fájlokat ad ki, és csak bejelentkezett felhasználóknak. Egy nagy fájlt, egy mappát vagy egyszerre több fájlt az asztali kliensre bíz. A legtöbb megosztásnál ez azt jelenti: kliens nélkül nincs letöltés.

## Kliens vagy böngésző?

| | Baidu Netdisk kliens | Böngészős letöltés a PanPull-lal |
| --- | --- | --- |
| Telepítés | Igen. Windowson ráadásul a rendszerrel együtt indul, és a háttérben fut | Nincs |
| Baidu-fiók | Kötelező | Nem kell |
| Nyelv | Csak kínai | 29 nyelv |
| Sebesség | Ingyenes fióknál korlátozott | Szokásos letöltés a PanPull tárhelyéről |
| Költség | Ingyenes, vagy a Baidu fizetős SVIP-tagsága | 150 MB-ig ingyenes, utána méret szerint |
| Rendszerek | Windows, macOS, Android, iOS; Linuxra `.deb` vagy `.rpm` csomagként | Bármi, amin van böngésző |

Ha mégis a klienst szeretné, magától a Baidutól töltse le a `pan.baidu.com/download` címről, ne letöltőportálról.

## Tipikus esetek a böngészős megoldáshoz

- **Munkahelyi vagy egyetemi gép:** nincs jogosultsága programokat telepíteni.
- **Linux:** egyetlen fájl miatt nem telepítene zárt forráskódú csomagot.
- **Saját Mac vagy PC:** nem szeretne még egy programot, amely a háttérben fut.

## Lépések

1. Másolja be a megosztási linket a [PanPull linkellenőrzőjébe](https://panpull.com/hu?utm_source=github&utm_medium=tutorial#link-checker). Ha van hozzáférési kód, adja meg azt is.
2. Nézze meg az eredményt: hány fájl, mekkora összesen, mennyi az ár.
3. Jelentkezzen be a PanPullba e-mail-címmel és jelszóval, és ha a rendelés nem ingyenes, fizessen PayPallal vagy kártyával.
4. Várja meg az e-mailt arról, hogy a letöltés elkészült, és nyissa meg a benne lévő linket. A rendelés oldalán ugyanez a link található.

Az egyfájlos megosztásból ugyanazt a fájlt kapja. A többfájlos megosztásból egyetlen ZIP-archívumot kap, benne a mappaszerkezettel.

## A ZIP kibontása

| Rendszer | Hogyan |
| --- | --- |
| Windows | Kattintson jobb gombbal az archívumra, majd válassza az **Összes kibontása** parancsot |
| macOS | Kattintson duplán az archívumra |
| Linux | Használja a fájlkezelőt, vagy írja be egy terminálba: `unzip` és a fájlnév |

Hagyjon szabadon nagyjából az archívum méretének kétszeresét: egyszer a ZIP-nek, egyszer a tartalmának.

Bővebben a PanPull blogján: [Letöltés a Baidu Panról kliens nélkül: Mac, Linux, munkahelyi gép](https://panpull.com/hu/blog/download-baidu-pan-without-client?utm_source=github&utm_medium=tutorial).

---

**Van egy Baidu-linkje? [Ellenőrizze a PanPullon](https://panpull.com/hu?utm_source=github&utm_medium=tutorial#link-checker)**, és előbb nézze meg a méretet és az árat. 150 MB-ig ingyenes.

[Az összes útmutató](README.md) · [Más nyelvek](../README.md#languages)
