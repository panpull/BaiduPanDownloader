# Baidu Pan bez desktopového klienta: stahování v prohlížeči na Windows, Macu a Linuxu

Kliknete na tlačítko pro stažení na stránce sdílení Baidu Pan a čínské okno vám řekne, ať si nejdřív nainstalujete Baidu Netdisk. Můžete ho ignorovat. Vysvětlíme, proč se okno objevuje, co by po vás klient chtěl a jak získat stejné soubory jen pomocí prohlížeče.

## Proč se okno objevuje

Web Baidu vydává jen malé jednotlivé soubory, a to jen přihlášeným uživatelům. Velký soubor, složka nebo více souborů najednou se předávají desktopovému klientovi. U většiny sdílení to znamená: bez klienta žádné stahování.

## Klient, nebo prohlížeč?

| | Klient Baidu Netdisk | Stahování v prohlížeči přes PanPull |
| --- | --- | --- |
| Instalace | Ano. Ve Windows se navíc spouští se systémem a běží na pozadí | Žádná |
| Účet Baidu | Nutný | Není potřeba |
| Jazyk | Jen čínština | 29 jazyků |
| Rychlost | U bezplatného účtu omezená | Běžné stahování z úložiště PanPull |
| Cena | Zdarma, nebo placené členství SVIP od Baidu | Do 150 MB zdarma, pak podle velikosti |
| Systémy | Windows, macOS, Android, iOS; Linux jako `.deb` nebo `.rpm` | Cokoli s prohlížečem |

Pokud klienta přece jen chcete, stáhněte ho přímo od Baidu na `pan.baidu.com/download`, ne ze stahovacího portálu.

## Typické situace pro prohlížeč

- **Počítač v práci nebo ve škole:** nemáte práva instalovat programy.
- **Linux:** kvůli jednomu souboru nechcete instalovat balík s uzavřeným kódem.
- **Vlastní Mac nebo PC:** nechcete další program, který běží na pozadí.

## Postup

1. Zkopírujte sdílený odkaz do [kontroly odkazu na PanPull](https://panpull.com/cs?utm_source=github&utm_medium=tutorial#link-checker). Pokud existuje přístupový kód, přidejte ho.
2. Podívejte se na výsledek: kolik souborů, jaká celková velikost, jaká cena.
3. Přihlaste se do PanPull e-mailovou adresou a heslem a zaplaťte přes PayPal nebo kartou, pokud objednávka není zdarma.
4. Počkejte na e-mail, že je stahování připravené, a otevřete odkaz v něm. Stejný odkaz je na stránce objednávky.

Ze sdílení s jedním souborem dostanete ten soubor. Ze sdílení s více soubory dostanete jeden archiv ZIP se strukturou složek uvnitř.

## Rozbalení ZIPu

| Systém | Jak |
| --- | --- |
| Windows | Klikněte na archiv pravým tlačítkem a zvolte **Extrahovat vše** |
| macOS | Dvakrát klikněte na archiv |
| Linux | Použijte správce souborů, nebo v terminálu napište `unzip` a název souboru |

Mějte na disku volné místo zhruba dvojnásobku velikosti archivu: jednou pro ZIP, jednou pro jeho obsah.

Více na blogu PanPull: [Stahování z Baidu Pan bez klienta: Mac, Linux a pracovní počítače](https://panpull.com/cs/blog/download-baidu-pan-without-client?utm_source=github&utm_medium=tutorial).

---

**Máte odkaz z Baidu? [Zkontrolujte ho na PanPull](https://panpull.com/cs?utm_source=github&utm_medium=tutorial#link-checker)** a nejdřív uvidíte velikost a cenu. Do 150 MB zdarma.

[Všechny návody](README.md) · [Další jazyky](../README.md#languages)
