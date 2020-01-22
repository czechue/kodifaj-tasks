# Zadanie "chat messenger"

Źródło: https://github.com/czechue/kodifaj-tasks

## Treść zadania

1. Instrukcja

    1. Stwórz strukturę aplikacji opartą o komponenty mając na uwadzę, że będzie się ona składała z dwóch, niezależnych widoków (strony logowania i strony chatu).
    
    2. Stwórz strukturę html komponentom i sformatuj style CSS tak, aby wygląd aplikacji był zbliżony projektom `/assets/chat - panel.png` i `assets\chat - chat.png` tak bardzo jak to tylko możliwe.

    3. Stwórz logikę wykonanym komponentom opierając się o wskazania wypisane w "Szczegółowym opisie akcji".
    
2. Szczegółowy opis akcji

    1. Wygląd aplikacji:

        - główne kontenery powinny być osadzone w po środku,

        - aplikacja powinna być napisana zgodnie z zasadami mobile first, a tym samym powinna być responsywna,

        - kolorystyka aplikacji powinna być w pełni odwzorowana (do próbkowania kolorów można wykorzystać narzędzie próbkowania w narzędziach developerskich przeglądarek internetowych),

        - do stworzenia avatarów w aplikacji należy skorzystać z dostarczonego pliku SVG `/assets/user icon.svg`,

        - kontener z wiadomościami nie powinien zmienić swojej wielkości jeżeli dialog będzie długi,

        - **w wersji zaawansowanej** na telefonach aplikacja powinna wykorzystać całą wysokość i szerokość ekranu tak, aby nie trzeba było jej scrollować.

    2. W panelu logowania:

        - stwórz dwa przyciski odpowiadające przekierowaniu lub wyrenderowaniu (w zależności od technologii z jakiej skorzystasz) do widoku chatu tego - w zależności którego wybrałeś - użytkownika,

        - za pomocą inputa można wysyłać wiadomości do - stworzonego w katalogach projektu - pliku z formatem .JSON. Podobnie cała rozmowa zostanie wyrenderowana na podstawie zawartości tego pliku,

        - **w wersji podstawowej** jeżeli wybrałeś użytkownika z szarym avatarem - na chatcie Twoje chmurki powinny być szare, a Twojego rozmówcy niebieskie.

        - **w wersji zaawansowanej** Twoje dymki zawsze będą niebieskie, niezależnie od tego które konto wybrałeś (niebieskie, czy szare),

        - wiadomości powinny renderować się od najnowszej w górę.

    
## Uwagi
    
*   Nie korzystaj z frameworków CSS (bootstrap etc.),

*   Do zbudowania aplikacji możesz wykorzystać freamwork JavaScript

*   Makiety są tylko poglądowe, odwzorowanie nie musi być pixel-perfect.

*   Użyty font to `quicksand`, znajdziesz go w bibliotece fontów google: `https://fonts.google.com/specimen/Quicksand`.
