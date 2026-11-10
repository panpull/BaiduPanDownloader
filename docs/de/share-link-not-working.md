# Baidu-Pan-Freigabelink funktioniert nicht: was die Meldungen bedeuten

Sie öffnen einen `pan.baidu.com`-Link und bekommen statt einer Dateiliste eine kurze Meldung auf Chinesisch. Hier erfahren Sie, was die Meldung bedeutet und was Sie tun können.

## Zuerst die Adresse prüfen

Ein intakter Link hat die Form `https://pan.baidu.com/s/1…` mit einer langen Folge aus Buchstaben und Ziffern nach der `1`. Nach dem Öffnen zeigt der Browser stattdessen vielleicht `https://pan.baidu.com/share/init?surl=…` an. Das ist dieselbe Freigabe.

Wurde der Link beim Kopieren abgeschnitten, öffnet er sich nicht. Kopieren Sie ihn noch einmal aus der ursprünglichen Nachricht, und zwar bis zum letzten Zeichen.

## Was Ihnen die Seite sagen will

| Was Sie sehen | Was es bedeutet | Wer es beheben kann |
| --- | --- | --- |
| Ein Feld, das vier Zeichen verlangt | Die Freigabe ist geschützt. Sie brauchen den [Zugangscode](extraction-code.md) | Sie, mit dem Code vom Eigentümer |
| Eine Meldung, dass Sie zu spät kommen und die Freigabe aufgehoben wurde | Der Eigentümer teilt nicht mehr, oder Baidu hat die Dateien entfernt | Der Eigentümer |
| Eine Meldung über Rechtsverletzungen oder verbotene Inhalte | Baidu hat die Freigabe gesperrt | Niemand: Die Freigabe bleibt gesperrt |
| Eine Dateiliste mit dem Hinweis, dass einige Dateien herausgefiltert wurden | Ein Teil der Freigabe hat gegen Baidus Regeln verstoßen und ist ausgeblendet | Der Eigentümer |
| Eine Meldung, dass die Freigabe nicht mehr gültig ist | Die Freigabe ist abgelaufen | Der Eigentümer |

Mit der Übersetzungsfunktion Ihres Browsers können Sie diese Meldungen auseinanderhalten.

## Was Sie tun können

- **Der Code wird abgelehnt:** Vergleichen Sie ihn Zeichen für Zeichen mit der ursprünglichen Nachricht. Siehe [Zugangscode](extraction-code.md).
- **Die Freigabe ist aufgehoben oder abgelaufen:** Bitten Sie den Eigentümer, die Dateien neu freizugeben und Ihnen den neuen Link samt Code zu schicken.
- **Die Freigabe ist gesperrt:** Es gibt nichts herunterzuladen. Fragen Sie den Eigentümer, ob die Dateien woanders verfügbar sind.

## Prüfen, bevor Sie irgendetwas bezahlen

Testen Sie den Link mit der [Linkprüfung von PanPull](https://panpull.com/de?utm_source=github&utm_medium=tutorial#link-checker). Die Prüfung ist kostenlos. Eine lesbare Freigabe kommt mit Dateianzahl, Gesamtgröße und Preis zurück. Lässt sie sich nicht lesen, bekommen Sie stattdessen eine Fehlermeldung, und es wird nichts berechnet.

Kein Dienst kann eine gelöschte, aufgehobene oder gesperrte Freigabe zurückholen. Scheitert eine Freigabe bei PanPull, öffnet sich beim Eigentümer aber problemlos, versuchen Sie es etwas später noch einmal: Die Ursache ist vielleicht nur vorübergehend.

Mehr im PanPull-Blog: [Baidu-Freigabelink funktioniert nicht: was Sie prüfen sollten](https://panpull.com/de/blog/baidu-share-unavailable-checklist?utm_source=github&utm_medium=tutorial).

---

**Sie haben einen Baidu-Link? [Prüfen Sie ihn bei PanPull](https://panpull.com/de?utm_source=github&utm_medium=tutorial#link-checker)** und sehen Sie vorher Größe und Preis. Bis 150 MB ist es kostenlos.

[Alle Anleitungen](README.md) · [Andere Sprachen](../README.md#languages)
