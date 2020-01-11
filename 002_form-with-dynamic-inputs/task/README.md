# Zadanie "form with dynamic input - create new redirect URL"

Źródło: https://github.com/czechue/kodifaj-tasks

## Treść zadania

1. Instrukcja

    1. Stwórz strukturę HTML widoku formularza w którym będziesz tworzył nowy adres przekierowania URL. 

    2. Po zatwierdzeniu formularza użytkownik będzie przekierowywany na nowo-powstały adres. 

    3. Formularz posiada minimum 1 pole (początkowy stan), a maksymalnie 6. 

    4. Pierwszego pola nie można usunąć. 

    5. Pola od numeru 2-6 są zawsze odpowiednio posortowane zgodnie z kolejnością.


2. Szczegółowy opis akcji na formularzu:

    1. Przycisk DODAJ - dodaje kolejne pole formularza. W momencie gdy jest tych pól maksymalna ilość - przycisk jest zablokowany ("disabled"). 

    2. Pola 2 - 6 posiadają przyciski "X" które pozwalają je usunąć. (Pamiętaj aby podczas usuwania pól, również labelki się odpowiednio zmieniały, tak aby kolejność zawszy była zachowana). Usunięcie pola 6 odblokowuje ponownie możliwość korzystania z przycisku DODAJ.

    3. W polu 1 domyślnie znajduje się wartość "test value".

    4. Nie można dodawać kolejnych inputów, jeśli którykolwiek poprzedni jest pusty. Wtedy pod pustym wyświetlamy podpowiedź: "pole nie może być puste".

    5. Każde kliknięcie w DODAJ - ustawia kursor na nowo-dodanym inpucie.

    6. Przycisk "ZAPISZ" - przekierowuje na URL-a z **query stringiem** o przykładowej wartości: `http://example.com?phrases=fraza1;fraza2;fraza3`, gdzie `fraza1` to wartość z pierwszego inputa, `fraza2` z drugiego itd. (pamiętaj o enkodowaniu znaków)
    
    7. Przy submicie również żadne pole nie może być puste - powinien pojawiać się message j.w.


## Uwagi
    
*   Nie korzystaj z frameworków CSS (bootstrap etc.) ani JS (react, angular, vue etc.)

*   Makiety są tylko poglądowe, odwzorowanie nie musi być pixel-perfect.

*   Użyty font to `Poppins`.
