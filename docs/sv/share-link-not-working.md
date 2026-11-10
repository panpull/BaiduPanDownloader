# Delningslänken från Baidu Pan fungerar inte: vad varje meddelande betyder

Du öppnar en `pan.baidu.com`-länk och får ett kort meddelande på kinesiska i stället för en fillista. Här får du veta vad meddelandet betyder och vad du kan göra.

## Kontrollera först adressen

En fungerande länk har formen `https://pan.baidu.com/s/1…` med en lång rad bokstäver och siffror efter `1`. När den har öppnats kan webbläsaren i stället visa `https://pan.baidu.com/share/init?surl=…`. Det är samma delning.

Om länken klipptes av när den kopierades går den inte att öppna. Kopiera den igen från originalmeddelandet, ända till slutet.

## Vad sidan försöker säga

| Vad du ser | Vad det betyder | Vem kan lösa det |
| --- | --- | --- |
| En ruta som ber om fyra tecken | Delningen är skyddad. Du behöver [åtkomstkoden](extraction-code.md) | Du, med koden från ägaren |
| Ett meddelande om att du kommer för sent och att delningen har avbrutits | Ägaren har slutat dela, eller Baidu har tagit bort filerna | Ägaren |
| Ett meddelande om intrång eller förbjudet innehåll | Baidu har blockerat delningen | Ingen: delningen förblir blockerad |
| En fillista med en notis om att vissa filer har filtrerats bort | En del av delningen bröt mot Baidus regler och är dold | Ägaren |
| Ett meddelande om att delningen inte längre är giltig | Delningen har gått ut | Ägaren |

Webbläsarens översättningsfunktion hjälper dig att skilja meddelandena åt.

## Vad du gör

- **Koden godtas inte:** jämför den med originalmeddelandet ett tecken i taget. Se [Åtkomstkod](extraction-code.md).
- **Delningen är avbruten eller har gått ut:** be ägaren dela filerna igen och skicka den nya länken och koden till dig.
- **Delningen är blockerad:** det finns inget att ladda ner. Fråga ägaren om filerna finns någon annanstans.

## Kontrollera innan du betalar något

Testa länken i [PanPulls länkkontroll](https://panpull.com/sv?utm_source=github&utm_medium=tutorial#link-checker). Kontrollen är gratis. En läsbar delning kommer tillbaka med antal filer, total storlek och pris. Om den inte går att läsa får du ett felmeddelande i stället, och ingenting debiteras.

Ingen tjänst kan få tillbaka en delning som har tagits bort, avbrutits eller blockerats. Om en delning misslyckas på PanPull men öppnas utan problem för ägaren, försök igen lite senare: orsaken kan vara tillfällig.

Mer på PanPulls blogg: [Delningslänk från Baidu fungerar inte? Det här ska du kontrollera](https://panpull.com/sv/blog/baidu-share-unavailable-checklist?utm_source=github&utm_medium=tutorial).

---

**Har du en Baidu-länk? [Kontrollera den på PanPull](https://panpull.com/sv?utm_source=github&utm_medium=tutorial#link-checker)** och se storlek och pris först. Upp till 150 MB är gratis.

[Alla guider](README.md) · [Andra språk](../README.md#languages)
