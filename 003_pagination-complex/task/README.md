# Zadanie "pagination - complex solution"

Źródło: https://github.com/czechue/kodifaj-tasks

## Treść zadania

1. Instrukcja

    1. Stwórz strukturę HTML która składa się z komponentu paginacji oraz pola do wpisania maksymalnego numeru strony.
    
    2. Zaimplementuj sposób działania paginacji zgodnie z 3 przykładowymi widokami i rysunkowym opisem funkcjonalności, które znajdują się na infografice w pliku `/assets/pagination-task.png`
    
2. Szczegółowy opis akcji

    1. Początkowy numer aktywnej strony odczytywany jest z adresu URL z wartości parametry `p=`.
    
    2. Maksymalny numer strony jest odczytywany dynamicznie na podstawie wartości w inpucie `Max page`.
    
    3. Każda zmiana strony za pomocą paginacji - zmienia również wartość parametru `p` w URL.
    
    4. Jeśli wartość `p` jest większa od `Max page` - stroną aktywną jest wartość `Max page`. (Przykład: url: `http://app.pl?p=15` max page: `10` strona aktywna, która jednocześnie jest ostatnią stroną w komponencie paginacji: `10`)
    
    5. Wykropkowanie pojawia się w zależności od różnicy pomiędzy stroną aktywną a max. lub min. wartościami przedziału. (Dokładny opis na infografice). Jest to nieaktywny kontener.
    
    5. Strzałki "lewo" i "prawo" zmieniają wartość aktywnej strony o 1. W momencie gdy osiagnięte jest minimum bądź maximum - stają się disabled.
    
    6. Po komponencie można nawigować za pomocą strzałek na klawiaturze i klawisza Enter.
    
## Uwagi
    
*   Nie korzystaj z frameworków CSS (bootstrap etc.) ani JS (react, angular, vue etc.)

*   Makiety są tylko poglądowe, odwzorowanie nie musi być pixel-perfect.

*   Użyty font to `Proxima Nova Regular`, znajduje się w assetach.
