# Baidu Pan bez klienta na komputer: pobieranie w przeglądarce na Windows, Macu i Linuksie

Klikasz przycisk pobierania na stronie udostępnienia Baidu Pan, a chińskie okienko każe ci najpierw zainstalować Baidu Netdisk. Możesz je zignorować. Poniżej wyjaśniamy, skąd bierze się to okienko, czego wymagałby od ciebie klient i jak pobrać te same pliki samą przeglądarką.

## Skąd to okienko

Strona Baidu wydaje tylko małe pojedyncze pliki i tylko zalogowanym użytkownikom. Duży plik, folder albo kilka plików naraz są przekazywane do klienta na komputer. W przypadku większości udostępnień oznacza to: bez klienta nie ma pobierania.

## Klient czy przeglądarka?

| | Klient Baidu Netdisk | Pobieranie w przeglądarce przez PanPull |
| --- | --- | --- |
| Instalacja | Tak. Na Windows uruchamia się też razem z systemem i działa w tle | Brak |
| Konto Baidu | Wymagane | Niepotrzebne |
| Język | Tylko chiński | 29 języków |
| Prędkość | Ograniczona na darmowym koncie | Zwykłe pobieranie z serwerów PanPull |
| Koszt | Za darmo albo płatne członkostwo SVIP w Baidu | Za darmo do 150 MB, potem według rozmiaru |
| Systemy | Windows, macOS, Android, iOS; Linux jako `.deb` lub `.rpm` | Wszystko, co ma przeglądarkę |

Jeśli jednak chcesz klienta, pobierz go bezpośrednio od Baidu ze strony `pan.baidu.com/download`, a nie z portalu z programami.

## Kiedy przeglądarka sprawdza się najlepiej

- **Komputer w pracy lub na uczelni:** nie masz uprawnień do instalowania programów.
- **Linux:** wolisz nie instalować pakietu o zamkniętym kodzie dla jednego pliku.
- **Twój własny Mac lub PC:** nie chcesz kolejnego programu działającego w tle.

## Kroki

1. Skopiuj udostępniony link do [narzędzia PanPull do sprawdzania linków](https://panpull.com/pl?utm_source=github&utm_medium=tutorial#link-checker). Jeśli jest kod dostępu, dodaj go.
2. Sprawdź wynik: ile plików, jaki łączny rozmiar, jaka cena.
3. Zaloguj się do PanPull adresem e-mail i hasłem i zapłać przez PayPal lub kartą, chyba że zamówienie jest darmowe.
4. Poczekaj na e-mail z informacją, że pobieranie jest gotowe, i otwórz link z wiadomości. Ten sam link jest na stronie zamówienia.

Z udostępnienia z jednym plikiem dostajesz ten plik. Z udostępnienia z kilkoma plikami dostajesz jedno archiwum ZIP ze strukturą folderów w środku.

## Rozpakowanie ZIP

| System | Jak |
| --- | --- |
| Windows | Kliknij archiwum prawym przyciskiem myszy, potem **Wyodrębnij wszystkie** |
| macOS | Kliknij archiwum dwukrotnie |
| Linux | Użyj menedżera plików albo wpisz w terminalu `unzip` i nazwę pliku |

Zadbaj o wolne miejsce na dysku równe mniej więcej dwukrotności rozmiaru archiwum: raz na ZIP, raz na jego zawartość.

Więcej na blogu PanPull: [Pobieranie z Baidu Pan bez klienta: Mac, Linux i komputery służbowe](https://panpull.com/pl/blog/download-baidu-pan-without-client?utm_source=github&utm_medium=tutorial).

---

**Masz link z Baidu? [Sprawdź go w PanPull](https://panpull.com/pl?utm_source=github&utm_medium=tutorial#link-checker)** i najpierw zobacz rozmiar i cenę. Do 150 MB za darmo.

[Wszystkie poradniki](README.md) · [Inne języki](../README.md#languages)
