# Sdílený odkaz z Baidu Pan nefunguje: co znamená která hláška

Otevřete odkaz `pan.baidu.com` a místo seznamu souborů uvidíte krátkou čínskou hlášku. Tady zjistíte, co znamená a co s tím můžete dělat.

## Nejdřív zkontrolujte adresu

Funkční odkaz má tvar `https://pan.baidu.com/s/1…` s dlouhou řadou písmen a číslic za `1`. Po otevření může prohlížeč místo toho ukázat `https://pan.baidu.com/share/init?surl=…`. Jde o stejné sdílení.

Pokud se odkaz při kopírování uřízl, neotevře se. Zkopírujte ho znovu z původní zprávy, a to celý až do konce.

## Co vám stránka říká

| Co vidíte | Co to znamená | Kdo to může vyřešit |
| --- | --- | --- |
| Pole, které chce čtyři znaky | Sdílení je chráněné. Potřebujete [přístupový kód](extraction-code.md) | Vy, s kódem od vlastníka |
| Hláška, že jdete pozdě a sdílení bylo zrušeno | Vlastník přestal sdílet, nebo Baidu soubory odstranilo | Vlastník |
| Hláška o porušení práv nebo zakázaném obsahu | Baidu sdílení zablokovalo | Nikdo: sdílení zůstane zablokované |
| Seznam souborů s poznámkou, že některé soubory byly odfiltrovány | Část sdílení porušila pravidla Baidu a je skrytá | Vlastník |
| Hláška, že sdílení už neplatí | Sdílení vypršelo | Vlastník |

Rozlišit tyto hlášky vám pomůže funkce překladu v prohlížeči.

## Co dělat

- **Kód je odmítnut:** porovnejte ho s původní zprávou znak po znaku. Viz [Přístupový kód](extraction-code.md).
- **Sdílení je zrušené nebo vypršelo:** požádejte vlastníka, ať soubory nasdílí znovu a pošle vám nový odkaz a kód.
- **Sdílení je zablokované:** není co stahovat. Zeptejte se vlastníka, jestli jsou soubory k dispozici jinde.

## Než cokoli zaplatíte, zkontrolujte

Vyzkoušejte odkaz v [kontrole odkazu na PanPull](https://panpull.com/cs?utm_source=github&utm_medium=tutorial#link-checker). Kontrola je zdarma. Čitelné sdílení se vrátí s počtem souborů, celkovou velikostí a cenou. Pokud ho přečíst nejde, dostanete místo toho chybovou hlášku a nic se neúčtuje.

Žádná služba nedokáže obnovit sdílení, které bylo smazáno, zrušeno nebo zablokováno. Pokud sdílení na PanPull selže, ale vlastníkovi se otevírá bez problémů, zkuste to o něco později znovu: příčina může být dočasná.

Více na blogu PanPull: [Sdílený odkaz Baidu nefunguje: co zkontrolovat](https://panpull.com/cs/blog/baidu-share-unavailable-checklist?utm_source=github&utm_medium=tutorial).

---

**Máte odkaz z Baidu? [Zkontrolujte ho na PanPull](https://panpull.com/cs?utm_source=github&utm_medium=tutorial#link-checker)** a nejdřív uvidíte velikost a cenu. Do 150 MB zdarma.

[Všechny návody](README.md) · [Další jazyky](../README.md#languages)
