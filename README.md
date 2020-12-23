|PROJEKT W RAMACH|
# CodersCamp 2020 - Projekt HTML & CSS
**CodersCamp (coderscamp.edu.pl) - Największy otwarty kurs programowania webowego** 

## Zarys projektu ##

Główne cechy:
- Strona-wizytówka
- 3-blokowa
- Wykonana w HTML + CSS
- Przyciąganie scroll'a do danego bloku
- Responsywność dla 3 zakresów rozmiaru ekranu
- Przejrzysty układ

Strona tytułowa:
- Logo strony
- Tytuł i podtytuł
- Grafiki wypełniające resztę ekranu
- Prosta animacja przepływającej żaglówki

Główna zawartość:
- Cześć lewa ze zdjęciem i głównymi elementami
- Część prawa z poszczególnymi elementami w siatce z 2 kolumnami
- W przypadku przepełnienia prawa cześć jest przewijana niezależnie od lewej
- Poszczególne sekcje jako bloki z rzuconym cieniem.

Stopka:
- Formularz kontaktowy z imieniem/firmą, adresem email, numerem oraz treścią wiadomości
- Z lewej statyczny obrazek jako wypełnienie
- Na dole linki do zewnętrznych stron (linkedin, github)

## Responsywność ##

Strona ma trzy stopnie responsywności w zależności od maksymalnej szerokości ekranu:
- -512px --> smartfony
- 512-1024 --> tablety i smartfony w trybie horyzontalnym
- +1024 --> duże tablety i klasyczne laptopy
Dodatkowo dla urządzeń bez wskaźnika (czyli głównie ekrany dotykowe) pasek nawigacyjny cały czas zostaje na wierzchu.

* Stopień 1
    - Strona przekształca się do pionowego układu
    - Na stronie tytułowej grafiki wypełniają górną część bloku
    - Logo wraz z tytułami jest wyśrodkowane i zajmuje większość bloku
    - W sekcji głównej wszystkie części są teraz jeden pod drugim i zajmują cały ekran na szerokość
    - Sekcja bloków z opisami ma teraz dodatkowy punkt przyciągania scroll'a
    - W stopce formularz jest wyśrodkowany i zajmuje większość bloku, grafika uzupełniająca na górze

* Stopień 2
    - Strona tytułowa taka sama jak w stopniu pierwszym
    - Sekcja główna ma dwie kolumny, z lewej kafelek ze zdjęciem i główny opis, z prawej sekcje dodatkowe jedna pod drugą

* Stopień 3
    - Domyślna wersja strony

## Dalszy rozwój ##

Pod względem wyglądu strona jest już w pełni gotowa. Dalsza praca to zapełnienie jej treścią i ewentualne stylizowanie dodanych rzeczy. Głębszych testów i uwagi wymagała by również responsywność, w niektórych konfiguracjach rozmiaru strony traci ona na czytelności. Implementacja skryptów JS'a pozwoliła by na płynniejszą/ciekawszą animację, bardziej niezawodny mechanizm przewijania bloków (plus ciekawy znacznik położenia).
