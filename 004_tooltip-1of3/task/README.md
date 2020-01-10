# Zadanie "reusable tooltip component 1 of 3"

Źródło: https://github.com/czechue/kodifaj-tasks

Pierwsza część zadania w której będziesz tworzył bardzo popularny i powszechnie stosowany w wielu sytuacjach komponent. Staraj się aby Twój kod był możliwie **generyczny** i przygotowany na dodawanie kolejnych funkcjonalności.

## Treść zadania

1. Stwórz strukturę HTML widoku komponentu Tooltip oraz napisz odpowiednie reguły CSS, tak aby jak najdokładniej odwzorować wygląd przedstawiony na makiecie (patrz katalog `assets/tooltip-1of3.png`).

    1. :point_right: Dodaj w HTML 3 obiekty "A", "B" i "C".

    2. :point_right: Stwórz komponent Tooltip, który będzie "przyczepiany" do elementów DOM. Przyjmij stałą szerokość 120px, wysokość powinna zmieniać się automatycznie w zależności od długości tekstu ale nie powinna być mniejsza niż 80px.

    3. :point_right: Stwórz panel konfiguracyjny dla swojego Tooltipa, z następującymi opcjami*:

        - **color**: Prime, Secondary, Dark, Light (dodaj wg. uznania),

        - **position**: Top, Right, Bottom, Left,

        - **text**: zawiera inputy z `color`, `max length` i `textarea` w który można wpisać tekst będący zawartością komponentu,

_*weź pod uwagę, że panel ten może być w przyszłości rozszerzony o kolejne opcje_

2. Interakcje zaawansowane:

    1. :point_right: Kliknięcie na element (A, B lub C) powoduje pojawienie się Tooltipa obok tego elementu.

    2. :point_right: Zmiana **color** - zmienia kolor Tooltipa.

    3. :point_right: Zmiana **position** - zmienia zarówno położenie Tooltipa względem elementu, jak i "strzałkę" na niego wskazującą. Strzałka znajduje się zawsze idealnie na środku boku Tooltipa.

    4. :point_right: Zmiana wartości pól **text**:

        - kolor można podawać **tylko w HEX**, wartość inputa powinna być walidowana, jeśli jest niepoprawna kolor tekstu ustawiamy na biały (#FFFFFF),

        - wartość max length pozwala nam określić jak długi może być tekst w textarea, jeśli jest za długi - skracamy do ustawionej wartości

## Uwagi
    
*   Nie korzystaj z frameworków CSS (bootstrap etc.) ani JS (react, angular, vue etc.)

*   Makiety są tylko poglądowe, odwzorowanie nie musi być pixel-perfect.

*   Użyty font to `Poppins`.

*  :heart: dla `pejotr` za podsunięcie pomysłu.