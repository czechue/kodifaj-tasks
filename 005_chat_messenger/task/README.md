# Zadanie "chat messenger"

Źródło: https://github.com/czechue/kodifaj-tasks

## Treść zadania

1. Instrukcja

    1. Stwórz strukturę aplikacji opartą o komponenty mając na uwadzę, że będzie się ona składała z dwóch, niezależnych widoków (strony logowania i strony chatu).
    
    2. Stwórz strukturę html komponentów i sformatuj style CSS tak, aby wygląd aplikacji był zbliżony projektom `/assets/chat - panel.png` i `assets\chat - chat.png` tak bardzo jak to tylko możliwe.
    
2. Szczegółowy opis akcji

    1. Wygląd aplikacji:

        - główne kontenery powinny być osadzone po środku,

        - aplikacja powinna być napisana zgodnie z zasadami mobile first, a tym samym powinna być responsywna,

        - kolorystyka aplikacji powinna być w pełni odwzorowana (do próbkowania kolorów można wykorzystać narzędzie próbkowania w narzędziach developerskich przeglądarek internetowych),

        - do stworzenia avatarów w aplikacji należy skorzystać z dostarczonego pliku SVG `/assets/user icon.svg`,

        - kontener z wiadomościami nie powinien zmienić swojej wysokości jeżeli dialog będzie długi,

        - **w wersji zaawansowanej** na telefonach aplikacja powinna wykorzystać całą wysokość i szerokość ekranu tak, aby nie trzeba było jej scrollować. Scrollować można jedynie konwersację,

    2. W panelu logowania:

        - stwórz dwa przyciski, dzięki którym można zmieniać aktywnego użytkownika,

        - zaznaczenie użytkownika powoduje pojawienie się widoku chatu i jednoczesne zamknięcie (ukrycie) panelu logowania,

    3. W widoku chatu:

        - za pomocą pola tekstowego można wysyłać wiadomości które pojawiają się w oknie czatu,

        - całą historia rozmowy zostaje zapisana w localStorage,
        
        - po przeładowaniu strony nie tracimy historii konwersacji,
        
         - **w wersji podstawowej** jeżeli wybrałeś użytkownika z szarym avatarem - na chatcie Twoje chmurki powinny być szare, a Twojego rozmówcy niebieskie,

        - **w wersji zaawansowanej** Twoje dymki zawsze będą niebieskie, niezależnie od tego które konto wybrałeś (niebieskie, czy szare),

        - wiadomości powinny renderować się od najnowszej w górę,

    
## Uwagi
    
*   Nie korzystaj z frameworków CSS (bootstrap etc.),

*   Do zbudowania aplikacji możesz wykorzystać freamwork JavaScript (np. React, Vue, Svelte)

*   Makiety są tylko poglądowe, odwzorowanie nie musi być pixel-perfect.

*   Użyty font to `quicksand`, znajdziesz go w bibliotece fontów google: `https://fonts.google.com/specimen/Quicksand`.
